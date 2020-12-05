# 创建自己的github博客
## 下载一个已经制作好的主题
在任意一个记得住的位置创建一个文件夹，用来保存文件
例如在桌面上创建qfr.github作为文件地址
```
cd 桌面
```
```
touch qfr.github
```
进入[jekllthems主题](http://jekyllthemes.org/)选择一个喜欢的主题,点击它,再点击Homepage，进入目标库，复制其HTTPS码。
![a theme](https://img-blog.csdnimg.cn/20201205202852947.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2p2ZGlkbnM=,size_16,color_FFFFFF,t_70)
![clone](https://img-blog.csdnimg.cn/20201205203756168.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2p2ZGlkbnM=,size_16,color_FFFFFF,t_70)
进入自己事先所创建的文件夹qfr.github，克隆这个主题
```
git clone "https://github.com/manid2/lone-wolf-theme.git"
```
## 创建自己的仓库
在自己的github中创建自己的repositories仓库，命名必须是自己账号加`.github.io`，然后重复上面的步骤，下载自己的仓库
```
git clone https://github.com/1142969015/1142969015.github.io.git
```
自己的仓库是空的，将下载的主题复制或者移动到自己的仓库
```
cp -r  jekyll-theme-chirpy/*  1142969015.github.io/
```
进入仓库
```
cd 1142969015.github.io/
```
跟踪自己仓库
```
git add .
```
提交更新
```
git commit -m "first"
```
提交到远程仓库
```
git push
```
就完成了
进入自己仓库的settings，在options往下拉，github pages即可以看到自己博客地址。
