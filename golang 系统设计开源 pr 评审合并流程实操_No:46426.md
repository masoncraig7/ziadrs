最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/870056.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.zpfbwd.asia/arts/127692.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.zpfbwd.asia/arts/874564.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.zpfbwd.asia/arts/420622.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.zpfbwd.asia/arts/312184.Doc

原标题：单元测试用例编写入门实操
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.zpfbwd.asia/arts/125306.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.zpfbwd.asia/arts/264922.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.zpfbwd.asia/arts/011322.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.zpfbwd.asia/arts/363570.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.zpfbwd.asia/arts/674658.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.zpfbwd.asia/arts/753743.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.zpfbwd.asia/arts/797262.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.zpfbwd.asia/arts/927144.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.zpfbwd.asia/arts/133367.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.zpfbwd.asia/arts/572803.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.zpfbwd.asia/arts/931373.Doc

原标题：nodejs 中间件模式原理剖析
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/786851.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.zpfbwd.asia/arts/057365.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.zpfbwd.asia/arts/717101.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.zpfbwd.asia/arts/119849.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.zpfbwd.asia/arts/388905.Doc

原标题：WebSocket 断线重连稳定优化
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.zpfbwd.asia/arts/159742.Doc

原标题：项目目录结构规范化最佳实践
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.zpfbwd.asia/arts/016866.Doc

原标题：服务熔断防止故障级联传播
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.zpfbwd.asia/arts/296440.Doc

原标题：golang github actions 发布 release 包
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.zpfbwd.asia/arts/977379.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/207952.Doc

原标题：golang 参数校验业务接口处理
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.zpfbwd.asia/arts/417695.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.zpfbwd.asia/arts/231522.Doc

原标题：golang 集成测试启动测试数据库
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.zpfbwd.asia/arts/617284.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.zpfbwd.asia/arts/452077.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.zpfbwd.asia/arts/404682.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/563488.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.zpfbwd.asia/arts/267069.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.zpfbwd.asia/arts/597609.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/011266.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.zpfbwd.asia/arts/166793.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.zpfbwd.asia/arts/990088.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.zpfbwd.asia/arts/567495.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.zpfbwd.asia/arts/222245.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.zpfbwd.asia/arts/346011.Doc


二、踩坑排错｜Troubleshooting
原标题：Cookie Session 会话状态管理
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/325559.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.zpfbwd.asia/arts/424124.Doc

原标题：golang 系统设计埋点数据上报方案
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/310397.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.zpfbwd.asia/arts/813221.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.zpfbwd.asia/arts/635614.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.zpfbwd.asia/arts/537695.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.zpfbwd.asia/arts/118729.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/856539.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.zpfbwd.asia/arts/713333.Doc

原标题：golang mysql 批量导入数据实操
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.zpfbwd.asia/arts/231926.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.zpfbwd.asia/arts/782239.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/574659.Doc

原标题：API 大版本不兼容平滑迁移
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.zpfbwd.asia/arts/826269.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.zpfbwd.asia/arts/198387.Doc

原标题：快速入门消息队列基础概念模型
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.zpfbwd.asia/arts/653552.Doc

原标题：版本升级服务启动失败处理
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.zpfbwd.asia/arts/675119.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.zpfbwd.asia/arts/077469.Doc

原标题：golang prometheus metrics 埋点开发
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.zpfbwd.asia/arts/538956.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.zpfbwd.asia/arts/153615.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.zpfbwd.asia/arts/215567.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.zpfbwd.asia/arts/664718.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.zpfbwd.asia/arts/069545.Doc

原标题：手写简易 RPC 服务通信原型
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.zpfbwd.asia/arts/576626.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.zpfbwd.asia/arts/577677.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.zpfbwd.asia/arts/620323.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.zpfbwd.asia/arts/774326.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.zpfbwd.asia/arts/255395.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.zpfbwd.asia/arts/266734.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.zpfbwd.asia/arts/423062.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.zpfbwd.asia/arts/048558.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.zpfbwd.asia/arts/121159.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.zpfbwd.asia/arts/995471.Doc

