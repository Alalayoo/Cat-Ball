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
  | 100~199(100&101)|信息性状态码|
  |200~299|成功状态码