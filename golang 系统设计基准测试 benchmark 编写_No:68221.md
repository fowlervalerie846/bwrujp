最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计基准测试 benchmark 编写
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.ylk9ot.asia/blog/014423.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.ylk9ot.asia/blog/041999.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.ylk9ot.asia/blog/143971.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.ylk9ot.asia/blog/058517.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.ylk9ot.asia/blog/870426.Doc

原标题：布隆过滤器误判问题修正
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.ylk9ot.asia/blog/168519.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.ylk9ot.asia/blog/888739.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.ylk9ot.asia/blog/814258.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.ylk9ot.asia/blog/906340.Doc

原标题：golang 配置热更新不重启服务
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.ylk9ot.asia/blog/494552.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.ylk9ot.asia/blog/915969.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.ylk9ot.asia/blog/666581.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.ylk9ot.asia/blog/560252.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.ylk9ot.asia/blog/878920.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.ylk9ot.asia/blog/163222.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.ylk9ot.asia/blog/788154.Doc

原标题：Git 子模块更新代码不全修复
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.ylk9ot.asia/blog/380492.Doc

原标题：golang kafka 生产者参数调优
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.ylk9ot.asia/blog/222608.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.ylk9ot.asia/blog/892117.Doc

原标题：分布式 ID 全局唯一生成方案
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.ylk9ot.asia/blog/617691.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.ylk9ot.asia/blog/059040.Doc

原标题：golang redis 过期策略内存淘汰
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.ylk9ot.asia/blog/932448.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.ylk9ot.asia/blog/163760.Doc

原标题：前端工程化 webpack 打包优化
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.ylk9ot.asia/blog/990243.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.ylk9ot.asia/blog/573701.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.ylk9ot.asia/blog/358579.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.ylk9ot.asia/blog/411512.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.ylk9ot.asia/blog/548045.Doc

原标题：golang 系统设计大文件上传架构
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.ylk9ot.asia/blog/123870.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.ylk9ot.asia/blog/833577.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.ylk9ot.asia/blog/085940.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.ylk9ot.asia/blog/462981.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.ylk9ot.asia/blog/783320.Doc

原标题：golang prometheus 告警规则编写
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.ylk9ot.asia/blog/895729.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.ylk9ot.asia/blog/344845.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.ylk9ot.asia/blog/896625.Doc

原标题：JWT 令牌过期异常处理
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.ylk9ot.asia/blog/933932.Doc

原标题：多实例部署 Session 共享方案
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.ylk9ot.asia/blog/895539.Doc

原标题：golang mysql 字符集排序规则设置
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.ylk9ot.asia/blog/118079.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.ylk9ot.asia/blog/287563.Doc


二、踩坑排错｜Troubleshooting
原标题：排错：静态资源404，打包路径配置错误
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.ylk9ot.asia/blog/455483.Doc

原标题：日志敏感信息脱敏泄露防护
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.ylk9ot.asia/blog/158937.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.ylk9ot.asia/blog/347720.Doc

原标题：限流规则误拦截正常请求修复
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.ylk9ot.asia/blog/092173.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.ylk9ot.asia/blog/254145.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.ylk9ot.asia/blog/974910.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.ylk9ot.asia/blog/836169.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.ylk9ot.asia/blog/085720.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.ylk9ot.asia/blog/892403.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.ylk9ot.asia/blog/693404.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.ylk9ot.asia/blog/125031.Doc

原标题：Nginx 请求头大小上限调整
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.ylk9ot.asia/blog/853743.Doc

原标题：golang mysql 行锁表锁场景区分
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.ylk9ot.asia/blog/202960.Doc

原标题：本地运行正常线上报错排查
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.ylk9ot.asia/blog/938549.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.ylk9ot.asia/blog/726761.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.ylk9ot.asia/blog/643586.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.ylk9ot.asia/blog/160516.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.ylk9ot.asia/blog/548702.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.ylk9ot.asia/blog/317040.Doc

原标题：跨平台 uniapp 多端开发实操
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.ylk9ot.asia/blog/896594.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.ylk9ot.asia/blog/356595.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.ylk9ot.asia/blog/343880.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.ylk9ot.asia/blog/495823.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.ylk9ot.asia/blog/871538.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.ylk9ot.asia/blog/999934.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.ylk9ot.asia/blog/990084.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.ylk9ot.asia/blog/313994.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.ylk9ot.asia/blog/324638.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.ylk9ot.asia/blog/274665.Doc

