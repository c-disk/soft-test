# soft-test
软件测试学习笔记:thought_balloon:
 
  
 
---
* [软件测试基础理论](https://github.com/c-disk/soft-test/blob/master/%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%9F%BA%E7%A1%80.png)
---
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
