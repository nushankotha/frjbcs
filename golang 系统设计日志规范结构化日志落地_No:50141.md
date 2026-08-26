最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计日志规范结构化日志落地
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.9p2k8h.asia/blog/122928.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.9p2k8h.asia/blog/538269.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.9p2k8h.asia/blog/853625.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.9p2k8h.asia/blog/788345.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.9p2k8h.asia/blog/847715.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.9p2k8h.asia/blog/120519.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.9p2k8h.asia/blog/318369.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.9p2k8h.asia/blog/890957.Doc

原标题：golang mysql 索引失效常见场景
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.9p2k8h.asia/blog/104293.Doc

原标题：golang redis 过期策略内存淘汰
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.9p2k8h.asia/blog/456434.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.9p2k8h.asia/blog/854587.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.9p2k8h.asia/blog/568414.Doc

原标题：新手参与开源社区贡献指南
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.9p2k8h.asia/blog/022216.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.9p2k8h.asia/blog/126273.Doc

原标题：golang gin 路由分组权限管控
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.9p2k8h.asia/blog/820547.Doc

原标题：内存泄漏定位分析完整流程
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.9p2k8h.asia/blog/063097.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.9p2k8h.asia/blog/663292.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.9p2k8h.asia/blog/012687.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.9p2k8h.asia/blog/046982.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.9p2k8h.asia/blog/202207.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.9p2k8h.asia/blog/573903.Doc

原标题：跨库查询性能优化处理
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.9p2k8h.asia/blog/296541.Doc

原标题：从零搭建本地数据库开发环境
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/348155.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.9p2k8h.asia/blog/757994.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.9p2k8h.asia/blog/791926.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.9p2k8h.asia/blog/529460.Doc

原标题：golang redis 过期策略内存淘汰
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.9p2k8h.asia/blog/407936.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.9p2k8h.asia/blog/382522.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.9p2k8h.asia/blog/234032.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.9p2k8h.asia/blog/719763.Doc

原标题：nodejs 跨域中间件配置细节
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.9p2k8h.asia/blog/193283.Doc

原标题：golang mysql limit 大分页优化
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.9p2k8h.asia/blog/990668.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.9p2k8h.asia/blog/087329.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.9p2k8h.asia/blog/260151.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.9p2k8h.asia/blog/368623.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.9p2k8h.asia/blog/596815.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.9p2k8h.asia/blog/041317.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.9p2k8h.asia/blog/901370.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.9p2k8h.asia/blog/471305.Doc

原标题：golang channel 通道并发处理
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.9p2k8h.asia/blog/678513.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/490077.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.9p2k8h.asia/blog/277465.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/130323.Doc

原标题：golang 工具函数库封装思路
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.9p2k8h.asia/blog/773197.Doc

原标题：golang docker 部署 mysql 注意事项
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.9p2k8h.asia/blog/560687.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.9p2k8h.asia/blog/312383.Doc

原标题：golang 互斥锁读写锁并发安全
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.9p2k8h.asia/blog/166209.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.9p2k8h.asia/blog/569772.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.9p2k8h.asia/blog/296946.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.9p2k8h.asia/blog/791698.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.9p2k8h.asia/blog/342862.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.9p2k8h.asia/blog/922487.Doc

原标题：golang docker 部署 mysql 注意事项
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.9p2k8h.asia/blog/621730.Doc

原标题：nodejs 全局异常捕获进程防护
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/152156.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.9p2k8h.asia/blog/899549.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.9p2k8h.asia/blog/953943.Doc

原标题：空指针异常判空容错处理
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.9p2k8h.asia/blog/715160.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.9p2k8h.asia/blog/909883.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.9p2k8h.asia/blog/912093.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.9p2k8h.asia/blog/317712.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.9p2k8h.asia/blog/652276.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.9p2k8h.asia/blog/142364.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.9p2k8h.asia/blog/707733.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.9p2k8h.asia/blog/902277.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.9p2k8h.asia/blog/233605.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.9p2k8h.asia/blog/293066.Doc

原标题：golang html 模板渲染简单示例
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.9p2k8h.asia/blog/571474.Doc

原标题：HTTPS 证书过期更新操作
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.9p2k8h.asia/blog/297429.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.9p2k8h.asia/blog/188406.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.9p2k8h.asia/blog/374224.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.9p2k8h.asia/blog/267433.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.9p2k8h.asia/blog/766283.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.9p2k8h.asia/blog/311118.Doc

