最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现请求ID透传全链路日志实践
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.weiz0k.asia/arts/084411.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.weiz0k.asia/arts/446950.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.weiz0k.asia/arts/859057.Doc

原标题：golang github actions 缓存依赖提速
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.weiz0k.asia/arts/680371.Doc

原标题：golang 数据库批量更新性能优化
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.weiz0k.asia/arts/181468.Doc

原标题：golang 系统设计错误码体系完整设计
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.weiz0k.asia/arts/156397.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.weiz0k.asia/arts/652667.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.weiz0k.asia/arts/382738.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.weiz0k.asia/arts/989525.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.weiz0k.asia/arts/042575.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.weiz0k.asia/arts/525185.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.weiz0k.asia/arts/127715.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.weiz0k.asia/arts/711804.Doc

原标题：Nginx 反向代理路由配置实战
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.weiz0k.asia/arts/129589.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.weiz0k.asia/arts/314704.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.weiz0k.asia/arts/006504.Doc

原标题：nodejs http 服务性能调优实战
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.weiz0k.asia/arts/085341.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.weiz0k.asia/arts/923882.Doc

原标题：消息队列重复消费业务处理
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.weiz0k.asia/arts/575588.Doc

原标题：golang 内存缓存简单实现方案
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.weiz0k.asia/arts/231760.Doc

原标题：golang 链路追踪简易实现方案
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.weiz0k.asia/arts/943700.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.weiz0k.asia/arts/296526.Doc

原标题：静态资源 404 路径打包修复
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.weiz0k.asia/arts/417180.Doc

原标题：上传接口跨域配置特殊适配
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.weiz0k.asia/arts/493423.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.weiz0k.asia/arts/896996.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.weiz0k.asia/arts/072919.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.weiz0k.asia/arts/427254.Doc

原标题：golang elasticsearch 索引设计思路
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.weiz0k.asia/arts/863952.Doc

原标题：golang redis 批量 pipeline 实践
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.weiz0k.asia/arts/744010.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.weiz0k.asia/arts/633112.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.weiz0k.asia/arts/532293.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.weiz0k.asia/arts/261044.Doc

原标题：快速入门消息队列基础概念模型
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.weiz0k.asia/arts/385323.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.weiz0k.asia/arts/666541.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.weiz0k.asia/arts/160397.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.weiz0k.asia/arts/343536.Doc

原标题：golang k8s helm chart 简单编写
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.weiz0k.asia/arts/766546.Doc

原标题：golang 优雅处理 http 超时设置
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.weiz0k.asia/arts/051701.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.weiz0k.asia/arts/012946.Doc

原标题：时间精度统一业务判断修复
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.weiz0k.asia/arts/371780.Doc


二、踩坑排错｜Troubleshooting
原标题：MySQL 慢查询索引优化实战
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.weiz0k.asia/arts/344102.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.weiz0k.asia/arts/935753.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.weiz0k.asia/arts/049948.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.weiz0k.asia/arts/713246.Doc

原标题：新手教程：本地环境变量配置全流程
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.weiz0k.asia/arts/202175.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.weiz0k.asia/arts/874291.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.weiz0k.asia/arts/120988.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.weiz0k.asia/arts/397439.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.weiz0k.asia/arts/089813.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.weiz0k.asia/arts/633586.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.weiz0k.asia/arts/390637.Doc

原标题：golang kafka 生产者参数调优
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.weiz0k.asia/arts/838852.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.weiz0k.asia/arts/507451.Doc

原标题：golang 分库分表简单路由实现
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.weiz0k.asia/arts/547460.Doc

原标题：express 请求参数校验处理
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.weiz0k.asia/arts/153961.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.weiz0k.asia/arts/961702.Doc

原标题：golang mock 单元测试编写技巧
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.weiz0k.asia/arts/383006.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.weiz0k.asia/arts/118979.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.weiz0k.asia/arts/566652.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.weiz0k.asia/arts/166716.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.weiz0k.asia/arts/386670.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.weiz0k.asia/arts/756021.Doc

原标题：从零编写简易 CLI 命令行工具
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.weiz0k.asia/arts/935054.Doc

原标题：golang 接口限流中间件开发
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.weiz0k.asia/arts/762522.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.weiz0k.asia/arts/350557.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.weiz0k.asia/arts/417827.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.weiz0k.asia/arts/739856.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.weiz0k.asia/arts/045926.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.weiz0k.asia/arts/456141.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.weiz0k.asia/arts/528051.Doc