原标题：后端分页查询逻辑代码实现
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.zpfbwd.asia/arts/323255.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.zpfbwd.asia/arts/834326.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.zpfbwd.asia/arts/823600.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/161316.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.zpfbwd.asia/arts/045458.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.zpfbwd.asia/arts/663899.Doc

原标题：多环境配置中心灵活切换方案
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.zpfbwd.asia/arts/503844.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.zpfbwd.asia/arts/296252.Doc

三、实战开发｜Practice
原标题：golang http 代理客户端配置
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.zpfbwd.asia/arts/904370.Doc

原标题：service‑worker 离线缓存实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/042522.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.zpfbwd.asia/arts/908825.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/741887.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.zpfbwd.asia/arts/499699.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.zpfbwd.asia/arts/277366.Doc

原标题：JWT 工具封装令牌刷新过期
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.zpfbwd.asia/arts/283362.Doc

原标题：golang md5 sha 加密工具实现
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.zpfbwd.asia/arts/330922.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.zpfbwd.asia/arts/351314.Doc

原标题：golang redis 缓存击穿防护实现
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.zpfbwd.asia/arts/029026.Doc

原标题：文件描述符优化进程卡死修复
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.zpfbwd.asia/arts/500751.Doc

原标题：短信服务封装失败自动重试
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.zpfbwd.asia/arts/169309.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.zpfbwd.asia/arts/751318.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.zpfbwd.asia/arts/743746.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/987825.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.zpfbwd.asia/arts/946592.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.zpfbwd.asia/arts/070603.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/126123.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.zpfbwd.asia/arts/712423.Doc

原标题：golang mysql 慢查询日志开启分析
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.zpfbwd.asia/arts/950088.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.zpfbwd.asia/arts/029441.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.zpfbwd.asia/arts/755853.Doc

原标题：后端大文件分片上传接口开发
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/237181.Doc

原标题：golang mysql 时间类型选型避坑
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.zpfbwd.asia/arts/798888.Doc

原标题：golang mysql 存储过程简单使用
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.zpfbwd.asia/arts/899713.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.zpfbwd.asia/arts/647070.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.zpfbwd.asia/arts/892561.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.zpfbwd.asia/arts/652200.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.zpfbwd.asia/arts/206596.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.zpfbwd.asia/arts/376042.Doc

原标题：Shell 脚本自动化命令编写
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/715191.Doc

原标题：golang excel 简单读写操作示例
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.zpfbwd.asia/arts/158223.Doc

原标题：多操作系统开发兼容处理
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.zpfbwd.asia/arts/376599.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.zpfbwd.asia/arts/017301.Doc

原标题：容器资源限制防止宿主机过载
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.zpfbwd.asia/arts/359691.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.zpfbwd.asia/arts/915268.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.zpfbwd.asia/arts/495363.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/024072.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.zpfbwd.asia/arts/384715.Doc

原标题：golang redis hyperloglog 基数统计
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.zpfbwd.asia/arts/944243.Doc

四、架构设计｜Architecture
原标题：golang 项目 makefile 脚本编写
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.zpfbwd.asia/arts/071865.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.zpfbwd.asia/arts/787287.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.zpfbwd.asia/arts/232739.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.zpfbwd.asia/arts/413252.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.zpfbwd.asia/arts/192844.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/317130.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.zpfbwd.asia/arts/784151.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.zpfbwd.asia/arts/905114.Doc

原标题：多线程线程安全脏数据规避
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.zpfbwd.asia/arts/643439.Doc

原标题：golang kafka 消息顺序性保证方案
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.zpfbwd.asia/arts/547718.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.zpfbwd.asia/arts/550332.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.zpfbwd.asia/arts/654185.Doc

原标题：消息队列重复消费业务处理
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.zpfbwd.asia/arts/025746.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.zpfbwd.asia/arts/676841.Doc

原标题：前端国际化多语言方案落地
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.zpfbwd.asia/arts/866885.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.zpfbwd.asia/arts/984708.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.zpfbwd.asia/arts/489355.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.zpfbwd.asia/arts/314187.Doc

?
