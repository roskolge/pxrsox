最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang es 更新文档注意版本冲突
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3874530.shtml

原标题：golang 系统设计代码安全审计简单思路
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6087234.shtml

原标题：安全复盘：定时任务权限过大风险管控
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5758721.shtml

原标题：开发复盘：分布式会话共享多种方案实践
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1285989.shtml

原标题：Cookie Session 会话状态管理
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4244820.shtml

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2320497.shtml

原标题：golang 系统设计灰度发布流量切分实现
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2841268.shtml

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0579979.shtml

原标题：golang 系统设计 http 接口基准测试实操示例
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0896348.shtml

原标题：golang 系统设计重试退避策略业务落地
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6273426.shtml

原标题：golang 系统设计多级缓存架构落地
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0505091.shtml

原标题：多版本开发环境共存配置
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3774691.shtml

原标题：零基础理解模块化与组件化基础思想
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8161710.shtml

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2569553.shtml

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1716444.shtml

原标题：golang 系统设计链路追踪架构简单讲解
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7746078.shtml

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4203106.shtml

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6324425.shtml

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1318982.shtml

原标题：vue pinia 状态管理实战教程
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8526169.shtml

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0458377.shtml

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5022655.shtml

原标题：golang cpu pprof 性能分析实操
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8503544.shtml

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2214242.shtml

原标题：程序信号中断退出处理逻辑
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0535669.shtml

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8560781.shtml

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4793615.shtml

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4958351.shtml

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3996102.shtml

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1046882.shtml

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8799877.shtml

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8044969.shtml

原标题：golang docker 网络模式桥接 host
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6571370.shtml

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8874538.shtml

原标题：Architecture：静态配置与动态配置架构分离
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5857768.shtml

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3167751.shtml

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1238422.shtml

原标题：golang 系统设计灰度发布流量切分实现
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8612485.shtml

原标题：golang 系统设计布隆过滤器原理与落地
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7586563.shtml

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3012576.shtml


二、踩坑排错｜Troubleshooting
原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7525631.shtml

原标题：零基础理解依赖管理与包管理器
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9451081.shtml

原标题：HelloTest：理解集成测试基础编写思路
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3565577.shtml

原标题：零基础理解进程、线程基础概念区别
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4538498.shtml

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4888523.shtml

原标题：Security：反序列化漏洞风险识别与规避
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3277975.shtml

原标题：golang 简易埋点日志上报实现
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9079421.shtml

原标题：golang 系统设计秒杀防超卖方案
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0158941.shtml

原标题：代码模块化组件化拆分思路
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3207192.shtml

原标题：golang 项目目录分层规范设计
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3133505.shtml

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9489951.shtml

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4938164.shtml

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9483943.shtml

原标题：新手教程：gitstash暂存工作区变更实操
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1325539.shtml

原标题：golang 系统设计开源项目协作流程梳理
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5301968.shtml

原标题：Performance：批量导入数据性能优化实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4539614.shtml

原标题：主干开发团队代码合并策略
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6083778.shtml

原标题：防火墙 IP 白名单回调接口放行
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6159572.shtml

原标题：设计思考：API网关和BFF职责边界划分
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9720951.shtml

原标题：零基础理解幂等性基础概念与场景
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7792742.shtml

原标题：快速启动：本地运行开源项目排障清单
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0170736.shtml

原标题：golang gin 路由分组权限管控
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1581505.shtml

原标题：Security：文件路径穿越漏洞完整防护
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2981610.shtml

原标题：热更新开发环境配置教程
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7614184.shtml

原标题：WebSocket 聊天室实时通讯开发
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7165276.shtml

原标题：golang k8s 镜像拉取密钥配置
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5930873.shtml

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0000910.shtml

原标题：golang 系统设计异步化改造业务流程思路
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1952714.shtml

原标题：避坑：版本升级之后项目直接无法启动
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0822003.shtml

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7133205.shtml

原标题：设计思考：分布式会话架构选型对比
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7867313.shtml

原标题：golang 系统设计故障止损降级回滚执行原则
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5330061.shtml

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4788736.shtml

原标题：实战：基于内存实现简单消息广播组件
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4898133.shtml

