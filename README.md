# subdomain_collect
一款子域名挖掘小工具
## 👋Feature:

- 通过Bing搜索引擎进行子域名搜集
- 使用urllib库实现网络请求、cookie保存和读取
- 设置网络请求频率随机延时以应对反爬机制
***
##  ✨Help menu:
![Help_Menu](https://github.com/Afl0wer/subdomain_collect/blob/main/help_menu.gif "Help Menu")  
## 🚀Usage:
- 指定爬取页面数量，并将收集到的子域名列表保存至本地文件：  
  
  `subdomain_collect_bing.py xxx.com -p 20 -f result.txt`
---
- 按照默认设置的页面数量爬取，并将收集到的子域名列表保存至本地文件：  
  
  `subdomain_collect_bing.py xxx.com -f result.txt`
---
- 按照默认设置的页面数量爬取，并将收集到的子域名列表打印：  
  
  `subdomain_collect_bing.py xxx.com`
## ⚡️Example：
![example_image](https://github.com/Afl0wer/subdomain_collect/blob/main/example_image.png "example image")  


