# Scrapy_Note

官方文档  https://docs.scrapy.org/en/latest/

scrapy中文网  http://www.scrapyd.cn/

## 目录

#### 1_twisted异步

twisted与deferred对象 https://www.cnblogs.com/xianguang/p/7027661.html

【源码解读】如何充分发挥 Scrapy 的异步能力 https://cloud.tencent.com/developer/article/1424507

#### 2_Scrapy限速模块AutoThrottle

https://docs.scrapy.org/en/latest/topics/autothrottle.html#

https://www.jianshu.com/p/c40d8b2f86dd

#### 3_Scrapy项目部署

https://www.cnblogs.com/pythoner6833/p/9100783.html

#### 4_scrapyd远程连接配置

https://www.cnblogs.com/zongfa/p/7967900.html

#### 5_Scrapy对接BloomFilter

https://cloud.tencent.com/developer/article/1084962

#### 6_Scrapy-Redis自动关闭

```
判断多次redis中的带爬取队列为空时，关闭爬虫
可以用 extensions 或 signal 实现
```

Scrapy-Redis 空跑问题，redis_key链接跑完后，自动关闭爬虫 https://www.cnblogs.com/zhongshuiping/p/9820922.html