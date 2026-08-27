最新前沿技术资讯

一、入门教程｜Getting Started
原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.fywybz.asia/blog/3865203.sHtMl

原标题：实践：前后端时间格式统一规范落地实践
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.fywybz.asia/blog/3400426.sHtMl

原标题：项目实践：多环境配置管理组件设计与实现
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.fywybz.asia/blog/1534383.sHtMl

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.fywybz.asia/blog/1582946.sHtMl

原标题：程序信号中断退出处理逻辑
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.fywybz.asia/blog/4595424.sHtMl

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.fywybz.asia/blog/6664888.sHtMl

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.fywybz.asia/blog/7838017.sHtMl

原标题：数值类型溢出错乱问题修复
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.fywybz.asia/blog/6917777.sHtMl

原标题：程序信号中断退出处理逻辑
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.fywybz.asia/blog/1844942.sHtMl

原标题：OpenAPI 自动接口文档生成
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.fywybz.asia/blog/6456549.sHtMl

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.fywybz.asia/blog/6324536.sHtMl

原标题：程序日志分级输出规范实践
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.fywybz.asia/blog/2650690.sHtMl

原标题：项目实践：定时任务防重复执行落地实践
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.fywybz.asia/blog/1760017.sHtMl

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.fywybz.asia/blog/9834664.sHtMl

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.fywybz.asia/blog/0786573.sHtMl

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.fywybz.asia/blog/8682103.sHtMl

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.fywybz.asia/blog/6391086.sHtMl

原标题：golang docker 部署 mongodb 开发环境
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.fywybz.asia/blog/9055236.sHtMl

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://book.fywybz.asia/blog/8861318.sHtMl

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.fywybz.asia/blog/1239085.sHtMl

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.fywybz.asia/blog/7167877.sHtMl

原标题：golang github actions 多平台构建
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.fywybz.asia/blog/8239153.sHtMl

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.fywybz.asia/blog/6424218.sHtMl

原标题：内网测试服务搭建团队调试
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.fywybz.asia/blog/4849895.sHtMl

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.fywybz.asia/blog/6072409.sHtMl

原标题：golang 系统设计限流算法原理代码实现
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.fywybz.asia/blog/5249491.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.fywybz.asia/blog/2831905.sHtMl

原标题：Docker 多阶段构建镜像瘦身
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.fywybz.asia/blog/3030145.sHtMl

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.fywybz.asia/blog/5129057.sHtMl

原标题：Practice：实现熔断降级组件简单原型代码
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.fywybz.asia/blog/4949425.sHtMl

原标题：Hands‑on：简易链路追踪原型开发实践
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.fywybz.asia/blog/5063589.sHtMl

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.fywybz.asia/blog/2098563.sHtMl

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.fywybz.asia/blog/3594017.sHtMl

原标题：跨平台 uniapp 多端开发实操
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.fywybz.asia/blog/8797389.sHtMl

原标题：golang k8s ingress 路由域名转发
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.fywybz.asia/blog/0416279.sHtMl

原标题：后端大文件分片上传接口开发
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.fywybz.asia/blog/1766440.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.fywybz.asia/blog/4466806.sHtMl

原标题：golang net/http 超时全套配置
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.fywybz.asia/blog/4839098.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.fywybz.asia/blog/9476730.sHtMl

原标题：开发记录：业务错误告警邮件通知组件实践
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.fywybz.asia/blog/7181762.sHtMl


二、踩坑排错｜Troubleshooting
原标题：入门实践：简单重试逻辑封装实现
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.fywybz.asia/blog/1708761.sHtMl

原标题：golang 系统设计容量评估简单方法论
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.fywybz.asia/blog/6706310.sHtMl

原标题：实战项目：GitSubmodule管理多仓库实践
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.fywybz.asia/blog/4938622.sHtMl

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.fywybz.asia/blog/9279135.sHtMl

原标题：实战项目：实现分布式任务调度最小原型
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.fywybz.asia/blog/4228251.sHtMl

原标题：从零搭建简单定时任务demo
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.fywybz.asia/blog/9941458.sHtMl

