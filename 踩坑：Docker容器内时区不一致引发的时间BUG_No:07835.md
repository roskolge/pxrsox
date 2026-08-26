最新前沿技术资讯

一、入门教程｜Getting Started
原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.etz8sf.asia/arts/044696.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.etz8sf.asia/arts/166600.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.etz8sf.asia/arts/618025.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.etz8sf.asia/arts/935192.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.etz8sf.asia/arts/239881.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.etz8sf.asia/arts/011919.Doc

原标题：golang github actions 缓存依赖提速
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.etz8sf.asia/arts/788014.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.etz8sf.asia/arts/305397.Doc

原标题：golang base64 编码解码实操
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.etz8sf.asia/arts/677039.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.etz8sf.asia/arts/906797.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.etz8sf.asia/arts/897397.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.etz8sf.asia/arts/888409.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.etz8sf.asia/arts/383584.Doc

原标题：从零搭建简单Mock接口服务
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.etz8sf.asia/arts/167936.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.etz8sf.asia/arts/742073.Doc

原标题：手写简易 RPC 服务通信原型
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.etz8sf.asia/arts/531338.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.etz8sf.asia/arts/375547.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.etz8sf.asia/arts/333492.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.etz8sf.asia/arts/156535.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.etz8sf.asia/arts/291462.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.etz8sf.asia/arts/202615.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.etz8sf.asia/arts/377391.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.etz8sf.asia/arts/607835.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.etz8sf.asia/arts/644500.Doc

原标题：golang net/http 超时全套配置
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.etz8sf.asia/arts/863862.Doc

原标题：golang es 查询语句 DSL 实操
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.etz8sf.asia/arts/360857.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.etz8sf.asia/arts/316118.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.etz8sf.asia/arts/437603.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.etz8sf.asia/arts/536217.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.etz8sf.asia/arts/740343.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.etz8sf.asia/arts/909008.Doc

原标题：端口占用访问失败排查方案
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.etz8sf.asia/arts/478810.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.etz8sf.asia/arts/450767.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.etz8sf.asia/arts/047053.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.etz8sf.asia/arts/803516.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.etz8sf.asia/arts/194579.Doc

原标题：站内邮件消息通知功能开发
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.etz8sf.asia/arts/749396.Doc

原标题：golang redis stream 消息队列实践
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.etz8sf.asia/arts/636730.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.etz8sf.asia/arts/805143.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.etz8sf.asia/arts/235072.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计回调签名校验防伪造实现
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.etz8sf.asia/arts/209802.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.etz8sf.asia/arts/120211.Doc

原标题：golang prometheus histogram 指标
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.etz8sf.asia/arts/821166.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.etz8sf.asia/arts/411373.Doc

原标题：golang k8s liveness readiness 探针
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.etz8sf.asia/arts/214657.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.etz8sf.asia/arts/733019.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.etz8sf.asia/arts/033345.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.etz8sf.asia/arts/453962.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.etz8sf.asia/arts/015145.Doc

原标题：golang docker 部署 prometheus 整套
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.etz8sf.asia/arts/346989.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.etz8sf.asia/arts/207681.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.etz8sf.asia/arts/675396.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.etz8sf.asia/arts/933058.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.etz8sf.asia/arts/682058.Doc

原标题：golang 简易埋点日志上报实现
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.etz8sf.asia/arts/936918.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.etz8sf.asia/arts/541754.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.etz8sf.asia/arts/150422.Doc

原标题：死信队列处理消息阻塞业务
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.etz8sf.asia/arts/798510.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.etz8sf.asia/arts/560141.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.etz8sf.asia/arts/272547.Doc

原标题：CORS 跨域问题多种解决方案
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.etz8sf.asia/arts/311125.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.etz8sf.asia/arts/370607.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.etz8sf.asia/arts/019617.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.etz8sf.asia/arts/855432.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.etz8sf.asia/arts/499848.Doc

原标题：零基础理解幂等性基础概念与场景
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.etz8sf.asia/arts/644604.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.etz8sf.asia/arts/429804.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.etz8sf.asia/arts/134927.Doc

原标题：程序性能指标 CPU 内存监控
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.etz8sf.asia/arts/826290.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.etz8sf.asia/arts/890871.Doc

