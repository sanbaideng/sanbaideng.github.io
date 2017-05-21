title: Hexo注意事项
date: 2015-08-04 10:49:58
tags: Tech
---
- **1**
		hexo init

- **2**
		npm install hexo-deployer-git --save
不然会报错 not found git

- **3**
		npm install 
安装所有依赖包，不然不会生成index.html,404错误。

- **4**
配置_config.yml
		url: http://sanbaideng.github.io/
	
	  deploy:
		  type: git
		  repo: https://github.com/sanbaideng/sanbaideng.github.io.git
		  branch: master
		  message: message

- **5**
		npm install hexo --save

- **6**
		hexo d -g
		
