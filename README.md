<!--
 * @Author: zhaoyang.liang
 * @Github: https://github.com/LzyRapx
 * @Date: 2019-10-30 22:24:47
 -->
# barley-ticket-grabbing

### 前提: 
#### 1. chrome 浏览器 和 chromedriver 的版本要一致。
#### 2. chromedriver 下载地址: http://chromedriver.storage.googleapis.com/index.html
### 操作方式：
#### 1. 将 config.ini 文件中的 url 后面的内容替换为想要抢票的网站,如 url = xxxxxx,price_number 是顺数第 price_number + 1 的票价。number 暂时只能为 1。因为抢一张票的成功概率大很多。

#### 2. 运行```python3 ticket.py```, chrome 自动弹出。

#### 3. 初始为大麦网主页，点击登录，跳转后扫码登录（只需一次，cookies.pkl 生成后就无需此步骤。如果需要换号删除文件夹下的 cookies.pkl）

#### 4. 开始抢票，在未放票前，每秒刷新一次网站，放票开始，进行抢票。

#### 5. 下单需要提前填好收件人信息和购票人信息，优先选择显示靠前的购票人。

#### 6. 买票成功后，有 15 分钟的时间可以付款，此时程序锁死并开始报警提示付款。

