Thank for [Mars Wang42](https://github.com/MarsWang42)
# WebAR

- 安装n与Node.js
	MacOS与Linux
	``` 
	下载n管理工具： curl -L https://raw.githubusercontent.com/tj/n/master/bin/n -o n
	下载node最新版本： bash n lts
	# Now node and npm are available
	```
	Windows于[官网下载](https://nodejs.org/zh-cn/download/)Node.js并安装

ios现在需要https来访问，所以需要内网穿透。
- 安装ngrok
	- MacOS `brew install ngrok`
	- Linux 使用对应的包管理器安装，如 `apt-get install ngrok`、`yum install ngrok`
	- Windows [https://ngrok.com/download](https://ngrok.com/download)

- 下载模型 [https://sketchfab.com](https://sketchfab.com)

- 实操(MacOS)
	
	```
	cd ~/WebAR
	```
	```
	node index.js
	```
	![image](https://user-images.githubusercontent.com/61532079/137856529-1c8b8657-e9ae-44d3-963d-0d7e6a0bf276.png)

	```
	./ngrok http 8080
	```
	![04631FF85D1A7925FCC5B670D9F0E3A5](https://user-images.githubusercontent.com/61532079/137856514-cf028bd3-17fd-4aa8-a0ea-1761c8095bf5.png)
	```
	[演示](https://github.com/jujimeizuo/WebAR/blob/master/description.mp4)
