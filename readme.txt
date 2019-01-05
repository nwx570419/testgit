1.git init
2. git config --global user.name "ningxiaoxia@huawei.com"
3.git config --global user.email "920322606@qq.com"
4. git add readme.txt
5.git commit -m 'readme'
6.git status



生成秘钥 配置远程仓库
1. ssh-keygen -t rsa -C "920322606@qq.com"
2.登录github,打开” settings”中的SSH Keys页面，然后点击“Add SSH Key”,填上任意title，在Key文本框里黏贴id_rsa.pub文件的内容。
3.首先，登录github上，然后在右上角找到“create a new repo”创建一个新的仓库。
4.在Repository name填入testgit，其他保持默认设置，点击“Create repository”按钮，就成功地创建了一个新的Git仓库
5.git remote add origin https://github.com/nwx570419/testgit.git
6.git push -u origin master



**https://blog.csdn.net/qq_36150631/article/details/81038485