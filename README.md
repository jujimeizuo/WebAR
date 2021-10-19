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
	node index.js
	![134933ED-23C2-432D-BE29-116F98413E50](https://user-images.githubusercontent.com/61532079/137855795-ab384958-7357-45ab-96be-65d0e9af2a4d.png)

	./ngrok http 8080
	![A836AAE2-5FF2-49AD-B2A8-628353BEE48E](https://user-images.githubusercontent.com/61532079/137855886-2417d2d1-5288-4c78-92e0-20291401164d.png)
	
	
	```
