test2 本地创建 上传
要先在github上面建立仓库,然后配置config文件
[remote "origin"]
	url = https://github.com/zhoufengjian/test.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
	remote = origin
	merge = refs/heads/master
