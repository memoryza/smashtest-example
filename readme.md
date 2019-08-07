###smashtest example

   `example/cicd` 比较特殊，需要自己配置对接域名以及接受socket数据，写了一个简单的demo，smashtest数据会输出到9000的端口，如果想在其他端口拿到数据
  
  1、指定 --report-domain  或者配置
  
  2、运行对接域名服务然后ws跟9000 通讯