原标题：golang prometheus 指标暴露实现
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.fywybz.asia/blog/2376629.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.fywybz.asia/blog/8345765.sHtMl

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.fywybz.asia/blog/3135890.sHtMl

原标题：多实例部署 Session 共享方案
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.fywybz.asia/blog/5762969.sHtMl

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.fywybz.asia/blog/0582020.sHtMl

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.fywybz.asia/blog/5488316.sHtMl

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.fywybz.asia/blog/9924604.sHtMl

原标题：ServiceWorker 缓存页面更新清理
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.fywybz.asia/blog/2811059.sHtMl

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.fywybz.asia/blog/6192495.sHtMl

原标题：新手指南：项目本地编译输出产物解析
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.fywybz.asia/blog/5111767.sHtMl

原标题：方案设计：分布式锁失效风险架构层面规避
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.fywybz.asia/blog/5734847.sHtMl

原标题：golang 系统设计熔断降级架构讲解
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.fywybz.asia/blog/6755915.sHtMl

原标题：golang 系统设计防重复提交实现
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.fywybz.asia/blog/0858510.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.fywybz.asia/blog/8999817.sHtMl

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.fywybz.asia/blog/4285089.sHtMl

原标题：批量数据处理脚本编写技巧
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.fywybz.asia/blog/8220436.sHtMl

原标题：短信服务封装失败自动重试
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.fywybz.asia/blog/7847166.sHtMl

原标题：入门实践：简单图片上传预览本地demo
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.fywybz.asia/blog/9430425.sHtMl

原标题：golang 系统设计联合索引设计避坑要点
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.fywybz.asia/blog/5319508.sHtMl

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.fywybz.asia/blog/9327643.sHtMl

原标题：golang 系统设计告警风暴抑制方案实现
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.fywybz.asia/blog/6482440.sHtMl

原标题：golang mysql 索引失效常见场景
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.fywybz.asia/blog/4211964.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.fywybz.asia/blog/4995376.sHtMl

原标题：golang 系统设计告警规则阈值设置方法论
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.fywybz.asia/blog/0353547.sHtMl

原标题：Nginx 透传真实客户端 IP 配置
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.fywybz.asia/blog/3780562.sHtMl

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.fywybz.asia/blog/5001861.sHtMl

原标题：Security：Web常见安全漏洞原理与修复清单
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.fywybz.asia/blog/0945815.sHtMl

原标题：golang 系统设计缓存基准测试对比方案
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.fywybz.asia/blog/0831706.sHtMl

原标题：golang 系统设计线上日志快速检索技巧
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.fywybz.asia/blog/3480476.sHtMl

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.fywybz.asia/blog/4563355.sHtMl

原标题：零基础理解HTTP常用请求头与状态码
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.fywybz.asia/blog/8946761.sHtMl

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.fywybz.asia/blog/0969630.sHtMl

原标题：Practice：数据库分表简单实现方案与代码示例
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.fywybz.asia/blog/3498764.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.fywybz.asia/blog/8494797.sHtMl

三、实战开发｜Practice
原标题：架构思考：单体应用向微服务拆分演进路径
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.fywybz.asia/blog/3826074.sHtMl

原标题：数据库排序规则统一结果一致
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.fywybz.asia/blog/9743387.sHtMl

原标题：优化实践：分页查询性能优化解决offset问题
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.fywybz.asia/blog/8270536.sHtMl

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.fywybz.asia/blog/6006547.sHtMl

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.fywybz.asia/blog/6716034.sHtMl

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.fywybz.asia/blog/4162994.sHtMl

原标题：golang 集成测试启动测试数据库
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.fywybz.asia/blog/6216911.sHtMl

原标题：golang github actions 发布 release 包
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.fywybz.asia/blog/8162360.sHtMl

原标题：golang 系统设计代码评审 checklist 清单
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.fywybz.asia/blog/2933206.sHtMl

原标题：golang redis 地理位置 geo 使用
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.fywybz.asia/blog/4449713.sHtMl

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.fywybz.asia/blog/1700911.sHtMl

