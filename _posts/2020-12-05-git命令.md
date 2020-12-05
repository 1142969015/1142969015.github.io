# git命令
*克隆仓库的命令 *
```
git clone <url> 
```
 比如，要克隆 Git 的链接库 libgit2，并且添加一个本地名字qfr1，可以用下面的命令：
 ```
git clone https://github.com/1142969015/1142969015.github.io.git qfr1
```
*跟踪命令*
```
git add
```
*提交暂存*
```
git commit
```
通常 commit 命令后添加 -m 选项，将提交信息与命令放在同一行
```
git commit -m
```
*查看哪些文件状态*
```
git status
```
*更新组仓库*
```
git pull
```
*移除某个文件*从已跟踪文件清单中移除,确切地说，是从暂存区域移除.
```
git rm
```
*上传文件到仓库*
首先进入仓库的_posts目录下
```
cd _posts/
```
按照格式命名md文件即可上传
```
2020-12-04-firstone
```
```
git add .
```
```
git commit -m "aa"
```
```
git pull
```
```
git push
```
上传完成，可以在博客上查看到已上传的md文件
