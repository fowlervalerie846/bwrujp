最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.9jnxlh.asia/arts/596791.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.9jnxlh.asia/arts/664455.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.9jnxlh.asia/arts/699041.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.9jnxlh.asia/arts/953266.Doc

原标题：golang prometheus histogram 指标
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/368291.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.9jnxlh.asia/arts/340130.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/283401.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.9jnxlh.asia/arts/686497.Doc

原标题：golang redis 过期策略内存淘汰
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.9jnxlh.asia/arts/696173.Doc

原标题：GET POST 接口请求参数处理
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.9jnxlh.asia/arts/542293.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.9jnxlh.asia/arts/997504.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.9jnxlh.asia/arts/170840.Doc

原标题：golang docker 部署 mysql 注意事项
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.9jnxlh.asia/arts/739288.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.9jnxlh.asia/arts/688942.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/783229.Doc

原标题：多规则数据脱敏组件开发
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.9jnxlh.asia/arts/680412.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/910879.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.9jnxlh.asia/arts/427637.Doc

原标题：golang 数据库批量更新性能优化
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.9jnxlh.asia/arts/744792.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.9jnxlh.asia/arts/379023.Doc

原标题：日志驱动异常日志不输出修复
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.9jnxlh.asia/arts/609875.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.9jnxlh.asia/arts/202380.Doc

原标题：golang docker compose 完整语法
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.9jnxlh.asia/arts/076301.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.9jnxlh.asia/arts/118225.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.9jnxlh.asia/arts/497236.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.9jnxlh.asia/arts/856436.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.9jnxlh.asia/arts/501303.Doc

原标题：分布式锁失效问题排查修复
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.9jnxlh.asia/arts/597314.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.9jnxlh.asia/arts/729324.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.9jnxlh.asia/arts/332720.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.9jnxlh.asia/arts/295550.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.9jnxlh.asia/arts/593114.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.9jnxlh.asia/arts/332505.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.9jnxlh.asia/arts/252817.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/453751.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/790066.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.9jnxlh.asia/arts/783563.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/798709.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.9jnxlh.asia/arts/668907.Doc

原标题：golang 文件上传下载接口开发
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.9jnxlh.asia/arts/080414.Doc


二、踩坑排错｜Troubleshooting
原标题：从零学习基础的接口请求与参数处理
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.9jnxlh.asia/arts/363336.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.9jnxlh.asia/arts/373204.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.9jnxlh.asia/arts/580333.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.9jnxlh.asia/arts/738385.Doc

原标题：灰度发布策略服务平滑升级
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.9jnxlh.asia/arts/588189.Doc

原标题：SourceMap 生成线上报错定位
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.9jnxlh.asia/arts/614533.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.9jnxlh.asia/arts/786945.Doc

原标题：K8s 镜像拉取网络故障修复
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/321669.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.9jnxlh.asia/arts/142071.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.9jnxlh.asia/arts/144606.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.9jnxlh.asia/arts/321133.Doc

原标题：golang 雪花 id 重复问题排查
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/951997.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.9jnxlh.asia/arts/154406.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.9jnxlh.asia/arts/070068.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.9jnxlh.asia/arts/452397.Doc

原标题：golang es 映射 mapping 设计避坑
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.9jnxlh.asia/arts/109359.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.9jnxlh.asia/arts/954473.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.9jnxlh.asia/arts/278262.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.9jnxlh.asia/arts/508593.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.9jnxlh.asia/arts/275118.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.9jnxlh.asia/arts/525984.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.9jnxlh.asia/arts/339058.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.9jnxlh.asia/arts/236929.Doc

原标题：golang 系统设计分布式锁选型对比
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/828813.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.9jnxlh.asia/arts/680156.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.9jnxlh.asia/arts/278744.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.9jnxlh.asia/arts/580631.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.9jnxlh.asia/arts/888925.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.9jnxlh.asia/arts/428172.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/155036.Doc

