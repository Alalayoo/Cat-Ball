* # HTTP报文

* 组成：
    * 起始行：对报文进行描述
    * 首部：包含属性
    * 主体：包含数据

* 分类：
    * 请求报文：
      ```xml
      <method> <request-URL> <version>
      <headers>
        
      <entity-body>
      ```
    * 响应报文：
      ```xml
      <version> <status> <reason-phrase>
      <headers>

      <entity-body>
      ```
* 方法：
  > GET、HEAD、PUT、POST、TRACE、OPTIONS、DELETE以及一些扩展方法

* 状态码：
  | 状态码 | 含义 |
  | :-: | :-:|
  |100~199|信息性状态码|
  |200~299|成功状态码|
  |300~399|重定向状态码|
  |400~499|客户端错误状态码(客户端发送了服务器端无法处理的内容)|
  |500~599|服务器错误状态码|