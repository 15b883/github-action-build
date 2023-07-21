## 测试 github action 各项功能

```
on:
#   schedule:
#     - cron: '25 17 * * *' # 每天的0时（UTC时间）
  workflow_dispatch:  
```
通过 workflow_dispatch: 可以在 Actions 里面手动触发 workflow



## 功能

* cron
> cron 定时任务 是UTC时间，转成中国时间后有点延迟 大概7分钟左右

* build