原标题：nodejs http 服务性能调优实战
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/011592.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/320700.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.9jnxlh.asia/arts/922388.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.9jnxlh.asia/arts/765200.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.9jnxlh.asia/arts/135894.Doc

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.9jnxlh.asia/arts/967752.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.9jnxlh.asia/arts/114218.Doc

原标题：golang redis 集群 hash 槽讲解
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.9jnxlh.asia/arts/487173.Doc

原标题：CORS 跨域问题多种解决方案
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.9jnxlh.asia/arts/070476.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.9jnxlh.asia/arts/294009.Doc

三、实战开发｜Practice
原标题：接口限流逻辑简单模拟实现
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.9jnxlh.asia/arts/902813.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/153695.Doc

原标题：golang 优雅处理 http 超时设置
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.9jnxlh.asia/arts/520413.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.9jnxlh.asia/arts/491320.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.9jnxlh.asia/arts/042576.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/509611.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/895725.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/468890.Doc

原标题：golang docker 部署 mysql 注意事项
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.9jnxlh.asia/arts/998857.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.9jnxlh.asia/arts/470294.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.9jnxlh.asia/arts/374395.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.9jnxlh.asia/arts/538951.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.9jnxlh.asia/arts/687550.Doc

原标题：GET POST 接口请求参数处理
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.9jnxlh.asia/arts/821776.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.9jnxlh.asia/arts/374621.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.9jnxlh.asia/arts/950081.Doc

原标题：golang 系统设计 README 开源文档模板
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/678455.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.9jnxlh.asia/arts/735218.Doc

原标题：极简方式搭建个人技术文档站点
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.9jnxlh.asia/arts/082969.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/054672.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.9jnxlh.asia/arts/897909.Doc

原标题：文件编码统一随机乱码修复
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.9jnxlh.asia/arts/377006.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.9jnxlh.asia/arts/920280.Doc

原标题：Git 混乱提交历史清理方法
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/743948.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/836330.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.9jnxlh.asia/arts/186917.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.9jnxlh.asia/arts/580180.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/342880.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.9jnxlh.asia/arts/040355.Doc

原标题：Performance：JSON序列化性能优化实践
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.9jnxlh.asia/arts/346085.Doc

原标题：golang gorm 预加载关联查询优化
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.9jnxlh.asia/arts/521610.Doc

原标题：golang http 代理客户端配置
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.9jnxlh.asia/arts/289349.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.9jnxlh.asia/arts/116946.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.9jnxlh.asia/arts/258012.Doc

原标题：golang etcd 租约 lease 过期机制
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.9jnxlh.asia/arts/249038.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.9jnxlh.asia/arts/017661.Doc

原标题：大文件导出内存溢出防护
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/208655.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.9jnxlh.asia/arts/050736.Doc

原标题：排错：前端缓存304异常更新不及时
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.9jnxlh.asia/arts/139067.Doc

原标题：死信队列处理消息阻塞业务
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/220796.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.9jnxlh.asia/arts/269961.Doc

原标题：本地简易配置中心动态管理
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/349377.Doc

原标题：任务执行锁防止并发重复调度
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.9jnxlh.asia/arts/751136.Doc

原标题：热更新开发环境配置教程
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.9jnxlh.asia/arts/905587.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.9jnxlh.asia/arts/225977.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/699918.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.9jnxlh.asia/arts/746947.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.9jnxlh.asia/arts/869247.Doc

原标题：golang redis lua 脚本原子操作
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.9jnxlh.asia/arts/159498.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.9jnxlh.asia/arts/549033.Doc

原标题：文件读写与异常捕获代码示例
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.9jnxlh.asia/arts/868181.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.9jnxlh.asia/arts/862851.Doc

原标题：eslint prettier 代码规范落地
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.9jnxlh.asia/arts/995261.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/881517.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/531176.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.9jnxlh.asia/arts/591842.Doc

原标题：golang redis 批量 pipeline 实践
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.9jnxlh.asia/arts/277022.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.9jnxlh.asia/arts/277246.Doc

?
