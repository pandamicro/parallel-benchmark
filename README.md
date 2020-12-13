# 简介

1. gp-perf: 性能测试结果，截图是 GP 工具内截图，主要包含 CPU 和功耗折线图
2. perfdog: 功耗测试结果，需要使用 [perfdog](https://perfdog.qq.com/) 打开，命名规则：
    device_parallellib_workload_innerloop_compute

    - device: 设备简称
    - parallellib: 并行库，包含 sequential(未使用并行库), taskflow, asio, tbb, job system
    - workload: 单任务负载
    - innerloop: 并行任务的循环数
    - compute: 后缀，有表示 compute only，否则包含一定的 IO 开销
