# 目录
* [线程模型](thread_model.md)
  * [client](client.md)
  * [server](server.md)
* Client端执行流程
  * [无异常状态下的一次完整RPC请求过程](client_rpc_normal.md)
  * 重试策略
  * Backup Request
  * [同一RPC过程中各个bthread间的同步](client_bthread_sync.md)
* Server端执行流程
* bthread 
  * 调度算法
  * [线程futex同步](futex.md)
* 容灾容错
  * 服务限流
  * 防雪崩
* 性能监控
* 基础库
  * 对象池
  * 定时器
  * 计数器
