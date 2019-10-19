# soft-test
软件测试学习笔记:thought_balloon:
 
  
 
---
* [软件测试基础理论](https://github.com/c-disk/soft-test/blob/master/%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%9F%BA%E7%A1%80.png)
---
# Jmeter
## http请求  get方法

    接口地址：http://v.juhe.cn/weather/index
    返回格式：json/xml
    请求方式：get
    请求示例：http://v.juhe.cn/weather/index?format=2&cityname=%E8%8B%8F%E5%B7%9E&key=您申请的KEY

    请求参数说明：
    名称	    必填	类型	   说明
    cityname	Y	 string	 城市名或城市ID，如："苏州"，需要utf8 urlencode
    dtype	   N	 string	 返回数据格式：json或xml,默认json
    format	  N	 int	    未来7天预报(future)两种返回格式，1或2，默认1
    key	     Y	 string	 在个人中心->我的数据,接口名称上方查看
