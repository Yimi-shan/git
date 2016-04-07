安装git


------------------------下载--------------------------------

新建文件夹---用于存放下载内容

打开Git Bash



输入 cd +文件夹地址 （文件夹地址“\”改为“/”）
git config --global user.name "Yimi-shan"
git config --global user.email "995164849@qq.com"
git clone +下载内容地址（git里面的内容地址）

-----------------------提交------------------------------
cd +文件夹地址
git init (创建仓库)
git add index.html（要上传文件名）
git add *（添加到缓存区）
git commit -m "add index.html"(commit文件---“”内为注释)（提交到本地）

git status（查看状态）
git reflog（查看修改历史）
git reset --hard HEAD^（返回上一次修改，两个^^则表示返回前两次）
git reset --hard 2978c1f(返回第几步，2978c1f为id)

---------------
git push origin master （提交到云端）
输入用户名和密码
