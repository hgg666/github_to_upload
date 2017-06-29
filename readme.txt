step1:在GigHub官网注册并登陆

step2:创建公共库,点击右上角+号,选择New repository,填入相应的库名称

step3:安装git

step4:配置git(下面步骤都在git-bash中完成),在本地创建ssh key,打开git命令界面,输入keygen -t rsa -C "your_email@youremail.com"然后一路回车

step5:输入git clone + 库地址,回车后本地会出现一个库地址同名的文件夹

step6:将要上传的文件复制到上一步的文件夹中

step7:分别执行以下命令
git init
git add 文件名
git commit -m "备注名称"
git remote add origin +库地址
git push -u origin master

step6:完成上述后会弹出一个窗口,输入在GitHub注册时的账户密码即可,刷新即可看到文件上传成功