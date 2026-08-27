最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计多级缓存架构落地
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.nzmxfj.asia/blog/8510689.sHtMl

原标题：golang 系统设计雪花算法 id 原理剖析
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.nzmxfj.asia/blog/1542654.sHtMl

原标题：nodejs 中间件模式原理剖析
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.nzmxfj.asia/blog/3808654.sHtMl

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.nzmxfj.asia/blog/3020922.sHtMl

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.nzmxfj.asia/blog/0317093.sHtMl

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.nzmxfj.asia/blog/6163900.sHtMl

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.nzmxfj.asia/blog/7691263.sHtMl

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.nzmxfj.asia/blog/4431355.sHtMl

原标题：开发代理服务网络限制解决
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.nzmxfj.asia/blog/7936947.sHtMl

原标题：golang 系统设计异步化改造业务流程思路
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.nzmxfj.asia/blog/1226729.sHtMl

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.nzmxfj.asia/blog/8725433.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.nzmxfj.asia/blog/9020408.sHtMl

原标题：golang 系统设计数据库死锁分析规避
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.nzmxfj.asia/blog/2420682.sHtMl

原标题：golang github actions 多平台构建
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.nzmxfj.asia/blog/7410619.sHtMl

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.nzmxfj.asia/blog/9401155.sHtMl

原标题：开源项目构建失败排查步骤
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.nzmxfj.asia/blog/4840864.sHtMl

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.nzmxfj.asia/blog/4251582.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.nzmxfj.asia/blog/3849430.sHtMl

原标题：安全实践：备份文件访问权限安全管控
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.nzmxfj.asia/blog/4506095.sHtMl

原标题：坑点：gitreset误删本地代码恢复方案
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.nzmxfj.asia/blog/7386747.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.nzmxfj.asia/blog/0701800.sHtMl

原标题：golang prometheus histogram 指标
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.nzmxfj.asia/blog/1058112.sHtMl

原标题：golang grafana 监控面板简单配置
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.nzmxfj.asia/blog/6780987.sHtMl

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.nzmxfj.asia/blog/4954007.sHtMl

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.nzmxfj.asia/blog/2431064.sHtMl

原标题：golang mysql 批量导入数据实操
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.nzmxfj.asia/blog/1099147.sHtMl

原标题：Architecture：鉴权授权系统架构设计思路
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.nzmxfj.asia/blog/9477388.sHtMl

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.nzmxfj.asia/blog/1379321.sHtMl

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.nzmxfj.asia/blog/4525252.sHtMl

原标题：手写简易 MQ 理解消息存储消费
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.nzmxfj.asia/blog/2191266.sHtMl

原标题：golang kafka 重试机制配置实操
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.nzmxfj.asia/blog/5137921.sHtMl

原标题：golang k8s 资源请求限制配置
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.nzmxfj.asia/blog/7944079.sHtMl

原标题：golang 系统设计依赖版本升级风险评估
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.nzmxfj.asia/blog/1046098.sHtMl

原标题：配置外部化线上部署防错误
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.nzmxfj.asia/blog/5217341.sHtMl

原标题：零基础理解版本控制核心概念与工作流
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.nzmxfj.asia/blog/0296996.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.nzmxfj.asia/blog/4210510.sHtMl

原标题：SDK 版本兼容线上崩溃修复
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.nzmxfj.asia/blog/2191347.sHtMl

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.nzmxfj.asia/blog/8245490.sHtMl

原标题：请求重试组件退避策略实现
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.nzmxfj.asia/blog/3052588.sHtMl

原标题：golang 系统设计降级策略开关配置方案
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.nzmxfj.asia/blog/4581247.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.nzmxfj.asia/blog/8799514.sHtMl

原标题：golang 系统设计线上故障排查完整流程
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.nzmxfj.asia/blog/8909436.sHtMl

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.nzmxfj.asia/blog/2248355.sHtMl

原标题：特殊输入字符过滤解析防护
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.nzmxfj.asia/blog/5053461.sHtMl

原标题：快速入门消息队列基础概念模型
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.nzmxfj.asia/blog/0763351.sHtMl

原标题：golang defer panic 异常处理
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.nzmxfj.asia/blog/6618468.sHtMl

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.nzmxfj.asia/blog/2099409.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.nzmxfj.asia/blog/8934017.sHtMl

