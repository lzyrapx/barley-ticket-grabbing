# barley-ticket-grabbing

### 前提: 
#### 1. chrome 浏览器 和 chromedriver 的版本要一致。
#### 2. chromedriver下载地址: http://chromedriver.storage.googleapis.com/index.html
### 操作方式：
#### 1.将 config.ini 文件中的 url 后面的内容替换为想要抢票的网站,如 url = xxxxxx,price_number 是顺数第 price_number + 1 的票价。number 暂时只能为 1.

#### 2.运行```python3 ticket.py```,允许进网

#### 3.初始为大麦网主页，点击登录，跳转后扫码登录（仅此一次，如果需要换号删除文件夹下的 cookies.pkl）

#### 4.开始抢票，在未放票前，每秒刷新一次网站，放票开始，进行抢票。

#### 5.下单需要提前填好收件人信息和购票人信息，优先选择显示靠前的购票人。

#### 6.买票成功后，有15分钟的时间可以付款，此时程序锁死并开始报警提示付款。

