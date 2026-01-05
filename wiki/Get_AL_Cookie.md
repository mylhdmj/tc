# 浏览器获取阿里cookie教程

1. 电脑浏览器打开阿里速卖通 [https://best.aliexpress.com](https://best.aliexpress.com)
2. 按键盘F12键打开开发者工具，然后点击Google图标使用Google账号登录（可能需要换美国全局代理才会出现Google授权登陆）
![](wiki/image/AL1.png)
3. 此时是未登录状态(使用Google账号授权登录)，最好先登录Google账号

   - 按步骤进行授权登录。
4. 登录后，依次点击Fetch/XHR->tokenLogin->Cookie, 然后就可以看到整个Cookie，复制整个Cookie使用。

![](wiki/image/AL2.png)

5. 如果tokenLogin的Cookie无效，则使用1.0/?jsv=2.7.5&appKey=这种链接里面的Cookie，然后复制整个Cookie使用。

![](wiki/image/AL3.png)
