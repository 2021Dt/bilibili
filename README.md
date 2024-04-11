本包目前为测试版本，仅支持web端B站的数据爬取。
1. 支持简单视频下载
2. 支持弹幕api返回
3. 支持评论区爬取（默认10轮）
4. 支持拜年祭相关视频下载，动漫加密和这个一模一样，但是我没写，~不让下的还是不要下好~
5. 当然可以单个模块使用，在Tool和API都可以直接使用

如果您只想要单独使用某个模块，那么就由我来给您讲解各个模块的使用
- ***所有模块都依赖于Tool下的RequestUrl模块***
- Tool下的DownLoad用于下载普通视频。
- API就是拜年祭，评论，弹幕的访问了。
- 在Comment API下有参数number当视频评论特别多的时候可以适当加大，其中response是未处理的原始数据，需要的可以自己改写。
- w_rid文件就是关键参数的js逆向。
- 暂不提供弹幕文件的解析，只提供api生成。



* 使用前请保证相关环境的配置完成，直接执行`main()`
* 这是我打算做的一个数据集合的一小部分。后续后加上各种各样的流行网站的爬取。
* 暂时没写多线程使用慢是很正常的。
* 本包还有很多bug，我也在努力让他变得更好。
* 如果有相关问题可以直接联系作者。
* ***严禁非法使用，本项目仅供学习使用，请注意请求频率，给B站带来压力。***
* ***违反这些限制可能会导致法律责任，打击作者的热情，对爬虫作者和使用者都会产生负面影响。在使用和分享爬虫代码时，请谨慎考虑其合法性和合规性，以维护互联网的健康和稳定。***