原标题：SourceMap 生成线上报错定位
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.weiz0k.asia/arts/615761.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.weiz0k.asia/arts/302427.Doc

原标题：golang etcd 分布式锁实现原理
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.weiz0k.asia/arts/651832.Doc

原标题：golang docker 部署 mysql 注意事项
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.weiz0k.asia/arts/565553.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.weiz0k.asia/arts/244179.Doc

原标题：golang 简单爬虫请求防封禁
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.weiz0k.asia/arts/460665.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.weiz0k.asia/arts/890927.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.weiz0k.asia/arts/498447.Doc

原标题：golang es 聚合统计查询实现
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.weiz0k.asia/arts/089736.Doc

原标题：内网测试服务搭建团队调试
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.weiz0k.asia/arts/146409.Doc

三、实战开发｜Practice
原标题：golang 内存 pprof 定位内存泄漏
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.weiz0k.asia/arts/203840.Doc

原标题：后端分页查询逻辑代码实现
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.weiz0k.asia/arts/267668.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.weiz0k.asia/arts/012541.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.weiz0k.asia/arts/978820.Doc

原标题：golang 系统设计故障演练简单思路
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.weiz0k.asia/arts/412847.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.weiz0k.asia/arts/800240.Doc

原标题：序列化版本不一致解析失败
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.weiz0k.asia/arts/155886.Doc

原标题：golang 协程泄露问题排查方法
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.weiz0k.asia/arts/240231.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.weiz0k.asia/arts/496504.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.weiz0k.asia/arts/744287.Doc

原标题：开发环境变量配置全平台教程
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.weiz0k.asia/arts/458038.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.weiz0k.asia/arts/617653.Doc

原标题：从零搭建本地数据库开发环境
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.weiz0k.asia/arts/825168.Doc

原标题：golang yaml 解析配置加载实操
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.weiz0k.asia/arts/057873.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.weiz0k.asia/arts/441408.Doc

原标题：golang pprof 线上采集性能数据
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.weiz0k.asia/arts/305602.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.weiz0k.asia/arts/299001.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.weiz0k.asia/arts/074277.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.weiz0k.asia/arts/299819.Doc

原标题：程序日志分级输出规范实践
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.weiz0k.asia/arts/378172.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.weiz0k.asia/arts/841286.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.weiz0k.asia/arts/751152.Doc

原标题：webpack chunk 分包策略详解
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.weiz0k.asia/arts/829438.Doc

原标题：golang 分布式上下文传递方案
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.weiz0k.asia/arts/301053.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.weiz0k.asia/arts/531656.Doc

原标题：前端静态缓存更新生效处理
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.weiz0k.asia/arts/783511.Doc

原标题：golang aes 对称加密解密示例
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.weiz0k.asia/arts/507698.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.weiz0k.asia/arts/674954.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.weiz0k.asia/arts/240064.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.weiz0k.asia/arts/345186.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.weiz0k.asia/arts/621208.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.weiz0k.asia/arts/349927.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.weiz0k.asia/arts/785734.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.weiz0k.asia/arts/337924.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.weiz0k.asia/arts/395372.Doc

原标题：nodejs 消息队列消费服务开发
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.weiz0k.asia/arts/272653.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.weiz0k.asia/arts/260992.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.weiz0k.asia/arts/372847.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.weiz0k.asia/arts/604667.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.weiz0k.asia/arts/212149.Doc

四、架构设计｜Architecture
原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.weiz0k.asia/arts/039614.Doc

原标题：大文件导出内存溢出防护
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.weiz0k.asia/arts/729885.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.weiz0k.asia/arts/347090.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.weiz0k.asia/arts/217312.Doc

原标题：环境变量不生效问题修复
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.weiz0k.asia/arts/204396.Doc

原标题：项目语义化版本号规范管理
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.weiz0k.asia/arts/493916.Doc

原标题：golang docker 基础命令实操汇总
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.weiz0k.asia/arts/237394.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.weiz0k.asia/arts/514473.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.weiz0k.asia/arts/007068.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.weiz0k.asia/arts/126523.Doc

原标题：文件编码统一随机乱码修复
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.weiz0k.asia/arts/788305.Doc

原标题：开源项目本地运行排错完整清单
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.weiz0k.asia/arts/632520.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.weiz0k.asia/arts/274725.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.weiz0k.asia/arts/010300.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.weiz0k.asia/arts/520591.Doc

原标题：容器软链接文件权限修复
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.weiz0k.asia/arts/410635.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.weiz0k.asia/arts/817285.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.weiz0k.asia/arts/179829.Doc

?
