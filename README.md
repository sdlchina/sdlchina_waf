# sdlchina_waf

sdlchina将会开始开源waf，基于nginx_lua

# 功能列表

1.0版本将会支持核心功能

1. 支持总开关功能、审计不防护、审计防护、临时关闭。
2. 支持IP白名单和黑名单功能
3. 支持URL白名单，将不需要过滤的URL进行定义。
4. 支持User-Agent的过滤
5. 支持CC攻击防护，单个URL指定时间的访问次数
6. 支持Cookie注入防护
7. 支持sql注入防护
8. 支持XSS防护
9. 支持URL黑名单过滤
10. 支持日志记录，将所有不安全的请求，记录日志
11. 日志记录为JSON格式，便于日志分析
12. 支持反爬虫策略
13. 支持盗链
14. 所有功能支持按模块开启。

2.0版本将会支持sdlchina center控制

1. 支持多节点策略下发
2. 支持不同业务分组控制
3. 支持按组分发策略
4. 支持nginx_proxy方式部署
5. 支持在线升级