原标题：Hands‑on：简易消息推送服务开发实践
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.nzmxfj.asia/blog/9952141.sHtMl

原标题：golang 错误包装 errors.wrap 用法
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.nzmxfj.asia/blog/2340039.sHtMl

原标题：golang gorm ORM 数据库操作
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.nzmxfj.asia/blog/6245022.sHtMl

原标题：golang redis 锁超时业务处理
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.nzmxfj.asia/blog/5811329.sHtMl

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.nzmxfj.asia/blog/1236502.sHtMl

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.nzmxfj.asia/blog/0686299.sHtMl

原标题：WebSocket 断线重连稳定优化
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.nzmxfj.asia/blog/8519363.sHtMl

原标题：golang 系统设计大流量削峰处理方案
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.nzmxfj.asia/blog/5409064.sHtMl

原标题：慢查询分析索引调优数据库实战
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.nzmxfj.asia/blog/6140432.sHtMl

原标题：golang url 参数编码处理方案
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.nzmxfj.asia/blog/5649604.sHtMl

原标题：开源实践：开源项目如何写好PullRequest
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.nzmxfj.asia/blog/0428579.sHtMl

原标题：缓存穿透防护保护数据库
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.nzmxfj.asia/blog/3314821.sHtMl

原标题：零基础理解依赖管理与包管理器
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.nzmxfj.asia/blog/8686603.sHtMl

原标题：golang redis 热点 key 业务规避
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.nzmxfj.asia/blog/5891057.sHtMl

原标题：运维笔记：服务器日志轮转logrotate配置
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.nzmxfj.asia/blog/2916296.sHtMl

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.nzmxfj.asia/blog/5919240.sHtMl

原标题：从零搭建简单定时任务demo
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.nzmxfj.asia/blog/9388339.sHtMl

原标题：golang 告警推送钉钉机器人实现
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.nzmxfj.asia/blog/9661726.sHtMl

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.nzmxfj.asia/blog/4835751.sHtMl

原标题：golang 信号量控制并发数量
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.nzmxfj.asia/blog/5957301.sHtMl

原标题：安全组端口开放网络访问
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.nzmxfj.asia/blog/4532136.sHtMl

原标题：请求重试组件退避策略实现
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.nzmxfj.asia/blog/6163864.sHtMl

原标题：Git 误删提交代码恢复找回
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.nzmxfj.asia/blog/6857179.sHtMl

原标题：golang proto 默认值坑点梳理
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.nzmxfj.asia/blog/6357616.sHtMl

原标题：异步任务堆积消费能力优化
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.nzmxfj.asia/blog/6245632.sHtMl

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.nzmxfj.asia/blog/3172953.sHtMl

原标题：golang 集成测试启动测试数据库
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.nzmxfj.asia/blog/4502678.sHtMl

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.nzmxfj.asia/blog/2359753.sHtMl

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.nzmxfj.asia/blog/7498898.sHtMl

原标题：golang mysql 长连接短连接对比
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.nzmxfj.asia/blog/7780880.sHtMl

原标题：开发复盘：超时参数统一治理线上服务实践
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.nzmxfj.asia/blog/8224117.sHtMl

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.nzmxfj.asia/blog/7677251.sHtMl

三、实战开发｜Practice
原标题：数据库索引重建提升查询速度
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.nzmxfj.asia/blog/0198666.sHtMl

原标题：Nginx 请求头大小上限调整
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.nzmxfj.asia/blog/0089789.sHtMl

原标题：golang 项目 docker compose 本地调试
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.nzmxfj.asia/blog/0072424.sHtMl

原标题：golang 数据库批量更新性能优化
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.nzmxfj.asia/blog/5312423.sHtMl

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.nzmxfj.asia/blog/1383948.sHtMl

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.nzmxfj.asia/blog/4435564.sHtMl

原标题：golang 系统设计故障预案编写模板参考示例
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.nzmxfj.asia/blog/4683594.sHtMl

原标题：nodejs 脚手架工具开发完整教程
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.nzmxfj.asia/blog/2032429.sHtMl

原标题：golang 系统设计线上日志快速检索技巧
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://book.nzmxfj.asia/blog/1680726.sHtMl

原标题：golang 定时任务 cron 使用指南
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.nzmxfj.asia/blog/5420776.sHtMl