原标题：零基础理解幂等性基础概念与场景
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.etz8sf.asia/arts/469451.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.etz8sf.asia/arts/687255.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.etz8sf.asia/arts/279743.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.etz8sf.asia/arts/933468.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.etz8sf.asia/arts/372260.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.etz8sf.asia/arts/420395.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.etz8sf.asia/arts/702289.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.etz8sf.asia/arts/047825.Doc

原标题：前后端交互跨域问题完整处理
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.etz8sf.asia/arts/782125.Doc

原标题：golang 系统设计防爬虫简单策略
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.etz8sf.asia/arts/343249.Doc

三、实战开发｜Practice
原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.etz8sf.asia/arts/133048.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.etz8sf.asia/arts/088221.Doc

原标题：golang redis 缓存更新策略讲解
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.etz8sf.asia/arts/322676.Doc

原标题：CI 构建缓存加速编译速度
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.etz8sf.asia/arts/830597.Doc

原标题：包管理器依赖冲突解决方案
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.etz8sf.asia/arts/347212.Doc

原标题：golang 开发环境快速搭建指南
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.etz8sf.asia/arts/612043.Doc

原标题：golang 系统设计多级缓存更新策略
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.etz8sf.asia/arts/845710.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.etz8sf.asia/arts/847258.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.etz8sf.asia/arts/947538.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.etz8sf.asia/arts/112015.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.etz8sf.asia/arts/673915.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.etz8sf.asia/arts/799626.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.etz8sf.asia/arts/520624.Doc

原标题：Shell 脚本自动化命令编写
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.etz8sf.asia/arts/694887.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.etz8sf.asia/arts/254612.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.etz8sf.asia/arts/695959.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.etz8sf.asia/arts/311824.Doc

原标题：golang 系统设计文件存储选型对比
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.etz8sf.asia/arts/151110.Doc

原标题：golang github actions 完整工作流示例
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.etz8sf.asia/arts/141800.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.etz8sf.asia/arts/761281.Doc

原标题：golang 系统设计分布式锁选型对比
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.etz8sf.asia/arts/172970.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.etz8sf.asia/arts/165476.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.etz8sf.asia/arts/973061.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.etz8sf.asia/arts/438421.Doc

原标题：golang docker 部署 mysql 注意事项
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.etz8sf.asia/arts/046217.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.etz8sf.asia/arts/002552.Doc

原标题：前端组件库按需加载性能优化
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.etz8sf.asia/arts/578038.Doc

原标题：不必要字符转义关闭业务异常
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.etz8sf.asia/arts/906446.Doc

原标题：OAuth2 第三方登录服务搭建
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.etz8sf.asia/arts/104847.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.etz8sf.asia/arts/898614.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.etz8sf.asia/arts/400391.Doc

原标题：限流规则误拦截正常请求修复
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.etz8sf.asia/arts/877830.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.etz8sf.asia/arts/518758.Doc

原标题：golang redis 网络超时参数调优
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.etz8sf.asia/arts/288958.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.etz8sf.asia/arts/036822.Doc

原标题：CI 流水线构建失败日志排查
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.etz8sf.asia/arts/142231.Doc

原标题：golang mysql limit 大分页优化
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.etz8sf.asia/arts/633272.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.etz8sf.asia/arts/591829.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.etz8sf.asia/arts/339656.Doc

原标题：快速入门消息通知简单实现方案
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.etz8sf.asia/arts/153579.Doc

四、架构设计｜Architecture
原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.etz8sf.asia/arts/795891.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.etz8sf.asia/arts/313164.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.etz8sf.asia/arts/964682.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.etz8sf.asia/arts/216431.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.etz8sf.asia/arts/051485.Doc

原标题：Git 误删提交代码恢复找回
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.etz8sf.asia/arts/729062.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.etz8sf.asia/arts/319232.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.etz8sf.asia/arts/166701.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.etz8sf.asia/arts/177768.Doc

原标题：容器资源限制防止宿主机过载
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.etz8sf.asia/arts/005273.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.etz8sf.asia/arts/971720.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.etz8sf.asia/arts/630256.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.etz8sf.asia/arts/452798.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.etz8sf.asia/arts/386678.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.etz8sf.asia/arts/848686.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.etz8sf.asia/arts/984393.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.etz8sf.asia/arts/521810.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.etz8sf.asia/arts/881832.Doc

?
