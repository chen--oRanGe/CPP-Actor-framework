本框架适用于复杂并发逻辑控制场合，免费使用，有问题或BUG反馈至 591170887@qq.com;
依赖于boost 1.57;
仅在VC2010编译器中测试，其它编译器不保证.

github url:
https://github.com/HAM-2015/CPP-Actor-framework

2015-02-05
增加外部可以直接拿另一个协程句柄创建一个消息管道或通知句柄.

2015-02-01
添加socket测试示例.

2015-01-26
修改了定时器在高版本VS下因与STL库冲突导致的编译错误问题;
增加异步触发和消息等待的超时处理功能.

2015-01-08
修改了挂起/恢复控制逻辑，原有逻辑在极端情况下存在安全风险.