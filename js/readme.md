在footer.pug最后加上
```
if (theme.time.enable)
  #sitetime
```
config.yml配置
```
  # 站点运行开始时间.
  time:
    enable: false
    year: 2019 # 年份
    month: 06 # 月份
    date: 28 # 日期
    hour: 00 # 小时
    minute: 00 # 分钟
    second: 00 # 秒
```