原标题：golang websocket 服务端开发
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.ylk9ot.asia/blog/143918.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.ylk9ot.asia/blog/059473.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.ylk9ot.asia/blog/642159.Doc

原标题：并发数据覆盖加锁安全处理
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.ylk9ot.asia/blog/933540.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.ylk9ot.asia/blog/191017.Doc

原标题：golang redis 缓存预热实现思路
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.ylk9ot.asia/blog/073691.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.ylk9ot.asia/blog/740854.Doc

原标题：容器软链接文件权限修复
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.ylk9ot.asia/blog/279780.Doc

原标题：DNS 解析异常第三方调用故障
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.ylk9ot.asia/blog/070355.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.ylk9ot.asia/blog/798175.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.ylk9ot.asia/blog/601880.Doc

三、实战开发｜Practice
原标题：方案设计：统一错误处理架构全链路方案
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.ylk9ot.asia/blog/526925.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.ylk9ot.asia/blog/689039.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.ylk9ot.asia/blog/481245.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.ylk9ot.asia/blog/230077.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.ylk9ot.asia/blog/013363.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.ylk9ot.asia/blog/820056.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.ylk9ot.asia/blog/758272.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.ylk9ot.asia/blog/740876.Doc

原标题：单元测试用例编写入门实操
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.ylk9ot.asia/blog/345281.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.ylk9ot.asia/blog/850998.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.ylk9ot.asia/blog/429108.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.ylk9ot.asia/blog/221085.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.ylk9ot.asia/blog/794301.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.ylk9ot.asia/blog/104043.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.ylk9ot.asia/blog/185772.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.ylk9ot.asia/blog/459302.Doc

原标题：golang mysql 主从同步延迟兼容
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.ylk9ot.asia/blog/075046.Doc

原标题：golang 系统设计序列化性能选型对比
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.ylk9ot.asia/blog/780605.Doc

原标题：golang 系统设计大文件上传架构
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.ylk9ot.asia/blog/392078.Doc

原标题：golang es 聚合统计查询实现
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.ylk9ot.asia/blog/210932.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.ylk9ot.asia/blog/442341.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.ylk9ot.asia/blog/768494.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.ylk9ot.asia/blog/253429.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.ylk9ot.asia/blog/049521.Doc

原标题：golang redis 连接池参数最佳值
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.ylk9ot.asia/blog/087691.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.ylk9ot.asia/blog/806848.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.ylk9ot.asia/blog/073938.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.ylk9ot.asia/blog/011279.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.ylk9ot.asia/blog/866604.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.ylk9ot.asia/blog/289854.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.ylk9ot.asia/blog/093069.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.ylk9ot.asia/blog/012933.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.ylk9ot.asia/blog/811760.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.ylk9ot.asia/blog/342444.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://book.ylk9ot.asia/blog/077130.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.ylk9ot.asia/blog/729459.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.ylk9ot.asia/blog/993122.Doc

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.ylk9ot.asia/blog/274495.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.ylk9ot.asia/blog/079339.Doc

原标题：golang 日志与链路 ID 关联打印
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.ylk9ot.asia/blog/652936.Doc

四、架构设计｜Architecture
原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.ylk9ot.asia/blog/290877.Doc

原标题：限流组件计数器令牌桶模式实现
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://book.ylk9ot.asia/blog/903660.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.ylk9ot.asia/blog/081981.Doc

原标题：CI 流水线构建失败日志排查
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.ylk9ot.asia/blog/811011.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.ylk9ot.asia/blog/375204.Doc

原标题：文件批量导入导出功能实现
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.ylk9ot.asia/blog/370760.Doc

原标题：express 请求参数校验处理
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.ylk9ot.asia/blog/283072.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.ylk9ot.asia/blog/849201.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.ylk9ot.asia/blog/895682.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.ylk9ot.asia/blog/106226.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.ylk9ot.asia/blog/150073.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.ylk9ot.asia/blog/995595.Doc

原标题：golang docker compose 环境变量
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.ylk9ot.asia/blog/782540.Doc

原标题：golang 配置热更新不重启服务
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.ylk9ot.asia/blog/505437.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.ylk9ot.asia/blog/596162.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.ylk9ot.asia/blog/901774.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.ylk9ot.asia/blog/561096.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.ylk9ot.asia/blog/638789.Doc

?
