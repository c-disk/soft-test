# Jmeter

## http请求  get方法
##### 需求文档
    接口地址：http://v.juhe.cn/weather/index
    返回格式：json/xml
    请求方式：get
    请求示例：http://v.juhe.cn/weather/index?format=2&cityname=%E8%8B%8F%E5%B7%9E&key=您申请的KEY
![](https://github.com/c-disk/soft-test/blob/master/接口参数.png)

- ###### http请求
![](https://github.com/c-disk/soft-test/blob/master/Jmeter%20http%E8%AF%B7%E6%B1%82.png)
- ###### 察看结果树
![](https://github.com/c-disk/soft-test/blob/master/%E6%9F%A5%E7%9C%8B%E6%A0%91%E7%BB%93%E6%9E%9C.png)

## soap请求  post方法
`SOAP：简单对象访问协议，简单对象访问协议（SOAP）是一种轻量的、简单的、基于 XML 的协议，它被设计成在 WEB 上交换结构化的和固化的信息。`

使用“腾讯QQ在线状态 WEB 服务”做示范
[qqOnlineWebService](http://www.webxml.com.cn/webservices/qqonlinewebservice.asmx)
![](https://github.com/c-disk/soft-test/blob/master/qqOnlineWebService.png)



- ###### soap请求
`xml请求放到body data`
![](https://github.com/c-disk/soft-test/blob/master/soap%E8%AF%B7%E6%B1%82.png)
- ###### HTTP信息头管理器
![](https://github.com/c-disk/soft-test/blob/master/%E4%BF%A1%E6%81%AF%E5%A4%B4%E7%AE%A1%E7%90%86%E5%99%A8.png)
- ###### 察看结果树
![](https://github.com/c-disk/soft-test/blob/master/%E5%AF%9F%E7%9C%8B%E7%BB%93%E6%9E%9C%E6%A0%91.png)

## HTTP Cookie管理器
`如果你有一个 HTTP 请求，其返回结果里包含一个 cookie，那么 使用JmeterCookie管理器会自动将该 cookie 保存起来，而且以后所有对该网站的请求都使用同一个 cookie。每个 JMeter 线程都有自己独立的”cookie 保存区域”。`
    
- ###### 登陆
![](图片素材/登陆cookies.png)
- ###### 保存cookies
![](图片素材/保存cookies.png)
- ###### 同域名使用
![](图片素材/使用cookies查询.png)
- ###### 使用cookies
![](图片素材/察看树cookies.png)
