最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang mysql 长连接短连接对比
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.fh21a7.asia/arts/563911.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.fh21a7.asia/arts/089781.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.fh21a7.asia/arts/524484.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.fh21a7.asia/arts/607770.Doc

原标题：golang cron 定时任务防并发执行
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.fh21a7.asia/arts/978181.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.fh21a7.asia/arts/515486.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.fh21a7.asia/arts/088969.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.fh21a7.asia/arts/285248.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.fh21a7.asia/arts/041405.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.fh21a7.asia/arts/906607.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.fh21a7.asia/arts/095163.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.fh21a7.asia/arts/145047.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.fh21a7.asia/arts/946993.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.fh21a7.asia/arts/139258.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.fh21a7.asia/arts/564497.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.fh21a7.asia/arts/896555.Doc

原标题：golang jwt 过期刷新 token 实现
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.fh21a7.asia/arts/365460.Doc

原标题：golang k8s ingress 路由域名转发
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.fh21a7.asia/arts/302106.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.fh21a7.asia/arts/196747.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.fh21a7.asia/arts/303915.Doc

原标题：端口占用释放资源重启服务
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.fh21a7.asia/arts/530352.Doc

原标题：分布式任务调度集群原型开发
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.fh21a7.asia/arts/326253.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.fh21a7.asia/arts/170214.Doc

原标题：rebase 操作防止代码丢失
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.fh21a7.asia/arts/634269.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.fh21a7.asia/arts/455374.Doc

原标题：Mock 接口服务快速搭建实操
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.fh21a7.asia/arts/305739.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.fh21a7.asia/arts/581392.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.fh21a7.asia/arts/553631.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.fh21a7.asia/arts/429609.Doc

原标题：golang grpc protobuf 开发实操
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.fh21a7.asia/arts/304395.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.fh21a7.asia/arts/862777.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.fh21a7.asia/arts/981301.Doc

原标题：golang mysql 字符集排序规则设置
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.fh21a7.asia/arts/071117.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.fh21a7.asia/arts/026142.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.fh21a7.asia/arts/552076.Doc

原标题：开源源码阅读拆解学习思路
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.fh21a7.asia/arts/649365.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.fh21a7.asia/arts/851476.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.fh21a7.asia/arts/371792.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.fh21a7.asia/arts/359455.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.fh21a7.asia/arts/336054.Doc


二、踩坑排错｜Troubleshooting
原标题：实战：搭建本地对象存储兼容S3协议demo
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.fh21a7.asia/arts/630691.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.fh21a7.asia/arts/667612.Doc

原标题：入门实践：实现简单文件读写功能
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.fh21a7.asia/arts/771646.Doc

原标题：文件读写与异常捕获代码示例
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.fh21a7.asia/arts/715977.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.fh21a7.asia/arts/891245.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.fh21a7.asia/arts/333901.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.fh21a7.asia/arts/774551.Doc

原标题：Security：RPC调用身份认证安全加固
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.fh21a7.asia/arts/531002.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.fh21a7.asia/arts/846156.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.fh21a7.asia/arts/787847.Doc

原标题：golang cron 定时任务防并发执行
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.fh21a7.asia/arts/712078.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.fh21a7.asia/arts/011708.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.fh21a7.asia/arts/961346.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.fh21a7.asia/arts/344699.Doc

原标题：操作系统内核版本适配服务
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.fh21a7.asia/arts/615703.Doc

原标题：后端分页查询逻辑代码实现
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.fh21a7.asia/arts/749742.Doc

原标题：日志切割配置防止日志丢失
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.fh21a7.asia/arts/043593.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.fh21a7.asia/arts/907039.Doc

原标题：数据库读写分离性能优化
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.fh21a7.asia/arts/440666.Doc

原标题：golang docker compose 环境变量
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.fh21a7.asia/arts/375432.Doc

原标题：数据库死锁成因规避方案
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.fh21a7.asia/arts/714999.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.fh21a7.asia/arts/114011.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.fh21a7.asia/arts/291742.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.fh21a7.asia/arts/157248.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.fh21a7.asia/arts/614125.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.fh21a7.asia/arts/572192.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.fh21a7.asia/arts/537039.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.fh21a7.asia/arts/644816.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.fh21a7.asia/arts/248841.Doc

