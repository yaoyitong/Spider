# 爬虫练习
**豆瓣爬虫-陈情令的评分**

本来想看看评分具体是如何变化，但不知为何，只能爬前7页，用浏览器也是到了第8页就无法显示不同用户的评分。换了一个影视剧翻页到第10页便无法查看用户评分。
目前，不触发验证码的情况下，直接post用户名密码登录后访问其他页面；若触发验证码，则采取selenium驱动chrome driver的方式模拟登录豆瓣，继而保存session访问其他网页。

**飞常准爬虫**

目前存储 航段信息、起飞降落机场、预计起飞和降落时间，实际起飞和实际到达时间以及准点率采用矢量图存储，可从单一航班界面获取实际时间信息，但此法过于繁琐，目前尝试采用svg映射关系获取该信息。


爬虫最难的地方在于反爬啊。
