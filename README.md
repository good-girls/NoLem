[# VPS库存监控NoLem]
这是一个简单的VPS库存监控，通过读取页面缺货关键字信息来达到监控目的，并且使用TG频道发送监控信息。  
[## 准备工作](url)
1.创建一个tg机器人以及一个tg频道  
2.一个独立的vps（自己完全控制，并注意避免泄露自己的机器人token）  
[## 安装](url)
[## 安装python3](url)
1.大多数 Linux 发行版都预装了 Python。您可以通过以下命令检查版本：  
```python --version```  
2.如果您的系统没有 Python，或者您需要特定版本，则可以使用发行版的包管理器进行安装。例如，在 Ubuntu 上，您可以使用以下命令：  
```sudo apt install python3```  
3.安装pip  
```sudo apt-get install python3-pip```  
4.安装python相关依赖包  
```pip install aiohttp beautifulsoup4 python-telegram-bot``` 
[## 下载monitor.py和config.json并修改config.json的tg机器人和频道配置](url)
```
"telegram_token": "你的tg机器人api token",  
"telegram_chat_id": "你的tg频道ID，注意机器人要加入频道并且是管理员"
```
[## 商家监控配置JSON以dmit商家举例说明，其他商家请自行添加相关配置](url)
[## 商家信息](url)
* 名称 (name): DMIT
* 标签 (tag): #dmit
* 商家评论 (review_content): 商家评论：大妈