原标题：golang mysql 联合索引最左匹配
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.fh21a7.asia/arts/230097.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.fh21a7.asia/arts/537364.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.fh21a7.asia/arts/874054.Doc

原标题：OpenAPI 自动接口文档生成
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.fh21a7.asia/arts/477320.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.fh21a7.asia/arts/160518.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.fh21a7.asia/arts/338572.Doc

原标题：重复提交幂等防护再次讲解
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.fh21a7.asia/arts/207451.Doc

原标题：接口幂等性防重复请求实现
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.fh21a7.asia/arts/085952.Doc

原标题：golang kafka 批量发送消费优化
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.fh21a7.asia/arts/124625.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.fh21a7.asia/arts/300812.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.fh21a7.asia/arts/381333.Doc

三、实战开发｜Practice
原标题：设计思考：业务埋点架构日志埋点设计原则
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.fh21a7.asia/arts/612441.Doc

原标题：golang gorm ORM 数据库操作
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.fh21a7.asia/arts/813540.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.fh21a7.asia/arts/168956.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.fh21a7.asia/arts/544631.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.fh21a7.asia/arts/228622.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.fh21a7.asia/arts/078298.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.fh21a7.asia/arts/004903.Doc

原标题：开源项目本地运行排错完整清单
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.fh21a7.asia/arts/926918.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.fh21a7.asia/arts/930846.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.fh21a7.asia/arts/678067.Doc

原标题：快速入门简单签名校验实现思路
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.fh21a7.asia/arts/097659.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.fh21a7.asia/arts/020073.Doc

原标题：golang 项目 go mod 依赖管理
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.fh21a7.asia/arts/428186.Doc

原标题：golang md5 sha 加密工具实现
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.fh21a7.asia/arts/276026.Doc

原标题：磁盘占满服务不可用清理方案
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.fh21a7.asia/arts/325683.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.fh21a7.asia/arts/165019.Doc

原标题：golang github actions 发布 release 包
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.fh21a7.asia/arts/934662.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.fh21a7.asia/arts/666751.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.fh21a7.asia/arts/552267.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.fh21a7.asia/arts/036462.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.fh21a7.asia/arts/647039.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.fh21a7.asia/arts/047577.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.fh21a7.asia/arts/377391.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.fh21a7.asia/arts/053260.Doc

原标题：前端错误监控上报系统搭建
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.fh21a7.asia/arts/758141.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.fh21a7.asia/arts/388743.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.fh21a7.asia/arts/938076.Doc

原标题：实践：灰度流量切分简易实现方案
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.fh21a7.asia/arts/014179.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.fh21a7.asia/arts/612892.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.fh21a7.asia/arts/859102.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.fh21a7.asia/arts/665286.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.fh21a7.asia/arts/123009.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.fh21a7.asia/arts/382542.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.fh21a7.asia/arts/138498.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.fh21a7.asia/arts/363338.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.fh21a7.asia/arts/426434.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.fh21a7.asia/arts/500059.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.fh21a7.asia/arts/829939.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.fh21a7.asia/arts/182556.Doc

原标题：golang redis 批量 pipeline 实践
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.fh21a7.asia/arts/634006.Doc

四、架构设计｜Architecture
原标题：golang 系统设计无锁编程思路简单示例
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.fh21a7.asia/arts/471864.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.fh21a7.asia/arts/133669.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.fh21a7.asia/arts/592158.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.fh21a7.asia/arts/706067.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.fh21a7.asia/arts/437477.Doc

原标题：golang context 上下文传参讲解
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.fh21a7.asia/arts/426659.Doc

原标题：golang docker compose 本地开发最佳实践
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.fh21a7.asia/arts/929004.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.fh21a7.asia/arts/480230.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.fh21a7.asia/arts/372121.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.fh21a7.asia/arts/919126.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.fh21a7.asia/arts/664718.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.fh21a7.asia/arts/001052.Doc

原标题：批量操作分批处理防止 OOM
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.fh21a7.asia/arts/634636.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.fh21a7.asia/arts/459111.Doc

原标题：golang 项目 go mod 依赖管理
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.fh21a7.asia/arts/854552.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.fh21a7.asia/arts/150207.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.fh21a7.asia/arts/578199.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.fh21a7.asia/arts/644600.Doc

?