原标题：新手教程：gitstash暂存工作区变更实操
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.fywybz.asia/blog/0491036.sHtMl

原标题：golang 系统设计接口参数防篡改校验
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.fywybz.asia/blog/8178758.sHtMl

原标题：时间同步修复令牌提前过期
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.fywybz.asia/blog/5927823.sHtMl

原标题：日志驱动异常日志不输出修复
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.fywybz.asia/blog/2057613.sHtMl

原标题：nodejs 集成测试业务流程编写
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.fywybz.asia/blog/8381382.sHtMl

原标题：golang 系统设计消息发送确认机制配置实操
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.fywybz.asia/blog/7327213.sHtMl

原标题：性能笔记：HTTP连接复用性能优化实践
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.fywybz.asia/blog/3343404.sHtMl

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.fywybz.asia/blog/3425342.sHtMl

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.fywybz.asia/blog/2318208.sHtMl

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.fywybz.asia/blog/0619912.sHtMl

原标题：零基础理解模块化与组件化基础思想
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.fywybz.asia/blog/2021069.sHtMl

原标题：golang 系统设计防爬虫简单策略
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.fywybz.asia/blog/1107846.sHtMl

原标题：设计思考：消息队列重复消费架构层防御手段
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.fywybz.asia/blog/8667681.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.fywybz.asia/blog/5599640.sHtMl

原标题：内存溢出问题现象识别排查
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.fywybz.asia/blog/5646003.sHtMl

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.fywybz.asia/blog/6094947.sHtMl

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.fywybz.asia/blog/7808553.sHtMl

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.fywybz.asia/blog/1176664.sHtMl

原标题：新手教程：本地项目初始化gitignore配置
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.fywybz.asia/blog/9084456.sHtMl

原标题：Performance：长连接管理优化减少连接重建开销
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.fywybz.asia/blog/3523339.sHtMl

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.fywybz.asia/blog/7451820.sHtMl

原标题：静态博客部署 GitHub Pages 教程
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.fywybz.asia/blog/4994578.sHtMl

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.fywybz.asia/blog/0485831.sHtMl

原标题：新手指南：本地多版本环境共存配置
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.fywybz.asia/blog/7959568.sHtMl

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.fywybz.asia/blog/6531879.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.fywybz.asia/blog/2280613.sHtMl

原标题：CI 持续集成自动构建流程
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.fywybz.asia/blog/2654806.sHtMl

原标题：golang mysql 联合索引最左匹配
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.fywybz.asia/blog/5413934.sHtMl

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.fywybz.asia/blog/6511615.sHtMl

四、架构设计｜Architecture
原标题：Performance：后端接口性能优化完整分析流程
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.fywybz.asia/blog/0877833.sHtMl

原标题：单元测试用例编写入门实操
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.fywybz.asia/blog/6794772.sHtMl

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.fywybz.asia/blog/9024311.sHtMl

原标题：golang 配置热更新不重启服务
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.fywybz.asia/blog/4417767.sHtMl

原标题：CORS 跨域问题多种解决方案
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.fywybz.asia/blog/8964364.sHtMl

原标题：Git 子模块更新代码不全修复
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.fywybz.asia/blog/7277640.sHtMl

原标题：浏览器本地存储安全使用技巧
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.fywybz.asia/blog/7965787.sHtMl

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.fywybz.asia/blog/0107646.sHtMl

原标题：安全实践：接口速率限制防止暴力破解
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.fywybz.asia/blog/4860323.sHtMl

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.fywybz.asia/blog/7594636.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.fywybz.asia/blog/6891991.sHtMl

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.fywybz.asia/blog/9281901.sHtMl

原标题：golang redis 布隆过滤器安装使用
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.fywybz.asia/blog/1905615.sHtMl

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.fywybz.asia/blog/8409028.sHtMl

原标题：数据库主从延迟业务兼容处理
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.fywybz.asia/blog/2905197.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.fywybz.asia/blog/8139114.sHtMl

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.fywybz.asia/blog/6583461.sHtMl

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.fywybz.asia/blog/0299953.sHtMl

?
