# 自定义监控

自定义监控是蓝鲸监控预置监控对象之外的监控方案，目前有`脚本采集`和`日志采集`。

- 日志采集，是从日志文件中解析上报的字段（比如一行日志的内容是 "2018-09-16 21:46:16 | aqq | 20020"），则可以知道 aqq 在 2018-09-16 21:46:16 的在线人数是 20020，也可以 sum 所有大区在 2018-09-16 21:46 的在线人数是多少。
    - 当前版本仅能在自定义监控页面配置视图。

- 脚本采集，通过 Shell、bat 脚本上报数据，只要会脚本就能上报数据。
    - 可在仪表盘和自定义监控页面配置视图。
