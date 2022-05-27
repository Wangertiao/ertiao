### 一、自定义的异常类

```
public class XDException extends Exception{

    private Integer code;

    private String msg;

    public XDException(Integer code, String msg){
        this.code = code;
        this.msg = msg;
    }

    public Integer getCode() {
        return code;
    }

    public void setCode(Integer code) {
        this.code = code;
    }

    public String getMsg() {
        return msg;
    }

    public void setMsg(String msg) {
        this.msg = msg;
    }

}
```

### 二、配置apo对异常进行拦截

```
@ControllerAdvice
public class CustomExceptionHandler {
    @ExceptionHandler(value = Exception.class)
    @ResponseBody
    public JsonData handle(Exception e){

        if( e instanceof XDException ){

            XDException xdException = (XDException) e;

            return JsonData.buildError(xdException.getCode(),xdException.getMsg());

        }else {

            return JsonData.buildError("全局异常，未知错误");

        }


    }
}
```

### 三、如何使用异常，能干什么

```
 //比如说一个接口在访问时候不符合业务逻辑那么可以直接抛出异常返回给前端
 @GetMapping("test2")
    public Object test2() throws XDException {
				
			//省略业务代码 n行
				int i= 1
				if(i=1){
				//抛出运行时异常返回给前端数据
				 throw new XDException(-1, "运行时异常");
				}else{
				return "成功返回数据"
				}

    }
```

