# doubanBookSpider
用Scrapy实现的一个爬取豆瓣读书TOP250的练手项目，初学者可以参考

### 如何使用
确保安装依赖Python2.7,scrapy,SQLAlchemy

进入目录，执行
```
scrapy crawl douban-book-spider
```
即可开始爬取书籍信息

成功的截图

![](http://opsfsk07z.bkt.clouddn.com/dobuan-book.png)

以下命令可以将数据库中数据转换成JSON格式
```
python parse_to_json.py
```


