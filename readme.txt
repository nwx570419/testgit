1.git init
2. git config --global user.name "ningxiaoxia@huawei.com"
3.git config --global user.email "920322606@qq.com"
4. git add readme.txt
5.git commit -m 'readme'
6.git status



������Կ ����Զ�ֿ̲�
1. ssh-keygen -t rsa -C "920322606@qq.com"
2.��¼github,�򿪡� settings���е�SSH Keysҳ�棬Ȼ������Add SSH Key��,��������title����Key�ı��������id_rsa.pub�ļ������ݡ�
3.���ȣ���¼github�ϣ�Ȼ�������Ͻ��ҵ���create a new repo������һ���µĲֿ⡣
4.��Repository name����testgit����������Ĭ�����ã������Create repository����ť���ͳɹ��ش�����һ���µ�Git�ֿ�
5.git remote add origin https://github.com/nwx570419/testgit.git
6.git push -u origin master



**https://blog.csdn.net/qq_36150631/article/details/81038485