原标题：零基础学习简单正则表达式实战案例
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.9p2k8h.asia/blog/428107.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.9p2k8h.asia/blog/464480.Doc

原标题：从零搭建简单的健康检查接口示例
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.9p2k8h.asia/blog/906196.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.9p2k8h.asia/blog/558339.Doc

原标题：golang rsa 非对称加密签名验签
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.9p2k8h.asia/blog/004390.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.9p2k8h.asia/blog/292848.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.9p2k8h.asia/blog/852101.Doc

三、实战开发｜Practice
原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.9p2k8h.asia/blog/001399.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.9p2k8h.asia/blog/499124.Doc

原标题：rebase 操作防止代码丢失
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.9p2k8h.asia/blog/153530.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.9p2k8h.asia/blog/696436.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.9p2k8h.asia/blog/290824.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.9p2k8h.asia/blog/117256.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.9p2k8h.asia/blog/312817.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.9p2k8h.asia/blog/406370.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.9p2k8h.asia/blog/922078.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.9p2k8h.asia/blog/425167.Doc

原标题：端口占用访问失败排查方案
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.9p2k8h.asia/blog/112965.Doc

原标题：golang grafana 面板变量模板制作
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://book.9p2k8h.asia/blog/075852.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.9p2k8h.asia/blog/156446.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.9p2k8h.asia/blog/911043.Doc

原标题：Shell 脚本自动化命令编写
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.9p2k8h.asia/blog/119943.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.9p2k8h.asia/blog/629009.Doc

原标题：golang excel 简单读写操作示例
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.9p2k8h.asia/blog/517731.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.9p2k8h.asia/blog/713633.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.9p2k8h.asia/blog/382213.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.9p2k8h.asia/blog/234654.Doc

原标题：服务启动依赖顺序配置正确
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://book.9p2k8h.asia/blog/842120.Doc

原标题：golang redis pipeline 原子性说明
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.9p2k8h.asia/blog/532637.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/829597.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.9p2k8h.asia/blog/816102.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.9p2k8h.asia/blog/899810.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/070221.Doc

原标题：golang kafka 监控指标简单梳理
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.9p2k8h.asia/blog/037269.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.9p2k8h.asia/blog/408747.Doc

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.9p2k8h.asia/blog/259450.Doc

原标题：Redis 分布式锁高并发安全实现
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.9p2k8h.asia/blog/003070.Doc

原标题：文件锁正确使用避免死锁
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.9p2k8h.asia/blog/897519.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.9p2k8h.asia/blog/046195.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.9p2k8h.asia/blog/414485.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.9p2k8h.asia/blog/319989.Doc

原标题：golang 系统设计日志系统架构思路
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.9p2k8h.asia/blog/454795.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/532557.Doc

原标题：布隆过滤器误判问题修正
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.9p2k8h.asia/blog/365679.Doc

原标题：缓存基础原理与简单代码实现
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.9p2k8h.asia/blog/557713.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.9p2k8h.asia/blog/128168.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.9p2k8h.asia/blog/076662.Doc

四、架构设计｜Architecture
原标题：golang redis 事务 multi exec 使用
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.9p2k8h.asia/blog/855473.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.9p2k8h.asia/blog/454376.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.9p2k8h.asia/blog/708877.Doc

原标题：接口请求重试容错机制实现
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.9p2k8h.asia/blog/047470.Doc

原标题：数据库索引重建提升查询速度
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.9p2k8h.asia/blog/960079.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.9p2k8h.asia/blog/066153.Doc

原标题：golang 跨域处理中间件编写
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.9p2k8h.asia/blog/411594.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.9p2k8h.asia/blog/946941.Doc

原标题：golang mysql exists in 性能对比
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.9p2k8h.asia/blog/376527.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.9p2k8h.asia/blog/155815.Doc

原标题：TCP 心跳检测清理僵死连接
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.9p2k8h.asia/blog/381236.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.9p2k8h.asia/blog/192755.Doc

原标题：简易网关请求路由过滤模拟
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.9p2k8h.asia/blog/847773.Doc

原标题：后端分页查询逻辑代码实现
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.9p2k8h.asia/blog/504376.Doc

原标题：golang prometheus 告警规则编写
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.9p2k8h.asia/blog/520032.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.9p2k8h.asia/blog/290809.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.9p2k8h.asia/blog/274025.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.9p2k8h.asia/blog/920393.Doc

?