原标题：golang 系统设计延迟消息实现几种方案对比
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2901095.shtml

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6047491.shtml

原标题：JWT 工具封装令牌刷新过期
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1566287.shtml

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9721532.shtml

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2059190.shtml

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0345350.shtml

三、实战开发｜Practice
原标题：golang 系统设计线上日志快速检索技巧
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7274549.shtml

原标题：新手教程：本地项目初始化gitignore配置
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4960788.shtml

原标题：Practice：实现请求body重复读取中间件实践
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5195457.shtml

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6785866.shtml

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1940752.shtml

原标题：golang grafana 面板变量模板制作
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5619616.shtml

原标题：golang 系统设计防爬虫简单策略
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1078782.shtml

原标题：新手指南：看懂开源项目的Issue与PR
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4545762.shtml

原标题：零基础学习简单正则表达式实战案例
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9561133.shtml

原标题：golang 限流熔断降级完整示例
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3196082.shtml

原标题：golang 系统设计数据库扩容几种方式
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6796806.shtml

原标题：大文件导出内存溢出防护
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1606094.shtml

原标题：实践：API版本控制多种策略落地对比实践
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3986649.shtml

原标题：调试工具断点调试变量查看技巧
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6017280.shtml

原标题：Architecture：BFF后端聚合层架构适用场景
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3478366.shtml

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5044162.shtml

原标题：nestjs 拦截器过滤器管道实战
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3487092.shtml

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5029575.shtml

原标题：Practice：实现多数据源动态切换组件实践
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1420320.shtml

原标题：golang kafka 消息顺序性保证方案
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2645862.shtml

原标题：golang docker compose 本地开发最佳实践
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3885209.shtml

原标题：golang 系统设计参数校验统一处理方案
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7809398.shtml

原标题：golang 系统设计配置回滚版本历史记录实现
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7520844.shtml

原标题：本地简易配置中心动态管理
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5360632.shtml

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0463356.shtml

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5100125.shtml

原标题：前端工程化 webpack 打包优化
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0548667.shtml

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8531722.shtml

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4273217.shtml

原标题：golang rate‑limiter 限流组件
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2028945.shtml

原标题：nodejs 多进程任务分发处理
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6835632.shtml

原标题：数值 key 浮点匹配异常规避
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6370618.shtml

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7279500.shtml

原标题：nodejs 接口限流防刷代码实现
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0509763.shtml

原标题：请求重试组件退避策略实现
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2714328.shtml

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5897892.shtml

原标题：golang prometheus counter gauge 使用
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7139310.shtml

原标题：golang 配置文件多环境加载
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7844317.shtml

原标题：service‑worker 离线缓存实践
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8367648.shtml

原标题：浮点计算精度错误处理方案
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7489941.shtml

四、架构设计｜Architecture
原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：www.blog.yzcygc.cn/Article/details/3743245.shtml

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9725405.shtml

原标题：复盘总结：技术选型对比文档模板实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6469355.shtml

原标题：golang 系统设计分布式会话方案对比
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1248590.shtml

原标题：Docker 容器网络不通排查
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：www.blog.yzcygc.cn/Article/details/7789787.shtml

原标题：nodejs redis 缓存业务实战
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1022688.shtml

原标题：golang yaml 解析配置加载实操
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8977276.shtml

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：www.blog.yzcygc.cn/Article/details/1929466.shtml

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：www.blog.yzcygc.cn/Article/details/8506790.shtml

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6179238.shtml

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5828198.shtml

原标题：前端打包分包加载提速方案
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：www.blog.yzcygc.cn/Article/details/2106156.shtml

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：www.blog.yzcygc.cn/Article/details/5704984.shtml

原标题：HTTPS 证书过期更新操作
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0998001.shtml

原标题：golang kafka 重试机制配置实操
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：www.blog.yzcygc.cn/Article/details/6080243.shtml

原标题：golang 系统设计数据库查询优化完整流程
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：www.blog.yzcygc.cn/Article/details/4197438.shtml

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：www.blog.yzcygc.cn/Article/details/0611405.shtml

原标题：gRPC 服务端客户端入门示例
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：www.blog.yzcygc.cn/Article/details/9320106.shtml

?
