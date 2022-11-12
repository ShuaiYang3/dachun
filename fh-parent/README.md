**吉象保项目依赖管理父工程（注意不引入实际依赖，仅做依赖管理**）

**相关微服务端口和模块定义**

| 微服务 | 端口 | 模块Code | 模块Name | 模块Desc | 模块prefix |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 监控中心 | 8777 | 77 | monitor | jxb-monitor | MON |
| 网关 | 8765 | 00 | zuul | jxb-zuul-gateway | ZUUL |
| 注册中心 | 8761 | 10 | eureka | jxb-eureka | EU |
| 用户中心 | 8762 | 20 | user | jxb-user | US |
| 产品中心 | 8763 | 30 | product | jxb-product | PRO |
| 消息中心 | 8764 | 40 | message | jxb-message | MSG |
| 内容中心 | 8766 | 50 | cms | jxb-cms | CMS |
| 订单中心 | 8767 | 60 | order | jxb-order | ORD |
| 结算中心 | 8769 | 69 | settle | jxb-settle | SET |
| 基础服务 | 8770 | 70 | basic | jxb-basic | BAS |
| 账户中心 | 8771 | 80 | acct | jxb-account | ACCT |
| 消息中心 | 8772 | 90 | msg | jxb-msg | MSG |
| 推送中心 | 8773 | 91 | push | jxb-push | PUSH |
| 搜索中心 | 8774 | 92 | search | jxb-search | SEARCH |
| 非保险商城 | 8776 | 93 | mall | jxb-product-mall | MALL |
| 客户服务 | 8779 | 94 | customer | jxb-customer | CUSTOMER |
| 第三方用户服务 | 8780 | 95 | thirduser | jxb-third-user | THIRDUSER |
**Zuul服务配置文件示例：**  
module.code=00  
module.name=zuul  
module.desc=jxb-zuul-gateway  
module.cache_prefix=ZUUL  