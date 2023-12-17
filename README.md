# Django_Mall
使用Django搭建商城系统

windows git配置？

1. 配置用户名和邮箱信息
	
	git config --global user.name "username"
	git config --global user.name "email"

2. 运行 rm -rf ~/.ssh/* 把现有的sshkey都删掉。
3. 运行 ssh-keygen -t rsa -b 4096 -C "你的邮箱" 。
4. 回车三次。
5. 运行 cat ~/.ssh/id_rsa.pub，得到一串东西，完整的复制这串东西。
6. 进入github，添加key 。
7. 运行 ssh -T git@github.com，查看是否添加成功。