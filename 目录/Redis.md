- 1、基础
	- 1. 纯内存
	- 2. 非阻塞IO
	- 3. 避免线程切换和竞争消耗

- 2、单线程Redis注意事项
	- 1. 一次只运行一条命令
	- 2. 拒绝长（慢）命令，例如：keys、flushall、flushdb、slow lua script、mutil/exec、operate big value(collection)
	- 3. Redis其实不是单线程，fysnc file descriptor进行持久化

- 3、特性

	- 1. 速度快
	- 2. 持久化
	- 3. 多钟数据结构
	- 4. 支持多种编程语言
	- 5. 功能丰富
	- 6. 简单
	- 7. 主从复制
	- 8. 高可用，分布式

- 4. 应用场景
	- 缓存系统
	- 排行版
	- 计数器
	- 社交网络
	- 消息队列系统
	- 实时系统