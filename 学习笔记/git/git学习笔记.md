**git**

1、创建ssh - key ：

```
ertiao@ertiaodeMacBook-Pro .ssh %  ssh-keygen -t rsa -C "597621350@qq.com"
```

2、查看ssh的秘钥：cat id_rsa.pub   （在.ssh目录下）

3、配置config :  

- Host github.com
- HostName github.com
- User Wangertiao
- IdentityFile /Users/ertiao/.ssh/id_rsa

4、拉取代码

```
ertiao@ertiaodeMacBook-Pro GitTest %git clone git@github.com:Wangertiao/JAVA.git

```

​		

5、查看文件状态

```
ertiao@ertiaodeMacBook-Pro JAVA % git status  
```

6、追踪文件

```
ertiao@ertiaodeMacBook-Pro JAVA % git add test.txt 
```

7、commit提交

```
ertiao@ertiaodeMacBook-Pro JAVA % git commit -m "增加测试文件"
```

8、上传push

```
ertiao@ertiaodeMacBook-Pro JAVA % git push
```

9、拉取代码

```
ertiao@ertiaodeMacBook-Pro JAVA % git pull                 
```

10、查看本地分支

```
ertiao@ertiaodeMacBook-Pro JAVA % git branch
```

11、查看远程分支

```
ertiao@ertiaodeMacBook-Pro JAVA % git branch -a
```

12、在本地创建分支

```
ertiao@ertiaodeMacBook-Pro JAVA % git chechout -b  branch1
```

13、切换分支

```
ertiao@ertiaodeMacBook-Pro JAVA % git checkout branch1
```

- 三个分支：

  master：主分支

  develop：开发分支

  lhfdev：本地开发分支

14、将lhfdev分支上的代码合并到develop上：

```
1. 从lhfdev分支切换到develop分支上：git checkout develop

2. 将lhfdev分支上的代码合并到develop上：
git merge --no-ff -m '合并 双十一预售活动' lhfdev 

3. 发现冲突文件，编辑冲突文件，解决冲突，再次提交
git add 文件
git commit -m ‘注释’

4. 提交之后，对比一下develop和lhfdev分支：
git diff develop lhfdev

5. 发现完全相同，说明冲突已经解决，可以查看一下日志：
git log

6. 提交之前，先更新一下远程代码到develop上：
git pull origin develop

7. 然后提交develop代码到远程：git push origin develop

8. 提交之后，比对一下develop与master的不同：
git diff develop master

9. 比对发现代码一致，然后切换到master分支上：
git checkout master

10. 再将develop的代码合并到master上：
git merge --no-ff -m '合并开发分支20181031' develop

11. 在比对一下master与develop分支是不是相同：
git diff develop master

12. 再将master分支的代码提交到远程，提交之前先更新：
git pull origin master

13. 更新完成后，进行提交：git push origin master
到此就完成开发分支与master分支代码的合并与提交操作了。

14. 任务完成之后，我们需要将本地开发分支删除，首先切换到develop开发分支上：git checkout develop

15. 然后删除本地开发分支：
git branch -d lhfdev

16. 再次查看分支：git branch  就剩下master与develop分支了，也就是一个干净的git了。

17. 下次再开发新功能的时候，需要再次从develop分支中创建一个新分支，开始开发。

 
```

15、删除远程分支

```
git branch -r -d origin/branch1
提交
git push origin :branch1
```

16、回退版本

```
#查看所有版本
git reflog
#回退到上一个版本  几个^就是回退到几版本
git reset --hard HEAD^
#回退到指定版本（需要先查看所有版本命令）
git reset --hard +版本id

```

