# 京东商品评论信息抓取
# 得到app电子书信息爬取
# 微信朋友圈信息爬取（appium）
github上传文件，如果太大感觉会卡住，其实是太慢了。。。  
windows上面只能使用mitmdump，不能用mitmproxy  
appium使用xpath查找可以直接获取app内容，但是容易出问题，搭配mitmdump效果更好  
fiddler可以抓取https请求，但是去哪网的接口还是很难模拟
# 微信公众号爬虫 
信息用fiddler+mitmdump获取，  
喜欢数和阅读量  https://mp.weixin.qq.com/mp/getappmsgext  
434  
55582  
文章正文和标题，用正则取出来  https://mp.weixin.qq.com/s  


但要用appium写一个自动脚本，公众号是h5的内容，不是原生的，要切换