原标题：快速入门日志打印与日志分级基础用法
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.nzmxfj.asia/blog/7832546.sHtMl

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.nzmxfj.asia/blog/6757158.sHtMl

原标题：golang 结构体 json 序列化坑点
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.nzmxfj.asia/blog/0022387.sHtMl

原标题：优化实践：内存池思想减少频繁分配释放
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.nzmxfj.asia/blog/3429983.sHtMl

原标题：程序性能指标 CPU 内存监控
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.nzmxfj.asia/blog/9457198.sHtMl

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.nzmxfj.asia/blog/2304627.sHtMl

原标题：静态网页 HTML CSS 快速入门实战
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.nzmxfj.asia/blog/4504353.sHtMl

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.nzmxfj.asia/blog/0860573.sHtMl

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.nzmxfj.asia/blog/2719704.sHtMl

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.nzmxfj.asia/blog/2917656.sHtMl

原标题：跨平台 uniapp 多端开发实操
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.nzmxfj.asia/blog/7231354.sHtMl

原标题：golang grafana 面板变量模板制作
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.nzmxfj.asia/blog/5323307.sHtMl

原标题：编译打包产物依赖分析解读
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.nzmxfj.asia/blog/8566610.sHtMl

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.nzmxfj.asia/blog/1902101.sHtMl

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.nzmxfj.asia/blog/9642722.sHtMl

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.nzmxfj.asia/blog/5616156.sHtMl

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.nzmxfj.asia/blog/0939032.sHtMl

原标题：从零搭建简单定时任务demo
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.nzmxfj.asia/blog/2315340.sHtMl

原标题：golang 接口限流中间件开发
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.nzmxfj.asia/blog/6199323.sHtMl

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.nzmxfj.asia/blog/9650909.sHtMl

原标题：golang pprof 线上采集性能数据
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.nzmxfj.asia/blog/0780754.sHtMl

原标题：golang kafka 消费者组原理讲解
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.nzmxfj.asia/blog/0561314.sHtMl

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.nzmxfj.asia/blog/2350272.sHtMl

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.nzmxfj.asia/blog/8602118.sHtMl

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.nzmxfj.asia/blog/3587094.sHtMl

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.nzmxfj.asia/blog/9182893.sHtMl

原标题：golang 系统设计秒杀防超卖方案
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.nzmxfj.asia/blog/7972456.sHtMl

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.nzmxfj.asia/blog/7830759.sHtMl

原标题：golang 系统设计服务优雅停机完整流程
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.nzmxfj.asia/blog/2476376.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.nzmxfj.asia/blog/5072133.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计数据库查询优化完整流程
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://book.nzmxfj.asia/blog/8263149.sHtMl

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.nzmxfj.asia/blog/9618612.sHtMl

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.nzmxfj.asia/blog/6177913.sHtMl

原标题：HTTP 状态码请求头完整梳理
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.nzmxfj.asia/blog/5022751.sHtMl

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.nzmxfj.asia/blog/2013076.sHtMl

原标题：golang goroutine 协程基础实操
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.nzmxfj.asia/blog/4147462.sHtMl

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.nzmxfj.asia/blog/2636041.sHtMl

原标题：调优方案：Web服务内核socket参数调优
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.nzmxfj.asia/blog/9663269.sHtMl

原标题：对象存储上传下载权限实操
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.nzmxfj.asia/blog/7271820.sHtMl

原标题：macOS 脚本执行权限开启
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.nzmxfj.asia/blog/2063330.sHtMl

原标题：系统时间同步定时任务偏移
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.nzmxfj.asia/blog/0724977.sHtMl

原标题：golang mongodb 聚合管道实操案例
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.nzmxfj.asia/blog/4768138.sHtMl

原标题：Debug：网关超时时间小于后端接口超时设置
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.nzmxfj.asia/blog/6881748.sHtMl

原标题：安全组端口开放网络访问
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.nzmxfj.asia/blog/5676319.sHtMl

原标题：golang 优雅处理 http 超时设置
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.nzmxfj.asia/blog/5096721.sHtMl

原标题：设计思考：API网关和BFF职责边界划分
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.nzmxfj.asia/blog/4975471.sHtMl

原标题：Security：服务器最小权限账号运维实践
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.nzmxfj.asia/blog/7218354.sHtMl

原标题：消息队列重复消费业务处理
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.nzmxfj.asia/blog/0137977.sHtMl

?
