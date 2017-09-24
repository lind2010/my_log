想上传文件到GitHub，首先你要在GitHub上创建一个存储库。

![Snip20170924_1](/Users/lindeguang/Desktop/Snip20170924_1.png)

然后打开终端，创建一个文件夹:

mkdir my_project

cd my_project

git clone + （你的GitHub存储库地址）



然后把你想上传的文件拖到刚刚创建的文件夹中，在终端操作：

cd 进入你的文件夹

// 查看文件的变化状态

git stattus

然后在本地做一次提交（在终端操作）

如果你有很多文件就git add -A

如果你只想上传一个文件，就git add your_file

然后把被添加的文件做本地提交git commit -m "代码提交的日志信息"

最后把提交到本地仓库的代码推送到远程仓库git push origin master



