## #AI

### [GPU 利用率(Utilization) 是一个误导性指标!](https://mp.weixin.qq.com/s/dUhxU3QBnZ4kUMBzxrmC_w)
- **发布日期**：2025-04-08 19:15  
- **所属合集**：#CUDA #GPU #AI Infra  
- **摘要**：评估GPU使用时，许多人首看利用率，但它并不等于性能高。例如仅内存读写也会让GPU Util达100%，因此不能简单类比CPU Util，需结合更多指标（例如 SM Efficiency 和 MFU）全面判断。  

### [原力注入：AI Infra 知识体系（Body of knowledge for AI Infra) v1.1](https://mp.weixin.qq.com/s/nMgHwGYb9vVBx0g9EpNNoQ)
- **发布日期**：2024-11-03 15:31  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：经过这半年的学习和整理，笔者也逐步构建了笔者心中的 AI Infra 知识体系（Body of knowledge for AI Infra），供大家参考，今天推出了 1.1 版本！  

### [CUDA Processing Streams](https://mp.weixin.qq.com/s/Hm1PZ4rZe7GbOp2xtFPgdA)
- **发布日期**：2024-10-22 08:31  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：结合代码示例来深入学习 CUDA Stream 编程。  

### [AI Infra - CUDA 并发编程之 Stream 简介](https://mp.weixin.qq.com/s/mXvQ1Xo1E4BUzA4q_dPDUw)
- **发布日期**：2024-10-18 22:51  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：CUDA streams 是 CUDA 编程中用来管理并发执行的单元，在一个流中，操作是串行的按序执行的，但是在不同的流中操作就可以同时执行，从而完成并发操作。  

### [AI Infra - nvtop 快速入门](https://mp.weixin.qq.com/s/0D8UEkSkkpPeCNcHMNhWSA)
- **发布日期**：2024-10-16 19:25  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：nvtop 是一款类似于 htop 的命令行工具，可用于监控 NVIDIA、AMD、Intel 等多种 GPU。它提供了一个直观的界面，可以实时查看和管理 GPU 状态、指标数据。  

### [推荐两本开源 AI 书籍：《动手学深度学习》和《机器学习系统：设计和实现》](https://mp.weixin.qq.com/s/-JcJbpvUOTFx8wdqTYVn9Q)
- **发布日期**：2024-10-15 08:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：推荐两本开源 AI 书：《动手学深度学习》和《机器学习系统：设计和实现》  

### [AI Infra - 集合通信框架 NCCL 概念介绍](https://mp.weixin.qq.com/s/5zk8Se6kZwMdsWQteDbq8Q)
- **发布日期**：2024-10-14 13:02  
- **所属合集**：#AI Infra  
- **摘要**：不同的并行模式下都离不开集合通信技术。集合通信的使用将分布式训练中多个硬件之间的数据通信变得简洁和高效。与此同时，集合通信也成为了分布式机器学习中不可或缺的一部分。  

### [AI Infra - 理解 GPU 架构之 Tesla V100 及 RTX 5000 简介](https://mp.weixin.qq.com/s/5_a1o6tRDMhC8dF__RTJTw)
- **发布日期**：2024-10-07 09:00  
- **所属合集**：#AI Infra  
- **摘要**：理解 GPU 架构之 Tesla V100 及 RTX 5000 简介  

### [AI Infra - 理解 GPU 架构之理解 GPU 特性「双语」](https://mp.weixin.qq.com/s/Agrtq4WqQj01MTlg-dwVlg)
- **发布日期**：2024-10-06 09:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：GPU 的硬件设计优化了高度并行处理。因此，GPU 的程序依赖于像 NVIDIA CUDA 这样的编程模型，与传统的基于CPU的串行编程模型有很大不同，本文就试图对 GPU 的特性进行阐述，帮助读者理解 GPU 和 CPU 的相同点和差异！  

### [原力注入：AI Infra 知识体系（Body of knowledge for AI Infra) v1.0](https://mp.weixin.qq.com/s/ptAdsvO5H34IOFSEwzWlsQ)
- **发布日期**：2024-10-05 17:00  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：经过这半年的学习和整理，笔者也逐步构建了笔者心中的 AI Infra 知识体系（Body of knowledge for AI Infra），供大家参考，后续会持续完善。  

### [AI Infra - 理解 GPU 架构之理解 GPU 内存「双语」](https://mp.weixin.qq.com/s/GEs5ZbStbggtMgwdhOUOWw)
- **发布日期**：2024-10-04 17:15  
- **所属合集**：#AI Infra  
- **摘要**：本文介绍了 GPU 内存层次结构，分析了寄存器、缓存、共享内存和全局内存的作用。与 CPU 相比，GPU 的寄存器文件和共享内存更大，适合并行计算，而 CPU 通过更大的 L1、L2 和 L3 缓存减少主存访问。  

### [深入了解 Nvidia CUDA 核心](https://mp.weixin.qq.com/s/PE3LmOAft27QCQNaaSFY7g)
- **发布日期**：2024-09-30 08:30  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：Nvidia 的 CUDA 核心是 Nvidia 显卡内的专门处理单元，旨在高效处理复杂的并行计算，使其成为高性能计算、游戏和各种图形渲染应用程序中的关键。  

### [AI Infra - 使用 CUDA 代码查询 GPU 卡详细信息](https://mp.weixin.qq.com/s/G6kfoNTdOmyOKQSHt83fHw)
- **发布日期**：2024-09-29 08:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：今天我们就来使用 CUDA 示例代码库提供的 deviceQueryDrv.cpp 示例代码来查询 GPU 卡的详细信息，用于全面了解 GPU 卡的详细特性。  

### [AI Infra - nvidia-smi 快速入门](https://mp.weixin.qq.com/s/Yu4UCprk9HfIMZGsrEOeXA)
- **发布日期**：2024-09-27 08:30  
- **所属合集**：#AI Infra  
- **摘要**：nvidia-smi 是 NVIDIA 驱动提供的命令行工具，能够帮助用户监控和管理 GPU 的状态与行为。本文整理了一些常用的 nvidia-smi 命令，帮助大家快速上手和高效使用。  

### [AI Infra - Nvidia GPU 卡 之 ECC 功能](https://mp.weixin.qq.com/s/nmZVOQAyfFyesm79HzjUlQ)
- **发布日期**：2024-09-25 08:30  
- **所属合集**：#AI Infra  
- **摘要**：nan  

### [AI Infra - Nvidia GPU XID 故障码解析](https://mp.weixin.qq.com/s/ekCnhr3qrhjuX_-CEyx65g)
- **发布日期**：2024-09-21 09:05  
- **所属合集**：#AI Infra  
- **摘要**：XID 信息是 NVIDIA 驱动程序的错误报告，它被打印到操作系统的内核日志或事件日志中。这些信息可能表明 NVIDIA 硬件问题、软件问题或者是用户应用程序的问题。  

### [推荐《CUDA Reading Group 相关讲座》](https://mp.weixin.qq.com/s/6sOrNzG0UeVBes8stWSoWA)
- **发布日期**：2024-07-02 09:00  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：推荐《CUDA Reading Group 相关讲座》，共包含24个讲座，每个讲座有视频以及配套材料，对于 CUDA 编程感兴趣的同学可以深入参考！  

### [深度学习（大模型）中的精度](https://mp.weixin.qq.com/s/b08gFicrKNCfrwSlpsecmQ)
- **发布日期**：2024-06-30 09:00  
- **所属合集**：#AI Infra #LLM  
- **摘要**：当谈到大型模型的训练和推理时，我们经常涉及到精度的概念，而这些精度种类繁多。同等精度级别下，还有不同的格式。笔者收集了几篇文章，供大家参考理解相关概念。  

### [万卡集群背后的系统架构：《NVIDIA DGX SuperPOD：下一代可扩展的AI领导基础设施》](https://mp.weixin.qq.com/s/a64Qb6DuAAZnCTBy8g1p2Q)
- **发布日期**：2024-06-28 09:00  
- **所属合集**：#AI Infra  
- **摘要**：万卡集群背后隐藏的硬件成本有哪些？网络和存储的开销不可被忽略，今天就让我们来读一读《NVIDIA DGX SuperPOD：下一代可扩展的AI领导基础设施》，来深入了解一下万卡集群背后的系统架构！  

### [使用 Nsight 工具定量分析 CUDA 矩阵乘法几种实现](https://mp.weixin.qq.com/s/JK_bsvG-Y3wLJknZ4YKCYQ)
- **发布日期**：2024-06-20 12:15  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：矩阵乘法是大模型训练和推理的重要基础，因此我们需要通过工具定量来分析矩阵乘法，尤其是多级内存的使用效率，本文使用 Nsight 工具定量分析了几种矩阵乘法的实现，基于 Nsight 提供的 Kernel Profiling 能力。  

### [AI Infra 基础知识 - 一文介绍并行计算、费林分类法和 CUDA 基本概念](https://mp.weixin.qq.com/s/NL_Bz8JB-LdAtrQake7EdA)
- **发布日期**：2024-06-11 13:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：一文了解并行计算、费林分类法和 CUDA 基本概念，入门基于 CUDA 的 GPGPU 编程！  

### [AI Infra 基础知识 - PCIe 知识大全](https://mp.weixin.qq.com/s/dHvKYcZoa4rcF90LLyo_0A)
- **发布日期**：2024-06-09 10:30  
- **所属合集**：#AI Infra  
- **摘要**：当进入到 AI Infra 的视角之后，我们越来越关注底层的硬件细节，今天就让我们来了解一下 PCI Express 吧！  

### [AI Infra 基础知识 - NVLink 入门](https://mp.weixin.qq.com/s/fP69UEgusOa_X4ZKLo30ig)
- **发布日期**：2024-06-08 11:00  
- **所属合集**：#AI Infra  
- **摘要**：AI Infra 背后是一系列硬件技术，今天我们来了解一下 NVLink。 NVLink 是一种专有系统互连硬件，可促进多个 Nvidia GPU 和支持CPU之间的一致数据和控制传输。  



## #BPF之巅

### [性能调优：学无止境](https://mp.weixin.qq.com/s/b8_A2sSL6SRvRyGR5824IA)
- **发布日期**：2024-12-27 07:15  
- **所属合集**：#系统可观测性 #BPF之巅  
- **摘要**：《BPF之巅》则为读者们打开了 Linux 的内核大门，可以一窥内核原理和深入了解工作机制，为大家的以后的内核开发之旅铺平道路。  

### [BPF 性能之巅 - 使用 bcc 工具做 Linux 内存回收性能分析](https://mp.weixin.qq.com/s/JNolqi9ENWEfygLtGnoHsQ)
- **发布日期**：2024-04-11 20:18  
- **所属合集**：#BPF之巅  
- **摘要**：当出现内存不足的时候，应用申请内存可能会遇到性能问题。我们如何来回答以下问题：系统是否出现了直接内存回收？直接内存回收对于相关进程的定量影响？正好 BPF 性能之巅提供了两个相关工具。  

### [《BPF 性能之巅》- 使用 perf tools 定位磁盘 IO util 高问题](https://mp.weixin.qq.com/s/6SZlT2WVmytOAgz_RbsqEw)
- **发布日期**：2024-03-19 19:30  
- **所属合集**：#BPF之巅 #系统可观测性  
- **摘要**：本文的目标是通过现有工具来回答一个我们经常会遇到的一个问题：sd* 设备上哪些进程的 IO 操作比较多？这些进程在做什么样的文件操作？  

### [【原理篇】《BPF性能之巅》如何快速分析系统的 I/O 瓶颈？](https://mp.weixin.qq.com/s/QtYQ-vLjCXUVF4pbbGtwgQ)
- **发布日期**：2024-03-19 19:30  
- **所属合集**：#BPF之巅 #Linux #存储  
- **摘要**：我们应该使用什么样的方法和工具，来“快准狠”地定位系统的 I/O 瓶颈呢？本文是原理篇，后续还会陆续推出实战篇。  

### [《性能之巅》系统可观测性综述](https://mp.weixin.qq.com/s/4oMVi37EnZg2RXfhsl5teA)
- **发布日期**：2024-03-18 19:30  
- **所属合集**：#系统可观测性 #BPF之巅  
- **摘要**：本文是对系统可观测性做了概述，介绍了相关概念和方法。  

### [【原理篇】《BPF性能之巅》如何快速分析系统的 I/O 瓶颈？](https://mp.weixin.qq.com/s/R7AbMDuIWe5jJpDWQHVp2A)
- **发布日期**：2024-03-17 09:00  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：我们应该使用什么样的方法和工具，来“快准狠”地定位系统的 I/O 瓶颈呢？本文是原理篇，后续还会陆续推出实战篇。  

### [《BPF 性能之巅》- 使用 perf tools 做性能分析（1）](https://mp.weixin.qq.com/s/dXw_6-zi19XuvJEnbZuz4w)
- **发布日期**：2024-03-17 09:00  
- **所属合集**：#BPF之巅 #系统可观测性  
- **摘要**：本文的目标是通过现有工具来回答一个我们经常会遇到的一个问题：sd* 设备上哪些进程的 IO 操作比较多？这些进程在做什么样的文件操作？  

### [【BPF 性能之巅】 系统性能分析的 USE 方法和 TSA 方法](https://mp.weixin.qq.com/s/CeIwZUmmQ7SjS8EvBSkiwQ)
- **发布日期**：2024-03-06 08:24  
- **所属合集**：#BPF之巅  
- **摘要**：nan  

### [【实战篇】使用火焰图定位 jbd2进程导致系统负载高问题](https://mp.weixin.qq.com/s/8DgCgJvhMETtzIq2570-uA)
- **发布日期**：2024-02-02 09:15  
- **所属合集**：#BPF之巅 #系统可观测性  
- **摘要**：我们可以使用火焰图定位 jbd2进程导致系统负载高问题  

### [The State of eBPF - 2024](https://mp.weixin.qq.com/s/TifVOJ_OyGbWNEwe3ImTsg)
- **发布日期**：2024-02-01 12:15  
- **所属合集**：#Kubernetes #BPF之巅 #Linux  
- **摘要**：（eBPF的拥护者认为）毫无疑问，eBPF 将成为新的云原生基础设施堆栈中的新的一层，影响所有应用的可观测性、性能、可靠性、网络和安全性。  

### [【原理篇】《BPF性能之巅》如何快速分析系统的 I/O 瓶颈？](https://mp.weixin.qq.com/s/X1WVRWSgUUyYbVyelnf_Nw)
- **发布日期**：2024-01-29 12:36  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：我们应该使用什么样的方法和工具，来“快准狠”地定位系统的 I/O 瓶颈呢？本文是原理篇，后续还会陆续推出实战篇。  

### [《BPF之巅》读书笔记 - Linux 内核锁](https://mp.weixin.qq.com/s/r6WadnmdiiWrFWntcApHbw)
- **发布日期**：2023-12-17 10:00  
- **所属合集**：#Linux #BPF之巅  
- **摘要**：Linux内核中有许多不同类型的锁，这些锁的类型包括：互斥锁（mutex）、读写锁（rwlock）、自旋锁（spinlock）和信号量（semaphore），今天我们就来介绍一下这些锁以及使用的场景  

### [《BPF 性能之巅》读书笔记 - bpftrace 入门](https://mp.weixin.qq.com/s/wkJMrljIpPSAART3NX-hTA)
- **发布日期**：2023-12-15 08:00  
- **所属合集**：#BPF之巅  
- **摘要**：bpftrace 是 BPF 跟踪的高级前端，我们可以很方便的用它来做动态的追踪，从而可以快速进行系统的观测。  

### [《BPF之巅》读书笔记 - 使用 perf + perf-agent-map 制作容器化 Java 火焰图](https://mp.weixin.qq.com/s/aIhQkg8YB2vHNzBoYghN0w)
- **发布日期**：2023-12-13 08:10  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：容器化 Java 程序火焰图制作秘籍  

### [周末学习 -《BPF 之巅：洞悉Linux系统和应用性能》汇总](https://mp.weixin.qq.com/s/RwxE7p4XzrIy5n8bSUSNoA)
- **发布日期**：2023-12-09 17:00  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：周末学习《BPF 之巅：洞悉Linux系统和应用性能》  

### [《BPF 之巅：洞悉Linux系统和应用性能》读书笔记（四）火焰图](https://mp.weixin.qq.com/s/mQmEckPLyz_HyH2N3PVlyQ)
- **发布日期**：2023-12-08 12:30  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：什么是火焰图？确定 CPU 繁忙的原因是性能分析的一项重要工作，通常涉及分析堆栈跟踪。通过以固定速率采样进行  

### [《BPF 之巅：洞悉Linux系统和应用性能》读书笔记（三）Linux Kernel 相关知识](https://mp.weixin.qq.com/s/pYHCdSgfVo0N2dpvLq2gtA)
- **发布日期**：2023-12-02 19:56  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：今天我们来快速复习一下 Linux Kernel 相关的知识点  

### [《BPF 之巅》读书笔记（二）番外篇 - Linux 存储软件栈](https://mp.weixin.qq.com/s/FOrlcaOZ6PqBvRZbHWHoPg)
- **发布日期**：2023-12-01 21:48  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：Linux 存储栈入门  

### [《BPF之巅》读书笔记（一）Linux Tracing System](https://mp.weixin.qq.com/s/dujbESzKzoZyAoYbaPf_Dg)
- **发布日期**：2023-11-30 09:48  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：Linux Tracing System 的数据源（ kprobe，tracepoint）入门  

### [《BPF 之巅：洞悉Linux系统和应用性能》读书笔记开篇](https://mp.weixin.qq.com/s/PxJN2jXb4CvMD6yckmwJNQ)
- **发布日期**：2023-11-28 07:38  
- **所属合集**：#BPF之巅 #Linux #好书推荐  
- **摘要**：《BPF之巅》一书为我们打开了 Linux 内核大门，可以一窥内核原理和工作机制，为大家的以后的内核开发之旅铺平道路！  

### [系统性的学习 Linux Systems Performance](https://mp.weixin.qq.com/s/aqco2RFUoIcLO1d54Moc9Q)
- **发布日期**：2023-11-18 23:47  
- **所属合集**：#Linux #BPF之巅  
- **摘要**：Linux 系统性能的六个重要领域：可观测性工具、方法、基准测试、分析、跟踪和调优。Brendan Gregg 的演讲为我们打开了 Linux 系统性能的大门！  



## #CS

### [不要盲目刷 LeetCode，要巧用编码模式](https://mp.weixin.qq.com/s/epBmZJ3mJo41Uw_bbgQlQA)
- **发布日期**：2024-07-14 09:01  
- **所属合集**：#CS #杂项  
- **摘要**：无论大家是否喜欢，LeetCode 类型的问题几乎是每次编程面试的一部分，因此每个软件开发人员都应该在面试前练习它们。大家唯一的选择是明智地准备并通过关注底层问题模式来学习解决问题。​  

### [为什么机器人不能勾选“我不是机器人”复选框？](https://mp.weixin.qq.com/s/X6FJ3RJ6sevkXy1_yxx3zw)
- **发布日期**：2024-07-13 17:01  
- **所属合集**：#CS  
- **摘要**：机器人当然可以根据命令勾选复选框。但复选框追踪的信息比简单的复选框点击要多得多，以确定你是人类还是机器人。  



## #CUDA

### [GPU 利用率(Utilization) 是一个误导性指标!](https://mp.weixin.qq.com/s/dUhxU3QBnZ4kUMBzxrmC_w)
- **发布日期**：2025-04-08 19:15  
- **所属合集**：#CUDA #GPU #AI Infra  
- **摘要**：评估GPU使用时，许多人首看利用率，但它并不等于性能高。例如仅内存读写也会让GPU Util达100%，因此不能简单类比CPU Util，需结合更多指标（例如 SM Efficiency 和 MFU）全面判断。  

### [原力注入：AI Infra 知识体系（Body of knowledge for AI Infra) v1.1](https://mp.weixin.qq.com/s/nMgHwGYb9vVBx0g9EpNNoQ)
- **发布日期**：2024-11-03 15:31  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：经过这半年的学习和整理，笔者也逐步构建了笔者心中的 AI Infra 知识体系（Body of knowledge for AI Infra），供大家参考，今天推出了 1.1 版本！  

### [CUDA Processing Streams](https://mp.weixin.qq.com/s/Hm1PZ4rZe7GbOp2xtFPgdA)
- **发布日期**：2024-10-22 08:31  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：结合代码示例来深入学习 CUDA Stream 编程。  

### [AI Infra - CUDA 并发编程之 Stream 简介](https://mp.weixin.qq.com/s/mXvQ1Xo1E4BUzA4q_dPDUw)
- **发布日期**：2024-10-18 22:51  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：CUDA streams 是 CUDA 编程中用来管理并发执行的单元，在一个流中，操作是串行的按序执行的，但是在不同的流中操作就可以同时执行，从而完成并发操作。  

### [AI Infra - nvtop 快速入门](https://mp.weixin.qq.com/s/0D8UEkSkkpPeCNcHMNhWSA)
- **发布日期**：2024-10-16 19:25  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：nvtop 是一款类似于 htop 的命令行工具，可用于监控 NVIDIA、AMD、Intel 等多种 GPU。它提供了一个直观的界面，可以实时查看和管理 GPU 状态、指标数据。  

### [推荐两本开源 AI 书籍：《动手学深度学习》和《机器学习系统：设计和实现》](https://mp.weixin.qq.com/s/-JcJbpvUOTFx8wdqTYVn9Q)
- **发布日期**：2024-10-15 08:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：推荐两本开源 AI 书：《动手学深度学习》和《机器学习系统：设计和实现》  

### [AI Infra - 理解 GPU 架构之理解 GPU 特性「双语」](https://mp.weixin.qq.com/s/Agrtq4WqQj01MTlg-dwVlg)
- **发布日期**：2024-10-06 09:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：GPU 的硬件设计优化了高度并行处理。因此，GPU 的程序依赖于像 NVIDIA CUDA 这样的编程模型，与传统的基于CPU的串行编程模型有很大不同，本文就试图对 GPU 的特性进行阐述，帮助读者理解 GPU 和 CPU 的相同点和差异！  

### [原力注入：AI Infra 知识体系（Body of knowledge for AI Infra) v1.0](https://mp.weixin.qq.com/s/ptAdsvO5H34IOFSEwzWlsQ)
- **发布日期**：2024-10-05 17:00  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：经过这半年的学习和整理，笔者也逐步构建了笔者心中的 AI Infra 知识体系（Body of knowledge for AI Infra），供大家参考，后续会持续完善。  

### [深入了解 Nvidia CUDA 核心](https://mp.weixin.qq.com/s/PE3LmOAft27QCQNaaSFY7g)
- **发布日期**：2024-09-30 08:30  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：Nvidia 的 CUDA 核心是 Nvidia 显卡内的专门处理单元，旨在高效处理复杂的并行计算，使其成为高性能计算、游戏和各种图形渲染应用程序中的关键。  

### [AI Infra - 使用 CUDA 代码查询 GPU 卡详细信息](https://mp.weixin.qq.com/s/G6kfoNTdOmyOKQSHt83fHw)
- **发布日期**：2024-09-29 08:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：今天我们就来使用 CUDA 示例代码库提供的 deviceQueryDrv.cpp 示例代码来查询 GPU 卡的详细信息，用于全面了解 GPU 卡的详细特性。  

### [NVIDIA 全面转向开源 GPU 内核模块](https://mp.weixin.qq.com/s/WbGSkNhkcxK1HwYa3Fz_1g)
- **发布日期**：2024-07-19 08:50  
- **所属合集**：#CUDA  
- **摘要**：NVIDIA 的阳谋，通过开源让更多的人深度参与进来，从而间接阻止潜在竞争对手的发展。  

### [推荐《CUDA Reading Group 相关讲座》](https://mp.weixin.qq.com/s/6sOrNzG0UeVBes8stWSoWA)
- **发布日期**：2024-07-02 09:00  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：推荐《CUDA Reading Group 相关讲座》，共包含24个讲座，每个讲座有视频以及配套材料，对于 CUDA 编程感兴趣的同学可以深入参考！  

### [使用 Nsight 工具定量分析 CUDA 矩阵乘法几种实现](https://mp.weixin.qq.com/s/JK_bsvG-Y3wLJknZ4YKCYQ)
- **发布日期**：2024-06-20 12:15  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：矩阵乘法是大模型训练和推理的重要基础，因此我们需要通过工具定量来分析矩阵乘法，尤其是多级内存的使用效率，本文使用 Nsight 工具定量分析了几种矩阵乘法的实现，基于 Nsight 提供的 Kernel Profiling 能力。  

### [好书推荐 - 《CUDA C 编程权威指南》](https://mp.weixin.qq.com/s/xJY5Znv3cuQi_UCd_XjJ4A)
- **发布日期**：2024-06-18 13:30  
- **所属合集**：#CUDA  
- **摘要**：一直想找一本深入介绍 CUDA 编程的书或者资料，一直缺一本能从并行编程的基本概念，CUDA 编程模型以及最佳实践，由浅入深讲解的书，而《CUDA C 编程权威指南》则正是我想要的书，今天推荐给大家！  

### [CUDA 编程模型入门](https://mp.weixin.qq.com/s/IUYzzgt6DUYhfaDnbxoZuQ)
- **发布日期**：2024-06-16 14:30  
- **所属合集**：#CUDA  
- **摘要**：结合 GPU 硬件架构和一维向量加问题来讲解 CUDA 编程模型，让读者可以掌握 CUDA 最基本的并行编程概念。  

### [AI Infra 基础知识 - 一文介绍并行计算、费林分类法和 CUDA 基本概念](https://mp.weixin.qq.com/s/NL_Bz8JB-LdAtrQake7EdA)
- **发布日期**：2024-06-11 13:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：一文了解并行计算、费林分类法和 CUDA 基本概念，入门基于 CUDA 的 GPGPU 编程！  



## #Containerd

### [Containerd 客户端命令行工具入门](https://mp.weixin.qq.com/s/-dErBiG6Wd89SblN5ZFBTA)
- **发布日期**：2024-05-16 19:10  
- **所属合集**：#Containerd  
- **摘要**：当我们的容器进行时从 Docker 切换为 Containerd 后，需要从 docker 命令行切换到 Containerd 的命令行。常见的 Containerd 客户端命令行有 ctr 和 crictl。  

### [Docker、Containerd 和 runc 之间的关系](https://mp.weixin.qq.com/s/J809gD9SuTBv2tZZkUSSOw)
- **发布日期**：2024-05-12 11:00  
- **所属合集**：#Kubernetes #Docker #Containerd  
- **摘要**：Docker 提供了一组面向开发者的工具链；Containerd 实现了 CRI 规范，实现了容器的生命周期管理；runc 实现了 OCI Runtime spec，它是一个 CLI 工具，用于根据 OCI 规范生成和运行容器。  

### [新书推荐 - 《Containerd 原理剖析与实战》](https://mp.weixin.qq.com/s/_YBPeJJ0BVaR_d2pa5CDwA)
- **发布日期**：2024-05-09 22:00  
- **所属合集**：#Kubernetes #Containerd  
- **摘要**：Containerd 已经变成一个业界标准的容器运行时了，连口号都有了：超简单！超健壮！可移植性超强！因此我们也要卷起来，搞懂 Containerd 的原理。  



## #Docker

### [Docker 多阶段构建简介](https://mp.weixin.qq.com/s/vYzo5bPF48NnTBmvGAb7kQ)
- **发布日期**：2025-01-06 21:25  
- **所属合集**：#Docker  
- **摘要**：在本文中，我们将探讨生产容器镜像中不必要的软件包最常见的来源。我们将看到如何使用多阶段构建来生成更小、更安全的镜像（推荐文中的几张图）！  

### [解读 Linux Cgroup 之 cpuset 子系统及其在 Docker 中的使用](https://mp.weixin.qq.com/s/2N_g7nfj1VVsdsE5LIIq5g)
- **发布日期**：2024-11-27 12:55  
- **所属合集**：#Linux #Docker  
- **摘要**：在 Linux 系统中，cgroup（Control Groups）是一种用于限制、记录和隔离进程资源使用的机制。其中，cpuset 子系统主要用于管理 CPU 和内存节点的分配，可以有效实现资源隔离和性能优化。  

### [xx - Dockerfile 交叉编译助手](https://mp.weixin.qq.com/s/YCYhBeJMhoPHkTZ4LPUBkA)
- **发布日期**：2024-09-18 12:45  
- **所属合集**：#Docker  
- **摘要**：xx 提供了工具来支持从 Dockerfile 进行交叉编译，这些 Dockerfile 能理解从 docker build 或 docker buildx build 传递进来的 --platform 标志。  

### [Docker 史上最快捷「单机多平台」镜像构建](https://mp.weixin.qq.com/s/uCJxwdfa4r3vtbjPU3V5Vg)
- **发布日期**：2024-09-13 19:30  
- **所属合集**：#Docker  
- **摘要**：模拟安装+代码交叉编译，可以让我们的单机多平台构建大大加速，再加上 xx 工具（没错，名字就是xx），提供了很多帮助方法，使得这种场景下，
Dockerfile 的编写大大简化，值得大家学习使用！  

### [容器技术回顾：消失的 Docker 网络命名空间](https://mp.weixin.qq.com/s/mciucLzKH8wAIoxuQyze1A)
- **发布日期**：2024-09-12 08:30  
- **所属合集**：#Linux #Docker #网络基础知识  
- **摘要**：从命名空间伪文件列表中，我们可以看到此进程的 net 文件的存在。由于 net 文件对应于 Linux 网络命名空间，因此我们可以预期它会在列出所有网络命名空间时显示出来。但是，我们可以看到事实并非如此。  

### [喜大普奔 - 国内可以直接下载 Docker 官方镜像了！！！](https://mp.weixin.qq.com/s/w6Jdx2ZvRxEQouu6-FS84w)
- **发布日期**：2024-09-10 12:30  
- **所属合集**：#Docker #Tech News  
- **摘要**：实测可以下载镜像了  

### [容器技术回顾 - OverlayFS 简介](https://mp.weixin.qq.com/s/6-6vHjRxZF1MOahSzZm0yg)
- **发布日期**：2024-09-02 08:30  
- **所属合集**：#Linux #Docker  
- **摘要**：OverlayFS 伪文件系统首次包含在 Linux 内核 3.18 版本中：它允许我们将两个目录树或文件系统（一个“上层”和一个“下层”）以对用户完全透明的方式结合起来，用户可以像在标准文件系统上一样访问“合并”层上的文件和目录。  

### [Docker 镜像、容器和存储卷清理指南【双语】](https://mp.weixin.qq.com/s/Pcb_yzbYJ4CiFEBOR5yyzQ)
- **发布日期**：2024-08-28 08:30  
- **所属合集**：#Docker #Linux  
- **摘要**：在这篇博客中，让我们探索有效清理 Docker 资源的基本命令和方法。此外，我们还将看到定期 Docker 清理在防止资源混乱和降低安全风险方面的重要性。  

### [Kubelet 报错：inotify_add_watch ... no space left on device](https://mp.weixin.qq.com/s/CIfciM_f_3m_0vm93GTnbw)
- **发布日期**：2024-08-27 08:30  
- **所属合集**：#Linux #Kubernetes #Docker  
- **摘要**：Kubelet 报错：inotify_add_watch ... no space left on device。是磁盘空间不足了吗？原来罪魁祸首是 inotify！  

### [Docker Registry 的一种高可用方案](https://mp.weixin.qq.com/s/P13Vlj7UGnKtghVsevJIig)
- **发布日期**：2024-08-26 08:30  
- **所属合集**：#Docker #Linux #Kubernetes  
- **摘要**：现有版本 registry 只运行在一台 master 节点上，若该 master 节点宕机或是出了其他问题，registry 就会不可用。我们提供了一个基于 inotify + rsync 的高可用方案，供大家参考。  

### [如何优化 Docker 镜像体积？](https://mp.weixin.qq.com/s/8MBUVgjKKCsle6XN7dBDsQ)
- **发布日期**：2024-08-23 08:35  
- **所属合集**：#Docker  
- **摘要**：本文将分析导致 Docker 镜像体积变大的主要原因，并针对不同的场景，提供有效的优化策略。  

### [江湖救急：Docker 构建镜像时报“max depth exceeded”，该如何解决？](https://mp.weixin.qq.com/s/KRV-qYjOgpUBc6AzmC2hHA)
- **发布日期**：2024-08-22 08:00  
- **所属合集**：#Docker  
- **摘要**：在建镜像时，我们可能会遇到一个不常见但非常棘手的问题：“max depth exceeded”。这种问题通常出现在使用不当的 Dockerfile 中，构建过程中镜像层数过多，本文提供几种有效的解决方案，供读者参考。  

### [在 Docker 中使用 Capabilities 实现权限控制](https://mp.weixin.qq.com/s/shaFiJ0Ih2G_hLkZ6u6daA)
- **发布日期**：2024-08-04 23:45  
- **所属合集**：#Linux #Docker  
- **摘要**：为了适应更复杂的权限需求，从 2.2 版本起 Linux 内核能够进一步将超级用户的权限分解为细颗粒度的单元，这些单元称为 capabilities.几乎所有与超级用户相关的特权都被分解成了单独的 capability。  

### [Dockerfile CMD vs Entrypoint](https://mp.weixin.qq.com/s/Xb0q8bnP-l4mOe7FV8g16A)
- **发布日期**：2024-08-02 13:10  
- **所属合集**：#Docker  
- **摘要**：在 Docker 中，CMD 和 ENTRYPOINT 是两个常用于编写 Dockerfile 时指定容  

### [Docker attach 与 exec - 有什么区别？](https://mp.weixin.qq.com/s/2J--HnfoM_EZiFPq0AJxOQ)
- **发布日期**：2024-07-25 12:35  
- **所属合集**：#Docker #Kubernetes  
- **摘要**：​Docker exec  和  attach​ 这两个命令之间的区别常常让人感到困惑。这两个命令具有相似的参数，乍一看行为也相似。然而，attach 和 exec 不能互换，它们旨在涵盖不同的用例，命令的实现也不同。  

### [知乎问题：宿主机是 ubuntu 22，容器是 ubuntu 24，容器是否可正常使用 ubuntu 24 特有的一些新功能？](https://mp.weixin.qq.com/s/C3Faz_g5nyP7WUEAzsJxFA)
- **发布日期**：2024-07-16 08:50  
- **所属合集**：#Docker #Linux  
- **摘要**：宿主机是 ubuntu 22，容器是 ubuntu 24，容器是否可正常使用 ubuntu 24 特有的一些新功能？  

### [深入研究 Linux Namespace - 第一部分](https://mp.weixin.qq.com/s/xOrUChPfHYyP2qQYxB8zDQ)
- **发布日期**：2024-07-10 14:05  
- **所属合集**：#Linux #Docker  
- **摘要**：进程隔离是容器的关键能力。用到的底层机制之一是 Linux Namespace。今天我们就深入研究一下。  

### [在 Docker 中使用 Linux User Namespace 隔离容器用户](https://mp.weixin.qq.com/s/7e75EVdlFeISqdoZqlbUrw)
- **发布日期**：2024-07-10 14:05  
- **所属合集**：#Docker #Linux  
- **摘要**：防止容器内特权升级攻击的最佳方法是将容器的应用程序配置为以非特权用户身份运行。对于其进程必须以root容器内用户身份运行的容器，我们可以将此用户重新映射到 Docker 主机上权限较低的用户。  

### [在 Docker 中使用 Linux User Namespace 隔离容器用户](https://mp.weixin.qq.com/s/bPuo36dhTs5d8VhQJUH4PQ)
- **发布日期**：2024-07-09 16:20  
- **所属合集**：#Docker #Linux  
- **摘要**：防止容器内特权升级攻击的最佳方法是将容器的应用程序配置为以非特权用户身份运行。对于其进程必须以root容器内用户身份运行的容器，我们可以将此用户重新映射到 Docker 主机上权限较低的用户。  

### [深入研究 Linux Namespace - 第一部分](https://mp.weixin.qq.com/s/V-5-xeAGkIwprkSGAfI32Q)
- **发布日期**：2024-07-06 09:00  
- **所属合集**：#Linux #Docker  
- **摘要**：进程隔离是容器的关键能力。用到的底层机制之一是 Linux Namespace。今天我们就深入研究一下。  

### [容器技术基础知识 - Cgroup 相关资料汇总](https://mp.weixin.qq.com/s/aXfnrlrWQKZEjnwzQGXsrg)
- **发布日期**：2024-07-04 09:00  
- **所属合集**：#Kubernetes #Docker  
- **摘要**：Cgroup是control group的简写，属于Linux内核提供的一个特性，用于限制和隔离一组进程对系统资源的使用，也就是做资源QoS，这些资源主要包括CPU、内存、block I/O和网络带宽。  

### [容器技术发展简史](https://mp.weixin.qq.com/s/Lnlpn5mGJ4X-rg5mF-vdFA)
- **发布日期**：2024-05-19 19:01  
- **所属合集**：#Docker  
- **摘要**：容器的使用越来越广泛，最近几年，越来越多的企业开始采用容器作为新的 IT 基础设施。为了更好理解容器技术的发展，我们需要回顾一下容器技术的发展历史。容器早在 20 世纪 70 年代末就已出现雏形，Docker 就是在这些技术上发扬光大了！  

### [Docker 小技巧：处理无名称的镜像（悬空镜像）](https://mp.weixin.qq.com/s/6RBjf83SXQA2iFob2XfvEg)
- **发布日期**：2024-05-17 19:31  
- **所属合集**：#Docker  
- **摘要**：这些没有名称和标签的镜像通常被称为“悬空镜像”（dangling images）。这些镜像在系统中可能占用大量的磁盘空间，但没有被引用，通常可以删除它们来释放空间。  

### [Docker、Containerd 和 runc 之间的关系](https://mp.weixin.qq.com/s/J809gD9SuTBv2tZZkUSSOw)
- **发布日期**：2024-05-12 11:00  
- **所属合集**：#Kubernetes #Docker #Containerd  
- **摘要**：Docker 提供了一组面向开发者的工具链；Containerd 实现了 CRI 规范，实现了容器的生命周期管理；runc 实现了 OCI Runtime spec，它是一个 CLI 工具，用于根据 OCI 规范生成和运行容器。  

### [好书推荐 - 《自己动手写 docker》](https://mp.weixin.qq.com/s/cpL3Y-UUzeqdYdrOOLH2NA)
- **发布日期**：2024-03-15 12:04  
- **所属合集**：#Docker #好书推荐  
- **摘要**：本书在详细分析Docker所依赖的技术栈的基础上，一步一步地通过代码实例，让读者可以自己循序渐进地用Go语言构建出一个容器的引擎。  

### [Linux 小技巧 - 模拟 Docker hang 住](https://mp.weixin.qq.com/s/emha2o0B55UTyJ_bBitMjw)
- **发布日期**：2024-01-27 10:20  
- **所属合集**：#Linux #Docker  
- **摘要**：我们是否可以模拟 Docke 命令 hang 住的情况呢？答案是 Yes，可以使用 freezer Cgroup 来制造包含 D 状态进程的容器！  

### [Docker & Kubernetes 原理入门课程推荐](https://mp.weixin.qq.com/s/gZBv6rm8cweBvYZ3v35t8Q)
- **发布日期**：2024-01-21 00:06  
- **所属合集**：#Docker  
- **摘要**：Docker 和 Kubernetes 原理课程推荐  

### [Docker & Kubernetes 原理入门课程推荐](https://mp.weixin.qq.com/s/zOGdMEX-xrdRIMddohgUQg)
- **发布日期**：2024-01-20 09:15  
- **所属合集**：#Docker  
- **摘要**：Docker 和 Kubernetes 原理课程推荐  

### [容器技术回顾 - 如何修改容器的内核参数](https://mp.weixin.qq.com/s/04O2Y66_JyXhBR9bd4Uzuw)
- **发布日期**：2024-01-19 08:01  
- **所属合集**：#Linux #Kubernetes #Docker  
- **摘要**：在某些场景中，我们需要调整内核参数，来调整操作系统行为。那在容器化场景中，我们是否可以调整？哪些可以调整？如何调整？  

### [容器技术回顾 - Linux 内存文件系统](https://mp.weixin.qq.com/s/5oDwatGU8kCDY_62P3piSg)
- **发布日期**：2024-01-16 21:56  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：大家是否有注意过 Linux 主机上的 /dev/shm 设备？它是什么  

### [容器技术回顾 - 多 Pod 间共享内存通信](https://mp.weixin.qq.com/s/JOzzrgrxgyca1EpQfn9NaQ)
- **发布日期**：2024-01-14 20:00  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：本文介绍了一种在单节点上使用 tmpfs 模拟共享内存的方式，实现多个 Pod 之间可以实现共享内存通信。  

### [容器技术回顾 - 从一个“D”状态容器进程回顾 cgroup freezer 子系统](https://mp.weixin.qq.com/s/SRnya2Y5kwJu3PYHug8jeQ)
- **发布日期**：2024-01-10 22:17  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：从一个 “D” 状态的容器进程，来回顾 cgroup freezer 子系统，同时提供相关脚本来帮助"解冻"进程！  

### [容器技术回顾 - 如何让我的容器/进程不要被 OOM Kill？](https://mp.weixin.qq.com/s/AoyWzaXQcgCPGTTBHjQzRQ)
- **发布日期**：2024-01-09 23:55  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：在 Kubernetes 环境中，我们会遇到 Java OOM -> Linux cgroup OOM -> Linux OOM 三种不同类型的 OOM，它们是什么？我们如何让我们的容器避免被 OOM Kill 呢？  

### [为什么同样使用2个vCPU的App在VM中比在容器中运行的快？](https://mp.weixin.qq.com/s/t3DjEmHxatWmYDonJKjjyA)
- **发布日期**：2024-01-06 10:32  
- **所属合集**：#Linux #Docker  
- **摘要**：容器技术回顾 - Kubernetes CPU request 和 limit 的作用与原理 一文中  

### [为什么同样使用2个vCPU的App在VM中比在容器中运行的快？](https://mp.weixin.qq.com/s/hqjx-PgHEkUEoOnRbdiXTA)
- **发布日期**：2024-01-04 12:12  
- **所属合集**：#Linux #Docker  
- **摘要**：容器技术回顾 - Kubernetes CPU request 和 limit 的作用与原理 一文中  

### [容器技术回顾（六） - 容器与主机共享内核是什么含义？](https://mp.weixin.qq.com/s/oA-tuw2vDB3TWO27mhGZiA)
- **发布日期**：2024-01-03 12:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：容器和主机共享内核，这得益于Linux有一个统一的内核体系。不同的 Linux 发行版使用了相同的内核体系，这使得基于不同 Linux 发行版构建的容器可以在一个 Linux 发行版上运行。那容器和主机共享内核有什么影响吗？​  

### [容器技术回顾 - Kubernetes memory limit 产生的 OOM](https://mp.weixin.qq.com/s/s-OKhQ1qa7w1muUQAUuyTQ)
- **发布日期**：2023-12-29 12:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：一次奇怪的 cgroup oom 问题分析，由此我们回顾了一下相关知识点。  

### [容器技术回顾 - Kubernetes CPU request 和 limit 的作用与原理](https://mp.weixin.qq.com/s/OinmIMOr5W0BWOUrC-LVTA)
- **发布日期**：2023-12-27 20:01  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：本文我们会回顾一下 Kubernetes 中 CPU request 和 limit 的含义，以及背后实现的原理。  

### [容器技术回顾（三） - 被误解的 Docker 存储驱动](https://mp.weixin.qq.com/s/R1p97qI3fE_7BF2wW0jc1w)
- **发布日期**：2023-12-23 10:00  
- **所属合集**：#Kubernetes #Docker  
- **摘要**：很多时候我们把 Docker 存储驱动（Storage Driver）和 Docker 存储卷（Volume）混为一谈，这里我们先回顾一下他们的概念，并明确一下两者的使用场景。  

### [容器技术回顾 - 什么是优雅关闭以及如何实现](https://mp.weixin.qq.com/s/IxnkW5App4xJJPOeUD-uIQ)
- **发布日期**：2023-12-21 09:00  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：要实现容器的优雅关闭，我们需要做哪些事情呢？今天就让我们从 Linux 进程的优雅退出开始，来回顾一下容器的优雅关闭原理以及实现方式。  

### [容器技术回顾  - 容器中的 0 号进程和 1 号进程](https://mp.weixin.qq.com/s/PIwVV7xfw3umSL-n2Hsw_g)
- **发布日期**：2023-12-19 08:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：对 Linux 系统来说 1 号进程为 init 进程，是由 0 号进程通过调用系统 init 函数创建的第一个用户进程 1 进程，主要做用户态进程的管理，垃圾回收等动作。那容器中是否存在 0 号进程和 1 号进程呢？它们有什么用？  

### [驳斥《把数据库放入Docker是一个好主意吗？》](https://mp.weixin.qq.com/s/dgeVOGNxuG7rBMQdjKoFgw)
- **发布日期**：2023-12-04 19:32  
- **所属合集**：#Docker #Kubernetes  
- **摘要**：容器（化带来了标准化、隔离、控制和高利用率的好处，数据库场景到底是否合适，笔者认为只要能够转变运维习惯，在没有引入太多 overhead 和性能损失的情况下，容器化实际上提供了更多运维自动化的可能性，结合 K8s，就可以实现 DBaaS  



## #GPU

### [GPU 利用率(Utilization) 是一个误导性指标!](https://mp.weixin.qq.com/s/dUhxU3QBnZ4kUMBzxrmC_w)
- **发布日期**：2025-04-08 19:15  
- **所属合集**：#CUDA #GPU #AI Infra  
- **摘要**：评估GPU使用时，许多人首看利用率，但它并不等于性能高。例如仅内存读写也会让GPU Util达100%，因此不能简单类比CPU Util，需结合更多指标（例如 SM Efficiency 和 MFU）全面判断。  



## #Java

### [应用上云 - Azure 官方 Java 容器化策略文档](https://mp.weixin.qq.com/s/U5KEB7mRMF7aXeAkmage-g)
- **发布日期**：2024-02-26 12:01  
- **所属合集**：#Kubernetes #应用上云 #Java  
- **摘要**：本文介绍了用于容器化 Java 应用程序以部署到 Kubernetes 上的建议策略。  

### [Java Spring 应用如何更好地在 Kubernetes 上运行？](https://mp.weixin.qq.com/s/3KWOFsA89AV9G20yzT2nDA)
- **发布日期**：2024-01-20 09:15  
- **所属合集**：#应用上云 #Kubernetes #Java  
- **摘要**：nan  

### [云原生之下的Java](https://mp.weixin.qq.com/s/SChVmqMzD25LJn6bpWSmrg)
- **发布日期**：2019-05-31 18:30  
- **所属合集**：#Java  
- **摘要**：nan  



## #Kubernetes

### [从入门到精通：全面解读 Kubernetes CronJobs](https://mp.weixin.qq.com/s/bHeJRsF-8EmiUi-w4KQBrQ)
- **发布日期**：2025-01-26 13:25  
- **所属合集**：#Kubernetes  
- **摘要**：本文将深入探讨 Kubernetes CronJobs 的工作原理、配置方法、最佳实践以及实际用例，以说明如何有效利用它们。  

### [好书推荐 - 《分布式系统应用设计》](https://mp.weixin.qq.com/s/ovopXcjXO-7ky35V36hW6g)
- **发布日期**：2025-01-25 21:07  
- **所属合集**：#Kubernetes #好书推荐  
- **摘要**：容器及编排系统的快速发展革新了分布式系统的开发与部署方式，为核心开发模式及容器化组件提供全新接口。《分布式系统应用设计》手册聚焦常见设计模式，助力开发者高效构建可靠分布式系统。  

### [Kubernetes 端口转发实战指南](https://mp.weixin.qq.com/s/Q6pB1YFb2zP8k8AalhT2ew)
- **发布日期**：2025-01-24 12:50  
- **所属合集**：#Kubernetes  
- **摘要**：本页面介绍如何使用 kubectl port-forward 连接到运行在 Kubernetes 集群中的服务器。这种连接方式对于调试开发非常有用。  

### [当我们谈论 Linux 主机/集群管理时，我们需要关注哪些工作呢？](https://mp.weixin.qq.com/s/yslC-waAyuXjFbrpUjF9DA)
- **发布日期**：2025-01-18 10:08  
- **所属合集**：#Linux #Kubernetes  
- **摘要**：在运行 Kubernetes 集群时，我们实际上依赖于底层的主机集群。本文讨论的集群特指主机集群，即从操作系统（OS）的视角来管理的资源集合。本文仅涵盖与 Linux 操作系统相关的操作。  

### [云原生应用生命周期管理：OAM 介绍](https://mp.weixin.qq.com/s/yby9j21KJpoMeNkEZjh55A)
- **发布日期**：2025-01-16 08:35  
- **所属合集**：#Kubernetes #云原生  
- **摘要**：Open Application Model是一个云原生应用的开放标准规范，其核心理念是“以应用为中心”，实现应用描述与基础设施的解耦。通过这种方式，OAM 为开发者提供了更高的关注点抽象，帮助他们专注于应用逻辑，而不必陷入底层技术的复杂性  

### [Kubernetes 生态中开源软件的 License 分析与合规指南](https://mp.weixin.qq.com/s/A0djGf1tX5uGIAU4qf6SNQ)
- **发布日期**：2025-01-15 08:15  
- **所属合集**：#Kubernetes  
- **摘要**：本文旨在梳理 Kubernetes 生态相关软件的 License 类型及其影响，为开发者基于 Kubernetes 开发和发布软件提供参考。  

### [云原生应用生命周期管理：主从架构 MySQL 案例解析](https://mp.weixin.qq.com/s/XnEx5IiybadQpBoie9iyWw)
- **发布日期**：2025-01-14 08:05  
- **所属合集**：#云原生 #Kubernetes  
- **摘要**：Kubernetes 的 Deployment 和 StatefulSet 适合无状态微服务，但在处理复杂分布式应用（如主从架构的 MySQL）时，原生资源难以满足拓扑管理、故障恢复和动态配置等高级需求。此时就需要使用Operator模式。  

### [云原生应用生命周期管理：需求分析](https://mp.weixin.qq.com/s/T-cR63-Kb6xD0zhgsUYtwA)
- **发布日期**：2025-01-12 23:15  
- **所属合集**：#Kubernetes #云原生  
- **摘要**：本文将从需求分析的角度，探讨云原生应用生命周期管理的必要性，并结合云原生应用的需求和 Kubernetes 工作负载的局限性。除此之外，本文还将根据作者多年在 PaaS 平台的工作经验，提出应用生命周期管理的一级功能和二级功能定义。  

### [Spring Boot on K8s 优雅停机流程解析【修改版】](https://mp.weixin.qq.com/s/AviHIUdxXI0f0pLHPJmnfQ)
- **发布日期**：2025-01-09 12:35  
- **所属合集**：#Kubernetes  
- **摘要**：本文将通过一个完整的时间轴，详细解析 Kubernetes 和 Spring Boot 在 Pod 停止时的交互过程，并附上具体配置示例，帮助开发者实现优雅的停止机制。  

### [K8s Pod 出现 UnexpectedAdmissionError 的原因及解决方案](https://mp.weixin.qq.com/s/AHmocDUJ54hn579V9mAZGQ)
- **发布日期**：2025-01-09 12:35  
- **所属合集**：#Kubernetes  
- **摘要**：UnexpectedAdmissionError 表示在 Pod 的准入控制阶段发生了意外错误，导致 Pod 无法正常启动。这种错误通常与资源分配、调度器配置或设备管理相关。本文提供了原因分析和解决方案。  

### [Spring Boot on K8s 优雅停机流程解析](https://mp.weixin.qq.com/s/HBczcBzLZW5fKG8EqzsghQ)
- **发布日期**：2025-01-08 19:30  
- **所属合集**：#Kubernetes  
- **摘要**：本文将通过一个完整的时间轴，详细解析 Kubernetes 和 Spring Boot 在 Pod 停止时的交互过程，并附上具体配置示例，帮助开发者实现优雅的停止机制。  

### [怀念一下 Mesos](https://mp.weixin.qq.com/s/Qw8VDRwREfWcxYY-qg8wsA)
- **发布日期**：2025-01-05 09:31  
- **所属合集**：#Kubernetes  
- **摘要**：大概 2017 年到 2018 年，大家开始全面转向到 Kubernetes 了。Kubernetes 的成功不仅是技术的胜利，更是生态的胜利。容器的标准化设计、社区的强大协作以及高易用性，成为容器编排领域的事实标准。  

### [CNCF: 在 Kubernetes 上运行数据白皮书 - 数据库模式](https://mp.weixin.qq.com/s/_UT5TwJdBTceHFKcQEzHoA)
- **发布日期**：2024-12-25 12:41  
- **所属合集**：#Kubernetes  
- **摘要**：本文档旨在描述 Kubernetes 上运行数据的模式，聚焦数据库应用。内容涵盖存储属性及其对数据库的影响，不同存储堆栈的差异，Kubernetes 内外运行数据的区别，Kubernetes 特性对数据运行的优势，以及最佳实践和经验总结。  

### [Open Policy Agent（OPA）简介](https://mp.weixin.qq.com/s/saj2BpowJjmeOzofOnCFxg)
- **发布日期**：2024-09-23 09:05  
- **所属合集**：#Kubernetes  
- **摘要**：Open Policy Agent（OPA）是一个开源的、通用的策略引擎，它统一了整个栈中的策略执行。OPA 提供了一个高级的声明式语言，让我们能够将策略以代码的形式指定，并通过简单的 API 将策略决策从 K8s 转到我们的代码来执行  

### [Kubernetes 生产最佳实践之「合规治理」](https://mp.weixin.qq.com/s/gRu_mEcjgMXzq2FDO2pD3w)
- **发布日期**：2024-09-20 08:30  
- **所属合集**：#Kubernetes  
- **摘要**：创建、管理和管理命名空间的最佳实践。  

### [在离线混部作业调度与资源管理技术研究综述 - 读后感（一）](https://mp.weixin.qq.com/s/Ur4EdbA32xRwZX6hxyT47w)
- **发布日期**：2024-09-09 08:30  
- **所属合集**：#Kubernetes  
- **摘要**：论文分析了在线作业与离线作业的特征，探讨了在离线作业间性能干扰等混部所面临的技术挑战，从性能干扰模型、作业调度、资源隔离与资源动态分配等方面就在离线混部技术进行了综述。本文就先聊一聊“资源隔离”技术！  

### [Kubernetes 存储卷快照「双语」](https://mp.weixin.qq.com/s/YDrneR44E8YtREur6OVn9A)
- **发布日期**：2024-08-30 08:30  
- **所属合集**：#Kubernetes  
- **摘要**：在这篇博客文章中，我们将深入探讨 Kubernetes 数据管理的核心。我们将揭示卷快照的细节，并理解它们在保护数据、创建备份计划和设置测试环境中的关键作用。  

### [Kubelet 报错：inotify_add_watch ... no space left on device](https://mp.weixin.qq.com/s/CIfciM_f_3m_0vm93GTnbw)
- **发布日期**：2024-08-27 08:30  
- **所属合集**：#Linux #Kubernetes #Docker  
- **摘要**：Kubelet 报错：inotify_add_watch ... no space left on device。是磁盘空间不足了吗？原来罪魁祸首是 inotify！  

### [Docker Registry 的一种高可用方案](https://mp.weixin.qq.com/s/P13Vlj7UGnKtghVsevJIig)
- **发布日期**：2024-08-26 08:30  
- **所属合集**：#Docker #Linux #Kubernetes  
- **摘要**：现有版本 registry 只运行在一台 master 节点上，若该 master 节点宕机或是出了其他问题，registry 就会不可用。我们提供了一个基于 inotify + rsync 的高可用方案，供大家参考。  

### [Kubernetes 基础知识 - 污点与容忍度、亲和性与节点选择器](https://mp.weixin.qq.com/s/FP7B2bi3IPqMeB2FmHZB6w)
- **发布日期**：2024-08-21 08:35  
- **所属合集**：#Kubernetes  
- **摘要**：​在 Kubernetes 中，污点、亲和性与节点选择器是三种主要机制，用于控制 Pod 在集群中的调度。本文将探讨这三种机制之间的区别，并展示如何有效使用它们来优化集群中的 Pod 调度。  

### [Kubernetes 生产最佳实践之「集群配置」（双语）](https://mp.weixin.qq.com/s/PLdVdZvBb1FsiFDbm2i_TA)
- **发布日期**：2024-08-08 19:25  
- **所属合集**：#Kubernetes  
- **摘要**：Kubernetes 生产最佳实践之「集群配置」  

### [Kubernetes 生产最佳实践之「应用适配」（双语）](https://mp.weixin.qq.com/s/qZVwpbbY-VqvJL9tI5iM7g)
- **发布日期**：2024-08-07 13:40  
- **所属合集**：#Kubernetes  
- **摘要**：Kubernetes 上应用开发的最佳实践（Best practices for application development on Kubernetes）。当然了这里的应用开发更多的是指如何利用好 Kubernetes 的功能。  

### [Kubernetes 攻防 - 窃取 Service Account 令牌获取集群权限及对应检测方式](https://mp.weixin.qq.com/s/OWjUoH5RITz4GT2RxKfsPQ)
- **发布日期**：2024-07-30 08:35  
- **所属合集**：#Kubernetes  
- **摘要**：k8s 的"service account tokens"包含了“应用程序用于进行身份验证和执行操作”的权限。本文说明了如何在容器中单独使用这些令牌，查看当今许多流行应用程序所请求的具体权限，并展示了如何利用它们进一步攻陷 k8s 环境。  

### [Kubernetes：批量创建命名空间，并为每个命名空间指定「用户」以及 「kube config」](https://mp.weixin.qq.com/s/qNDD-2RyZTls8psQQ7eWYw)
- **发布日期**：2024-07-28 18:05  
- **所属合集**：#Kubernetes  
- **摘要**：有 N 组同学要在一个 Kubernetes 集群上做实验，因此需要为每个组创建命名空间，service account 和 kube config，为了偷懒，笔者就写了一个脚本用于自动生成相关配置！  

### [Docker attach 与 exec - 有什么区别？](https://mp.weixin.qq.com/s/2J--HnfoM_EZiFPq0AJxOQ)
- **发布日期**：2024-07-25 12:35  
- **所属合集**：#Docker #Kubernetes  
- **摘要**：​Docker exec  和  attach​ 这两个命令之间的区别常常让人感到困惑。这两个命令具有相似的参数，乍一看行为也相似。然而，attach 和 exec 不能互换，它们旨在涵盖不同的用例，命令的实现也不同。  

### [好书推荐 - 《Certified Kubernetes Administrator (CKA) Study Guide》](https://mp.weixin.qq.com/s/_AIw0lQcU-bOufjlUKceLQ)
- **发布日期**：2024-07-16 08:50  
- **所属合集**：#Kubernetes  
- **摘要**：大家肯定听说过 CKA 认证考试吧，那除了自学之外，有什么比较有针对性的学习资料呢？今天就给大家推荐一本好书！  

### [Kubernetes 1.30：对 Pod 使用用户命名空间的支持进阶至 Beta](https://mp.weixin.qq.com/s/tZwzd0W7U_68x04WtGY2NQ)
- **发布日期**：2024-07-11 09:05  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：在 Kubernetes v1.25 中，我们仅为无状态 Pod 引入了对用户命名空间的支持。Kubernetes 1.28 取消了这一限制，目前在 Kubernetes 1.30 中，这个特性进阶到了 Beta！  

### [Kuberentes 小课堂 - 快捷运行 Python 服务](https://mp.weixin.qq.com/s/GkI8b77WKR3laFj6Wr9OAA)
- **发布日期**：2024-07-06 09:00  
- **所属合集**：#Kubernetes  
- **摘要**：那我们有没有简单方法，直接一个 YAML 文件就运行呢？答案是有的，那就是使用 Configmap（同时 Python 程序是解释性语言，不需要编译，这个也为我们提供了方便），  

### [容器技术基础知识 - Cgroup 相关资料汇总](https://mp.weixin.qq.com/s/aXfnrlrWQKZEjnwzQGXsrg)
- **发布日期**：2024-07-04 09:00  
- **所属合集**：#Kubernetes #Docker  
- **摘要**：Cgroup是control group的简写，属于Linux内核提供的一个特性，用于限制和隔离一组进程对系统资源的使用，也就是做资源QoS，这些资源主要包括CPU、内存、block I/O和网络带宽。  

### [Kubernetes 小技巧 - 使用 Downward API 将配置传递给 Pod](https://mp.weixin.qq.com/s/l6jEetEe8quzhK5jgCFvMg)
- **发布日期**：2024-07-03 22:30  
- **所属合集**：#Kubernetes  
- **摘要**：容器需要有关自身的信息很有用，但我们又不希望让容器与 Kubernetes 过度耦合。Downward API 允许容器使用有关自身或系统的信息，并按照多种方式将这些信息暴露给到容器，而不必与 Kubernetes 耦合。  

### [你现在用的 Kubernetes Secrets 安全吗？](https://mp.weixin.qq.com/s/GtPcMRtii9coU5N8Wh-BBg)
- **发布日期**：2024-06-29 09:02  
- **所属合集**：#Kubernetes  
- **摘要**：K8s 提供了 Secret 资源来保存、设置一些敏感信息。 但是 Secret 并不安全，我们可以非常方便的看到 Secret 的原文，只要有相关的权限即可，本文讨论了几个 secret 保护的方案，供大家参考！  

### [在 Linux 容器中可以使用独立于主机的系统时间吗？](https://mp.weixin.qq.com/s/qppow2Wok1zwY5bgQEzJEw)
- **发布日期**：2024-06-27 08:05  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：在 Linux 容器中可以使用独立于主机的时间吗？老版本内核不支持，但是随着 Linux Kernel 5.6 引入了 time namespace，以及 runc 开始支持 time namespace，将来的版本就可以支持了！  

### [Kubernetes 网络和 Cilium：网络工程师手册](https://mp.weixin.qq.com/s/EU32HV8h6qZ57OUWUVhPPg)
- **发布日期**：2024-06-22 10:00  
- **所属合集**：#Kubernetes #网络基础知识  
- **摘要**：Cilium 是业界较早采用 BPF 技术的 Kubernetes CNI，今天推荐由它发布的一本网络小册子，让我们来看看它们视角的 Kunernetes 网络。  

### [Kubernetes 基础知识：持久卷、持久卷声明和 StorageClass](https://mp.weixin.qq.com/s/2cDj2Yr_GExoCHeLASl0uA)
- **发布日期**：2024-06-17 19:01  
- **所属合集**：#Kubernetes  
- **摘要**：在这篇文章中，我们将深入研究持久卷 (PV) 并探索其特性和功能，并且也介绍了 Storage Class（用于动态供应）。  

### [【Kubernetes 网络】好书推荐](https://mp.weixin.qq.com/s/4YQXZgqMYCaJGS4ZRZJwig)
- **发布日期**：2024-06-13 12:40  
- **所属合集**：#Kubernetes #网络基础知识  
- **摘要**：看了昨天“强烈推荐：《Container Networking: From Docker to Kubernetes》中文翻译”还意犹未尽，想再深入了解的同学，可以读一下文中推荐的两本书！  

### [强烈推荐：《Container Networking: From Docker to Kubernetes》中文翻译](https://mp.weixin.qq.com/s/h1NH52AyMgrcp336ajsdOQ)
- **发布日期**：2024-06-12 09:10  
- **所属合集**：#Kubernetes  
- **摘要**：一文入门容器网络！虽然内容有些过时，但是不妨碍我们建立起整个容器网络的知识体系，同时也算是见证了过去十年容器技术的发展！  

### [Kubernetes 小技巧 - 使用 Helmify 将 K8s YAML 文件转换成 Helm Chart](https://mp.weixin.qq.com/s/Wl3rCofbb5UVB8Vil1RSxA)
- **发布日期**：2024-06-07 08:45  
- **所属合集**：#Kubernetes  
- **摘要**：前文：Kuberneters 小技巧 - 将 K8s YAML 文件转换为 Helm Chart，有读者说可以使用 helmify 来将 K8s YAML 文件转换成 Helm Chart，笔者今天就来实验一下。  

### [Kuberneters 小技巧 - 将 K8s YAML 文件转换为 Helm Chart](https://mp.weixin.qq.com/s/tnSRJPbP9Rc3d8XkdbEj9g)
- **发布日期**：2024-06-05 09:04  
- **所属合集**：#Kubernetes  
- **摘要**：Helm 允许用户将 Kubernetes 应用程序定义、安装和管理为称为 Charts 的包。在本文中，我们将探讨如何将 Kubernetes  YAML 文件转换为 Helm Charts。  

### [Kubernetes 小技巧：kube-state-metrics 入门](https://mp.weixin.qq.com/s/WLHXdrtjOG_9hYGENRcBWw)
- **发布日期**：2024-05-24 12:40  
- **所属合集**：#Kubernetes  
- **摘要**：kube-state-metrics 通过监听 Kubernetes API 服务器来生成不同资源的状态的指标数据，配合 Grafana Dashboard，是 Kubernetes 集群监控的利器！  

### [Kubernetes 网络和安全简介（一）](https://mp.weixin.qq.com/s/lVG1pYqsc2WdZiE57xJDqg)
- **发布日期**：2024-05-23 23:00  
- **所属合集**：#Kubernetes #网络基础知识  
- **摘要**：Calico 背后的公司 TIGERA 出了一本书《Introduction to Kubernetes Networking and Security》，此书难度中等，可以让大家对相关概念或者原理有个初步了解。  

### [Docker、Containerd 和 runc 之间的关系](https://mp.weixin.qq.com/s/J809gD9SuTBv2tZZkUSSOw)
- **发布日期**：2024-05-12 11:00  
- **所属合集**：#Kubernetes #Docker #Containerd  
- **摘要**：Docker 提供了一组面向开发者的工具链；Containerd 实现了 CRI 规范，实现了容器的生命周期管理；runc 实现了 OCI Runtime spec，它是一个 CLI 工具，用于根据 OCI 规范生成和运行容器。  

### [新书推荐 - 《Containerd 原理剖析与实战》](https://mp.weixin.qq.com/s/_YBPeJJ0BVaR_d2pa5CDwA)
- **发布日期**：2024-05-09 22:00  
- **所属合集**：#Kubernetes #Containerd  
- **摘要**：Containerd 已经变成一个业界标准的容器运行时了，连口号都有了：超简单！超健壮！可移植性超强！因此我们也要卷起来，搞懂 Containerd 的原理。  

### [Kubernetes 基础知识：Finalizers 是什么？有什么作用？](https://mp.weixin.qq.com/s/Wtg0dpxMxIreOJYL9Y2xRQ)
- **发布日期**：2024-04-05 17:00  
- **所属合集**：#Kubernetes  
- **摘要**：Kubernetes 对象删除并不像表面上看起来那么简单。删除对象是一个复杂的过程，其中包括条件检查以确定是否可以安全删除。这是通过称为 Finalizers 的 API 对象来实现的。  

### [新书推荐 - 《边缘云部署与运营：系统性实现方法》（博主翻译）](https://mp.weixin.qq.com/s/F0c8IKLlCbLJ3OlDVpCoDw)
- **发布日期**：2024-03-16 10:30  
- **所属合集**：#Kubernetes #好书推荐  
- **摘要**：本书以 Aether 平台为例，从边缘云整个平台的架构设计到每个子系统的构建与运维做了细致的阐述，使得读者可以比较全面地了解边缘云的建设与运维，浅显易懂。  

### [Kubernetes 缩容工作负载时，如何指定要被删除的 Pod？](https://mp.weixin.qq.com/s/GzOOdbf7eUO1x7KFrSqIOg)
- **发布日期**：2024-03-08 12:15  
- **所属合集**：#Kubernetes  
- **摘要**：大家是否好奇，手工修改 Deployment 中 Pod 的数量或者是通过 HPA 更改 Pod 数量，Kubernetes 是随机选择要删除的 Pod 吗？  

### [云原生混合部署（在线离线混合部署）资料整理](https://mp.weixin.qq.com/s/m9bC_-wm6u6bzgOKAjVRiA)
- **发布日期**：2024-03-01 22:30  
- **所属合集**：#Kubernetes  
- **摘要**：服务器资源利用率低一直是业界公认的难题，随着云原生技术的发展，将在线（高优先级）、离线（低优先级）业务混合部署成为了当下提高资源利用率的有效手段。  

### [应用上云 - Azure 官方 Java 容器化策略文档](https://mp.weixin.qq.com/s/U5KEB7mRMF7aXeAkmage-g)
- **发布日期**：2024-02-26 12:01  
- **所属合集**：#Kubernetes #应用上云 #Java  
- **摘要**：本文介绍了用于容器化 Java 应用程序以部署到 Kubernetes 上的建议策略。  

### [Kubernetes 内存和 CPU 排错 - CPU 节流和 OOM](https://mp.weixin.qq.com/s/WEC9G3inhzle_aeeXkNDtA)
- **发布日期**：2024-02-25 11:02  
- **所属合集**：#Kubernetes #cpu  
- **摘要**：使用 Kubernetes 时，内存不足 (OOM) 错误和 CPU 限制是资源处理的主要难题。我们可以做到事先的监控，事后的分析，并最终通过历史数据合理调整容器的 request 和 limit  

### [Kubernetes 容量规划：如何合理设置 limit 大小](https://mp.weixin.qq.com/s/FAIC5IWaWjvw0oPujI1zOg)
- **发布日期**：2024-02-24 17:30  
- **所属合集**：#Kubernetes  
- **摘要**：资源限制始终是一个难以调整的设置，因为我们必须在限制太紧或太松之间找到最佳平衡点。本文将探讨如何设置正确的 Kubernetes 资源限制：从检测没有任何限制的容器，到找到应在集群中设置的正确 Kubernetes 资源限制。  

### [Kubernetes 容量规划：如何合理设置 request 大小](https://mp.weixin.qq.com/s/1hd9B6ZP5_VOf4hm9Z3hJg)
- **发布日期**：2024-02-23 22:55  
- **所属合集**：#Kubernetes  
- **摘要**：容量规划是用好 Kubernetes 必须面对的主要挑战之一，因为了解 Kubernetes 的限制和请求并不是一件容易的事情。Kubernetes 容量规划始终就是集群的稳定性和可靠性与资源的有效使用之间的平衡。  

### [Kubernetes 小技巧 - Pod Pending 问题解析](https://mp.weixin.qq.com/s/_Ongqth_ZhhJLJaTSUU3iA)
- **发布日期**：2024-02-22 08:31  
- **所属合集**：#Kubernetes  
- **摘要**：有多种原因可能会导致 Pod 无法运行，以下是三种主要原因：

调度问题： pod 无法被调度到任何节点上（不满足要求）；

镜像问题：下载容器镜像时出现问题；

依赖性问题： pod 需要卷、密钥或配置映射才能运行。  

### [禁用/启用 SMT 引发的 CGroup 绑定 CPU 的问题](https://mp.weixin.qq.com/s/wQ-5d9TmOW8zZQxXgnkcsQ)
- **发布日期**：2024-02-10 11:01  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：背景知识同步多线程 (SMT) 允许在单个物理 CPU 内核上执行多个执行线程。在容器环境中，我们开关 SMT 引发了一个 cgroup 绑定 CPU 的问题 。  

### [K8s 的核心是 API 而非容器（二）：从开源项目看 k8s 的几种 API 扩展机制](https://mp.weixin.qq.com/s/3q6ronOby5oN_3NNjkNYrg)
- **发布日期**：2024-02-07 09:30  
- **所属合集**：#Kubernetes  
- **摘要**：接上一篇：Kubernetes 的核心是 API 而非容器从理论到 CRD 实践，通过具体开源项目来了解 k8s API 的几种扩展机制。  

### [Kubernetes 小技巧 - kubectl 指北](https://mp.weixin.qq.com/s/vX7Wz8nvD4_AdAueW58FLA)
- **发布日期**：2024-02-07 08:25  
- **所属合集**：#Kubernetes  
- **摘要**：用好 kubectl，让你更好管理 Kubernetes 集群  

### [Kubernetes 的核心是 API 而非容器（一）：从理论到 CRD 实践](https://mp.weixin.qq.com/s/nDv6ZCNqsfalKjNLX8aKuQ)
- **发布日期**：2024-02-06 08:55  
- **所属合集**：#Kubernetes  
- **摘要**：K8s 的核心价值是其通用、跨厂商和平台、可灵活扩展的声明式 API 框架， 而不是容器（虽然容器是它成功的基础）  

### [容器技术国产化 - 从 500 行 C 代码到生产级容器运行时](https://mp.weixin.qq.com/s/i7SqPGTDzy-3Qd8kRKUVUA)
- **发布日期**：2024-02-05 08:55  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：本文试图通过一段简单但又尽量全面的代码来串联起这些底层核心技术，看看一个容器是如何创建出来的。有了对这个过程的理解，容器就不再是一个无从下手的黑盒，排查一些线上疑难杂症时也会更有方向。  

### [The State of eBPF - 2024](https://mp.weixin.qq.com/s/TifVOJ_OyGbWNEwe3ImTsg)
- **发布日期**：2024-02-01 12:15  
- **所属合集**：#Kubernetes #BPF之巅 #Linux  
- **摘要**：（eBPF的拥护者认为）毫无疑问，eBPF 将成为新的云原生基础设施堆栈中的新的一层，影响所有应用的可观测性、性能、可靠性、网络和安全性。  

### [不敢把数据库运行在 K8s 上？容器化对数据库性能有影响吗？](https://mp.weixin.qq.com/s/e6D6K9_6ZuhrijH0cd0erg)
- **发布日期**：2024-01-31 09:01  
- **所属合集**：#Kubernetes  
- **摘要**：数据库容器化的趋势已经非常明显，数据库 + 分析类的 workload 已经占据了半壁江山，但是依然有很多人在做技术选型时面临一个难题：容器化是否对数据库性能有影响？如果有，影响的因素是什么？如何面对容器化带来的性能甚至是稳定性的问题？  

### [Kubernetes 小技巧 - 通过 API 获取任意节点 kubelet 的配置](https://mp.weixin.qq.com/s/mbnHv3C4IDJY3W14jcx0aw)
- **发布日期**：2024-01-30 12:37  
- **所属合集**：#Kubernetes  
- **摘要**：本文介绍了使用 kubectl proxy 快速访问 API Server 来获取 kubelet 的配置  

### [Kubernetes 小技巧 - 通过 Events 发现问题](https://mp.weixin.qq.com/s/UwHK8f9HeBq7mzA1ddSABg)
- **发布日期**：2024-01-26 12:28  
- **所属合集**：#Kubernetes  
- **摘要**：在本文中，我们将回顾 Kubernetes 中的事件，以及使用 kubectl get events 命令来获取相关事件并进行分析。  

### [容器技术回顾 - 节点资源预留让节点更加稳定](https://mp.weixin.qq.com/s/j9zEvz4xfxpzVRMPMypYCQ)
- **发布日期**：2024-01-22 08:45  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：如何让节点的可用资源更加确定呢？如何不要让节点的其它进程占用过多的资源，尤其是内存？
如何预留一些资源给到系统关键进程呢（例如sshd，以确保在关键时候我们可以远程登录）？  

### [Java Spring 应用如何更好地在 Kubernetes 上运行？](https://mp.weixin.qq.com/s/3KWOFsA89AV9G20yzT2nDA)
- **发布日期**：2024-01-20 09:15  
- **所属合集**：#应用上云 #Kubernetes #Java  
- **摘要**：nan  

### [容器技术回顾 - 如何修改容器的内核参数](https://mp.weixin.qq.com/s/04O2Y66_JyXhBR9bd4Uzuw)
- **发布日期**：2024-01-19 08:01  
- **所属合集**：#Linux #Kubernetes #Docker  
- **摘要**：在某些场景中，我们需要调整内核参数，来调整操作系统行为。那在容器化场景中，我们是否可以调整？哪些可以调整？如何调整？  

### [容器技术回顾 - 使用 UDS 实现 Pod 间通信](https://mp.weixin.qq.com/s/vqR-2hqJwXGBgmAsWL6uAQ)
- **发布日期**：2024-01-18 12:18  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：简介传统 Socket 包含 Stream Socket 和 Datagram Socket，这两种 Sock  

### [容器技术回顾 - Linux 内存文件系统](https://mp.weixin.qq.com/s/5oDwatGU8kCDY_62P3piSg)
- **发布日期**：2024-01-16 21:56  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：大家是否有注意过 Linux 主机上的 /dev/shm 设备？它是什么  

### [容器技术回顾 - 多 Pod 间共享内存通信](https://mp.weixin.qq.com/s/JOzzrgrxgyca1EpQfn9NaQ)
- **发布日期**：2024-01-14 20:00  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：本文介绍了一种在单节点上使用 tmpfs 模拟共享内存的方式，实现多个 Pod 之间可以实现共享内存通信。  

### [为啥 Pod 被驱逐了？浅谈 Kubernetes 驱逐机制](https://mp.weixin.qq.com/s/QsMRT5FgId-JTCVp9R4wbw)
- **发布日期**：2024-01-12 08:30  
- **所属合集**：#Kubernetes  
- **摘要**：在 Kubernetes 集群运行过程中，偶尔会发现我们的业务 Pod 状态从 running 变成了 Evicted，这个状态是什么含义？又发送了什么呢？  

### [容器技术回顾 - 从一个“D”状态容器进程回顾 cgroup freezer 子系统](https://mp.weixin.qq.com/s/SRnya2Y5kwJu3PYHug8jeQ)
- **发布日期**：2024-01-10 22:17  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：从一个 “D” 状态的容器进程，来回顾 cgroup freezer 子系统，同时提供相关脚本来帮助"解冻"进程！  

### [容器技术回顾 - 如何让我的容器/进程不要被 OOM Kill？](https://mp.weixin.qq.com/s/AoyWzaXQcgCPGTTBHjQzRQ)
- **发布日期**：2024-01-09 23:55  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：在 Kubernetes 环境中，我们会遇到 Java OOM -> Linux cgroup OOM -> Linux OOM 三种不同类型的 OOM，它们是什么？我们如何让我们的容器避免被 OOM Kill 呢？  

### [Kubernetes：如何实现应用零宕机？](https://mp.weixin.qq.com/s/wmxXuCSfDAFpA5o04XlXbA)
- **发布日期**：2024-01-08 12:14  
- **所属合集**：#Kubernetes #应用上云  
- **摘要**：只要注意这几点，我们就能利用 Kubernetes 来实现应用的零宕机。  

### [从 Kubernetes Pod 的故障诊断需求评价 K8sGPT 的 Pod analyzer 的实现](https://mp.weixin.qq.com/s/-1dMiOhYQZ-RuzVl73ZeAw)
- **发布日期**：2024-01-07 09:09  
- **所属合集**：#Kubernetes #大模型  
- **摘要**：故障诊断的流程：异常识别 -> 相关数据采集 -> 检查项评估 -> 根因分析  

### [Kubernetes Pod 异常诊断](https://mp.weixin.qq.com/s/-yf3wB9yLY-Mu_zit9Hahg)
- **发布日期**：2024-01-06 10:32  
- **所属合集**：#Kubernetes  
- **摘要**：我们学习了一文学会 Kubernetes Pod 的生命周期管理之后，那有什么方式来诊断 Pod 异常呢？文中作者提供了一个脚本，可以辅助做 K8s Pod 故障诊断。  

### [插上 AIGC 翅膀的 Kubernetes AIOps工具 - K8sGPT](https://mp.weixin.qq.com/s/Tes-6S63AsBl6rdbbB2ddQ)
- **发布日期**：2024-01-06 10:32  
- **所属合集**：#Kubernetes #大模型  
- **摘要**：本文我们以 K8sGPT 为例为读者介绍了AIGC + Kubernetes 领域中目前热度比较高的一个工具 - K8sGPT，并通过一个例子做了一个完整的演示。  

### [容器技术回顾（六） - 容器与主机共享内核是什么含义？](https://mp.weixin.qq.com/s/oA-tuw2vDB3TWO27mhGZiA)
- **发布日期**：2024-01-03 12:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：容器和主机共享内核，这得益于Linux有一个统一的内核体系。不同的 Linux 发行版使用了相同的内核体系，这使得基于不同 Linux 发行版构建的容器可以在一个 Linux 发行版上运行。那容器和主机共享内核有什么影响吗？​  

### [Kubernetes 上运行 Spring 生产应用的注意事项](https://mp.weixin.qq.com/s/yADIyAlpVxYUC3XaZogLKA)
- **发布日期**：2024-01-01 10:00  
- **所属合集**：#应用上云 #Kubernetes  
- **摘要**：​我们学习容器技术，最终目的还是为了使用​容器技术。而 Spring 应用，是目前被广泛使用的业务开发框架，作者将新开一个系列来介绍应用​在 Kubernetes 生产化运行的注意事项和最佳实践。  

### [容器技术回顾 - Kubernetes memory limit 产生的 OOM](https://mp.weixin.qq.com/s/s-OKhQ1qa7w1muUQAUuyTQ)
- **发布日期**：2023-12-29 12:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：一次奇怪的 cgroup oom 问题分析，由此我们回顾了一下相关知识点。  

### [容器技术回顾 - Kubernetes CPU request 和 limit 的作用与原理](https://mp.weixin.qq.com/s/OinmIMOr5W0BWOUrC-LVTA)
- **发布日期**：2023-12-27 20:01  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：本文我们会回顾一下 Kubernetes 中 CPU request 和 limit 的含义，以及背后实现的原理。  

### [Kubernetes Pod 异常诊断](https://mp.weixin.qq.com/s/rUNDLGl7ZKaynbMVi0vNHw)
- **发布日期**：2023-12-26 13:00  
- **所属合集**：#Kubernetes  
- **摘要**：我们学习了一文学会 Kubernetes Pod 的生命周期管理之后，那有什么方式来诊断 Pod 异常呢？文中作者提供了一个脚本，可以辅助做 K8s Pod 故障诊断。  

### [一文学会 Kubernetes Pod 的生命周期管理](https://mp.weixin.qq.com/s/MG5V8Pqa-Ua_Je9OXxdt1A)
- **发布日期**：2023-12-25 12:59  
- **所属合集**：#Kubernetes  
- **摘要**：Kubernetes 中最核心的抽象是 Pod，让我们通过本来来掌握 Pod 的生命周期。  

### [容器技术回顾（三） - 被误解的 Docker 存储驱动](https://mp.weixin.qq.com/s/R1p97qI3fE_7BF2wW0jc1w)
- **发布日期**：2023-12-23 10:00  
- **所属合集**：#Kubernetes #Docker  
- **摘要**：很多时候我们把 Docker 存储驱动（Storage Driver）和 Docker 存储卷（Volume）混为一谈，这里我们先回顾一下他们的概念，并明确一下两者的使用场景。  

### [三张图了解 Pod 的生命周期（初始化、运行与终止）](https://mp.weixin.qq.com/s/unVwBprr0UeuWNpXVdgdxg)
- **发布日期**：2023-12-22 09:00  
- **所属合集**：#Kubernetes  
- **摘要**：图解 Pod 生命周期的三个阶段：
1. 初始化阶段，Pod 的 init 容器运行。
2. 运行阶段，Pod 的常规容器在该阶段运行。
3. 终止阶段，Pod 的容器被终止。  

### [容器技术回顾 - 什么是优雅关闭以及如何实现](https://mp.weixin.qq.com/s/IxnkW5App4xJJPOeUD-uIQ)
- **发布日期**：2023-12-21 09:00  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：要实现容器的优雅关闭，我们需要做哪些事情呢？今天就让我们从 Linux 进程的优雅退出开始，来回顾一下容器的优雅关闭原理以及实现方式。  

### [【转载】Kubernetes 基于 cgroup 的资源限额：模型设计与代码实现](https://mp.weixin.qq.com/s/LmJnIrh438iOWq1uSxCJdA)
- **发布日期**：2023-12-20 09:00  
- **所属合集**：#Kubernetes  
- **摘要**：Docker 的 cgroup 结构相对比较简单，但是 Kubernetes 引入了 Pod 以及 Quality of Service 这些资源，因此它的 cgroup 结构相对来讲就变得很复杂，希望通过本文给大家深入讲解原理和实现！  

### [容器技术回顾  - 容器中的 0 号进程和 1 号进程](https://mp.weixin.qq.com/s/PIwVV7xfw3umSL-n2Hsw_g)
- **发布日期**：2023-12-19 08:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：对 Linux 系统来说 1 号进程为 init 进程，是由 0 号进程通过调用系统 init 函数创建的第一个用户进程 1 进程，主要做用户态进程的管理，垃圾回收等动作。那容器中是否存在 0 号进程和 1 号进程呢？它们有什么用？  

### [理性看待数据库/大数据 on K8s](https://mp.weixin.qq.com/s/tx3rHn1z8ihte1cWb1sZDg)
- **发布日期**：2023-12-06 13:49  
- **所属合集**：#Kubernetes #大数据  
- **摘要**：技术要深入了解，场景要深入理解，尺有所短，寸有所长  

### [驳斥《把数据库放入Docker是一个好主意吗？》](https://mp.weixin.qq.com/s/dgeVOGNxuG7rBMQdjKoFgw)
- **发布日期**：2023-12-04 19:32  
- **所属合集**：#Docker #Kubernetes  
- **摘要**：容器（化带来了标准化、隔离、控制和高利用率的好处，数据库场景到底是否合适，笔者认为只要能够转变运维习惯，在没有引入太多 overhead 和性能损失的情况下，容器化实际上提供了更多运维自动化的可能性，结合 K8s，就可以实现 DBaaS  

### [OpenAI 背后的 Kubernetes 发展历程（翻译）](https://mp.weixin.qq.com/s/VXHZkgjni-ve_eBJ0pK-FA)
- **发布日期**：2023-04-09 14:57  
- **所属合集**：#Kubernetes  
- **摘要**：大家应该知道 Kubernetes 为 ChatGPT 提供支持吧？ 当今天每个人都在谈论这个突破性的 AI技术的时候，让我们来回顾一下 Kubernetes powered 基础设施的发展历程吧！  

### [技术分享预告](https://mp.weixin.qq.com/s/qSJfz6TC7SfQVBGd4POxNw)
- **发布日期**：2022-10-15 20:08  
- **所属合集**：#云原生 #Kubernetes  
- **摘要**：《Edge Cloud Operations_A System Approach》，《Kubernetes in Action 2nd Edition》，《Patterns of Distributed Systems》，总有一款你喜欢！  

### [【转载】kubernetes 弹性伸缩指南](https://mp.weixin.qq.com/s/Qh1wwyVKkZPQfFcBAM2IAA)
- **发布日期**：2021-06-13 15:30  
- **所属合集**：#云原生 #Kubernetes  
- **摘要**：一文成为 Kubernetes 弹性伸缩的专家，知其然，知其所以然！  



## #LLM

### [LangChain + 模型上下文协议（MCP）：AI 智能体 Demo](https://mp.weixin.qq.com/s/D5d3F3xKeqstBataPBVbFA)
- **发布日期**：2025-04-07 20:18  
- **所属合集**：#智能 Agent #LLM  
- **摘要**：在基于大语言模型构建应用时，一个核心痛点是数据与工具的接入困难。模型虽然能力强大，但通常处于“沙盒”状态，无法直接访问外部环境。为此，RAG、微调、插件等方案陆续诞生。而MCP的目标正是统一接口协议，以便标准化集成上下文、工具、服务与数据源  

### [MCP、Function Calling 有什么区别？与 AI Agent 有什么关系？](https://mp.weixin.qq.com/s/LF3p1m1qapY1O7JFp-WP4w)
- **发布日期**：2025-04-05 12:20  
- **所属合集**：#智能 Agent #好书推荐 #LLM  
- **摘要**：Function Calling、MCP 以及 AI Agent 是三个密切相关但层级分明的概念。我们可以把这三者类比为“调用指令 → 调度系统 → 自主执行者”，分别解决不同层级的问题。  

### [好书推荐《大模型应用开发极简入门》](https://mp.weixin.qq.com/s/fapHgJtV--lzEDpn5MiSBA)
- **发布日期**：2025-04-04 08:55  
- **所属合集**：#LLM #好书推荐  
- **摘要**：《大模型应用开发极简入门：基于GPT-4和ChatGPT（第2版）》一书为开发者提供了系统化的答案。作为热销2万册的经典升级版，本书不仅是初学者的“最小可用知识”手册，更是进阶者构建复杂AI应用的实战指南。  

### [【转载】MCP（Model Context Protocol）全面研究报告：概念、实践与未来趋势](https://mp.weixin.qq.com/s/iRHqxurMx72xg5YRS4VzPA)
- **发布日期**：2025-04-02 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：模型上下文协议（Model Context Protocol，简称MCP）是Anthropic于2024年推出的一种开放标准，旨在规范AI模型与外部数据源、工具之间的交互方式。  

### [Chroma 技术报告 - Evaluating Chunking Strategies for Retrieval 总结](https://mp.weixin.qq.com/s/ttYBpV7I0yZZRwDsD7VPTw)
- **发布日期**：2025-04-01 19:15  
- **所属合集**：#LLM  
- **摘要**：在检索增强生成（RAG）系统中，如何将长文档高效切分为适合嵌入和检索的小块，是提高系统性能的关键步骤。本文总结了 Chroma 技术报告的主要内容，重点讨论了文档分块策略对检索性能的影响，并提出了一种基于 token 级别的新型评估方法。  

### [LLM 嵌入技术详解：图文指南](https://mp.weixin.qq.com/s/X3Gbiam3z-Hdn9JOTEe0uw)
- **发布日期**：2025-03-30 10:20  
- **所属合集**：#LLM  
- **摘要**：本文探讨嵌入技术，解析其本质特征，回顾从传统统计方法到现代技术的演进，考察实际应用，实现方式及核心技术，并展示大语言模型DeepSeek-R1-Distill-Qwen-1.5B的嵌入向量在图示化中的形态特征。  

### [基于大型语言模型的意图检测](https://mp.weixin.qq.com/s/rG35b3lA-Ubc4rcjMwDVcg)
- **发布日期**：2025-03-25 23:40  
- **所属合集**：#LLM #RAG实战  
- **摘要**：意图识别是NLP技术，专注于解析用户查询背后的核心诉求，在搜索与推荐系统领域具有重要地位，包括自然语言理解，即解析用户话语中隐含的语义；上下文分析，结合用户查询的上下文来精准识别意图；以及分类，将预定义标签或类别分配给用户输入及其预测意图  

### [Qwen2 大模型指令微调入门实战](https://mp.weixin.qq.com/s/Atf61jocM3FBoGjZ_DZ1UA)
- **发布日期**：2025-03-24 23:25  
- **所属合集**：#LLM  
- **摘要**：本文是笔者在 Mac 上复现林泽毅的微调流程，方便其他读者在本地实验！  

### [学习总结 - RAG 快速开发实战 - 《02｜从0到1快速搭建RAG应用》](https://mp.weixin.qq.com/s/89-bwZ4aPor4ySj5U3n5zw)
- **发布日期**：2025-03-23 11:45  
- **所属合集**：#LLM #RAG实战  
- **摘要**：实战内容包括技术框架的介绍与选型、开发环境搭建与技术库安装、RAG 流程的代码实现。  

### [提示词工程 vs RAG vs 微调](https://mp.weixin.qq.com/s/kdeksSoFNoXLzd1vp5Ho6A)
- **发布日期**：2025-03-22 16:48  
- **所属合集**：#LLM  
- **摘要**：提示工程 vs RAG vs 微调  

### [混合专家系统（MoE）图解指南](https://mp.weixin.qq.com/s/9B_F6xbrWEMTXrtccjTsiw)
- **发布日期**：2025-03-19 19:15  
- **所属合集**：#LLM  
- **摘要**：混合专家系统是一种提升大型语言模型计算效率的架构，通过多个专精不同任务的专家单元协同工作。其核心包括专家集群，即由多个前馈神经网络组成的可动态调度专家单元，以及路由分配器，用于智能选择合适专家处理输入数据。  

### [大模型量化技术（Quantization）可视化指南](https://mp.weixin.qq.com/s/8ABfKytTXp78ZTOWyoT0yw)
- **发布日期**：2025-03-18 19:15  
- **所属合集**：#好书推荐 #LLM  
- **摘要**：大型语言模型的规模通常过于庞大，难以在消费级硬件上运行。这类模型的参数量可达数十亿级别，通常需要配备大容量显存的GPU来加速推理过程。为此，越来越多的研究聚焦于通过优化训练方式、引入适配器等技术缩小模型规模。其中一项关键技术便是量化。  

### [一文了解思维链（Chain-of-Thought, CoT）](https://mp.weixin.qq.com/s/RJymdxTIMVjalZyIRRSftg)
- **发布日期**：2025-03-17 12:15  
- **所属合集**：#LLM  
- **摘要**：对于普通用户而言，如果某个问题必须依赖 COT 才能准确解答，那就请忘掉 COT，直接让大模型自动推理即可！  

### [大模型时代，智能体崛起：从技术解构到工程落地的全栈指南 ——《大模型技术30讲》](https://mp.weixin.qq.com/s/bNH2HaN1GJPyHTftg62Erg)
- **发布日期**：2025-03-15 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：《大模型技术30讲》这本书如同一座桥梁，连接起了学术理论与工程实践的两岸，为工程师们提供了一套全面且深入的技术知识体系和实践指导。它不仅详细阐述了Transformer架构背后的数学原理，还构建了一条从单卡调试到大规模集群部署的完整工程路径  

### [AI Agents for Beginners 课程之 AI Agent及使用场景简介](https://mp.weixin.qq.com/s/XpBYMTKj4j7CT-N_xkKvBg)
- **发布日期**：2025-03-12 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：AI Agents for Beginners是一门由微软提供的课程，旨在帮助初学者全面了解 `AI Agent` 的构建与应用。课程涵盖的基础概念、开发框架、设计模式、工具使用、可信赖构建、规划、多智能体系统、元认知以及生产环境部署等内容  

### [什么是大模型的幻觉？用户如何应对呢？](https://mp.weixin.qq.com/s/7OCNx37k9xCouF08fnoJMQ)
- **发布日期**：2025-03-09 08:30  
- **所属合集**：#LLM  
- **摘要**：大模型的幻觉问题是一个复杂且多面的挑战，需要从数据治理、模型优化、解码控制以及用户侧防御等多个维度综合应对。当然了作为普通用户，我们更加关注用户侧防御！  

### [上海人工智能实验室开源工具 MinerU 助力复杂 PDF 高效解析提取](https://mp.weixin.qq.com/s/toz-sSNV7_t3mgFTxCEBgw)
- **发布日期**：2025-03-04 08:15  
- **所属合集**：#deepseek #LLM  
- **摘要**：MinerU 是一款开源智能文档解析工具，专注于将 PDF、网页、电子书等多模态内容转换为结构化数据（如 Markdown、JSON），支持 AI 训练、知识管理、RAG（检索增强生成）等场景。  

### [深入探索：AI 驱动的 PDF 布局检测引擎源代码解析](https://mp.weixin.qq.com/s/NPKjONTcLCUfMUGr4mc_wQ)
- **发布日期**：2025-03-03 08:15  
- **所属合集**：#LLM #deepseek  
- **摘要**：Marker 能够将 `PDF`、`EPUB` 和 `MOBI` 文件转换成 `Markdown` 格式。它的转换速度比 `nougat` 快 10 倍，准确度更高，且几乎没有误解风险。  

### [DeepSeek Open Infra 开源五天乐及好书《动手学机器学习》推荐](https://mp.weixin.qq.com/s/pgwpndnu0vUru7r4qTgTJw)
- **发布日期**：2025-02-26 10:10  
- **所属合集**：#LLM #机器学习  
- **摘要**：DeepSeek Open Infra 开源五天乐及好书《动手学机器学习》推荐  

### [Hello, DeepSeek Open Infra!](https://mp.weixin.qq.com/s/UzlIZR3i7nKbzE3lvE3nNQ)
- **发布日期**：2025-02-24 11:10  
- **所属合集**：#LLM #deepseek  
- **摘要**：没有任何虚假信息，只有【真诚的代码】，推动着我们微小却雄心勃勃的梦想不断前行。  

### [万字长文深入浅出文本嵌入（Text-Embedding）技术](https://mp.weixin.qq.com/s/npwT3_kaS5RDtYslz1caFQ)
- **发布日期**：2025-02-19 08:15  
- **所属合集**：#LLM  
- **摘要**：Text-embedding 技术是一种将文本数据转换为向量的技术，通过深度学习模型将文本的语义信息嵌入到高维向量空间中。这些向量不仅能表达文本内容，还能捕捉文本之间的相似性和关系，从而让计算机高效地进行文本检索、分类、聚类等任务。  

### [Google Cloud 的免费生成式 AI 课程](https://mp.weixin.qq.com/s/91iwIWhzhne1DwOCjCEMCw)
- **发布日期**：2025-02-18 08:15  
- **所属合集**：#LLM  
- **摘要**：本学习路径全面介绍了生成式 AI。本专业探索了大型语言模型 (LLM) 的基础、其多样化应用以及负责任的 AI 开发和部署所必需的道德考量。  

### [解密大语言模型中的 Tokens](https://mp.weixin.qq.com/s/ln-AoMyKZG4TzNbkpJBaIQ)
- **发布日期**：2025-02-15 21:45  
- **所属合集**：#LLM  
- **摘要**：本文将详细解析大语言模型中 token 的概念、如何估算其数量，并提供具体的 Python 示例，帮助开发者更好地理解和调用大语言模型。  

### [全系列 DeepSeek R1 模型单机部署配置要求](https://mp.weixin.qq.com/s/p_NwBZyf4uT-iU_RFIOXzw)
- **发布日期**：2025-02-14 18:35  
- **所属合集**：#LLM  
- **摘要**：全系列 DeepSeek R1 模型「单机部署」配置要求!  

### [基于大语言模型的文本分类实践](https://mp.weixin.qq.com/s/TPr5CwoAO4sIyTZf7IfZJg)
- **发布日期**：2025-02-13 19:15  
- **所属合集**：#LLM  
- **摘要**：随着 **大语言模型**（如 GPT-4、BERT）的出现，文本分类任务也进入了一个新的阶段。大语言模型能够理解文本的上下文，并通过 `zero-shot` 或 `few-shot` 学习进行分类。  

### [4090单卡跑满血版DeepSeek-R1，清华团队开源项目再破大模型推理门槛](https://mp.weixin.qq.com/s/C0e6ooiR1NgqeMj7z8yOJQ)
- **发布日期**：2025-02-12 19:05  
- **所属合集**：#LLM  
- **摘要**：清华大学KVCache.AI团队与趋境科技联手放了个大招——开源项目KTransformers，直接让单张RTX 4090显卡（24GB显存）搭配382GB内存就能跑满血版DeepSeek-R1（671B参数）！  

### [关于DeepSeek：五大误解与真相解读](https://mp.weixin.qq.com/s/xl9gN-Oc-3QU0IeVSjIVlw)
- **发布日期**：2025-02-10 19:05  
- **所属合集**：#LLM  
- **摘要**：春节至今，DeepSeek 的热度持续攀升，伴随而来的，还有很多误解和争议，有人说它是"吊打OpenAI的国货之光"，也有人说它"不过是抄国外大模型作业的小聪明"。  

### [DeepSeek 蒸馏模型简易性能 benchmark](https://mp.weixin.qq.com/s/EIIXUkRUG7cvcN7bXiW6Sg)
- **发布日期**：2025-02-09 09:15  
- **所属合集**：#LLM  
- **摘要**：为了评估模型运行性能，博主根据 ollama 官方的 API 文档，编写了一个 benchmark 脚本，用于测试 deepseek 模型运行性能，供大家参考！  

### [大模型辅助 “Diagram as Code” 设计范式初探](https://mp.weixin.qq.com/s/7TNKEGEC7hcnHJ3cHJdDWg)
- **发布日期**：2025-02-05 19:05  
- **所属合集**：#LLM  
- **摘要**：相比直接从自然语言生成代码，引入 UML 作为中间产物能带来更大优势——表达清晰、结构直观，更便于理解和验证设计。“Diagram as Code” 设计范式：用自然语言描述需求，大模型同步生成设计图、代码、测试用例及部署脚本。  

### [过年八天乐 - 读者来信：请问7b阅读分析不同中医古籍的能力怎么样？可以进行专项训练大幅度提高这方面能力么？](https://mp.weixin.qq.com/s/scomZshsZFK8Ul8rtmBWow)
- **发布日期**：2025-01-31 10:40  
- **所属合集**：#deepseek #LLM  
- **摘要**：请问7b阅读分析不同中医古籍的能力怎么样？可以进行专项训练大幅度提高这方面能力么？  

### [过年八天乐 - DeepSeek 1.5b、7b 和官网模型快速对比](https://mp.weixin.qq.com/s/MbVoImyvvKuTxhceqeviCA)
- **发布日期**：2025-01-30 09:15  
- **所属合集**：#deepseek #LLM  
- **摘要**：在昨天的文章（过年八天乐 - 在 Mac 上运行 DeepSeek-R1 模型）中，我们通过 ollma 在本地运行了 deepseek-r1:1.5b 模型，今天让我们对比一下 1.5b、7b 和官网模型。  

### [过年八天乐 - 在 Mac 上运行 DeepSeek-R1 模型](https://mp.weixin.qq.com/s/nnIsTZSaC6nNeVRZ7g7epw)
- **发布日期**：2025-01-29 13:35  
- **所属合集**：#LLM #deepseek  
- **摘要**：本教程将指导你在 Mac 上使用 Ollama 运行 DeepSeek-R1，并介绍如何通过 Open-WebUI 提供 Web 端访问。  

### [使用 Spring AI 高效构建 LLM 代理（第一部分）](https://mp.weixin.qq.com/s/QIe5ZIOZMRiH8-9lyXiWJA)
- **发布日期**：2025-01-23 17:02  
- **所属合集**：#LLM  
- **摘要**：在最近的一篇研究论文中：构建高效代理，Anthropic 分享了关于构建高效大型语言模型代理的宝贵见解。这项研究特别有趣的地方在于它强调简单性和可组合性，而非复杂框架。让我们探讨如何利用 Spring AI 将这些原则转化为实际实现。  

### [Microsoft AutoGen：具有高级自动化功能的多代理 AI 工作流](https://mp.weixin.qq.com/s/TYIxpB9vYuCExySpDTcujw)
- **发布日期**：2025-01-19 15:16  
- **所属合集**：#LLM  
- **摘要**：AutoGen 框架为构建智能多代理系统开辟了新途径。它能够自动化复杂的工作流程、强大的社区、代码执行，并促进无缝代理协作，这些都使其有别于其他 AI 框架。  

### [大模型安全之“字节一实习生。。。对算力分配不满、发起恶意攻击。。。被开除”大瓜](https://mp.weixin.qq.com/s/0uLClu18EdQ_cDupozhTJQ)
- **发布日期**：2024-10-20 09:50  
- **所属合集**：#LLM  
- **摘要**：从吃瓜...延伸到大模型安全！  

### [面向大语言模型的检索增强生成技术：综述 [译]](https://mp.weixin.qq.com/s/-3qoRfoDT5ZEWzqvThummw)
- **发布日期**：2024-07-24 20:31  
- **所属合集**：#LLM  
- **摘要**：本文概述了 RAG 在大语言模型时代的发展模式，总结了三种模式：初级 RAG、高级 RAG 和模块化 RAG。接着，本文梳理了 RAG 的三个主要组成部分：检索器、生成器和增强方法，以及每个部分的关键技术。  

### [Awesome LLM RAG 学习材料](https://mp.weixin.qq.com/s/w6PDRf_AHkEnmTbPtRaIxw)
- **发布日期**：2024-07-24 20:31  
- **所属合集**：#LLM  
- **摘要**：Awesome LLM RAG Application 是基于 LLM 和 RAG 模式的应用程序资源精选列表。  

### [深度学习（大模型）中的精度](https://mp.weixin.qq.com/s/b08gFicrKNCfrwSlpsecmQ)
- **发布日期**：2024-06-30 09:00  
- **所属合集**：#AI Infra #LLM  
- **摘要**：当谈到大型模型的训练和推理时，我们经常涉及到精度的概念，而这些精度种类繁多。同等精度级别下，还有不同的格式。笔者收集了几篇文章，供大家参考理解相关概念。  

### [AI Infra 论文：使用 AI 做 vAttention 论文翻译尝鲜](https://mp.weixin.qq.com/s/xBukJV9_l_5PnSIofze4cw)
- **发布日期**：2024-06-01 10:01  
- **所属合集**：#LLM  
- **摘要**：nan  

### [LLM 小技巧 - 在 Mac 上运行大语言模型](https://mp.weixin.qq.com/s/ii2I-yRQfeyiqvbkDoIG-g)
- **发布日期**：2024-05-31 13:02  
- **所属合集**：#大模型 #LLM  
- **摘要**：今天我们来介绍一款工具 - GPT4All，可以让我们在本地运行大语言模型，从而可以​体验大语言模型带来的快乐！​  

### [用 Transformers 处理自然语言：创建基于Hugging Face的文本内容处理程序](https://mp.weixin.qq.com/s/PzkEyLnfRiJrOT8lJd-0IA)
- **发布日期**：2024-04-15 08:30  
- **所属合集**：#LLM #大模型  
- **摘要**：今天在寻找 Transformer 学习材料的时候，找到了《Natural Language Processing with Transformers》的开源翻译，如果没有买书的同学可以看一下。  

### [推荐 - 《大模型技术栈》让我们快速建立起大模型知识体系](https://mp.weixin.qq.com/s/cAN8-BqOUiE3TkBEuEENXA)
- **发布日期**：2024-04-14 09:30  
- **所属合集**：#大模型 #LLM  
- **摘要**：LLM 领域算法、技术和工具浩如烟海，而且每天都会涌现新的内容。笔者在互联网搜索的过程中，发现黄志国整理的《大模型技术栈》，可以让我们快速建立起知识体系。  

### [强烈推荐几篇 vLLM 原理及源码解析文章](https://mp.weixin.qq.com/s/JqubXK1VbMaShrJY20aKMg)
- **发布日期**：2024-04-12 23:00  
- **所属合集**：#LLM  
- **摘要**：笔者最近在学习 LLM Model Serving，打算入门一下 vLLM​，今天正好读到几篇原理和源码讲解的文章，​写得非常好，推荐给大家！  



## #Linux

### [Deepseek 3FS（ Fire-Flyer File System）设计笔记](https://mp.weixin.qq.com/s/B_5xdV2gl9APcJyBuBuUgQ)
- **发布日期**：2025-03-01 10:40  
- **所属合集**：#Linux #deepseek #分布式系统  
- **摘要**：Fire-Flyer File System (3FS) 是一种高性能分布式文件系统，旨在解决 AI 训练和推理工作负载的挑战。它利用现代 SSD 和 RDMA 网络来提供共享存储层，从而简化分布式应用程序的开发。  

### [Linux 进程间共享内存通信方案 v2：基于 Futex 锁的实现](https://mp.weixin.qq.com/s/CIrXEOBA2NSF95JDdPVcmw)
- **发布日期**：2025-02-28 23:29  
- **所属合集**：#Linux  
- **摘要**：Linux 进程间共享内存通信方案 v2：基于 Futex 锁的实现  

### [Linux 进程间共享内存通信方案（代码版）](https://mp.weixin.qq.com/s/9-3oSrNkxYcjphwimruMbg)
- **发布日期**：2025-02-27 08:15  
- **所属合集**：#Linux  
- **摘要**：共享内存是一种高效的进程间通信机制，允许多个进程直接访问同一块内存区域，从而实现数据的快速交换。  

### [好书推荐 - 《高级 Bash 脚本编程指南》](https://mp.weixin.qq.com/s/fVYZ1N_N5RL7wfKDxGYp4g)
- **发布日期**：2025-02-08 12:35  
- **所属合集**：#Linux  
- **摘要**：《高级 Bash 脚本编程指南》（Advanced Bash-Scripting Guide）是由 Mendel Cooper 编写的一本深入探讨 Shell 脚本艺术的教程。  

### [Linux 6.13：30 行代码如何节省 30% 数据中心能耗？](https://mp.weixin.qq.com/s/IoFIWkFIiAadIXv3hSNPJg)
- **发布日期**：2025-02-02 08:31  
- **所属合集**：#Linux  
- **摘要**：Linux 6.13 中一个 30 行代码的「提交」可以节约数据中心 30% 能源消耗？让我们深入剖析一下！  

### [好书推荐 - 《信息存储与管理（第二版）：数字信息的存储、管理和保护》](https://mp.weixin.qq.com/s/FqzDvywg6JLgpDD4rq5ItQ)
- **发布日期**：2025-01-21 19:35  
- **所属合集**：#Linux #好书推荐  
- **摘要**：该书脱胎于 EMC 与麻省理工学院合作开发的《信息基础架构技术》课程，既保留了原课程的系统性，又新增了符合中国《网络安全法》的合规实践指南。作为中国存储领域首部体系化教材，它至今仍是笔者案头必备的技术参考书。  

### [深入理解 Linux Bond：原理与实践](https://mp.weixin.qq.com/s/J0h_i3BwrIX0wtjAub3t6g)
- **发布日期**：2025-01-20 12:35  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：nan  

### [当我们谈论 Linux 主机/集群管理时，我们需要关注哪些工作呢？](https://mp.weixin.qq.com/s/yslC-waAyuXjFbrpUjF9DA)
- **发布日期**：2025-01-18 10:08  
- **所属合集**：#Linux #Kubernetes  
- **摘要**：在运行 Kubernetes 集群时，我们实际上依赖于底层的主机集群。本文讨论的集群特指主机集群，即从操作系统（OS）的视角来管理的资源集合。本文仅涵盖与 Linux 操作系统相关的操作。  

### [FUSE 文件系统 - 使用 securefs 实现文件系统透明加解密](https://mp.weixin.qq.com/s/A1iF_qEoQ5RYT7n75PZ9xg)
- **发布日期**：2025-01-17 08:35  
- **所属合集**：#Linux #好书推荐  
- **摘要**：为了满足应用程序对敏感数据安全存储的需求，本文使用 securefs 实现了透明的数据加密与解密功能，确保应用程序在无需额外改动的情况下，能够自动处理数据的加密与解密。同时整个方案以容器化的方式运行，进一步增强了部署的便捷性与安全性。  

### [【翻译】Linux 中 x86 上下文切换的演变](https://mp.weixin.qq.com/s/zkIV1ijOMvl8mobl8QPang)
- **发布日期**：2025-01-03 13:20  
- **所属合集**：#Linux  
- **摘要**：分析从最早的（0.01）到 LTS 版本（4.14.67）的 Linux 内核中的上下文切换代码（内容比较艰难，需要懂内核代码和汇编才能读懂！）  

### [AWK 入门教程：强大的文本处理工具](https://mp.weixin.qq.com/s/Gd8U1bL5S5VHTMAs_jsWRQ)
- **发布日期**：2025-01-02 19:15  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：AWK 是一种强大的文本处理工具，广泛用于 Linux/Unix 系统中对文本文件或数据流进行操作。它能够基于条件筛选、统计字段、重新排列数据等。  

### [AWK 入门教程：强大的文本处理工具](https://mp.weixin.qq.com/s/Gd8U1bL5S5VHTMAs_jsWRQ)
- **发布日期**：2025-01-02 19:15  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：AWK 是一种强大的文本处理工具，广泛用于 Linux/Unix 系统中对文本文件或数据流进行操作。它能够基于条件筛选、统计字段、重新排列数据等。  

### [鲲鹏性能优化十板斧](https://mp.weixin.qq.com/s/gf851jn1I6lA4JOp0aS6tw)
- **发布日期**：2025-01-01 15:35  
- **所属合集**：#Linux #系统可观测性  
- **摘要**：本文系统介绍了鲲鹏芯片性能优化的常用方法与工具，从 CPU 与内存子系统、网络子系统、磁盘 IO 子系统及应用程序优化四方面展开，内容详实，可作为系统性能优化的实用参考手册！  

### [基于 FUSE 的简单文件系统实现](https://mp.weixin.qq.com/s/NkfteGlcXi05_PbSqIdIeA)
- **发布日期**：2024-12-30 22:03  
- **所属合集**：#Linux  
- **摘要**：一个使用 C 语言和 FUSE（libfuse） 编写的示例文件系统实现，可用于教学目的。  

### [文件性能测试工具 IOzone 使用简介](https://mp.weixin.qq.com/s/gEB-sbPOuELTQITeFnaqzg)
- **发布日期**：2024-12-29 14:01  
- **所属合集**：#Linux #系统可观测性  
- **摘要**：IOzone 是一款用于文件系统性能基准测试的开源工具。它可以帮助用户评估文件系统在不同操作模式下的性能，特别是用于磁盘 I/O 操作。IOzone 支持多种操作系统，并提供了多种测试模式来测量不同类型的文件操作性能.  

### [Linux Slab 内存管理机制简介](https://mp.weixin.qq.com/s/Nk32Asrd7nJTk6zH19vfpg)
- **发布日期**：2024-12-28 11:45  
- **所属合集**：#Linux #系统可观测性  
- **摘要**：Slab 层通过向内核申请完整的页（Page），然后对这些页进行精细化管理，从而高效分配和回收小型内存块。通过这种方式，Slab 不仅优化了小对象的内存利用率，还显著降低了分配和销毁的开销。  

### [Linux VFS （Virtual File System）简介](https://mp.weixin.qq.com/s/Rnn30qDvBoKJ7Ylxy_zkMg)
- **发布日期**：2024-12-23 12:28  
- **所属合集**：#Linux  
- **摘要**：Linux VFS是操作系统内核中的抽象层，提供统一的文件操作接口，屏蔽底层文件系统差异。它允许用户通过标准系统调用访问多种文件系统。VFS 通过对象模型（超级块、索引节点、目录项和文件对象）管理文件和目录，支持设备文件、网络文件系统等。  

### [To FUSE or Not to FUSE: Performance of User-Space File Systems](https://mp.weixin.qq.com/s/6GDPfij75z4PXGVlAqTJhQ)
- **发布日期**：2024-12-19 19:15  
- **所属合集**：#Linux  
- **摘要**：作者分析了最广为人知的用户空间文件系统框架 FUSE 的设计和实现，并表征了其在各种工作负载下的性能。作者使用 FUSE 来提取有用的统计数据和跟踪，这有助于分析其性能瓶颈并呈现我们的分析结果。  

### [存储知识拾遗：LVM && Device Mapper](https://mp.weixin.qq.com/s/D64L6h9av3SbMP3XQQ2kFQ)
- **发布日期**：2024-12-19 19:15  
- **所属合集**：#Linux #存储  
- **摘要**：Device Mapper 是由 Linux 内核提供的一个框架，用于将物理块设备映射到更高级别的虚拟块设备。它是逻辑卷管理器（LVM）、软件 RAID 和 dm-crypt 磁盘加密的基础，并提供了其他功能，如文件系统快照。  

### [网络收发路径上的一些冷知识 - 参数单位](https://mp.weixin.qq.com/s/6--GJA3sGWekk-hUleBmAg)
- **发布日期**：2024-12-14 11:52  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：在网络调优和排查过程中，了解各种参数及其单位的意义至关重要，因此本文将对常见的参数及其单位进行说明。  

### [Linux 网络优化：RPS 和 RFS 技术概述](https://mp.weixin.qq.com/s/QhsFzATYJDGblSbnNxxVDQ)
- **发布日期**：2024-12-12 12:35  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：RPS和RFS是Linux内核中的两种技术，它们优化网络数据包处理性能，特别是在多核处理器和高吞吐量场景中。这些技术通过将数据包分配到不同的CPU核心上，改善负载均衡并减少缓存未命中。  

### [快速了解 TCP 连接的 11 种状态及其转换](https://mp.weixin.qq.com/s/Bjq39k78p9uliudcIW0T9Q)
- **发布日期**：2024-12-10 19:10  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：本文意在用简短的文字总结一下 TCP 的 11 种状态及其转换过程。  

### [Linux 网络参考书籍推荐](https://mp.weixin.qq.com/s/-GaqOPQr-nRxZ5gdo1SiFw)
- **发布日期**：2024-12-06 12:30  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：推荐笔者看过的 Linux 网络相关的书单，分为四大类：网络七层协议、Linux 内核中的网络栈与收发路径、Linux 网络编程及高性能编程、Linux 网络性能分析与调优，适合不同角色的人员参考。  

### [Java 网络异常及其解决方案](https://mp.weixin.qq.com/s/kzZvj9sMReoVjRwlmuSVvQ)
- **发布日期**：2024-12-04 15:01  
- **所属合集**：#Linux  
- **摘要**：在 Java 开发中，网络异常是常见的挑战之一，尤其是在处理客户端与服务器之间的通信时，本文介绍了常见的异常类型​及其发生场景以及解决方法。  

### [Linux FUSE 文件系统的相关一些管理操作](https://mp.weixin.qq.com/s/ZVTdSeF-LtsiSvVeLYsubw)
- **发布日期**：2024-12-02 20:00  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：书接上文(Linux 用户态文件系统 FUSE 简介)，大家学习完 FUSE 文件系统后，实操中可能会遇到一些问题，笔者（博主）整理了与 FUSE 文件系统相关的一些管理操作，供大家参考。  

### [Linux FUSE 文件系统的相关一些管理操作](https://mp.weixin.qq.com/s/ZVTdSeF-LtsiSvVeLYsubw)
- **发布日期**：2024-12-02 20:00  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：书接上文(Linux 用户态文件系统 FUSE 简介)，大家学习完 FUSE 文件系统后，实操中可能会遇到一些问题，笔者（博主）整理了与 FUSE 文件系统相关的一些管理操作，供大家参考。  

### [Linux 基础知识 - 软链接 vs. 硬链接](https://mp.weixin.qq.com/s/tdVgBAORr3sSzCbxO85EwA)
- **发布日期**：2024-12-01 22:00  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：一文了解 Linux 的硬链接和软链接！  

### [Linux 基础知识 - 软链接 vs. 硬链接](https://mp.weixin.qq.com/s/tdVgBAORr3sSzCbxO85EwA)
- **发布日期**：2024-12-01 22:00  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：一文了解 Linux 的硬链接和软链接！  

### [Linux 用户态文件系统 FUSE 简介](https://mp.weixin.qq.com/s/Db0xBSMzqT_wPIKaLkGtNA)
- **发布日期**：2024-11-30 19:30  
- **所属合集**：#Linux  
- **摘要**：FUSE 是一个开源框架，允许在用户空间构建文件系统，而不是走传统的内核空间路径。许多人认为在用户空间构建文件系统不适合用于生产环境，并且认为其开销过大，无法实际使用。但这一机制为程序员提供了一个更“友好”的开发环境，拥有更丰富的工具集  

### [Linux 小技巧 - 使用 smem 了解内存使用情况](https://mp.weixin.qq.com/s/W0dEXBR0oRuWKD0J9EbN9A)
- **发布日期**：2024-11-29 14:22  
- **所属合集**：#Linux 小技巧 #Linux #系统可观测性  
- **摘要**：smem 是一个命令行工具，它报告每个进程的内存使用情况，与主要显示 RSS 的 top 或 htop 不同，smem 还可以显示 USS，这是评估终止特定进程将释放多少内存的更好指标。  

### [Linux 小技巧 - 使用 smem 了解内存使用情况](https://mp.weixin.qq.com/s/W0dEXBR0oRuWKD0J9EbN9A)
- **发布日期**：2024-11-29 14:22  
- **所属合集**：#Linux 小技巧 #Linux #系统可观测性  
- **摘要**：smem 是一个命令行工具，它报告每个进程的内存使用情况，与主要显示 RSS 的 top 或 htop 不同，smem 还可以显示 USS，这是评估终止特定进程将释放多少内存的更好指标。  

### [解读 Linux Cgroup 之 cpuset 子系统及其在 Docker 中的使用](https://mp.weixin.qq.com/s/2N_g7nfj1VVsdsE5LIIq5g)
- **发布日期**：2024-11-27 12:55  
- **所属合集**：#Linux #Docker  
- **摘要**：在 Linux 系统中，cgroup（Control Groups）是一种用于限制、记录和隔离进程资源使用的机制。其中，cpuset 子系统主要用于管理 CPU 和内存节点的分配，可以有效实现资源隔离和性能优化。  

### [「鲲鹏软件性能调优基础知识」之「基于硬件特性的性能调优方向」](https://mp.weixin.qq.com/s/d0TgvpxEQzknt1BkGD5RYA)
- **发布日期**：2024-11-25 22:40  
- **所属合集**：#Linux  
- **摘要**：以「鲲鹏软件性能调优基础知识」之「基于硬件特性的性能调优方向」，构建整个调优知识及方法体系！  

### [推荐：《百万并发下 Nginx 的优化之道》](https://mp.weixin.qq.com/s/9RFI5ChDTB7tbW8lYGZSYg)
- **发布日期**：2024-11-24 20:55  
- **所属合集**：#Linux  
- **摘要**：今天水一篇，把《百万并发下Nginx的优化之道》博文，以及作者陶辉在极客时间开的课给大家介绍一下，有兴趣的小伙伴可以自取！  

### [TCP Keepalive 指南](https://mp.weixin.qq.com/s/bKpvKeXZwXn1kytmxRfilA)
- **发布日期**：2024-11-22 12:45  
- **所属合集**：#Linux  
- **摘要**：TCP Keepalive 指南  

### [Linux 基础知识 - CPU 上下文切换之问题排查](https://mp.weixin.qq.com/s/hv823hRDirjtRciEQBe3eQ)
- **发布日期**：2024-11-20 19:15  
- **所属合集**：#Linux  
- **摘要**：今天我们讨论一下关于 Linux CPU 上下文切换相关的一些问题排查思路与方法！  

### [全新视角解析 Linux 非缓存缓冲 I/O “RWF_UNCACHED”：性能提升 65%~75%](https://mp.weixin.qq.com/s/SvHSM_qwcppRMJEmDda1GQ)
- **发布日期**：2024-11-18 19:25  
- **所属合集**：#Linux  
- **摘要**：内存异步回收以及内存直接回收有时候就是性能杀手，解决方案要么用 direct IO，要么自己管理缓存，总之都不好做。而 Uncached Buffered I/O 正是针对这种场景提供了一种新的 IO 模式，从作者的测试来看，性能提升不少！  

### [网络协议分析神器 - tcpdump 简介及抓取 HTTP Header 实战](https://mp.weixin.qq.com/s/vmat80PacZbGfKfCZ8g9Vw)
- **发布日期**：2024-11-17 10:05  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：tcpdump 网络嗅探器，将强大和简单结合到一个单一的命令行界面中，能够将网络中的报文抓取，输出到屏幕或者记录到文件中。本文列举了一些常用的命令，并例举了一个在容器网络中抓取 HTTP Header 的实战，供读者参考！  

### [I/O 多路复用与网络服务器并发策略](https://mp.weixin.qq.com/s/3Zvo_48wVNI747M9dIrJaw)
- **发布日期**：2024-11-14 19:05  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：目前主流的网络服务器，网络 I/O 相关的底层最核心的技术都是 I/O 多路复用。本文尝试解释各种 I/O 模型，同时也总结 I/O 多路复用底层的系统调用 select、poll、kqueue 和 epoll 的演进和区别，并辅以代码！  

### [超越 POSIX：一个时代的终结？](https://mp.weixin.qq.com/s/xZ1-rk_O56WWbojVPsLECw)
- **发布日期**：2024-11-12 12:59  
- **所属合集**：#Linux  
- **摘要**：在本文中，我们通过系统回顾可移植操作系统接口 (POSIX) 抽象的历史演变，提供对它的全面了解。我们讨论了推动演变的一些关键因素，并找出了在构建现代应用程序时导致它们不可行的缺陷。  

### [Linux TCP 统计指标详解](https://mp.weixin.qq.com/s/F7KjHOzHjRmdbFxnSaA4mw)
- **发布日期**：2024-11-09 09:59  
- **所属合集**：#Linux  
- **摘要**：最近写了几篇关于 Linux 网络收发包，TCP 连接三次握手、结束连接四次挥手以及 TCP 收发包优化的内核参数。那最后我们就把 Linux TCP 统计指标这块再和大家讲一讲。  

### [图解 TCP 收发包需要注意的内核参数](https://mp.weixin.qq.com/s/3pGiiWPLHQsVNzTjBy6lmg)
- **发布日期**：2024-11-07 12:59  
- **所属合集**：#Linux  
- **摘要**：TCP 收包和发包的过程是网络应用中容易出现问题的地方，最常见的问题就是丢包。要解决这些问题，我们需要理解 TCP 收发包过程中的关键因素，以及如何配置参数使之与业务场景匹配！  

### [图解 TCP 连接生命周期](https://mp.weixin.qq.com/s/cOXUH8knOomVLGE6YWs9Mg)
- **发布日期**：2024-11-05 12:31  
- **所属合集**：#Linux  
- **摘要**：图解 TCP 连接生命周期，包含建立连接三次握手以及关闭连接四次挥手，并重点介绍了 Linux 相关内核参数的含义和使用建议，从系统层解决 C10K 这样的问题！  

### [来自《Broadcom 以太网网络适配器用户指南》中提到的「 Linux 命令」](https://mp.weixin.qq.com/s/R3IQZJwjlMH5Qtqlcj1g2Q)
- **发布日期**：2024-11-01 08:31  
- **所属合集**：#网络基础知识 #Linux  
- **摘要**：来自《Broadcom 以太网网络适配器用户指南》中提到的「 Linux 命令」  

### [Linux 网络收发包路径简介](https://mp.weixin.qq.com/s/fSYzPfG2tjJ1hD8uWp39Ug)
- **发布日期**：2024-10-31 13:01  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：为了最终写作《网络性能探案惊奇：三步揪出 CPU 软中断一直处于 100%的元凶》，今天先来介绍一下 Linux 网络收发包路径，并重点讲解收包路径。  

### [了解 Linux 中的中断、软中断和 Softnet 之原理篇](https://mp.weixin.qq.com/s/lBaP4Nd5F28YSt8IEXw_Lw)
- **发布日期**：2024-10-30 08:31  
- **所属合集**：#Linux  
- **摘要**：了解 Linux 中的中断、软中断和 Softnet 之原理篇，为后续的案例分析作准备！  

### [周末好书推荐《Linux/Unix 系统编程手册（上下册）》](https://mp.weixin.qq.com/s/9H3Cmw0Tp281WGKcbAvtFA)
- **发布日期**：2024-10-27 09:30  
- **所属合集**：#Linux  
- **摘要**：推荐一本工具书《Linux/Unix 系统编程手册（上下册）》，大部分系统调用相关的都涵盖的了，非常实用！  

### [Linux 删除文件或者目录时，出现“Operation not permitted” ，如何解决？](https://mp.weixin.qq.com/s/i1irz1t1BfUpd1jjc2r78w)
- **发布日期**：2024-10-24 08:31  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：用户在对文件做删除，移动等操作，会提示 “Operation not permitted“ 错误，无法操作成功，此时我们就需要检查文件属性了！  

### [Linux 删除文件或者目录时，出现“Operation not permitted” ，如何解决？](https://mp.weixin.qq.com/s/i1irz1t1BfUpd1jjc2r78w)
- **发布日期**：2024-10-24 08:31  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：用户在对文件做删除，移动等操作，会提示 “Operation not permitted“ 错误，无法操作成功，此时我们就需要检查文件属性了！  

### [好书推荐 《Linux 二进制分析》](https://mp.weixin.qq.com/s/iB7oeeXuCR-W9JTeByetDw)
- **发布日期**：2024-10-24 08:31  
- **所属合集**：#Linux  
- **摘要**：​大家读完：《Linux 二进制文件格式 ELF 入门​》 是否还意犹未尽？希望了解更多 ELF 分析的使用场景，那笔者就推荐大家阅读​以下书籍《Linux 二进制分析》一书，可以更加深入学习和使用 Linux 二进制分析技术。  

### [Linux 二进制文件格式 ELF 入门](https://mp.weixin.qq.com/s/8L04s20E-9Qyz0DKhlOrKQ)
- **发布日期**：2024-10-23 08:31  
- **所属合集**：#Linux  
- **摘要**：ELF 是 “Executable and Linkable Format”的缩写，它定义了二进制文件、库和核心文件的结构。正式的规范允许操作系统正确解释其底层机器指令。ELF 文件通常是编译器或链接器的输出，并且是一种二进制格式。  

### [管理 Linux 上的内核驱动程序和模块](https://mp.weixin.qq.com/s/WuA8O7D3ouFqYq8IL2d9cA)
- **发布日期**：2024-10-12 13:00  
- **所属合集**：#Linux  
- **摘要**：内核模块是 Linux 操作系统中必不可少的组件，可以扩展内核的功能，而无需重新启动系统。这些模块可以动态加载和卸载，从而可以灵活高效地管理硬件驱动程序、文件系统和其他内核功能。本文将指导用于操作内核模块的各种命令，并用示例来说明它们的用法  

### [推荐：原力注入  Linux 从入门到精通](https://mp.weixin.qq.com/s/aKW_mgAzcGls-AaorGsqGA)
- **发布日期**：2024-10-11 08:30  
- **所属合集**：#Linux  
- **摘要**：为了能够让读者更加方便阅读和使用相关文章，笔者之后也会同步整理到「原力注入」的 Github repo 中，含义从入门到精通。  

### [安全证书简介](https://mp.weixin.qq.com/s/nH2sfKVfIKvWIgL0Z4FKAA)
- **发布日期**：2024-10-09 08:30  
- **所属合集**：#Linux  
- **摘要**：以 pem, der, key, csr, crt 等为后缀的证书文件简介。  

### [深入了解 SSL 证书（英文版）](https://mp.weixin.qq.com/s/EBgh8U5qqCNBLfoJGrdcDQ)
- **发布日期**：2024-10-09 08:30  
- **所属合集**：#Linux  
- **摘要**：了解 SSL 证书对任何软件开发人员来说都是至关重要的，本文介绍了 SSL 证书的生命周期，以及相关原理和概念，可以帮助大家对于 SSL 证书有个深入的掌握！  

### [Linux set 命令详解](https://mp.weixin.qq.com/s/j1ilyudm6tsn4vDsFP-urg)
- **发布日期**：2024-09-19 08:30  
- **所属合集**：#Linux  
- **摘要**：set 命令用于显示和设置 shell 及 Linux 环境中的各种变量、选项。set 提供了强大的控制功能，使用户可以改变 shell 的行为，尤其适合调试、错误处理、环境配置等场景。  

### [容器技术回顾：消失的 Docker 网络命名空间](https://mp.weixin.qq.com/s/mciucLzKH8wAIoxuQyze1A)
- **发布日期**：2024-09-12 08:30  
- **所属合集**：#Linux #Docker #网络基础知识  
- **摘要**：从命名空间伪文件列表中，我们可以看到此进程的 net 文件的存在。由于 net 文件对应于 Linux 网络命名空间，因此我们可以预期它会在列出所有网络命名空间时显示出来。但是，我们可以看到事实并非如此。  

### [理解 Linux 中的进程状态【翻译】](https://mp.weixin.qq.com/s/Jo_pL6W6lgMGkQz5vQhfmg)
- **发布日期**：2024-09-07 09:30  
- **所属合集**：#Linux  
- **摘要**：理解“进程”及其“状态”的概念对于清晰了解 Unix/Linux 的工作方式至关重要。本文使用一个常见的类比(汽车）来解释这些概念。  

### [容器技术回顾 - OverlayFS 简介](https://mp.weixin.qq.com/s/6-6vHjRxZF1MOahSzZm0yg)
- **发布日期**：2024-09-02 08:30  
- **所属合集**：#Linux #Docker  
- **摘要**：OverlayFS 伪文件系统首次包含在 Linux 内核 3.18 版本中：它允许我们将两个目录树或文件系统（一个“上层”和一个“下层”）以对用户完全透明的方式结合起来，用户可以像在标准文件系统上一样访问“合并”层上的文件和目录。  

### [江湖救急，远程服务器无法 Reboot！！！](https://mp.weixin.qq.com/s/KIArpI_VZ15mjeq4DCge7Q)
- **发布日期**：2024-08-31 09:15  
- **所属合集**：#Linux  
- **摘要**：Reboot 不起作用，除了人肉物理 power off/on，还有什么方法吗？  

### [Linux 上统计进程 inotify 和 inotify watches 【更新】](https://mp.weixin.qq.com/s/5bYUgi4K7G-iTotKwPscBg)
- **发布日期**：2024-08-29 08:30  
- **所属合集**：#Linux  
- **摘要**：一个 inotify 实例可以有多个 watches，用户的 inotify 数量受 max_user_instances 限制，用户的 watch 数量受 max_user_watches 限制。此外本体提供了一个更新的脚本！  

### [Linux inotify 简介「双语」](https://mp.weixin.qq.com/s/ls8Ia8rajc74hi17tWgWZA)
- **发布日期**：2024-08-29 08:30  
- **所属合集**：#Linux  
- **摘要**：inotify 是 Linux 内核的一个子系统，提供了文件和目录监控的能力。它使应用程序能够接收到文件系统中发生的各种事件的通知，包括文件修改、创建、删除和属性变化。  

### [Docker 镜像、容器和存储卷清理指南【双语】](https://mp.weixin.qq.com/s/Pcb_yzbYJ4CiFEBOR5yyzQ)
- **发布日期**：2024-08-28 08:30  
- **所属合集**：#Docker #Linux  
- **摘要**：在这篇博客中，让我们探索有效清理 Docker 资源的基本命令和方法。此外，我们还将看到定期 Docker 清理在防止资源混乱和降低安全风险方面的重要性。  

### [Kubelet 报错：inotify_add_watch ... no space left on device](https://mp.weixin.qq.com/s/CIfciM_f_3m_0vm93GTnbw)
- **发布日期**：2024-08-27 08:30  
- **所属合集**：#Linux #Kubernetes #Docker  
- **摘要**：Kubelet 报错：inotify_add_watch ... no space left on device。是磁盘空间不足了吗？原来罪魁祸首是 inotify！  

### [Docker Registry 的一种高可用方案](https://mp.weixin.qq.com/s/P13Vlj7UGnKtghVsevJIig)
- **发布日期**：2024-08-26 08:30  
- **所属合集**：#Docker #Linux #Kubernetes  
- **摘要**：现有版本 registry 只运行在一台 master 节点上，若该 master 节点宕机或是出了其他问题，registry 就会不可用。我们提供了一个基于 inotify + rsync 的高可用方案，供大家参考。  

### [如何在 Linux 中创建 Systemd 服务](https://mp.weixin.qq.com/s/7zPysYgKRpGFRU2gyjhsGw)
- **发布日期**：2024-08-24 09:01  
- **所属合集**：#Linux  
- **摘要**：本文介绍了在 Linux 系统中创建和管理 Systemd 服务的详细步骤。我们以 shell 脚本为例做一个简单的说明。  

### [Linux 及 Docker 文件句柄数限制及配置指南](https://mp.weixin.qq.com/s/G2biIN_zJWKeuUeFM0CrUQ)
- **发布日期**：2024-08-18 09:01  
- **所属合集**：#Linux  
- **摘要**：最大文件句柄数即打开文件数的最大限制，Linux系统中包含两个文件句柄限制：一个是系统级的，即所有用户的进程同时打开文件数的上限；一种是用户级的，即单个用户进程打开文件数的上限。但容器中还有另一个文件句柄限制，即容器内部单进程最大文件句柄数  

### [系统调用 sync、fsync 和 fdatasync 的区别](https://mp.weixin.qq.com/s/B1imUDz4oyerIC6u0oe0hg)
- **发布日期**：2024-08-13 08:35  
- **所属合集**：#Linux  
- **摘要**：为了保证磁盘上的实际文件和缓冲区中的内容保持一致，UNIX 系统提供了三个系统调用：sync、fsync、fdatasync，那这三者有什么区别呢？今天我们就来探讨一下。  

### [使用 Stress-ng 对实时系统进行压力测试](https://mp.weixin.qq.com/s/APyXrWvxaAfKkjuc_eSNbQ)
- **发布日期**：2024-08-12 08:25  
- **所属合集**：#Linux  
- **摘要**：stress-ng 工具是一个压力工作负载生成器，用于加载和强调所有内核接口。它包括各种压力机制，称为压力源。压力测试使机器努力工作并引发硬件问题，例如系统过度工作时发生的热超限和操作系统错误。  

### [好书推荐 - 《图解 Linux 内核 基于6.x》](https://mp.weixin.qq.com/s/dkGn-TIzqyf3MIMxx1VFhw)
- **发布日期**：2024-08-09 08:36  
- **所属合集**：#Linux  
- **摘要**：基于新发布的 Linux 6.x，包含前沿的技术（如近几年流行的 CXL）和巨量的代码更新。 以【图解】【看图说话】等巧妙形式增强读者的阅读体验，涉及的复杂机制均配图表且提供下载，帮助读者快速厘清脉络。  

### [在 Docker 中使用 Capabilities 实现权限控制](https://mp.weixin.qq.com/s/shaFiJ0Ih2G_hLkZ6u6daA)
- **发布日期**：2024-08-04 23:45  
- **所属合集**：#Linux #Docker  
- **摘要**：为了适应更复杂的权限需求，从 2.2 版本起 Linux 内核能够进一步将超级用户的权限分解为细颗粒度的单元，这些单元称为 capabilities.几乎所有与超级用户相关的特权都被分解成了单独的 capability。  

### [Linux /dev 目录揭秘](https://mp.weixin.qq.com/s/o6-Gzu5g4l3Rz6Sq6jVhbg)
- **发布日期**：2024-08-01 08:35  
- **所属合集**：#Linux #存储  
- **摘要**：Linux 是一个类 Unix 操作系统，其中一项重要的特性就是一切皆文件。/dev 目录是 Linux 文件系统的重要组成部分，用于存放设备文件。设备文件代表系统中的硬件设备，通过这些文件，用户可以以文件的方式访问硬件。  

### [【深度】操作系统技术实践：解读 CPU 隔离](https://mp.weixin.qq.com/s/ZUjAZt4ZNFBMDmbh-dFVRg)
- **发布日期**：2024-07-21 09:30  
- **所属合集**：#Linux #cpu  
- **摘要**：CPU 隔离是一组强大的功能，可以为那些依赖特定且通常对延迟或性能有极端要求的工作负载设置提供支持。  

### [揭秘静态链接和动态链接](https://mp.weixin.qq.com/s/VptqgINDk1zoh0n-F2empw)
- **发布日期**：2024-07-17 08:50  
- **所属合集**：#Linux  
- **摘要**：编程语言中，常常将包含大量函数（类、方法）的文件称为库文件。库文件是最常用的共享代码的方式，根据使用方法的不同，库文件可以分为静态链接库（简称“静态库文件”或者“静态库”）和动态链接库（“动态库文件”或者“动态库”）两种  

### [知乎问题：宿主机是 ubuntu 22，容器是 ubuntu 24，容器是否可正常使用 ubuntu 24 特有的一些新功能？](https://mp.weixin.qq.com/s/C3Faz_g5nyP7WUEAzsJxFA)
- **发布日期**：2024-07-16 08:50  
- **所属合集**：#Docker #Linux  
- **摘要**：宿主机是 ubuntu 22，容器是 ubuntu 24，容器是否可正常使用 ubuntu 24 特有的一些新功能？  

### [《Linux 网络编程》第四章进程间通信（4）- System V IPC](https://mp.weixin.qq.com/s/mDzQDCapwQ5fnwqn6sy6BA)
- **发布日期**：2024-07-12 09:05  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：消息队列（Message Queues），信号量（semaphores）和共享内存（shared memory），统称为 System V IPC。在 Linux 系统编程中，它们有着广泛的应用。  

### [Kubernetes 1.30：对 Pod 使用用户命名空间的支持进阶至 Beta](https://mp.weixin.qq.com/s/tZwzd0W7U_68x04WtGY2NQ)
- **发布日期**：2024-07-11 09:05  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：在 Kubernetes v1.25 中，我们仅为无状态 Pod 引入了对用户命名空间的支持。Kubernetes 1.28 取消了这一限制，目前在 Kubernetes 1.30 中，这个特性进阶到了 Beta！  

### [深入研究 Linux Namespace - 第一部分](https://mp.weixin.qq.com/s/xOrUChPfHYyP2qQYxB8zDQ)
- **发布日期**：2024-07-10 14:05  
- **所属合集**：#Linux #Docker  
- **摘要**：进程隔离是容器的关键能力。用到的底层机制之一是 Linux Namespace。今天我们就深入研究一下。  

### [深入研究 Linux Namespace - User Namespace](https://mp.weixin.qq.com/s/9FVKbKrw688Fhm_1KGXwfg)
- **发布日期**：2024-07-10 14:05  
- **所属合集**：#Linux  
- **摘要**：Linux 世界中所有进程都有其所有者。 根据其有效用户 ID (UID) 属性，进程可分为特权进程和非特权进程。根据此 UID，进程对操作系统拥有不同的权限。用户命名空间是一项内核功能，允许每个进程虚拟化此属性。  

### [在 Docker 中使用 Linux User Namespace 隔离容器用户](https://mp.weixin.qq.com/s/7e75EVdlFeISqdoZqlbUrw)
- **发布日期**：2024-07-10 14:05  
- **所属合集**：#Docker #Linux  
- **摘要**：防止容器内特权升级攻击的最佳方法是将容器的应用程序配置为以非特权用户身份运行。对于其进程必须以root容器内用户身份运行的容器，我们可以将此用户重新映射到 Docker 主机上权限较低的用户。  

### [在 Docker 中使用 Linux User Namespace 隔离容器用户](https://mp.weixin.qq.com/s/bPuo36dhTs5d8VhQJUH4PQ)
- **发布日期**：2024-07-09 16:20  
- **所属合集**：#Docker #Linux  
- **摘要**：防止容器内特权升级攻击的最佳方法是将容器的应用程序配置为以非特权用户身份运行。对于其进程必须以root容器内用户身份运行的容器，我们可以将此用户重新映射到 Docker 主机上权限较低的用户。  

### [深入研究 Linux Namespace - User Namespace](https://mp.weixin.qq.com/s/fk5sUzU8Kk9SmNuwLL1UZQ)
- **发布日期**：2024-07-09 13:05  
- **所属合集**：#Linux  
- **摘要**：Linux 世界中所有进程都有其所有者。 根据其有效用户 ID (UID) 属性，进程可分为特权进程和非特权进程。根据此 UID，进程对操作系统拥有不同的权限。用户命名空间是一项内核功能，允许每个进程虚拟化此属性。  

### [深入研究 Linux Namespace - 第一部分](https://mp.weixin.qq.com/s/V-5-xeAGkIwprkSGAfI32Q)
- **发布日期**：2024-07-06 09:00  
- **所属合集**：#Linux #Docker  
- **摘要**：进程隔离是容器的关键能力。用到的底层机制之一是 Linux Namespace。今天我们就深入研究一下。  

### [《Linux 网络编程》第四章进程间通信（3）- 文件和记录锁定](https://mp.weixin.qq.com/s/1xehQj1mgXXzds3rob4UYA)
- **发布日期**：2024-07-05 09:00  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：《Linux 网络编程》第四章进程间通信（3）- 文件和记录锁定  

### [在 Linux 容器中可以使用独立于主机的系统时间吗？](https://mp.weixin.qq.com/s/qppow2Wok1zwY5bgQEzJEw)
- **发布日期**：2024-06-27 08:05  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：在 Linux 容器中可以使用独立于主机的时间吗？老版本内核不支持，但是随着 Linux Kernel 5.6 引入了 time namespace，以及 runc 开始支持 time namespace，将来的版本就可以支持了！  

### [《Linux 网络编程》第四章进程间通信（2）- 管道](https://mp.weixin.qq.com/s/TkqSFtHF92pesXr8SrTv3A)
- **发布日期**：2024-06-06 08:45  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：管道就是将一个程序的输出和另外一个程序的输入连接起来的单向通道。它是UNIX/Linux 系统的各种进程通信方法中，最古老而应用最为广泛的一种（特别是在 shell 中）.  

### [《Linux 网络编程》第四章进程间通信（1）- 信号](https://mp.weixin.qq.com/s/LbXABLAHu6fXTYxce71wEg)
- **发布日期**：2024-06-03 12:05  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：今天介绍一下 Linux 进程间通信的方法一信号。  

### [Linux 基础知识 - 进程间通信与同步](https://mp.weixin.qq.com/s/JSs6IB1sKTpMlsLlThb_ow)
- **发布日期**：2024-06-02 18:05  
- **所属合集**：#Linux  
- **摘要**：Linux 系统上可用的 IPC 机制种类繁多，这反映了不同应用程序的不同需求。常见的方式包括信号、管道和 FIFO、套接字、文件锁、消息队列、信号量和共享内存，接下来我们会依次对这些方法做一个讲解。  

### [Linxu 小技巧 - 使用 nsenter 在主机上调试容器](https://mp.weixin.qq.com/s/Y-9vkIPawFjSfYaNKF1fiQ)
- **发布日期**：2024-06-01 10:01  
- **所属合集**：#Linux  
- **摘要**：nsenter 是一个可以用来进入到目标程序所在 Namespace 中运行命令的工具，一般常用于在宿主机上调试容器中运行的程序。  

### [补几张 VXLAN 的图](https://mp.weixin.qq.com/s/DjRHn6DVJIG20HtLRQFBdA)
- **发布日期**：2024-05-29 12:31  
- **所属合集**：#Linux #网络基础知识 #虚拟化  
- **摘要**：补几张 VXLAN 的图，细化一下相关概念。  

### [Linux 网络基础知识 - VXLAN 原理介绍](https://mp.weixin.qq.com/s/WJ6d0eie0yKZvECvLygcDw)
- **发布日期**：2024-05-28 12:30  
- **所属合集**：#Linux #网络基础知识 #虚拟化  
- **摘要**：VXLAN（Virtual eXtensible Local Area Network ）就是一种基于虚拟交换机实现的 overlay 网络。本文介绍了为什么需要 VXLAN 、 VXLAN 的基本原理以及基于 Linux 内核的实现。  

### [Linux 基础知识 - 一文学会网络虚拟化](https://mp.weixin.qq.com/s/Sn1ql5Pa5rBc7_C7QPqZbg)
- **发布日期**：2024-05-26 10:00  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：Linux 网络虚拟化技术包含了网络命名空间以及各类虚拟设备，如 veth、Bridge、tap/tun 等。这些虚拟设备模拟现实世界中的物理设备彼此协作，将各个独立的网络命名空间连接起来，构建出不受物理环境约束的各类动态网络拓扑架构。  

### [Linux 基础知识：连接跟踪 conntrack 入门](https://mp.weixin.qq.com/s/zaS3F5LVwj4ASIZN5gMaNg)
- **发布日期**：2024-05-25 10:00  
- **所属合集**：#Linux  
- **摘要**：连接跟踪是许多网络功能及应用的基础，例如：Kubernetes Service、ServiceMesh sidecar、 软件四层负载均衡器 LVS/IPVS、Docker network、OVS、iptables 主机防火墙等等。  

### [Linux 小技巧 - 使用 iftop 监控实时端口流量](https://mp.weixin.qq.com/s/4TTBeinb2_xrAZ-f9w3pUA)
- **发布日期**：2024-05-20 23:00  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：iftop 是一个用于实时监控网络流量的命令行工具，有可交互图形界面，可以指定网络接口统计实时流量。  

### [Linux 小技巧 - 使用 iftop 监控实时端口流量](https://mp.weixin.qq.com/s/4TTBeinb2_xrAZ-f9w3pUA)
- **发布日期**：2024-05-20 23:00  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：iftop 是一个用于实时监控网络流量的命令行工具，有可交互图形界面，可以指定网络接口统计实时流量。  

### [Linux 小技巧 - 使用 ab 命令做性能压测](https://mp.weixin.qq.com/s/qHgusLmiVmuocYdb5OxFlg)
- **发布日期**：2024-05-07 12:28  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：ab 是 Apache 自带的压力测试工具，可以对 Web 服务器进行访问压力测试。ab 命令会创建多个并发线程，模拟多个访问者同时对某一个url地址进行访问，实现压力测试。  

### [Linux 小技巧 - 使用 ab 命令做性能压测](https://mp.weixin.qq.com/s/qHgusLmiVmuocYdb5OxFlg)
- **发布日期**：2024-05-07 12:28  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：ab 是 Apache 自带的压力测试工具，可以对 Web 服务器进行访问压力测试。ab 命令会创建多个并发线程，模拟多个访问者同时对某一个url地址进行访问，实现压力测试。  

### [一文搞清楚操作系统中的锁](https://mp.weixin.qq.com/s/2H1-7Iiuxyp3uWNEItqJ8g)
- **发布日期**：2024-05-06 12:35  
- **所属合集**：#Linux #南京大学  
- **摘要**：本文介绍了操作系统中锁的原理以及实现，包括一些硬件支持（更加强大的指令）和
一些操作系统支持（例如 Solaris 的 park() 和 unpark() 原语，Linux 的 futex ）。  

### [使用 lstopo 查看服务器逻辑拓扑结构](https://mp.weixin.qq.com/s/0H-Oa3SEI6IPDFn7L9uAyw)
- **发布日期**：2024-04-28 22:33  
- **所属合集**：#系统可观测性 #Linux  
- **摘要**：本文介绍了使用 hwloc 工具查看服务器的逻辑拓扑，帮助我们深入了解服务器的硬件结构，以便更好地进行性能调优。  

### [通用 CPU 性能基准测试研究综述](https://mp.weixin.qq.com/s/rauCUcbDtwHCepeB6BpmYg)
- **发布日期**：2024-04-24 19:31  
- **所属合集**：#Linux #系统可观测性 #cpu  
- **摘要**：今天我们就来看一篇论文《通用 CPU 性能基准测试研究综述》，讨论一下 CPU 性能测试应该如何做。  

### [【转载】主流CPU性能比较（Hygon7280、Intel、AMD、鲲鹏920、飞腾2500）](https://mp.weixin.qq.com/s/x_TqZlvgyDiwU8rdphgizA)
- **发布日期**：2024-04-20 22:01  
- **所属合集**：#cpu #Linux  
- **摘要**：本文在Sysbench、TPCC等实践场景下对多款CPU的性能进行对比，同时分析各款CPU的硬件指标，最后分析不同场景下的实际性能和核心参数的关系。  

### [Linux 环境为什么文件迁移完成后，源端与目的端文件大小不一致？ - “文件空洞”解析](https://mp.weixin.qq.com/s/EJ90wdU-wd7FgZwowLT-Cg)
- **发布日期**：2024-04-17 21:05  
- **所属合集**：#Linux  
- **摘要**：什么是空洞文件？在 Linux （Unix）中，lseek的系统调用是可以改变在文件上面的偏移量的，而且还允许其超出文件的长度。空洞文件的一个常见用途是在数据库等应用中预分配磁盘空间，以便将来可以向其中写入数据而无需频繁扩展文件大小。  

### [Linux 小知识：ls -l 命令的输出中目录的大小是什么含义？](https://mp.weixin.qq.com/s/0Q1FLPoUwU-7-XcIQydiwA)
- **发布日期**：2024-04-09 08:00  
- **所属合集**：#Linux  
- **摘要**：在 Linux 中，文件目录的大小是什么含义呢？我们该如何查看？我们以 xfs 为例进行了说明。  

### [好书推荐 - 《深入理解 Linux 网络》](https://mp.weixin.qq.com/s/crZ29epWXF6_HP0GKtXDUQ)
- **发布日期**：2024-03-30 10:46  
- **所属合集**：#好书推荐 #Linux #网络基础知识  
- **摘要**：本书对 Linux 网络建立连接，收发包流程等相关知识的一个概览与总结，贴近实战，适合帮助大家快速入门。  

### [Linux 基础知识：CPU Usage 和 System Load 的关系](https://mp.weixin.qq.com/s/gkLNZLcEW8tyanbcT8y0Zw)
- **发布日期**：2024-03-25 12:15  
- **所属合集**：#Linux #cpu  
- **摘要**：CPU 密集型应用，大量进程在等待或使用 CPU，此时 CPU 使用率与平均负载呈正相关状态。
I/O 密集型应用，大量进程在等待 I/O，此时平均负载会升高，但 CPU 使用率不一定很高。  

### [Linux 小技巧 - SIGTERM 与 SIGKILL：有什么区别？](https://mp.weixin.qq.com/s/RpRHa0nE-aRC_rS8VVdO3g)
- **发布日期**：2024-03-21 19:30  
- **所属合集**：#Linux 小技巧  
- **摘要**：SIGTERM 和 SIGKILL 都用于终止 Linux 中的进程，我们应该有哪个呢？  

### [【原理篇】《BPF性能之巅》如何快速分析系统的 I/O 瓶颈？](https://mp.weixin.qq.com/s/QtYQ-vLjCXUVF4pbbGtwgQ)
- **发布日期**：2024-03-19 19:30  
- **所属合集**：#BPF之巅 #Linux #存储  
- **摘要**：我们应该使用什么样的方法和工具，来“快准狠”地定位系统的 I/O 瓶颈呢？本文是原理篇，后续还会陆续推出实战篇。  

### [【原理篇】《BPF性能之巅》如何快速分析系统的 I/O 瓶颈？](https://mp.weixin.qq.com/s/R7AbMDuIWe5jJpDWQHVp2A)
- **发布日期**：2024-03-17 09:00  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：我们应该使用什么样的方法和工具，来“快准狠”地定位系统的 I/O 瓶颈呢？本文是原理篇，后续还会陆续推出实战篇。  

### [好文推荐 - 掌握 Linux 内存故障追踪：技术指南](https://mp.weixin.qq.com/s/upeMRdmGLQYmXgizmz06Ng)
- **发布日期**：2024-03-01 22:30  
- **所属合集**：#系统可观测性 #Linux  
- **摘要**：掌握 Linux 内存故障追踪：技术指南  

### [Linux 基础知识 - CPU 上下文切换](https://mp.weixin.qq.com/s/Tls0gCGn12qRGh2m3fBdEQ)
- **发布日期**：2024-02-20 08:15  
- **所属合集**：#Linux #cpu  
- **摘要**：CPU 上下文切换 ，就是先把前一个任务的 CPU 上下文（也就是 CPU 寄存器和程序计数器）保存起来，然后加载新任务的上下文到这些寄存器和程序计数器，最后再跳转到程序计数器所指的新位置，运行新任务。  

### [Linux 小技巧 - 在 fstab 文件中配置 UUID 方式自动挂载（防止盘符漂移导致挂载失败）](https://mp.weixin.qq.com/s/KoblhHY-zqgyZJImzwciqQ)
- **发布日期**：2024-02-19 10:30  
- **所属合集**：#Linux  
- **摘要**：在 Linux 系统中，我们可以通过配置 fstab 文件让主机启动时会自动挂载数据盘的文件系统，同时为了解决盘符变化无法自动挂载，我们应该使用 UUID 方式。  

### [Linux 基础知识 - The LinuxProcess Journey](https://mp.weixin.qq.com/s/I3dDxgjqi4fMI-79btGXYQ)
- **发布日期**：2024-02-18 10:01  
- **所属合集**：#Linux  
- **摘要**：对 Linux 的默认进程以及进程的管理有一个更加全面的认识。  

### [nmi_watchdog：Softlockup 与 hardlockup 检测机制](https://mp.weixin.qq.com/s/j7moQV7dpnjGX4vL_t7IIg)
- **发布日期**：2024-02-11 11:01  
- **所属合集**：#Linux  
- **摘要**：nmi_watchdog 是 Linux 的内核实现了一种用以检测系统发生 softlockup 和 hardlockup 的看门狗机制。  

### [Linux 小技巧 - 如何杀死僵尸进程](https://mp.weixin.qq.com/s/8IVee9wiYJe09VNFaJL2uw)
- **发布日期**：2024-02-10 11:01  
- **所属合集**：#Linux  
- **摘要**：僵尸进程也称为“已失效”或“死亡”进程 - 简而言之，僵尸进程是已死亡但存在于系统进程表中的进程。今天我们就讨论一下来如何杀死它们。  

### [禁用/启用 SMT 引发的 CGroup 绑定 CPU 的问题](https://mp.weixin.qq.com/s/wQ-5d9TmOW8zZQxXgnkcsQ)
- **发布日期**：2024-02-10 11:01  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：背景知识同步多线程 (SMT) 允许在单个物理 CPU 内核上执行多个执行线程。在容器环境中，我们开关 SMT 引发了一个 cgroup 绑定 CPU 的问题 。  

### [容器技术国产化 - 从 500 行 C 代码到生产级容器运行时](https://mp.weixin.qq.com/s/i7SqPGTDzy-3Qd8kRKUVUA)
- **发布日期**：2024-02-05 08:55  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：本文试图通过一段简单但又尽量全面的代码来串联起这些底层核心技术，看看一个容器是如何创建出来的。有了对这个过程的理解，容器就不再是一个无从下手的黑盒，排查一些线上疑难杂症时也会更有方向。  

### [Linux 基础知识 - LVM 逻辑卷管理器介绍](https://mp.weixin.qq.com/s/Wu6zo4OCGt93lZVPwavALQ)
- **发布日期**：2024-02-04 19:20  
- **所属合集**：#Linux #存储  
- **摘要**：LVM 是逻辑卷管理（Logical Volume Manager）的简称，它是 Linux 环境下对磁盘分区进行管理的一种机制。LVM通过在硬盘和文件系统之间添加一个逻辑层，来为文件系统屏蔽下层硬盘分区布局，提高硬盘分区管理的灵活性。  

### [The State of eBPF - 2024](https://mp.weixin.qq.com/s/TifVOJ_OyGbWNEwe3ImTsg)
- **发布日期**：2024-02-01 12:15  
- **所属合集**：#Kubernetes #BPF之巅 #Linux  
- **摘要**：（eBPF的拥护者认为）毫无疑问，eBPF 将成为新的云原生基础设施堆栈中的新的一层，影响所有应用的可观测性、性能、可靠性、网络和安全性。  

### [【原理篇】《BPF性能之巅》如何快速分析系统的 I/O 瓶颈？](https://mp.weixin.qq.com/s/X1WVRWSgUUyYbVyelnf_Nw)
- **发布日期**：2024-01-29 12:36  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：我们应该使用什么样的方法和工具，来“快准狠”地定位系统的 I/O 瓶颈呢？本文是原理篇，后续还会陆续推出实战篇。  

### [Linux 小技巧 - 模拟 Docker hang 住](https://mp.weixin.qq.com/s/emha2o0B55UTyJ_bBitMjw)
- **发布日期**：2024-01-27 10:20  
- **所属合集**：#Linux #Docker  
- **摘要**：我们是否可以模拟 Docke 命令 hang 住的情况呢？答案是 Yes，可以使用 freezer Cgroup 来制造包含 D 状态进程的容器！  

### [Linux 小技巧 - 查看所有的内核进程](https://mp.weixin.qq.com/s/0Vg6hpof-sqyBWLPRudvTQ)
- **发布日期**：2024-01-25 12:27  
- **所属合集**：#Linux  
- **摘要**：Linux 小技巧 - 查看所有的内核进程  

### [Linux IO Scheduler: noop/deadline/cfq/bfq 到 blk-mq](https://mp.weixin.qq.com/s/XF5GEsOiBXj__VdqMLlcQQ)
- **发布日期**：2024-01-24 12:26  
- **所属合集**：#Linux  
- **摘要**：Linux I/O Scheduler 相关资料  

### [Linux 基础知识 - 进程组、作业和会话](https://mp.weixin.qq.com/s/7MmARq3raF2X4c2Dp_jSag)
- **发布日期**：2024-01-23 12:25  
- **所属合集**：#Linux  
- **摘要**：进程组是进程的集合。在 shell 内，进程组通常称为作业。每个进程组又属于一个会话（Session），因此会话是相关进程组的集合。Linux 内核为所有正在运行的进程提供两级层次结构。  

### [容器技术回顾 - 节点资源预留让节点更加稳定](https://mp.weixin.qq.com/s/j9zEvz4xfxpzVRMPMypYCQ)
- **发布日期**：2024-01-22 08:45  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：如何让节点的可用资源更加确定呢？如何不要让节点的其它进程占用过多的资源，尤其是内存？
如何预留一些资源给到系统关键进程呢（例如sshd，以确保在关键时候我们可以远程登录）？  

### [Linux 可观测性 - 你真的了解 Linux Load Average 吗？](https://mp.weixin.qq.com/s/MKOj8xdsG6mihuDT7Gd25A)
- **发布日期**：2024-01-21 00:06  
- **所属合集**：#Linux #系统可观测性  
- **摘要**：Linux Load Average：算法、实现与实用指南  

### [容器技术回顾 - 如何修改容器的内核参数](https://mp.weixin.qq.com/s/04O2Y66_JyXhBR9bd4Uzuw)
- **发布日期**：2024-01-19 08:01  
- **所属合集**：#Linux #Kubernetes #Docker  
- **摘要**：在某些场景中，我们需要调整内核参数，来调整操作系统行为。那在容器化场景中，我们是否可以调整？哪些可以调整？如何调整？  

### [容器技术回顾 - 使用 UDS 实现 Pod 间通信](https://mp.weixin.qq.com/s/vqR-2hqJwXGBgmAsWL6uAQ)
- **发布日期**：2024-01-18 12:18  
- **所属合集**：#Kubernetes #Linux  
- **摘要**：简介传统 Socket 包含 Stream Socket 和 Datagram Socket，这两种 Sock  

### [容器技术回顾 - Linux 内存文件系统](https://mp.weixin.qq.com/s/5oDwatGU8kCDY_62P3piSg)
- **发布日期**：2024-01-16 21:56  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：大家是否有注意过 Linux 主机上的 /dev/shm 设备？它是什么  

### [容器技术回顾 - 多 Pod 间共享内存通信](https://mp.weixin.qq.com/s/JOzzrgrxgyca1EpQfn9NaQ)
- **发布日期**：2024-01-14 20:00  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：本文介绍了一种在单节点上使用 tmpfs 模拟共享内存的方式，实现多个 Pod 之间可以实现共享内存通信。  

### [容器技术回顾 - 从一个“D”状态容器进程回顾 cgroup freezer 子系统](https://mp.weixin.qq.com/s/SRnya2Y5kwJu3PYHug8jeQ)
- **发布日期**：2024-01-10 22:17  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：从一个 “D” 状态的容器进程，来回顾 cgroup freezer 子系统，同时提供相关脚本来帮助"解冻"进程！  

### [容器技术回顾 - 如何让我的容器/进程不要被 OOM Kill？](https://mp.weixin.qq.com/s/AoyWzaXQcgCPGTTBHjQzRQ)
- **发布日期**：2024-01-09 23:55  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：在 Kubernetes 环境中，我们会遇到 Java OOM -> Linux cgroup OOM -> Linux OOM 三种不同类型的 OOM，它们是什么？我们如何让我们的容器避免被 OOM Kill 呢？  

### [为什么同样使用2个vCPU的App在VM中比在容器中运行的快？](https://mp.weixin.qq.com/s/t3DjEmHxatWmYDonJKjjyA)
- **发布日期**：2024-01-06 10:32  
- **所属合集**：#Linux #Docker  
- **摘要**：容器技术回顾 - Kubernetes CPU request 和 limit 的作用与原理 一文中  

### [为什么同样使用2个vCPU的App在VM中比在容器中运行的快？](https://mp.weixin.qq.com/s/hqjx-PgHEkUEoOnRbdiXTA)
- **发布日期**：2024-01-04 12:12  
- **所属合集**：#Linux #Docker  
- **摘要**：容器技术回顾 - Kubernetes CPU request 和 limit 的作用与原理 一文中  

### [容器技术回顾（六） - 容器与主机共享内核是什么含义？](https://mp.weixin.qq.com/s/oA-tuw2vDB3TWO27mhGZiA)
- **发布日期**：2024-01-03 12:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：容器和主机共享内核，这得益于Linux有一个统一的内核体系。不同的 Linux 发行版使用了相同的内核体系，这使得基于不同 Linux 发行版构建的容器可以在一个 Linux 发行版上运行。那容器和主机共享内核有什么影响吗？​  

### [容器技术回顾 - Kubernetes memory limit 产生的 OOM](https://mp.weixin.qq.com/s/s-OKhQ1qa7w1muUQAUuyTQ)
- **发布日期**：2023-12-29 12:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：一次奇怪的 cgroup oom 问题分析，由此我们回顾了一下相关知识点。  

### [容器技术回顾 - Kubernetes CPU request 和 limit 的作用与原理](https://mp.weixin.qq.com/s/OinmIMOr5W0BWOUrC-LVTA)
- **发布日期**：2023-12-27 20:01  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：本文我们会回顾一下 Kubernetes 中 CPU request 和 limit 的含义，以及背后实现的原理。  

### [容器技术回顾 - 什么是优雅关闭以及如何实现](https://mp.weixin.qq.com/s/IxnkW5App4xJJPOeUD-uIQ)
- **发布日期**：2023-12-21 09:00  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：要实现容器的优雅关闭，我们需要做哪些事情呢？今天就让我们从 Linux 进程的优雅退出开始，来回顾一下容器的优雅关闭原理以及实现方式。  

### [容器技术回顾  - 容器中的 0 号进程和 1 号进程](https://mp.weixin.qq.com/s/PIwVV7xfw3umSL-n2Hsw_g)
- **发布日期**：2023-12-19 08:30  
- **所属合集**：#Kubernetes #Linux #Docker  
- **摘要**：对 Linux 系统来说 1 号进程为 init 进程，是由 0 号进程通过调用系统 init 函数创建的第一个用户进程 1 进程，主要做用户态进程的管理，垃圾回收等动作。那容器中是否存在 0 号进程和 1 号进程呢？它们有什么用？  

### [Linux系统 - 进程管理入门](https://mp.weixin.qq.com/s/amoHgnjzgCIFBpgNkeoYXw)
- **发布日期**：2023-12-18 08:00  
- **所属合集**：#Linux  
- **摘要**：通过 fork() 和 execve() 函数来了解一下 Linux 进程创建及删除功能  

### [《BPF之巅》读书笔记 - Linux 内核锁](https://mp.weixin.qq.com/s/r6WadnmdiiWrFWntcApHbw)
- **发布日期**：2023-12-17 10:00  
- **所属合集**：#Linux #BPF之巅  
- **摘要**：Linux内核中有许多不同类型的锁，这些锁的类型包括：互斥锁（mutex）、读写锁（rwlock）、自旋锁（spinlock）和信号量（semaphore），今天我们就来介绍一下这些锁以及使用的场景  

### [《BPF之巅》读书笔记 - 使用 perf + perf-agent-map 制作容器化 Java 火焰图](https://mp.weixin.qq.com/s/aIhQkg8YB2vHNzBoYghN0w)
- **发布日期**：2023-12-13 08:10  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：容器化 Java 程序火焰图制作秘籍  

### [周末学习 -《BPF 之巅：洞悉Linux系统和应用性能》汇总](https://mp.weixin.qq.com/s/RwxE7p4XzrIy5n8bSUSNoA)
- **发布日期**：2023-12-09 17:00  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：周末学习《BPF 之巅：洞悉Linux系统和应用性能》  

### [《BPF 之巅：洞悉Linux系统和应用性能》读书笔记（四）火焰图](https://mp.weixin.qq.com/s/mQmEckPLyz_HyH2N3PVlyQ)
- **发布日期**：2023-12-08 12:30  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：什么是火焰图？确定 CPU 繁忙的原因是性能分析的一项重要工作，通常涉及分析堆栈跟踪。通过以固定速率采样进行  

### [《BPF 之巅：洞悉Linux系统和应用性能》读书笔记（三）Linux Kernel 相关知识](https://mp.weixin.qq.com/s/pYHCdSgfVo0N2dpvLq2gtA)
- **发布日期**：2023-12-02 19:56  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：今天我们来快速复习一下 Linux Kernel 相关的知识点  

### [《BPF 之巅》读书笔记（二）番外篇 - Linux 存储软件栈](https://mp.weixin.qq.com/s/FOrlcaOZ6PqBvRZbHWHoPg)
- **发布日期**：2023-12-01 21:48  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：Linux 存储栈入门  

### [《BPF之巅》读书笔记（一）Linux Tracing System](https://mp.weixin.qq.com/s/dujbESzKzoZyAoYbaPf_Dg)
- **发布日期**：2023-11-30 09:48  
- **所属合集**：#BPF之巅 #Linux  
- **摘要**：Linux Tracing System 的数据源（ kprobe，tracepoint）入门  

### [《BPF 之巅：洞悉Linux系统和应用性能》读书笔记开篇](https://mp.weixin.qq.com/s/PxJN2jXb4CvMD6yckmwJNQ)
- **发布日期**：2023-11-28 07:38  
- **所属合集**：#BPF之巅 #Linux #好书推荐  
- **摘要**：《BPF之巅》一书为我们打开了 Linux 内核大门，可以一窥内核原理和工作机制，为大家的以后的内核开发之旅铺平道路！  

### [系统性的学习 Linux Systems Performance](https://mp.weixin.qq.com/s/aqco2RFUoIcLO1d54Moc9Q)
- **发布日期**：2023-11-18 23:47  
- **所属合集**：#Linux #BPF之巅  
- **摘要**：Linux 系统性能的六个重要领域：可观测性工具、方法、基准测试、分析、跟踪和调优。Brendan Gregg 的演讲为我们打开了 Linux 系统性能的大门！  

### [Linux 小技巧 - 删除大量文件](https://mp.weixin.qq.com/s/g2nIl_P4sS89Rjp4JWf0Pw)
- **发布日期**：2023-11-15 09:33  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：Linux 系统下删除大量文件  

### [Linux 小技巧 - 删除大量文件](https://mp.weixin.qq.com/s/g2nIl_P4sS89Rjp4JWf0Pw)
- **发布日期**：2023-11-15 09:33  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：Linux 系统下删除大量文件  

### [一文让你应对Linux 进程“D”状态](https://mp.weixin.qq.com/s/aZgMvNR5_-qoQztMLXxSJw)
- **发布日期**：2023-10-29 22:07  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：进程长时间处于“D”状态，会导致进程无法响应，系统负载升高，最终导致整个系统响应慢甚至无法响应。那我们就来看看 Red hat 官方是如何来处理的吧！  

### [一文让你应对Linux 进程“D”状态](https://mp.weixin.qq.com/s/aZgMvNR5_-qoQztMLXxSJw)
- **发布日期**：2023-10-29 22:07  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：进程长时间处于“D”状态，会导致进程无法响应，系统负载升高，最终导致整个系统响应慢甚至无法响应。那我们就来看看 Red hat 官方是如何来处理的吧！  

### [【转载】Linux CFS 调度器：原理、设计与内核实现](https://mp.weixin.qq.com/s/ngSFPqFe_4xI1AAR30d5Vw)
- **发布日期**：2023-10-15 19:16  
- **所属合集**：#Linux  
- **摘要**：Linux 内核总是那么神秘，可谓是软件的掌上明珠！今天就让我们来深入学习一下 Linux 的 Completely Fair Scheduler，逐步揭开它的神秘面纱！  



## #RAG实战

### [基于大型语言模型的意图检测](https://mp.weixin.qq.com/s/rG35b3lA-Ubc4rcjMwDVcg)
- **发布日期**：2025-03-25 23:40  
- **所属合集**：#LLM #RAG实战  
- **摘要**：意图识别是NLP技术，专注于解析用户查询背后的核心诉求，在搜索与推荐系统领域具有重要地位，包括自然语言理解，即解析用户话语中隐含的语义；上下文分析，结合用户查询的上下文来精准识别意图；以及分类，将预定义标签或类别分配给用户输入及其预测意图  

### [学习总结 - RAG 快速开发实战 - 《02｜从0到1快速搭建RAG应用》](https://mp.weixin.qq.com/s/89-bwZ4aPor4ySj5U3n5zw)
- **发布日期**：2025-03-23 11:45  
- **所属合集**：#LLM #RAG实战  
- **摘要**：实战内容包括技术框架的介绍与选型、开发环境搭建与技术库安装、RAG 流程的代码实现。  



## #SRE

### [推荐 - SRE 精英联盟发布的《SRE实践白皮书》1.0.5 版本](https://mp.weixin.qq.com/s/y8fTkBEpAdZ5IOe6gv9tQQ)
- **发布日期**：2024-12-09 13:01  
- **所属合集**：#SRE  
- **摘要**：本次更新重点优化和扩展了《5 故障应急》章节内容：新增了 B 站和蚂蚁在Qcon上海SRE专场上分享的两个案例。并根据实际需求，调整“应用服务 SLI/SLO/SLA” “重大技术保障”章节至本章，并在后者新增《OPPO 春节业务保障》案例  



## #Tech

### [OpenAI 【2024 年 12 月 11 日】停服事件复盘](https://mp.weixin.qq.com/s/l3jXly81SiPco-FfESeXFA)
- **发布日期**：2024-12-15 08:05  
- **所属合集**：#Tech News  
- **摘要**：这篇事后分析详细描述了 2024 年 12 月 11 日发生的一起事件，当时所有 OpenAI 服务都经历了显著的停机时间。问题源于一个新的遥测服务部署，该服务无意中压垮了 Kubernetes 控制平面，导致关键系统出现连锁故障。  

### [归还一座岛屿导致“ .io ”顶级域名面临消失风险，从而影响海量网站和软件 - 让我们一探这可能的黑天鹅事件](https://mp.weixin.qq.com/s/6NA4tSM8HmazhNLIDpItcQ)
- **发布日期**：2024-10-21 08:31  
- **所属合集**：#Tech News  
- **摘要**：英国将归还一座岛屿给毛里求斯，这是好事，但是却可能导致“.io ”顶级域名面临消失，而这又会影响到数以百万计的网站和软件，你们准备好了吗？  

### [喜大普奔 - 国内可以直接下载 Docker 官方镜像了！！！](https://mp.weixin.qq.com/s/w6Jdx2ZvRxEQouu6-FS84w)
- **发布日期**：2024-09-10 12:30  
- **所属合集**：#Docker #Tech News  
- **摘要**：实测可以下载镜像了  

### [老万> 深度吐槽CrowdStrike事故报告](https://mp.weixin.qq.com/s/POvdJDr-KFCGwg2XQXWGaA)
- **发布日期**：2024-08-11 18:20  
- **所属合集**：#Tech News  
- **摘要**：我们从 CrowdStrike 史无前例的事故中能学到什么？  

### [新范式：AIGC推动的数据要素产业价值促进创新](https://mp.weixin.qq.com/s/LCJJimv_rQ7eYsHwUNyzzQ)
- **发布日期**：2024-07-26 08:30  
- **所属合集**：#Tech News  
- **摘要**：大模型的发展与数据要素的价值创造互为因果，LLM正推动着数据要素以“激发AGI”的全新范式创造价值。  

### [阿里云 11.12 事故报告：【AK 异常】](https://mp.weixin.qq.com/s/O1gUArqUlCFBe__S1OpPFw)
- **发布日期**：2023-11-16 08:17  
- **所属合集**：#杂项 #Tech News  
- **摘要**：事情暂时告一段落，期望阿里云能够持续改进，认真对待好员工、技术、客户，这样才能成为一家伟大的公司！  

### [语雀 23 日故障带给我们的启示](https://mp.weixin.qq.com/s/26cm0QUfoea7PVtxi8Lqng)
- **发布日期**：2023-10-24 21:42  
- **所属合集**：#杂项 #Tech News  
- **摘要**：1024祝大家：代码零 bug，IT 基础设施无故障，国家国泰民安！  



## #cpu

### [CPU 虚拟化](https://mp.weixin.qq.com/s/XLay0qoKr-UeXMyw9kVEpg)
- **发布日期**：2024-07-22 08:50  
- **所属合集**：#虚拟化 #cpu  
- **摘要**：CPU 虚拟化是系统虚拟化技术中最核心的部分，因为 CPU 是计算机中最核心的组件，直接控制着整个系统的运行，同时内存访问（内存虚拟化）与 I/O 操作（I/O 虚拟化）也都直接依赖于 CPU，因此 CPU 虚拟化是系统虚拟化技术中的核心。  

### [【深度】操作系统技术实践：解读 CPU 隔离](https://mp.weixin.qq.com/s/ZUjAZt4ZNFBMDmbh-dFVRg)
- **发布日期**：2024-07-21 09:30  
- **所属合集**：#Linux #cpu  
- **摘要**：CPU 隔离是一组强大的功能，可以为那些依赖特定且通常对延迟或性能有极端要求的工作负载设置提供支持。  

### [125 张大图诠释 CPU 40年发展简史（至2007年4月）](https://mp.weixin.qq.com/s/WQXevmZ0LjfgQ7JjnkfsjA)
- **发布日期**：2024-07-01 19:20  
- **所属合集**：#cpu  
- **摘要**：CPU 是现代计算机的核心部件，对于 PC 而言，CPU 的规格与频率常常被用来作为衡量一台电脑性能强弱重要指标。Intel x86 架构已经经历了 28 个年头，而 x86 架构的 CPU 对我们大多数人的工作、生活影响颇为深远。  

### [通用 CPU 性能基准测试研究综述](https://mp.weixin.qq.com/s/rauCUcbDtwHCepeB6BpmYg)
- **发布日期**：2024-04-24 19:31  
- **所属合集**：#Linux #系统可观测性 #cpu  
- **摘要**：今天我们就来看一篇论文《通用 CPU 性能基准测试研究综述》，讨论一下 CPU 性能测试应该如何做。  

### [【转载】主流CPU性能比较（Hygon7280、Intel、AMD、鲲鹏920、飞腾2500）](https://mp.weixin.qq.com/s/x_TqZlvgyDiwU8rdphgizA)
- **发布日期**：2024-04-20 22:01  
- **所属合集**：#cpu #Linux  
- **摘要**：本文在Sysbench、TPCC等实践场景下对多款CPU的性能进行对比，同时分析各款CPU的硬件指标，最后分析不同场景下的实际性能和核心参数的关系。  

### [Linux 基础知识：CPU Usage 和 System Load 的关系](https://mp.weixin.qq.com/s/gkLNZLcEW8tyanbcT8y0Zw)
- **发布日期**：2024-03-25 12:15  
- **所属合集**：#Linux #cpu  
- **摘要**：CPU 密集型应用，大量进程在等待或使用 CPU，此时 CPU 使用率与平均负载呈正相关状态。
I/O 密集型应用，大量进程在等待 I/O，此时平均负载会升高，但 CPU 使用率不一定很高。  

### [Kubernetes 内存和 CPU 排错 - CPU 节流和 OOM](https://mp.weixin.qq.com/s/WEC9G3inhzle_aeeXkNDtA)
- **发布日期**：2024-02-25 11:02  
- **所属合集**：#Kubernetes #cpu  
- **摘要**：使用 Kubernetes 时，内存不足 (OOM) 错误和 CPU 限制是资源处理的主要难题。我们可以做到事先的监控，事后的分析，并最终通过历史数据合理调整容器的 request 和 limit  

### [Linux 基础知识 - CPU 上下文切换](https://mp.weixin.qq.com/s/Tls0gCGn12qRGh2m3fBdEQ)
- **发布日期**：2024-02-20 08:15  
- **所属合集**：#Linux #cpu  
- **摘要**：CPU 上下文切换 ，就是先把前一个任务的 CPU 上下文（也就是 CPU 寄存器和程序计数器）保存起来，然后加载新任务的上下文到这些寄存器和程序计数器，最后再跳转到程序计数器所指的新位置，运行新任务。  



## #deepseek

### [上海人工智能实验室开源工具 MinerU 助力复杂 PDF 高效解析提取](https://mp.weixin.qq.com/s/toz-sSNV7_t3mgFTxCEBgw)
- **发布日期**：2025-03-04 08:15  
- **所属合集**：#deepseek #LLM  
- **摘要**：MinerU 是一款开源智能文档解析工具，专注于将 PDF、网页、电子书等多模态内容转换为结构化数据（如 Markdown、JSON），支持 AI 训练、知识管理、RAG（检索增强生成）等场景。  

### [深入探索：AI 驱动的 PDF 布局检测引擎源代码解析](https://mp.weixin.qq.com/s/NPKjONTcLCUfMUGr4mc_wQ)
- **发布日期**：2025-03-03 08:15  
- **所属合集**：#LLM #deepseek  
- **摘要**：Marker 能够将 `PDF`、`EPUB` 和 `MOBI` 文件转换成 `Markdown` 格式。它的转换速度比 `nougat` 快 10 倍，准确度更高，且几乎没有误解风险。  

### [Deepseek 3FS（ Fire-Flyer File System）设计笔记](https://mp.weixin.qq.com/s/B_5xdV2gl9APcJyBuBuUgQ)
- **发布日期**：2025-03-01 10:40  
- **所属合集**：#Linux #deepseek #分布式系统  
- **摘要**：Fire-Flyer File System (3FS) 是一种高性能分布式文件系统，旨在解决 AI 训练和推理工作负载的挑战。它利用现代 SSD 和 RDMA 网络来提供共享存储层，从而简化分布式应用程序的开发。  

### [Hello, DeepSeek Open Infra!](https://mp.weixin.qq.com/s/UzlIZR3i7nKbzE3lvE3nNQ)
- **发布日期**：2025-02-24 11:10  
- **所属合集**：#LLM #deepseek  
- **摘要**：没有任何虚假信息，只有【真诚的代码】，推动着我们微小却雄心勃勃的梦想不断前行。  

### [过年八天乐 - 读者来信：请问7b阅读分析不同中医古籍的能力怎么样？可以进行专项训练大幅度提高这方面能力么？](https://mp.weixin.qq.com/s/scomZshsZFK8Ul8rtmBWow)
- **发布日期**：2025-01-31 10:40  
- **所属合集**：#deepseek #LLM  
- **摘要**：请问7b阅读分析不同中医古籍的能力怎么样？可以进行专项训练大幅度提高这方面能力么？  

### [过年八天乐 - DeepSeek 1.5b、7b 和官网模型快速对比](https://mp.weixin.qq.com/s/MbVoImyvvKuTxhceqeviCA)
- **发布日期**：2025-01-30 09:15  
- **所属合集**：#deepseek #LLM  
- **摘要**：在昨天的文章（过年八天乐 - 在 Mac 上运行 DeepSeek-R1 模型）中，我们通过 ollma 在本地运行了 deepseek-r1:1.5b 模型，今天让我们对比一下 1.5b、7b 和官网模型。  

### [过年八天乐 - 在 Mac 上运行 DeepSeek-R1 模型](https://mp.weixin.qq.com/s/nnIsTZSaC6nNeVRZ7g7epw)
- **发布日期**：2025-01-29 13:35  
- **所属合集**：#LLM #deepseek  
- **摘要**：本教程将指导你在 Mac 上使用 Ollama 运行 DeepSeek-R1，并介绍如何通过 Open-WebUI 提供 Web 端访问。  



## #云原生

### [云原生应用生命周期管理：OAM 介绍](https://mp.weixin.qq.com/s/yby9j21KJpoMeNkEZjh55A)
- **发布日期**：2025-01-16 08:35  
- **所属合集**：#Kubernetes #云原生  
- **摘要**：Open Application Model是一个云原生应用的开放标准规范，其核心理念是“以应用为中心”，实现应用描述与基础设施的解耦。通过这种方式，OAM 为开发者提供了更高的关注点抽象，帮助他们专注于应用逻辑，而不必陷入底层技术的复杂性  

### [云原生应用生命周期管理：主从架构 MySQL 案例解析](https://mp.weixin.qq.com/s/XnEx5IiybadQpBoie9iyWw)
- **发布日期**：2025-01-14 08:05  
- **所属合集**：#云原生 #Kubernetes  
- **摘要**：Kubernetes 的 Deployment 和 StatefulSet 适合无状态微服务，但在处理复杂分布式应用（如主从架构的 MySQL）时，原生资源难以满足拓扑管理、故障恢复和动态配置等高级需求。此时就需要使用Operator模式。  

### [云原生应用生命周期管理：需求分析](https://mp.weixin.qq.com/s/T-cR63-Kb6xD0zhgsUYtwA)
- **发布日期**：2025-01-12 23:15  
- **所属合集**：#Kubernetes #云原生  
- **摘要**：本文将从需求分析的角度，探讨云原生应用生命周期管理的必要性，并结合云原生应用的需求和 Kubernetes 工作负载的局限性。除此之外，本文还将根据作者多年在 PaaS 平台的工作经验，提出应用生命周期管理的一级功能和二级功能定义。  

### [技术分享预告](https://mp.weixin.qq.com/s/qSJfz6TC7SfQVBGd4POxNw)
- **发布日期**：2022-10-15 20:08  
- **所属合集**：#云原生 #Kubernetes  
- **摘要**：《Edge Cloud Operations_A System Approach》，《Kubernetes in Action 2nd Edition》，《Patterns of Distributed Systems》，总有一款你喜欢！  

### [【转载】kubernetes 弹性伸缩指南](https://mp.weixin.qq.com/s/Qh1wwyVKkZPQfFcBAM2IAA)
- **发布日期**：2021-06-13 15:30  
- **所属合集**：#云原生 #Kubernetes  
- **摘要**：一文成为 Kubernetes 弹性伸缩的专家，知其然，知其所以然！  

### [一文全掌握 Kubernetes Operator 精髓](https://mp.weixin.qq.com/s/_wGNSJw4pp35z0liq1vNag)
- **发布日期**：2020-11-06 10:32  
- **所属合集**：#云原生  
- **摘要**：Operators 是一种打包，部署和管理 kubernetes 应用的一种方法，一文带你全掌握 Kubernetes Operator 精髓  



## #分布式系统

### [读《数据密集型应用系统设计》，学分布式系统～！](https://mp.weixin.qq.com/s/gH8FvAxuQKwc1HvOleyoLw)
- **发布日期**：2025-03-06 08:15  
- **所属合集**：#分布式系统 #好书推荐  
- **摘要**：《数据密集型应用系统设计》这本书对与「数据」相关的知识点进行了深入剖析、整理和总结。它从宏观层面阐述了各项技术的共性与差异，并将底层原理讲解得透彻清晰。理解了这些原理后，我们就能明白每项技术的诞生背景、所要解决的问题以及适用场景。  

### [送书了 - 《数据密集型应用系统设计》](https://mp.weixin.qq.com/s/I8RWdzAJu7lTlta1BC5blQ)
- **发布日期**：2025-03-05 08:15  
- **所属合集**：#分布式系统 #好书推荐  
- **摘要**：《数据密集型应用系统设计》，英文名称是《Designing Data-Intensive Application》 ，也被简称为 DDIA。这是一本神书，豆瓣评分高达 9.7 分。  

### [Deepseek 3FS（ Fire-Flyer File System）设计笔记](https://mp.weixin.qq.com/s/B_5xdV2gl9APcJyBuBuUgQ)
- **发布日期**：2025-03-01 10:40  
- **所属合集**：#Linux #deepseek #分布式系统  
- **摘要**：Fire-Flyer File System (3FS) 是一种高性能分布式文件系统，旨在解决 AI 训练和推理工作负载的挑战。它利用现代 SSD 和 RDMA 网络来提供共享存储层，从而简化分布式应用程序的开发。  

### [极客时间《大数据经典论文解读》：建立你的大数据知识网络](https://mp.weixin.qq.com/s/DSg8FqdE1cwTVDxxjbOUcA)
- **发布日期**：2024-12-18 12:30  
- **所属合集**：#大数据 #分布式系统  
- **摘要**：大数据领域的知识地图涵盖了分布式系统、单节点存储引擎和计算引擎。分布式系统需满足可靠性、可扩展性和可维护性，涉及主从架构、复制策略和分片策略等。这些技术相互关联，需要综合考虑组成原理、算法和数据结构、数据库原理等知识。  

### [领导者和追随者（Leader and Followers）](https://mp.weixin.qq.com/s/0fhT6ILnbJJndfvOOSHIPg)
- **发布日期**：2023-04-08 23:27  
- **所属合集**：#分布式系统  
- **摘要**：分布式系统最经典的角色 - 领导者和追随者概述  

### [分布式模式 - 固定分区](https://mp.weixin.qq.com/s/5PgS5zfOfuV3wIMim7T2GQ)
- **发布日期**：2022-10-29 10:58  
- **所属合集**：#分布式系统 #基础知识  
- **摘要**：保持分区数量固定，以便在集群大小发生变化时保持数据到分区的映射不变。  

### [一致性核心（Consistent Core）](https://mp.weixin.qq.com/s/MxUzYlq6OXl2Qnbbg8bs-A)
- **发布日期**：2022-10-23 09:43  
- **所属合集**：#分布式系统  
- **摘要**：分布式系统模式 - 一致性核心：维护一个较小的核心系统，为大规模数据集群提供更强的一致性，这样，可以在无需实现基于 Quorum 算法的前提下协调各服务的行为。  

### [分布式系统的模式（译）](https://mp.weixin.qq.com/s/0wq85NMk5qh5vVqJGfmetw)
- **发布日期**：2022-10-16 09:00  
- **所属合集**：#分布式系统 #基础知识  
- **摘要**：《分布式系统模式》是 Unmesh Joshi 编写的一系列关于分布式系统实现的文章。这个系列的文章采用模式的格式，介绍了分布式系统在设计与实现的过程中采用的通用模式，是学习分布式系统实现的基础。  



## #南京大学

### [一文搞清楚操作系统中的锁](https://mp.weixin.qq.com/s/2H1-7Iiuxyp3uWNEItqJ8g)
- **发布日期**：2024-05-06 12:35  
- **所属合集**：#Linux #南京大学  
- **摘要**：本文介绍了操作系统中锁的原理以及实现，包括一些硬件支持（更加强大的指令）和
一些操作系统支持（例如 Solaris 的 park() 和 unpark() 原语，Linux 的 futex ）。  

### [原力注入 - 2023年文章合集](https://mp.weixin.qq.com/s/AYvZXojGjEvdmgJRywAvbQ)
- **发布日期**：2023-12-30 10:00  
- **所属合集**：#南京大学  
- **摘要**：学而时习之，不亦说乎，感觉以前看得多，但是总结的少，从2023年11月底开始，坚持学习，笔耕不辍，与大家共同进步！  

### [致敬 Turbo Pascal，致敬 Borland，致敬逝去的青春](https://mp.weixin.qq.com/s/LaZVP-8cg0Xq8qR6zXSUwQ)
- **发布日期**：2023-12-05 20:11  
- **所属合集**：#南京大学  
- **摘要**：致敬 Turbo Pascal，致敬 Borland！  



## #基础知识

### [【推荐】系统设计面试：内幕指南](https://mp.weixin.qq.com/s/aRKSJmu8qAOpIWVPQUNFSg)
- **发布日期**：2024-08-20 12:35  
- **所属合集**：#基础知识  
- **摘要**：今天推荐一本书《系统设计面试：内幕指南》，目前出版了两卷。精灵王 @Admol 翻译了卷一，大家可以一睹为快！  

### [《分布式系统模式》在线中文翻译版](https://mp.weixin.qq.com/s/xg6gq8Rrk4vqnAeb7Yj3pw)
- **发布日期**：2023-12-14 08:00  
- **所属合集**：#基础知识  
- **摘要**：推荐《分布式系统模式》在线中文翻译版  

### [分布式模式 - 固定分区](https://mp.weixin.qq.com/s/5PgS5zfOfuV3wIMim7T2GQ)
- **发布日期**：2022-10-29 10:58  
- **所属合集**：#分布式系统 #基础知识  
- **摘要**：保持分区数量固定，以便在集群大小发生变化时保持数据到分区的映射不变。  

### [分布式系统的模式（译）](https://mp.weixin.qq.com/s/0wq85NMk5qh5vVqJGfmetw)
- **发布日期**：2022-10-16 09:00  
- **所属合集**：#分布式系统 #基础知识  
- **摘要**：《分布式系统模式》是 Unmesh Joshi 编写的一系列关于分布式系统实现的文章。这个系列的文章采用模式的格式，介绍了分布式系统在设计与实现的过程中采用的通用模式，是学习分布式系统实现的基础。  



## #大数据

### [列式存储的 Repetition Level 与 Definition Level](https://mp.weixin.qq.com/s/BuKKnxm3OmPUPhwx17eddQ)
- **发布日期**：2025-02-25 12:05  
- **所属合集**：#大数据  
- **摘要**：Parquet 的 Repetition Level（重复层级）和 Definition Level（定义层级）是处理嵌套数据结构的关键机制，尤其在列式存储中高效编码和重建复杂数据。  

### [大数据中的「文件格式」vs. 「表格格式」](https://mp.weixin.qq.com/s/4hNp_SagYQRjZewAHheZYw)
- **发布日期**：2025-02-23 08:25  
- **所属合集**：#大数据  
- **摘要**：文件格式用于高效存储和压缩数据，定义字节组织方式；表格格式在其上提供逻辑抽象，方便组织、查询和更新，使 SQL 引擎能将文件集合当作有行和列的表格来执行操作。  

### [大数据基础之 Parquet 文件格式解析](https://mp.weixin.qq.com/s/bMLjLqNLMcAaYrizXGPl5g)
- **发布日期**：2024-12-31 17:40  
- **所属合集**：#大数据 #存储引擎  
- **摘要**：Parquet 是一种开源的列式存储文件格式，专为高效存储和处理大规模数据而设计。它最初由 Apache 软件基金会开发，现已成为大数据生态系统中的重要组成部分。  

### [RocksDB 工作原理入门](https://mp.weixin.qq.com/s/TmsUx-LMbqcLUG-xvOJotA)
- **发布日期**：2024-12-26 16:30  
- **所属合集**：#大数据 #存储引擎  
- **摘要**：RocksDB 的核心数据结构是 “LSM” 树，一种按键排序、分层存储的高效树形结构。LSM 树专为写入密集型场景设计，通过将写入操作集中到内存中，定期批量刷新到磁盘，提升写入性能并优化存储效率。本文将概述 RocksDB 的工作原理。  

### [极客时间《大数据经典论文解读》：建立你的大数据知识网络](https://mp.weixin.qq.com/s/DSg8FqdE1cwTVDxxjbOUcA)
- **发布日期**：2024-12-18 12:30  
- **所属合集**：#大数据 #分布式系统  
- **摘要**：大数据领域的知识地图涵盖了分布式系统、单节点存储引擎和计算引擎。分布式系统需满足可靠性、可扩展性和可维护性，涉及主从架构、复制策略和分片策略等。这些技术相互关联，需要综合考虑组成原理、算法和数据结构、数据库原理等知识。  

### [列式存储 vs 行式存储：它们之间的本质区别在哪里？](https://mp.weixin.qq.com/s/vIRzYLpuG0snTbprINYnRw)
- **发布日期**：2024-12-16 19:15  
- **所属合集**：#大数据 #存储引擎  
- **摘要**：经典论文《Column-Stores vs. Row-Stores: How Different Are They Really?》解读。  

### [理性看待数据库/大数据 on K8s](https://mp.weixin.qq.com/s/tx3rHn1z8ihte1cWb1sZDg)
- **发布日期**：2023-12-06 13:49  
- **所属合集**：#Kubernetes #大数据  
- **摘要**：技术要深入了解，场景要深入理解，尺有所短，寸有所长  



## #大模型

### [LLM 小技巧 - 在 Mac 上运行大语言模型](https://mp.weixin.qq.com/s/ii2I-yRQfeyiqvbkDoIG-g)
- **发布日期**：2024-05-31 13:02  
- **所属合集**：#大模型 #LLM  
- **摘要**：今天我们来介绍一款工具 - GPT4All，可以让我们在本地运行大语言模型，从而可以​体验大语言模型带来的快乐！​  

### [用 Transformers 处理自然语言：创建基于Hugging Face的文本内容处理程序](https://mp.weixin.qq.com/s/PzkEyLnfRiJrOT8lJd-0IA)
- **发布日期**：2024-04-15 08:30  
- **所属合集**：#LLM #大模型  
- **摘要**：今天在寻找 Transformer 学习材料的时候，找到了《Natural Language Processing with Transformers》的开源翻译，如果没有买书的同学可以看一下。  

### [推荐 - 《大模型技术栈》让我们快速建立起大模型知识体系](https://mp.weixin.qq.com/s/cAN8-BqOUiE3TkBEuEENXA)
- **发布日期**：2024-04-14 09:30  
- **所属合集**：#大模型 #LLM  
- **摘要**：LLM 领域算法、技术和工具浩如烟海，而且每天都会涌现新的内容。笔者在互联网搜索的过程中，发现黄志国整理的《大模型技术栈》，可以让我们快速建立起知识体系。  

### [【重磅推荐】大模型基础 - Deep Learning System & AI System](https://mp.weixin.qq.com/s/9t3A7Ygt9yHh3WwbtesRKw)
- **发布日期**：2024-03-04 08:30  
- **所属合集**：#大模型  
- **摘要**：本开源项目主要是跟大家一起探讨和学习人工智能、深度学习的系统设计，而整个系统是围绕着 ZOMI 在工作当中所积累、梳理、构建 AI 系统全栈的内容。  

### [从 Kubernetes Pod 的故障诊断需求评价 K8sGPT 的 Pod analyzer 的实现](https://mp.weixin.qq.com/s/-1dMiOhYQZ-RuzVl73ZeAw)
- **发布日期**：2024-01-07 09:09  
- **所属合集**：#Kubernetes #大模型  
- **摘要**：故障诊断的流程：异常识别 -> 相关数据采集 -> 检查项评估 -> 根因分析  

### [插上 AIGC 翅膀的 Kubernetes AIOps工具 - K8sGPT](https://mp.weixin.qq.com/s/Tes-6S63AsBl6rdbbB2ddQ)
- **发布日期**：2024-01-06 10:32  
- **所属合集**：#Kubernetes #大模型  
- **摘要**：本文我们以 K8sGPT 为例为读者介绍了AIGC + Kubernetes 领域中目前热度比较高的一个工具 - K8sGPT，并通过一个例子做了一个完整的演示。  

### [复旦大学奇书《大规模语言模型：从理论到实践》- 第1章  绪论](https://mp.weixin.qq.com/s/82EXJu3-nFCQ9QLyiDIE_Q)
- **发布日期**：2024-01-05 12:13  
- **所属合集**：#大模型  
- **摘要**：开启来自复旦大学的《大规模语言模型 : 从理论到实践》学习篇，今天带来第一章的内容，介绍大语言模型的前世今生！  

### [从 GPU 池化到 云原生 AI Infra - 附上第四届CID大会明日开启 | 线下+线上参会指南](https://mp.weixin.qq.com/s/9Xkw4xiBSYQtLkop2pj6MA)
- **发布日期**：2023-10-20 20:28  
- **所属合集**：#大模型  
- **摘要**：作为云原生大数据 + AI 领域的深度参与者，星环科技在 2023 年5月份发布了金融大模型“无涯”和大数据  



## #好书推荐

### [MCP、Function Calling 有什么区别？与 AI Agent 有什么关系？](https://mp.weixin.qq.com/s/LF3p1m1qapY1O7JFp-WP4w)
- **发布日期**：2025-04-05 12:20  
- **所属合集**：#智能 Agent #好书推荐 #LLM  
- **摘要**：Function Calling、MCP 以及 AI Agent 是三个密切相关但层级分明的概念。我们可以把这三者类比为“调用指令 → 调度系统 → 自主执行者”，分别解决不同层级的问题。  

### [好书推荐《大模型应用开发极简入门》](https://mp.weixin.qq.com/s/fapHgJtV--lzEDpn5MiSBA)
- **发布日期**：2025-04-04 08:55  
- **所属合集**：#LLM #好书推荐  
- **摘要**：《大模型应用开发极简入门：基于GPT-4和ChatGPT（第2版）》一书为开发者提供了系统化的答案。作为热销2万册的经典升级版，本书不仅是初学者的“最小可用知识”手册，更是进阶者构建复杂AI应用的实战指南。  

### [文本特征向量化：词袋模型、Word2Vec 以及 TF-IDF 介绍](https://mp.weixin.qq.com/s/Djw5GiPbvYmS1M5yBIWEMw)
- **发布日期**：2025-03-28 08:15  
- **所属合集**：#机器学习 #好书推荐  
- **摘要**：在自然语言处理（NLP）领域，计算机无法直接理解文本信息，因此需要将文本转换为数值向量，以便进行后续的分析和计算。这一过程被称为文本特征向量化。常见的文本向量化方法包括词袋模型（BoW）、TF-IDF 以及Word2Vec  

### [《精通特征工程》：让数据真正为模型赋能](https://mp.weixin.qq.com/s/iblZE9Rz6pd0P8GiF8y7Rg)
- **发布日期**：2025-03-27 19:15  
- **所属合集**：#机器学习 #好书推荐  
- **摘要**：引言在机器学习的世界里，数据决定了模型的上限，算法只是无限逼近这个上限。这句话深刻揭示了数据和特征工程的核心地位。  

### [大模型量化技术（Quantization）可视化指南](https://mp.weixin.qq.com/s/8ABfKytTXp78ZTOWyoT0yw)
- **发布日期**：2025-03-18 19:15  
- **所属合集**：#好书推荐 #LLM  
- **摘要**：大型语言模型的规模通常过于庞大，难以在消费级硬件上运行。这类模型的参数量可达数十亿级别，通常需要配备大容量显存的GPU来加速推理过程。为此，越来越多的研究聚焦于通过优化训练方式、引入适配器等技术缩小模型规模。其中一项关键技术便是量化。  

### [读《数据密集型应用系统设计》，学分布式系统～！](https://mp.weixin.qq.com/s/gH8FvAxuQKwc1HvOleyoLw)
- **发布日期**：2025-03-06 08:15  
- **所属合集**：#分布式系统 #好书推荐  
- **摘要**：《数据密集型应用系统设计》这本书对与「数据」相关的知识点进行了深入剖析、整理和总结。它从宏观层面阐述了各项技术的共性与差异，并将底层原理讲解得透彻清晰。理解了这些原理后，我们就能明白每项技术的诞生背景、所要解决的问题以及适用场景。  

### [送书了 - 《数据密集型应用系统设计》](https://mp.weixin.qq.com/s/I8RWdzAJu7lTlta1BC5blQ)
- **发布日期**：2025-03-05 08:15  
- **所属合集**：#分布式系统 #好书推荐  
- **摘要**：《数据密集型应用系统设计》，英文名称是《Designing Data-Intensive Application》 ，也被简称为 DDIA。这是一本神书，豆瓣评分高达 9.7 分。  

### [好书推荐 - 《分布式系统应用设计》](https://mp.weixin.qq.com/s/ovopXcjXO-7ky35V36hW6g)
- **发布日期**：2025-01-25 21:07  
- **所属合集**：#Kubernetes #好书推荐  
- **摘要**：容器及编排系统的快速发展革新了分布式系统的开发与部署方式，为核心开发模式及容器化组件提供全新接口。《分布式系统应用设计》手册聚焦常见设计模式，助力开发者高效构建可靠分布式系统。  

### [好书推荐 - 《信息存储与管理（第二版）：数字信息的存储、管理和保护》](https://mp.weixin.qq.com/s/FqzDvywg6JLgpDD4rq5ItQ)
- **发布日期**：2025-01-21 19:35  
- **所属合集**：#Linux #好书推荐  
- **摘要**：该书脱胎于 EMC 与麻省理工学院合作开发的《信息基础架构技术》课程，既保留了原课程的系统性，又新增了符合中国《网络安全法》的合规实践指南。作为中国存储领域首部体系化教材，它至今仍是笔者案头必备的技术参考书。  

### [FUSE 文件系统 - 使用 securefs 实现文件系统透明加解密](https://mp.weixin.qq.com/s/A1iF_qEoQ5RYT7n75PZ9xg)
- **发布日期**：2025-01-17 08:35  
- **所属合集**：#Linux #好书推荐  
- **摘要**：为了满足应用程序对敏感数据安全存储的需求，本文使用 securefs 实现了透明的数据加密与解密功能，确保应用程序在无需额外改动的情况下，能够自动处理数据的加密与解密。同时整个方案以容器化的方式运行，进一步增强了部署的便捷性与安全性。  

### [好书推荐：软件设计的哲学（第二版）](https://mp.weixin.qq.com/s/bQ1J-i-Z6uM1Kx8Z1uDBBg)
- **发布日期**：2024-12-31 17:40  
- **所属合集**：#好书推荐  
- **摘要**：这是一本关于软件设计的书（英文原名：A Philosophy of Software Design）：如何将复杂的软件系统分解成模块（比如类和方法），以便这些模块可以相对独立地实现。  

### [好书推荐 - 《深入理解 Linux 网络》](https://mp.weixin.qq.com/s/crZ29epWXF6_HP0GKtXDUQ)
- **发布日期**：2024-03-30 10:46  
- **所属合集**：#好书推荐 #Linux #网络基础知识  
- **摘要**：本书对 Linux 网络建立连接，收发包流程等相关知识的一个概览与总结，贴近实战，适合帮助大家快速入门。  

### [新书推荐 - 《边缘云部署与运营：系统性实现方法》（博主翻译）](https://mp.weixin.qq.com/s/F0c8IKLlCbLJ3OlDVpCoDw)
- **发布日期**：2024-03-16 10:30  
- **所属合集**：#Kubernetes #好书推荐  
- **摘要**：本书以 Aether 平台为例，从边缘云整个平台的架构设计到每个子系统的构建与运维做了细致的阐述，使得读者可以比较全面地了解边缘云的建设与运维，浅显易懂。  

### [好书推荐 - 《自己动手写 docker》](https://mp.weixin.qq.com/s/cpL3Y-UUzeqdYdrOOLH2NA)
- **发布日期**：2024-03-15 12:04  
- **所属合集**：#Docker #好书推荐  
- **摘要**：本书在详细分析Docker所依赖的技术栈的基础上，一步一步地通过代码实例，让读者可以自己循序渐进地用Go语言构建出一个容器的引擎。  

### [好书推荐 -《Hello 算法》](https://mp.weixin.qq.com/s/fKbmE1BoLb9Iw__HHIVv3Q)
- **发布日期**：2024-03-12 09:45  
- **所属合集**：#好书推荐  
- **摘要**：本项目旨在打造一本开源免费、新手友好的数据结构与算法入门教程。全书采用动画图解，内容清晰易懂、学习曲线平滑，引导初学者探索数据结构与算法的知识地图。源代码可一键运行，帮助读者在练习中提升编程技能，了解算法工作原理和数据结构底层实现。  

### [《BPF 之巅：洞悉Linux系统和应用性能》读书笔记开篇](https://mp.weixin.qq.com/s/PxJN2jXb4CvMD6yckmwJNQ)
- **发布日期**：2023-11-28 07:38  
- **所属合集**：#BPF之巅 #Linux #好书推荐  
- **摘要**：《BPF之巅》一书为我们打开了 Linux 内核大门，可以一窥内核原理和工作机制，为大家的以后的内核开发之旅铺平道路！  



## #存储

### [存储知识拾遗：LVM && Device Mapper](https://mp.weixin.qq.com/s/D64L6h9av3SbMP3XQQ2kFQ)
- **发布日期**：2024-12-19 19:15  
- **所属合集**：#Linux #存储  
- **摘要**：Device Mapper 是由 Linux 内核提供的一个框架，用于将物理块设备映射到更高级别的虚拟块设备。它是逻辑卷管理器（LVM）、软件 RAID 和 dm-crypt 磁盘加密的基础，并提供了其他功能，如文件系统快照。  

### [Linux /dev 目录揭秘](https://mp.weixin.qq.com/s/o6-Gzu5g4l3Rz6Sq6jVhbg)
- **发布日期**：2024-08-01 08:35  
- **所属合集**：#Linux #存储  
- **摘要**：Linux 是一个类 Unix 操作系统，其中一项重要的特性就是一切皆文件。/dev 目录是 Linux 文件系统的重要组成部分，用于存放设备文件。设备文件代表系统中的硬件设备，通过这些文件，用户可以以文件的方式访问硬件。  

### [【原理篇】《BPF性能之巅》如何快速分析系统的 I/O 瓶颈？](https://mp.weixin.qq.com/s/QtYQ-vLjCXUVF4pbbGtwgQ)
- **发布日期**：2024-03-19 19:30  
- **所属合集**：#BPF之巅 #Linux #存储  
- **摘要**：我们应该使用什么样的方法和工具，来“快准狠”地定位系统的 I/O 瓶颈呢？本文是原理篇，后续还会陆续推出实战篇。  

### [好文推荐 - RAID 技术介绍](https://mp.weixin.qq.com/s/9635XVMA6-kbr2sSGjKH5w)
- **发布日期**：2024-03-03 09:28  
- **所属合集**：#存储  
- **摘要**：RAID 的基本思想是将多个容量较小、相对廉价的磁盘进行有机组合，从而以较低的成本获得与昂贵大容量磁盘相当的容量、性能、可靠性。  

### [Linux 基础知识 - LVM 逻辑卷管理器介绍](https://mp.weixin.qq.com/s/Wu6zo4OCGt93lZVPwavALQ)
- **发布日期**：2024-02-04 19:20  
- **所属合集**：#Linux #存储  
- **摘要**：LVM 是逻辑卷管理（Logical Volume Manager）的简称，它是 Linux 环境下对磁盘分区进行管理的一种机制。LVM通过在硬盘和文件系统之间添加一个逻辑层，来为文件系统屏蔽下层硬盘分区布局，提高硬盘分区管理的灵活性。  



## #存储引擎

### [大数据基础之 Parquet 文件格式解析](https://mp.weixin.qq.com/s/bMLjLqNLMcAaYrizXGPl5g)
- **发布日期**：2024-12-31 17:40  
- **所属合集**：#大数据 #存储引擎  
- **摘要**：Parquet 是一种开源的列式存储文件格式，专为高效存储和处理大规模数据而设计。它最初由 Apache 软件基金会开发，现已成为大数据生态系统中的重要组成部分。  

### [RocksDB 工作原理入门](https://mp.weixin.qq.com/s/TmsUx-LMbqcLUG-xvOJotA)
- **发布日期**：2024-12-26 16:30  
- **所属合集**：#大数据 #存储引擎  
- **摘要**：RocksDB 的核心数据结构是 “LSM” 树，一种按键排序、分层存储的高效树形结构。LSM 树专为写入密集型场景设计，通过将写入操作集中到内存中，定期批量刷新到磁盘，提升写入性能并优化存储效率。本文将概述 RocksDB 的工作原理。  

### [列式存储 vs 行式存储：它们之间的本质区别在哪里？](https://mp.weixin.qq.com/s/vIRzYLpuG0snTbprINYnRw)
- **发布日期**：2024-12-16 19:15  
- **所属合集**：#大数据 #存储引擎  
- **摘要**：经典论文《Column-Stores vs. Row-Stores: How Different Are They Really?》解读。  



## #应用上云

### [应用上云 - Azure 官方 Java 容器化策略文档](https://mp.weixin.qq.com/s/U5KEB7mRMF7aXeAkmage-g)
- **发布日期**：2024-02-26 12:01  
- **所属合集**：#Kubernetes #应用上云 #Java  
- **摘要**：本文介绍了用于容器化 Java 应用程序以部署到 Kubernetes 上的建议策略。  

### [Java Spring 应用如何更好地在 Kubernetes 上运行？](https://mp.weixin.qq.com/s/3KWOFsA89AV9G20yzT2nDA)
- **发布日期**：2024-01-20 09:15  
- **所属合集**：#应用上云 #Kubernetes #Java  
- **摘要**：nan  

### [Kubernetes：如何实现应用零宕机？](https://mp.weixin.qq.com/s/wmxXuCSfDAFpA5o04XlXbA)
- **发布日期**：2024-01-08 12:14  
- **所属合集**：#Kubernetes #应用上云  
- **摘要**：只要注意这几点，我们就能利用 Kubernetes 来实现应用的零宕机。  

### [Kubernetes 上运行 Spring 生产应用的注意事项](https://mp.weixin.qq.com/s/yADIyAlpVxYUC3XaZogLKA)
- **发布日期**：2024-01-01 10:00  
- **所属合集**：#应用上云 #Kubernetes  
- **摘要**：​我们学习容器技术，最终目的还是为了使用​容器技术。而 Spring 应用，是目前被广泛使用的业务开发框架，作者将新开一个系列来介绍应用​在 Kubernetes 生产化运行的注意事项和最佳实践。  



## #旅游

### [非常科幻 - 超级镜子发电站](https://mp.weixin.qq.com/s/aEVwu-ysK5bsBCREJkvObg)
- **发布日期**：2024-06-25 12:00  
- **所属合集**：#旅游  
- **摘要**：敦煌100兆瓦熔盐塔式光热电站就运用了最先进的CSP技术建造而成。发电站装备了1.2万多面定日镜，以同心圆状围绕着260米高的吸热塔，镜场总反射面积达140多万平方米，设计年发电量达3.9亿千瓦时。  



## #智能

### [LangChain + 模型上下文协议（MCP）：AI 智能体 Demo](https://mp.weixin.qq.com/s/D5d3F3xKeqstBataPBVbFA)
- **发布日期**：2025-04-07 20:18  
- **所属合集**：#智能 Agent #LLM  
- **摘要**：在基于大语言模型构建应用时，一个核心痛点是数据与工具的接入困难。模型虽然能力强大，但通常处于“沙盒”状态，无法直接访问外部环境。为此，RAG、微调、插件等方案陆续诞生。而MCP的目标正是统一接口协议，以便标准化集成上下文、工具、服务与数据源  

### [MCP、Function Calling 有什么区别？与 AI Agent 有什么关系？](https://mp.weixin.qq.com/s/LF3p1m1qapY1O7JFp-WP4w)
- **发布日期**：2025-04-05 12:20  
- **所属合集**：#智能 Agent #好书推荐 #LLM  
- **摘要**：Function Calling、MCP 以及 AI Agent 是三个密切相关但层级分明的概念。我们可以把这三者类比为“调用指令 → 调度系统 → 自主执行者”，分别解决不同层级的问题。  

### [Cline 55k 系统提示词刷新了我对提示词工程的认知](https://mp.weixin.qq.com/s/aYi7SnAzqDV93lwZxiCDIw)
- **发布日期**：2025-04-03 19:24  
- **所属合集**：#智能 Agent  
- **摘要**：该系统的核心价值在于将复杂的开发环境操作抽象为标准化工具集，通过严谨的流程控制和安全机制，使AI能在真实开发环境中可靠执行任务。其设计平衡了灵活性与安全性，特别适合作为AI辅助开发的基础平台。  

### [【转载】MCP（Model Context Protocol）全面研究报告：概念、实践与未来趋势](https://mp.weixin.qq.com/s/iRHqxurMx72xg5YRS4VzPA)
- **发布日期**：2025-04-02 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：模型上下文协议（Model Context Protocol，简称MCP）是Anthropic于2024年推出的一种开放标准，旨在规范AI模型与外部数据源、工具之间的交互方式。  

### [大模型时代，智能体崛起：从技术解构到工程落地的全栈指南 ——《大模型技术30讲》](https://mp.weixin.qq.com/s/bNH2HaN1GJPyHTftg62Erg)
- **发布日期**：2025-03-15 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：《大模型技术30讲》这本书如同一座桥梁，连接起了学术理论与工程实践的两岸，为工程师们提供了一套全面且深入的技术知识体系和实践指导。它不仅详细阐述了Transformer架构背后的数学原理，还构建了一条从单卡调试到大规模集群部署的完整工程路径  

### [AI Agents for Beginners 课程之 AI Agent及使用场景简介](https://mp.weixin.qq.com/s/XpBYMTKj4j7CT-N_xkKvBg)
- **发布日期**：2025-03-12 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：AI Agents for Beginners是一门由微软提供的课程，旨在帮助初学者全面了解 `AI Agent` 的构建与应用。课程涵盖的基础概念、开发框架、设计模式、工具使用、可信赖构建、规划、多智能体系统、元认知以及生产环境部署等内容  



## #机器学习

### [【极客时间】零基础实战机器学习 - RFM 模型在用户消费行为分析中的应用](https://mp.weixin.qq.com/s/gpEvWgVYwHHTmkB4ZfGllg)
- **发布日期**：2025-03-29 09:15  
- **所属合集**：#机器学习  
- **摘要**：在数字化时代，理解用户行为是企业制定精准运营策略的关键。因此，将行为转化为可量化的指标，成为企业洞察用户特征、优化运营决策的第一步。在众多分析方法中，RFM模型（Recency、Frequency、Monetary）是被广泛采用的经典工具。  

### [文本特征向量化：词袋模型、Word2Vec 以及 TF-IDF 介绍](https://mp.weixin.qq.com/s/Djw5GiPbvYmS1M5yBIWEMw)
- **发布日期**：2025-03-28 08:15  
- **所属合集**：#机器学习 #好书推荐  
- **摘要**：在自然语言处理（NLP）领域，计算机无法直接理解文本信息，因此需要将文本转换为数值向量，以便进行后续的分析和计算。这一过程被称为文本特征向量化。常见的文本向量化方法包括词袋模型（BoW）、TF-IDF 以及Word2Vec  

### [《精通特征工程》：让数据真正为模型赋能](https://mp.weixin.qq.com/s/iblZE9Rz6pd0P8GiF8y7Rg)
- **发布日期**：2025-03-27 19:15  
- **所属合集**：#机器学习 #好书推荐  
- **摘要**：引言在机器学习的世界里，数据决定了模型的上限，算法只是无限逼近这个上限。这句话深刻揭示了数据和特征工程的核心地位。  

### [动手学机器学习层次聚类算法](https://mp.weixin.qq.com/s/9qM0hB_7kwfSa_gAW7-tNg)
- **发布日期**：2025-03-21 08:15  
- **所属合集**：#机器学习  
- **摘要**：层次聚类算法是一种重要的聚类分析方法，它通过构建一个层次结构（树形结构）来表示数据之间的相似性或距离关系。与划分聚类方法（如K-Means）不同，层次聚类无需预先指定聚类的类别数量，这使得它在某些特定场景下具有独特的优势。  

### [动手学机器学习 Kmeans 聚类算法](https://mp.weixin.qq.com/s/4UwH6GxcjeZF6bgObjhrGQ)
- **发布日期**：2025-03-20 19:15  
- **所属合集**：#机器学习  
- **摘要**：Kmeans 算法是聚类算法中的一种，其基本思想是将数据集划分为 K 个簇，每个簇由其质心（centroid）表示。算法通过迭代优化的方式，使得每个样本被分配到最近的质心所在的簇，并不断更新质心的位置，直到达到收敛条件。  

### [动手学机器学习随机森林算法](https://mp.weixin.qq.com/s/Rj2WwD96HAI5yqnOGjt8JA)
- **发布日期**：2025-03-16 08:25  
- **所属合集**：#机器学习  
- **摘要**：随机森林是一种集成学习方法，它通过构建多个决策树并将其结果进行整合，利用降低方差的策略提高模型的泛化能力，从而减少过拟合风险。随机森林就像是一个由许多棵决策树组成的 “森林”，每棵树都是独立生长的，最终的预测结果是综合所有树的输出得出的。  

### [动手学机器学习朴素贝叶斯算法](https://mp.weixin.qq.com/s/Vd5gibkU3oeHURSm63lphQ)
- **发布日期**：2025-03-14 08:15  
- **所属合集**：#机器学习  
- **摘要**：朴素贝叶斯算法基于贝叶斯定理和特征条件独立性假设，通过计算后验概率进行分类。尽管独立性假设在现实中可能不完全成立，但该算法在许多实际应用中仍能取得较好的效果，尤其在文本分类等任务中表现突出。  

### [动手学机器学习逻辑回归算法](https://mp.weixin.qq.com/s/sy5nu3jtJ81yIT6i03n7Tg)
- **发布日期**：2025-03-13 08:15  
- **所属合集**：#机器学习  
- **摘要**：逻辑回归是一种广为人知且应用广泛的算法。尽管它的名字中包含 “回归”，但它实际上主要用于分类任务，尤其是二分类问题。所谓二分类问题，就是我们要将数据划分为两个互斥的类别，例如判断一封邮件是否为垃圾邮件，或者预测一个患者是否有某种疾病。  

### [动手学机器学习支持向量机](https://mp.weixin.qq.com/s/xg3LsueOdGyniZmibgB2Lw)
- **发布日期**：2025-03-12 08:15  
- **所属合集**：#机器学习  
- **摘要**：支持向量机（Support Vector Machine，简称 SVM）是一种监督学习算法，主要用于分类和回归任务。其核心思想是通过寻找一个最优的超平面，将不同类别的数据点尽可能宽地分开，这个超平面在高维空间中起到分类决策边界的作用。  

### [动手学线性回归算法](https://mp.weixin.qq.com/s/3W72yBZ3YjfVXjCKZHF_Ug)
- **发布日期**：2025-03-11 08:15  
- **所属合集**：#机器学习  
- **摘要**：在统计学中，线性回归（linear regression）是利用称为线性回归方程的最小二乘函数对一个或多个自变量和因变量之间关系进行建模的一种回归分析。这种函数是一个或多个称为回归系数的模型参数的线性组合。  

### [分类模型评估工具 - 混淆矩阵](https://mp.weixin.qq.com/s/B8Ogm3mnzQzzL-gofMdq3Q)
- **发布日期**：2025-03-10 08:15  
- **所属合集**：#机器学习  
- **摘要**：混淆矩阵（Confusion Matrix）是评估分类模型性能的重要工具，尤其适用于二分类问题，但也可扩展至多分类。它通过统计模型预测结果与真实结果的对应关系，直观展示分类模型的优势和不足。  

### [动手学决策树算法](https://mp.weixin.qq.com/s/oduSu4oFpum82Tf7LlZnag)
- **发布日期**：2025-03-08 09:15  
- **所属合集**：#机器学习  
- **摘要**：决策树是一种监督学习算法，广泛应用于分类和回归任务。它通过递归地分裂数据集，将数据分成越来越小的子集，直到达到某种停止条件。每个内部节点表示一个特征或属性，每个分支表示一个决策规则，每个叶节点表示一个类别或预测值。  

### [KNN 算法简介](https://mp.weixin.qq.com/s/o3gMk515fp5abW4yjG9UmQ)
- **发布日期**：2025-03-07 12:35  
- **所属合集**：#机器学习  
- **摘要**：K 近邻（K-Nearest Neighbors，KNN）是一种基本的机器学习算法，广泛应用于分类和回归任务。它的核心思想是：“物以类聚”，即如果一个数据点在特征空间中与某些已知类别的数据点靠得很近，那么它很可能属于这些数据点所属的类别。  

### [DeepSeek Open Infra 开源五天乐及好书《动手学机器学习》推荐](https://mp.weixin.qq.com/s/pgwpndnu0vUru7r4qTgTJw)
- **发布日期**：2025-02-26 10:10  
- **所属合集**：#LLM #机器学习  
- **摘要**：DeepSeek Open Infra 开源五天乐及好书《动手学机器学习》推荐  

### [啤酒与尿布的故事，以及背后的 Apriori 算法](https://mp.weixin.qq.com/s/5WgVQtWIV6UMNDJLqGv6kA)
- **发布日期**：2025-02-22 08:31  
- **所属合集**：#机器学习  
- **摘要**：关联分析（关联规则学习): 从大规模数据集中寻找物品间的隐含关系被称作关联分析(associati analysis)或者关联规则学习（association rule learning），APriori 算法则是常用的算法。  



## #杂项

### [【转载】独立开发变现（搞钱）周刊](https://mp.weixin.qq.com/s/L76Q5VxocehgnRD35VKTCw)
- **发布日期**：2024-08-17 08:35  
- **所属合集**：#杂项  
- **摘要**：搞技术的同时，可以思考一下如何将技术变现。今天正好读到一个周刊，感觉可以了解一下，说不一定可以复制。  

### [不要盲目刷 LeetCode，要巧用编码模式](https://mp.weixin.qq.com/s/epBmZJ3mJo41Uw_bbgQlQA)
- **发布日期**：2024-07-14 09:01  
- **所属合集**：#CS #杂项  
- **摘要**：无论大家是否喜欢，LeetCode 类型的问题几乎是每次编程面试的一部分，因此每个软件开发人员都应该在面试前练习它们。大家唯一的选择是明智地准备并通过关注底层问题模式来学习解决问题。​  

### [阿里云 11.12 事故报告：【AK 异常】](https://mp.weixin.qq.com/s/O1gUArqUlCFBe__S1OpPFw)
- **发布日期**：2023-11-16 08:17  
- **所属合集**：#杂项 #Tech News  
- **摘要**：事情暂时告一段落，期望阿里云能够持续改进，认真对待好员工、技术、客户，这样才能成为一家伟大的公司！  

### [语雀 23 日故障带给我们的启示](https://mp.weixin.qq.com/s/26cm0QUfoea7PVtxi8Lqng)
- **发布日期**：2023-10-24 21:42  
- **所属合集**：#杂项 #Tech News  
- **摘要**：1024祝大家：代码零 bug，IT 基础设施无故障，国家国泰民安！  

### [Homebrew 飞起 - 清华镜像站使用步骤](https://mp.weixin.qq.com/s/dIDnBVPky1lXfjQbghx-8g)
- **发布日期**：2023-05-10 08:01  
- **所属合集**：#杂项  
- **摘要**：用清华镜像站的宝库，让你的 mac 用起 homebrew 飞起～！  



## #模型

### [SearchGPT 来了](https://mp.weixin.qq.com/s/3lHmpHhBDqVcjpdWetNzAA)
- **发布日期**：2024-07-26 08:30  
- **所属合集**：#模型  
- **摘要**：OpenAI 发布了一个新产品：SearchGPT，一个新搜索功能的原型，可以利用ChatGPT 大模型的优势，提供更清晰和更相关的答案。

有兴趣的同学可以到 「https://chatgpt.com/search」 加入等待 list，有更多信息的时候，笔者第一时间搬回来告诉大家！  



## #系统可观测性

### [鲲鹏性能优化十板斧](https://mp.weixin.qq.com/s/gf851jn1I6lA4JOp0aS6tw)
- **发布日期**：2025-01-01 15:35  
- **所属合集**：#Linux #系统可观测性  
- **摘要**：本文系统介绍了鲲鹏芯片性能优化的常用方法与工具，从 CPU 与内存子系统、网络子系统、磁盘 IO 子系统及应用程序优化四方面展开，内容详实，可作为系统性能优化的实用参考手册！  

### [文件性能测试工具 IOzone 使用简介](https://mp.weixin.qq.com/s/gEB-sbPOuELTQITeFnaqzg)
- **发布日期**：2024-12-29 14:01  
- **所属合集**：#Linux #系统可观测性  
- **摘要**：IOzone 是一款用于文件系统性能基准测试的开源工具。它可以帮助用户评估文件系统在不同操作模式下的性能，特别是用于磁盘 I/O 操作。IOzone 支持多种操作系统，并提供了多种测试模式来测量不同类型的文件操作性能.  

### [Linux Slab 内存管理机制简介](https://mp.weixin.qq.com/s/Nk32Asrd7nJTk6zH19vfpg)
- **发布日期**：2024-12-28 11:45  
- **所属合集**：#Linux #系统可观测性  
- **摘要**：Slab 层通过向内核申请完整的页（Page），然后对这些页进行精细化管理，从而高效分配和回收小型内存块。通过这种方式，Slab 不仅优化了小对象的内存利用率，还显著降低了分配和销毁的开销。  

### [性能调优：学无止境](https://mp.weixin.qq.com/s/b8_A2sSL6SRvRyGR5824IA)
- **发布日期**：2024-12-27 07:15  
- **所属合集**：#系统可观测性 #BPF之巅  
- **摘要**：《BPF之巅》则为读者们打开了 Linux 的内核大门，可以一窥内核原理和深入了解工作机制，为大家的以后的内核开发之旅铺平道路。  

### [Linux 小技巧 - 使用 smem 了解内存使用情况](https://mp.weixin.qq.com/s/W0dEXBR0oRuWKD0J9EbN9A)
- **发布日期**：2024-11-29 14:22  
- **所属合集**：#Linux 小技巧 #Linux #系统可观测性  
- **摘要**：smem 是一个命令行工具，它报告每个进程的内存使用情况，与主要显示 RSS 的 top 或 htop 不同，smem 还可以显示 USS，这是评估终止特定进程将释放多少内存的更好指标。  

### [可观察性 vs 监控「双语」](https://mp.weixin.qq.com/s/x59QhSycx9pt3t2l1E569g)
- **发布日期**：2024-08-15 08:35  
- **所属合集**：#系统可观测性  
- **摘要**：如今，大多数应用软件都采用多个微服务并采用分布式架构，因此获取对系统全面了解的需求不容小觑。这就是“监控”和“可观测性”这两个术语发挥作用的地方。  

### [BPF 入门学习资料汇总](https://mp.weixin.qq.com/s/Oey5nSht88CR5zxUjYjDCQ)
- **发布日期**：2024-06-14 09:01  
- **所属合集**：#系统可观测性  
- **摘要**：今天有读者想学习 BPF，因此作者将一些常用的资料做了一个汇总，供大家参考！  

### [使用 lstopo 查看服务器逻辑拓扑结构](https://mp.weixin.qq.com/s/0H-Oa3SEI6IPDFn7L9uAyw)
- **发布日期**：2024-04-28 22:33  
- **所属合集**：#系统可观测性 #Linux  
- **摘要**：本文介绍了使用 hwloc 工具查看服务器的逻辑拓扑，帮助我们深入了解服务器的硬件结构，以便更好地进行性能调优。  

### [通用 CPU 性能基准测试研究综述](https://mp.weixin.qq.com/s/rauCUcbDtwHCepeB6BpmYg)
- **发布日期**：2024-04-24 19:31  
- **所属合集**：#Linux #系统可观测性 #cpu  
- **摘要**：今天我们就来看一篇论文《通用 CPU 性能基准测试研究综述》，讨论一下 CPU 性能测试应该如何做。  

### [《BPF 性能之巅》- 使用 perf tools 定位磁盘 IO util 高问题](https://mp.weixin.qq.com/s/6SZlT2WVmytOAgz_RbsqEw)
- **发布日期**：2024-03-19 19:30  
- **所属合集**：#BPF之巅 #系统可观测性  
- **摘要**：本文的目标是通过现有工具来回答一个我们经常会遇到的一个问题：sd* 设备上哪些进程的 IO 操作比较多？这些进程在做什么样的文件操作？  

### [使用 iodump 一步定位磁盘 IO Util 高的元凶](https://mp.weixin.qq.com/s/NPaWbokAulLMOnx63Gb1Sg)
- **发布日期**：2024-03-19 19:30  
- **所属合集**：#系统可观测性  
- **摘要**：odump 是利用内核 tracepoint 静态探针点技术实现的一个 IO 问题排查工具，可以一步到位帮我定位磁盘 IO util 高背后的元凶！  

### [《性能之巅》系统可观测性综述](https://mp.weixin.qq.com/s/4oMVi37EnZg2RXfhsl5teA)
- **发布日期**：2024-03-18 19:30  
- **所属合集**：#系统可观测性 #BPF之巅  
- **摘要**：本文是对系统可观测性做了概述，介绍了相关概念和方法。  

### [《BPF 性能之巅》- 使用 perf tools 做性能分析（1）](https://mp.weixin.qq.com/s/dXw_6-zi19XuvJEnbZuz4w)
- **发布日期**：2024-03-17 09:00  
- **所属合集**：#BPF之巅 #系统可观测性  
- **摘要**：本文的目标是通过现有工具来回答一个我们经常会遇到的一个问题：sd* 设备上哪些进程的 IO 操作比较多？这些进程在做什么样的文件操作？  

### [好文推荐 - 掌握 Linux 内存故障追踪：技术指南](https://mp.weixin.qq.com/s/upeMRdmGLQYmXgizmz06Ng)
- **发布日期**：2024-03-01 22:30  
- **所属合集**：#系统可观测性 #Linux  
- **摘要**：掌握 Linux 内存故障追踪：技术指南  

### [性能分析实战篇 - Linux 网络性能优化指南](https://mp.weixin.qq.com/s/ou8DW6nst1bhPy-dtwNzXQ)
- **发布日期**：2024-02-27 08:31  
- **所属合集**：#系统可观测性 #网络基础知识  
- **摘要**：我们先来了解一下网络基础，然后了解一下 Linux 网络栈以及网络性能分析方法，最后再来看几个常见的网络优化实操。  

### [【实战篇】使用火焰图定位 jbd2进程导致系统负载高问题](https://mp.weixin.qq.com/s/8DgCgJvhMETtzIq2570-uA)
- **发布日期**：2024-02-02 09:15  
- **所属合集**：#BPF之巅 #系统可观测性  
- **摘要**：我们可以使用火焰图定位 jbd2进程导致系统负载高问题  

### [Linux 性能分析课程推荐](https://mp.weixin.qq.com/s/KlJKkWwa3DLXsurTb8tRmQ)
- **发布日期**：2024-01-21 00:06  
- **所属合集**：#系统可观测性  
- **摘要**：Linux 性能分析课程推荐  

### [Linux 可观测性 - 你真的了解 Linux Load Average 吗？](https://mp.weixin.qq.com/s/MKOj8xdsG6mihuDT7Gd25A)
- **发布日期**：2024-01-21 00:06  
- **所属合集**：#Linux #系统可观测性  
- **摘要**：Linux Load Average：算法、实现与实用指南  

### [Linux 性能分析课程推荐](https://mp.weixin.qq.com/s/7nX5mhfnDnYt4FBe-mHXZA)
- **发布日期**：2024-01-20 09:15  
- **所属合集**：#系统可观测性  
- **摘要**：Linux 性能分析课程推荐  

### [《可观测性成熟度模型白皮书》解读](https://mp.weixin.qq.com/s/Sogg_KgPpSpU1HLGJ0mqZw)
- **发布日期**：2023-12-31 10:00  
- **所属合集**：#系统可观测性  
- **摘要**：什么是可观测性呢？可观测性解决了什么问题？《可观测性成熟度模型白皮书》为可观测性建设提供了一个指导路径，当然了笔者认为螺旋上升（围绕业务目标五个等级同步建设）是实现业务连续性的最佳做法  



## #网络基础知识

### [深入理解 Linux Bond：原理与实践](https://mp.weixin.qq.com/s/J0h_i3BwrIX0wtjAub3t6g)
- **发布日期**：2025-01-20 12:35  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：nan  

### [网络收发路径上的一些冷知识 - 参数单位](https://mp.weixin.qq.com/s/6--GJA3sGWekk-hUleBmAg)
- **发布日期**：2024-12-14 11:52  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：在网络调优和排查过程中，了解各种参数及其单位的意义至关重要，因此本文将对常见的参数及其单位进行说明。  

### [Linux 网络优化：RPS 和 RFS 技术概述](https://mp.weixin.qq.com/s/QhsFzATYJDGblSbnNxxVDQ)
- **发布日期**：2024-12-12 12:35  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：RPS和RFS是Linux内核中的两种技术，它们优化网络数据包处理性能，特别是在多核处理器和高吞吐量场景中。这些技术通过将数据包分配到不同的CPU核心上，改善负载均衡并减少缓存未命中。  

### [快速了解 TCP 连接的 11 种状态及其转换](https://mp.weixin.qq.com/s/Bjq39k78p9uliudcIW0T9Q)
- **发布日期**：2024-12-10 19:10  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：本文意在用简短的文字总结一下 TCP 的 11 种状态及其转换过程。  

### [Linux 网络参考书籍推荐](https://mp.weixin.qq.com/s/-GaqOPQr-nRxZ5gdo1SiFw)
- **发布日期**：2024-12-06 12:30  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：推荐笔者看过的 Linux 网络相关的书单，分为四大类：网络七层协议、Linux 内核中的网络栈与收发路径、Linux 网络编程及高性能编程、Linux 网络性能分析与调优，适合不同角色的人员参考。  

### [网络协议分析神器 - tcpdump 简介及抓取 HTTP Header 实战](https://mp.weixin.qq.com/s/vmat80PacZbGfKfCZ8g9Vw)
- **发布日期**：2024-11-17 10:05  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：tcpdump 网络嗅探器，将强大和简单结合到一个单一的命令行界面中，能够将网络中的报文抓取，输出到屏幕或者记录到文件中。本文列举了一些常用的命令，并例举了一个在容器网络中抓取 HTTP Header 的实战，供读者参考！  

### [I/O 多路复用与网络服务器并发策略](https://mp.weixin.qq.com/s/3Zvo_48wVNI747M9dIrJaw)
- **发布日期**：2024-11-14 19:05  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：目前主流的网络服务器，网络 I/O 相关的底层最核心的技术都是 I/O 多路复用。本文尝试解释各种 I/O 模型，同时也总结 I/O 多路复用底层的系统调用 select、poll、kqueue 和 epoll 的演进和区别，并辅以代码！  

### [来自《Broadcom 以太网网络适配器用户指南》中提到的「 Linux 命令」](https://mp.weixin.qq.com/s/R3IQZJwjlMH5Qtqlcj1g2Q)
- **发布日期**：2024-11-01 08:31  
- **所属合集**：#网络基础知识 #Linux  
- **摘要**：来自《Broadcom 以太网网络适配器用户指南》中提到的「 Linux 命令」  

### [Linux 网络收发包路径简介](https://mp.weixin.qq.com/s/fSYzPfG2tjJ1hD8uWp39Ug)
- **发布日期**：2024-10-31 13:01  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：为了最终写作《网络性能探案惊奇：三步揪出 CPU 软中断一直处于 100%的元凶》，今天先来介绍一下 Linux 网络收发包路径，并重点讲解收包路径。  

### [容器技术回顾：消失的 Docker 网络命名空间](https://mp.weixin.qq.com/s/mciucLzKH8wAIoxuQyze1A)
- **发布日期**：2024-09-12 08:30  
- **所属合集**：#Linux #Docker #网络基础知识  
- **摘要**：从命名空间伪文件列表中，我们可以看到此进程的 net 文件的存在。由于 net 文件对应于 Linux 网络命名空间，因此我们可以预期它会在列出所有网络命名空间时显示出来。但是，我们可以看到事实并非如此。  

### [《Linux 网络编程》第四章进程间通信（4）- System V IPC](https://mp.weixin.qq.com/s/mDzQDCapwQ5fnwqn6sy6BA)
- **发布日期**：2024-07-12 09:05  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：消息队列（Message Queues），信号量（semaphores）和共享内存（shared memory），统称为 System V IPC。在 Linux 系统编程中，它们有着广泛的应用。  

### [《Linux 网络编程》第四章进程间通信（3）- 文件和记录锁定](https://mp.weixin.qq.com/s/1xehQj1mgXXzds3rob4UYA)
- **发布日期**：2024-07-05 09:00  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：《Linux 网络编程》第四章进程间通信（3）- 文件和记录锁定  

### [Kubernetes 网络和 Cilium：网络工程师手册](https://mp.weixin.qq.com/s/EU32HV8h6qZ57OUWUVhPPg)
- **发布日期**：2024-06-22 10:00  
- **所属合集**：#Kubernetes #网络基础知识  
- **摘要**：Cilium 是业界较早采用 BPF 技术的 Kubernetes CNI，今天推荐由它发布的一本网络小册子，让我们来看看它们视角的 Kunernetes 网络。  

### [【Kubernetes 网络】好书推荐](https://mp.weixin.qq.com/s/4YQXZgqMYCaJGS4ZRZJwig)
- **发布日期**：2024-06-13 12:40  
- **所属合集**：#Kubernetes #网络基础知识  
- **摘要**：看了昨天“强烈推荐：《Container Networking: From Docker to Kubernetes》中文翻译”还意犹未尽，想再深入了解的同学，可以读一下文中推荐的两本书！  

### [《Linux 网络编程》第四章进程间通信（2）- 管道](https://mp.weixin.qq.com/s/TkqSFtHF92pesXr8SrTv3A)
- **发布日期**：2024-06-06 08:45  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：管道就是将一个程序的输出和另外一个程序的输入连接起来的单向通道。它是UNIX/Linux 系统的各种进程通信方法中，最古老而应用最为广泛的一种（特别是在 shell 中）.  

### [《Linux 网络编程》第四章进程间通信（1）- 信号](https://mp.weixin.qq.com/s/LbXABLAHu6fXTYxce71wEg)
- **发布日期**：2024-06-03 12:05  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：今天介绍一下 Linux 进程间通信的方法一信号。  

### [Linux 网络基础知识 - 网络命名空间动手实践（一）](https://mp.weixin.qq.com/s/gGoNphKCxU3ZZvzQzT0PTA)
- **发布日期**：2024-05-30 12:40  
- **所属合集**：#网络基础知识  
- **摘要**：网络命名空间是 Linux Kernel 提供的用于实现网络虚拟化的核心，它能创建多个隔离的网络空间，该网络空间内的防火墙、网卡、路由表、邻居表、协议栈与外部独立，不管是虚拟机还是容器，当运行在独立的命名空间时，就像是一台单独的物理主机  

### [补几张 VXLAN 的图](https://mp.weixin.qq.com/s/DjRHn6DVJIG20HtLRQFBdA)
- **发布日期**：2024-05-29 12:31  
- **所属合集**：#Linux #网络基础知识 #虚拟化  
- **摘要**：补几张 VXLAN 的图，细化一下相关概念。  

### [Linux 网络基础知识 - VXLAN 原理介绍](https://mp.weixin.qq.com/s/WJ6d0eie0yKZvECvLygcDw)
- **发布日期**：2024-05-28 12:30  
- **所属合集**：#Linux #网络基础知识 #虚拟化  
- **摘要**：VXLAN（Virtual eXtensible Local Area Network ）就是一种基于虚拟交换机实现的 overlay 网络。本文介绍了为什么需要 VXLAN 、 VXLAN 的基本原理以及基于 Linux 内核的实现。  

### [Linux 基础知识 - 一文学会网络虚拟化](https://mp.weixin.qq.com/s/Sn1ql5Pa5rBc7_C7QPqZbg)
- **发布日期**：2024-05-26 10:00  
- **所属合集**：#Linux #网络基础知识  
- **摘要**：Linux 网络虚拟化技术包含了网络命名空间以及各类虚拟设备，如 veth、Bridge、tap/tun 等。这些虚拟设备模拟现实世界中的物理设备彼此协作，将各个独立的网络命名空间连接起来，构建出不受物理环境约束的各类动态网络拓扑架构。  

### [Kubernetes 网络和安全简介（一）](https://mp.weixin.qq.com/s/lVG1pYqsc2WdZiE57xJDqg)
- **发布日期**：2024-05-23 23:00  
- **所属合集**：#Kubernetes #网络基础知识  
- **摘要**：Calico 背后的公司 TIGERA 出了一本书《Introduction to Kubernetes Networking and Security》，此书难度中等，可以让大家对相关概念或者原理有个初步了解。  

### [好书推荐 - 《深入理解 Linux 网络》](https://mp.weixin.qq.com/s/crZ29epWXF6_HP0GKtXDUQ)
- **发布日期**：2024-03-30 10:46  
- **所属合集**：#好书推荐 #Linux #网络基础知识  
- **摘要**：本书对 Linux 网络建立连接，收发包流程等相关知识的一个概览与总结，贴近实战，适合帮助大家快速入门。  

### [性能分析实战篇 - Linux 网络性能优化指南](https://mp.weixin.qq.com/s/ou8DW6nst1bhPy-dtwNzXQ)
- **发布日期**：2024-02-27 08:31  
- **所属合集**：#系统可观测性 #网络基础知识  
- **摘要**：我们先来了解一下网络基础，然后了解一下 Linux 网络栈以及网络性能分析方法，最后再来看几个常见的网络优化实操。  

### [网络协议知识温故知新](https://mp.weixin.qq.com/s/CXet-aOrBhRZbwr4N0HrRA)
- **发布日期**：2023-09-23 09:13  
- **所属合集**：#网络基础知识  
- **摘要**：云计算的核心技术中，网络无疑是最复杂的。正所谓学而时习之，不亦乐乎！很多时候我们要停下来，温习一下基础知识，  

### [​如何实现一个 Kubernetes 网络插件](https://mp.weixin.qq.com/s/nrZWcftRjrT9um47Y2yQ_g)
- **发布日期**：2021-02-18 08:32  
- **所属合集**：#网络基础知识  
- **摘要**：目前容器的网络解决方案越来越多，每出现一种新的解决方案，都要为网络方案和不同的容器运行时进行适配，这显然是不  

### [Linux 网络大全（四）——用户态](https://mp.weixin.qq.com/s/ec0Kkw1vGlBJj_E_UsmVQA)
- **发布日期**：2020-10-14 13:59  
- **所属合集**：#网络基础知识  
- **摘要**：在前面的章节中，我们已经走完了所有内核部分的网络代码，最后一章就是用户态的部分了  

### [Linux 网络大全（三）——IP+TCP](https://mp.weixin.qq.com/s/a5y8wXri-FGSCG8xViF0tA)
- **发布日期**：2020-10-11 10:00  
- **所属合集**：#网络基础知识  
- **摘要**：从软中断归来，数据开始进入了我们熟悉的协议处理部分  

### [Linux 网络大全（二）——网卡驱动](https://mp.weixin.qq.com/s/NJSdpJw1ncvrSkvZwkRxQg)
- **发布日期**：2020-10-10 10:00  
- **所属合集**：#网络基础知识  
- **摘要**：本文试图从软件的角度解释一个网络请求的今生前世  

### [Kubernetes 网络插件工作原理](https://mp.weixin.qq.com/s/cl5ZbQvSreCi-3KVf5JwPw)
- **发布日期**：2020-10-09 10:00  
- **所属合集**：#网络基础知识  
- **摘要**：容器的网络解决方案有很多种，每支持一种网络实现就进行一次适配显然是不现实的，而 CNI 就是为了兼容多种网络  

### [Linux 网络大全（一）—— 基础知识](https://mp.weixin.qq.com/s/XrAXdIZx0OC3DjrHFACFrQ)
- **发布日期**：2020-09-29 10:53  
- **所属合集**：#网络基础知识  
- **摘要**：这次带大家一起从软件工程师的角度看一看 Linux Network 的全貌  

### [十分钟漫谈容器网络方案01—Flannel](https://mp.weixin.qq.com/s/LiAor_36owbsfIH6Q57FhA)
- **发布日期**：2020-08-25 08:30  
- **所属合集**：#网络基础知识  
- **摘要**：在《Docker和Kubernetes的前世今生（下）》中我们介绍了作为目前主流的容器编排系统，Kubern  

### [Kubernetes 入门之网络详解](https://mp.weixin.qq.com/s/HH-hsaM6VxNoj4ZaotgPaA)
- **发布日期**：2018-09-24 20:38  
- **所属合集**：#网络基础知识  
- **摘要**：祝大家中秋快乐~好好学习，天天向上！  



## #虚拟化

### [系统虚拟化导论](https://mp.weixin.qq.com/s/HaPeiKMjYB3pRaeHxMCfqw)
- **发布日期**：2024-07-23 08:50  
- **所属合集**：#虚拟化  
- **摘要**：什么是虚拟化？狭义地说，大家在日常生活中说到的虚拟化主要指的还是 虚拟机 （Virtual Machine），即通过虚拟化技术将一台计算机虚拟为多台逻辑计算机——这其实是虚拟化技术中的一个抽象粒度为单个计算机的分支：系统虚拟化！  

### [CPU 虚拟化](https://mp.weixin.qq.com/s/XLay0qoKr-UeXMyw9kVEpg)
- **发布日期**：2024-07-22 08:50  
- **所属合集**：#虚拟化 #cpu  
- **摘要**：CPU 虚拟化是系统虚拟化技术中最核心的部分，因为 CPU 是计算机中最核心的组件，直接控制着整个系统的运行，同时内存访问（内存虚拟化）与 I/O 操作（I/O 虚拟化）也都直接依赖于 CPU，因此 CPU 虚拟化是系统虚拟化技术中的核心。  

### [补几张 VXLAN 的图](https://mp.weixin.qq.com/s/DjRHn6DVJIG20HtLRQFBdA)
- **发布日期**：2024-05-29 12:31  
- **所属合集**：#Linux #网络基础知识 #虚拟化  
- **摘要**：补几张 VXLAN 的图，细化一下相关概念。  

### [Linux 网络基础知识 - VXLAN 原理介绍](https://mp.weixin.qq.com/s/WJ6d0eie0yKZvECvLygcDw)
- **发布日期**：2024-05-28 12:30  
- **所属合集**：#Linux #网络基础知识 #虚拟化  
- **摘要**：VXLAN（Virtual eXtensible Local Area Network ）就是一种基于虚拟交换机实现的 overlay 网络。本文介绍了为什么需要 VXLAN 、 VXLAN 的基本原理以及基于 Linux 内核的实现。  



## Agent

### [LangChain + 模型上下文协议（MCP）：AI 智能体 Demo](https://mp.weixin.qq.com/s/D5d3F3xKeqstBataPBVbFA)
- **发布日期**：2025-04-07 20:18  
- **所属合集**：#智能 Agent #LLM  
- **摘要**：在基于大语言模型构建应用时，一个核心痛点是数据与工具的接入困难。模型虽然能力强大，但通常处于“沙盒”状态，无法直接访问外部环境。为此，RAG、微调、插件等方案陆续诞生。而MCP的目标正是统一接口协议，以便标准化集成上下文、工具、服务与数据源  

### [MCP、Function Calling 有什么区别？与 AI Agent 有什么关系？](https://mp.weixin.qq.com/s/LF3p1m1qapY1O7JFp-WP4w)
- **发布日期**：2025-04-05 12:20  
- **所属合集**：#智能 Agent #好书推荐 #LLM  
- **摘要**：Function Calling、MCP 以及 AI Agent 是三个密切相关但层级分明的概念。我们可以把这三者类比为“调用指令 → 调度系统 → 自主执行者”，分别解决不同层级的问题。  

### [Cline 55k 系统提示词刷新了我对提示词工程的认知](https://mp.weixin.qq.com/s/aYi7SnAzqDV93lwZxiCDIw)
- **发布日期**：2025-04-03 19:24  
- **所属合集**：#智能 Agent  
- **摘要**：该系统的核心价值在于将复杂的开发环境操作抽象为标准化工具集，通过严谨的流程控制和安全机制，使AI能在真实开发环境中可靠执行任务。其设计平衡了灵活性与安全性，特别适合作为AI辅助开发的基础平台。  

### [【转载】MCP（Model Context Protocol）全面研究报告：概念、实践与未来趋势](https://mp.weixin.qq.com/s/iRHqxurMx72xg5YRS4VzPA)
- **发布日期**：2025-04-02 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：模型上下文协议（Model Context Protocol，简称MCP）是Anthropic于2024年推出的一种开放标准，旨在规范AI模型与外部数据源、工具之间的交互方式。  

### [大模型时代，智能体崛起：从技术解构到工程落地的全栈指南 ——《大模型技术30讲》](https://mp.weixin.qq.com/s/bNH2HaN1GJPyHTftg62Erg)
- **发布日期**：2025-03-15 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：《大模型技术30讲》这本书如同一座桥梁，连接起了学术理论与工程实践的两岸，为工程师们提供了一套全面且深入的技术知识体系和实践指导。它不仅详细阐述了Transformer架构背后的数学原理，还构建了一条从单卡调试到大规模集群部署的完整工程路径  

### [AI Agents for Beginners 课程之 AI Agent及使用场景简介](https://mp.weixin.qq.com/s/XpBYMTKj4j7CT-N_xkKvBg)
- **发布日期**：2025-03-12 08:15  
- **所属合集**：#LLM #智能 Agent  
- **摘要**：AI Agents for Beginners是一门由微软提供的课程，旨在帮助初学者全面了解 `AI Agent` 的构建与应用。课程涵盖的基础概念、开发框架、设计模式、工具使用、可信赖构建、规划、多智能体系统、元认知以及生产环境部署等内容  



## Infra

### [GPU 利用率(Utilization) 是一个误导性指标!](https://mp.weixin.qq.com/s/dUhxU3QBnZ4kUMBzxrmC_w)
- **发布日期**：2025-04-08 19:15  
- **所属合集**：#CUDA #GPU #AI Infra  
- **摘要**：评估GPU使用时，许多人首看利用率，但它并不等于性能高。例如仅内存读写也会让GPU Util达100%，因此不能简单类比CPU Util，需结合更多指标（例如 SM Efficiency 和 MFU）全面判断。  

### [原力注入：AI Infra 知识体系（Body of knowledge for AI Infra) v1.1](https://mp.weixin.qq.com/s/nMgHwGYb9vVBx0g9EpNNoQ)
- **发布日期**：2024-11-03 15:31  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：经过这半年的学习和整理，笔者也逐步构建了笔者心中的 AI Infra 知识体系（Body of knowledge for AI Infra），供大家参考，今天推出了 1.1 版本！  

### [CUDA Processing Streams](https://mp.weixin.qq.com/s/Hm1PZ4rZe7GbOp2xtFPgdA)
- **发布日期**：2024-10-22 08:31  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：结合代码示例来深入学习 CUDA Stream 编程。  

### [AI Infra - CUDA 并发编程之 Stream 简介](https://mp.weixin.qq.com/s/mXvQ1Xo1E4BUzA4q_dPDUw)
- **发布日期**：2024-10-18 22:51  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：CUDA streams 是 CUDA 编程中用来管理并发执行的单元，在一个流中，操作是串行的按序执行的，但是在不同的流中操作就可以同时执行，从而完成并发操作。  

### [AI Infra - nvtop 快速入门](https://mp.weixin.qq.com/s/0D8UEkSkkpPeCNcHMNhWSA)
- **发布日期**：2024-10-16 19:25  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：nvtop 是一款类似于 htop 的命令行工具，可用于监控 NVIDIA、AMD、Intel 等多种 GPU。它提供了一个直观的界面，可以实时查看和管理 GPU 状态、指标数据。  

### [推荐两本开源 AI 书籍：《动手学深度学习》和《机器学习系统：设计和实现》](https://mp.weixin.qq.com/s/-JcJbpvUOTFx8wdqTYVn9Q)
- **发布日期**：2024-10-15 08:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：推荐两本开源 AI 书：《动手学深度学习》和《机器学习系统：设计和实现》  

### [AI Infra - 集合通信框架 NCCL 概念介绍](https://mp.weixin.qq.com/s/5zk8Se6kZwMdsWQteDbq8Q)
- **发布日期**：2024-10-14 13:02  
- **所属合集**：#AI Infra  
- **摘要**：不同的并行模式下都离不开集合通信技术。集合通信的使用将分布式训练中多个硬件之间的数据通信变得简洁和高效。与此同时，集合通信也成为了分布式机器学习中不可或缺的一部分。  

### [AI Infra - 理解 GPU 架构之 Tesla V100 及 RTX 5000 简介](https://mp.weixin.qq.com/s/5_a1o6tRDMhC8dF__RTJTw)
- **发布日期**：2024-10-07 09:00  
- **所属合集**：#AI Infra  
- **摘要**：理解 GPU 架构之 Tesla V100 及 RTX 5000 简介  

### [AI Infra - 理解 GPU 架构之理解 GPU 特性「双语」](https://mp.weixin.qq.com/s/Agrtq4WqQj01MTlg-dwVlg)
- **发布日期**：2024-10-06 09:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：GPU 的硬件设计优化了高度并行处理。因此，GPU 的程序依赖于像 NVIDIA CUDA 这样的编程模型，与传统的基于CPU的串行编程模型有很大不同，本文就试图对 GPU 的特性进行阐述，帮助读者理解 GPU 和 CPU 的相同点和差异！  

### [原力注入：AI Infra 知识体系（Body of knowledge for AI Infra) v1.0](https://mp.weixin.qq.com/s/ptAdsvO5H34IOFSEwzWlsQ)
- **发布日期**：2024-10-05 17:00  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：经过这半年的学习和整理，笔者也逐步构建了笔者心中的 AI Infra 知识体系（Body of knowledge for AI Infra），供大家参考，后续会持续完善。  

### [AI Infra - 理解 GPU 架构之理解 GPU 内存「双语」](https://mp.weixin.qq.com/s/GEs5ZbStbggtMgwdhOUOWw)
- **发布日期**：2024-10-04 17:15  
- **所属合集**：#AI Infra  
- **摘要**：本文介绍了 GPU 内存层次结构，分析了寄存器、缓存、共享内存和全局内存的作用。与 CPU 相比，GPU 的寄存器文件和共享内存更大，适合并行计算，而 CPU 通过更大的 L1、L2 和 L3 缓存减少主存访问。  

### [深入了解 Nvidia CUDA 核心](https://mp.weixin.qq.com/s/PE3LmOAft27QCQNaaSFY7g)
- **发布日期**：2024-09-30 08:30  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：Nvidia 的 CUDA 核心是 Nvidia 显卡内的专门处理单元，旨在高效处理复杂的并行计算，使其成为高性能计算、游戏和各种图形渲染应用程序中的关键。  

### [AI Infra - 使用 CUDA 代码查询 GPU 卡详细信息](https://mp.weixin.qq.com/s/G6kfoNTdOmyOKQSHt83fHw)
- **发布日期**：2024-09-29 08:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：今天我们就来使用 CUDA 示例代码库提供的 deviceQueryDrv.cpp 示例代码来查询 GPU 卡的详细信息，用于全面了解 GPU 卡的详细特性。  

### [AI Infra - nvidia-smi 快速入门](https://mp.weixin.qq.com/s/Yu4UCprk9HfIMZGsrEOeXA)
- **发布日期**：2024-09-27 08:30  
- **所属合集**：#AI Infra  
- **摘要**：nvidia-smi 是 NVIDIA 驱动提供的命令行工具，能够帮助用户监控和管理 GPU 的状态与行为。本文整理了一些常用的 nvidia-smi 命令，帮助大家快速上手和高效使用。  

### [AI Infra - Nvidia GPU 卡 之 ECC 功能](https://mp.weixin.qq.com/s/nmZVOQAyfFyesm79HzjUlQ)
- **发布日期**：2024-09-25 08:30  
- **所属合集**：#AI Infra  
- **摘要**：nan  

### [AI Infra - Nvidia GPU XID 故障码解析](https://mp.weixin.qq.com/s/ekCnhr3qrhjuX_-CEyx65g)
- **发布日期**：2024-09-21 09:05  
- **所属合集**：#AI Infra  
- **摘要**：XID 信息是 NVIDIA 驱动程序的错误报告，它被打印到操作系统的内核日志或事件日志中。这些信息可能表明 NVIDIA 硬件问题、软件问题或者是用户应用程序的问题。  

### [推荐《CUDA Reading Group 相关讲座》](https://mp.weixin.qq.com/s/6sOrNzG0UeVBes8stWSoWA)
- **发布日期**：2024-07-02 09:00  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：推荐《CUDA Reading Group 相关讲座》，共包含24个讲座，每个讲座有视频以及配套材料，对于 CUDA 编程感兴趣的同学可以深入参考！  

### [深度学习（大模型）中的精度](https://mp.weixin.qq.com/s/b08gFicrKNCfrwSlpsecmQ)
- **发布日期**：2024-06-30 09:00  
- **所属合集**：#AI Infra #LLM  
- **摘要**：当谈到大型模型的训练和推理时，我们经常涉及到精度的概念，而这些精度种类繁多。同等精度级别下，还有不同的格式。笔者收集了几篇文章，供大家参考理解相关概念。  

### [万卡集群背后的系统架构：《NVIDIA DGX SuperPOD：下一代可扩展的AI领导基础设施》](https://mp.weixin.qq.com/s/a64Qb6DuAAZnCTBy8g1p2Q)
- **发布日期**：2024-06-28 09:00  
- **所属合集**：#AI Infra  
- **摘要**：万卡集群背后隐藏的硬件成本有哪些？网络和存储的开销不可被忽略，今天就让我们来读一读《NVIDIA DGX SuperPOD：下一代可扩展的AI领导基础设施》，来深入了解一下万卡集群背后的系统架构！  

### [使用 Nsight 工具定量分析 CUDA 矩阵乘法几种实现](https://mp.weixin.qq.com/s/JK_bsvG-Y3wLJknZ4YKCYQ)
- **发布日期**：2024-06-20 12:15  
- **所属合集**：#CUDA #AI Infra  
- **摘要**：矩阵乘法是大模型训练和推理的重要基础，因此我们需要通过工具定量来分析矩阵乘法，尤其是多级内存的使用效率，本文使用 Nsight 工具定量分析了几种矩阵乘法的实现，基于 Nsight 提供的 Kernel Profiling 能力。  

### [AI Infra 基础知识 - 一文介绍并行计算、费林分类法和 CUDA 基本概念](https://mp.weixin.qq.com/s/NL_Bz8JB-LdAtrQake7EdA)
- **发布日期**：2024-06-11 13:30  
- **所属合集**：#AI Infra #CUDA  
- **摘要**：一文了解并行计算、费林分类法和 CUDA 基本概念，入门基于 CUDA 的 GPGPU 编程！  

### [AI Infra 基础知识 - PCIe 知识大全](https://mp.weixin.qq.com/s/dHvKYcZoa4rcF90LLyo_0A)
- **发布日期**：2024-06-09 10:30  
- **所属合集**：#AI Infra  
- **摘要**：当进入到 AI Infra 的视角之后，我们越来越关注底层的硬件细节，今天就让我们来了解一下 PCI Express 吧！  

### [AI Infra 基础知识 - NVLink 入门](https://mp.weixin.qq.com/s/fP69UEgusOa_X4ZKLo30ig)
- **发布日期**：2024-06-08 11:00  
- **所属合集**：#AI Infra  
- **摘要**：AI Infra 背后是一系列硬件技术，今天我们来了解一下 NVLink。 NVLink 是一种专有系统互连硬件，可促进多个 Nvidia GPU 和支持CPU之间的一致数据和控制传输。  



## News

### [OpenAI 【2024 年 12 月 11 日】停服事件复盘](https://mp.weixin.qq.com/s/l3jXly81SiPco-FfESeXFA)
- **发布日期**：2024-12-15 08:05  
- **所属合集**：#Tech News  
- **摘要**：这篇事后分析详细描述了 2024 年 12 月 11 日发生的一起事件，当时所有 OpenAI 服务都经历了显著的停机时间。问题源于一个新的遥测服务部署，该服务无意中压垮了 Kubernetes 控制平面，导致关键系统出现连锁故障。  

### [归还一座岛屿导致“ .io ”顶级域名面临消失风险，从而影响海量网站和软件 - 让我们一探这可能的黑天鹅事件](https://mp.weixin.qq.com/s/6NA4tSM8HmazhNLIDpItcQ)
- **发布日期**：2024-10-21 08:31  
- **所属合集**：#Tech News  
- **摘要**：英国将归还一座岛屿给毛里求斯，这是好事，但是却可能导致“.io ”顶级域名面临消失，而这又会影响到数以百万计的网站和软件，你们准备好了吗？  

### [喜大普奔 - 国内可以直接下载 Docker 官方镜像了！！！](https://mp.weixin.qq.com/s/w6Jdx2ZvRxEQouu6-FS84w)
- **发布日期**：2024-09-10 12:30  
- **所属合集**：#Docker #Tech News  
- **摘要**：实测可以下载镜像了  

### [老万> 深度吐槽CrowdStrike事故报告](https://mp.weixin.qq.com/s/POvdJDr-KFCGwg2XQXWGaA)
- **发布日期**：2024-08-11 18:20  
- **所属合集**：#Tech News  
- **摘要**：我们从 CrowdStrike 史无前例的事故中能学到什么？  

### [新范式：AIGC推动的数据要素产业价值促进创新](https://mp.weixin.qq.com/s/LCJJimv_rQ7eYsHwUNyzzQ)
- **发布日期**：2024-07-26 08:30  
- **所属合集**：#Tech News  
- **摘要**：大模型的发展与数据要素的价值创造互为因果，LLM正推动着数据要素以“激发AGI”的全新范式创造价值。  

### [阿里云 11.12 事故报告：【AK 异常】](https://mp.weixin.qq.com/s/O1gUArqUlCFBe__S1OpPFw)
- **发布日期**：2023-11-16 08:17  
- **所属合集**：#杂项 #Tech News  
- **摘要**：事情暂时告一段落，期望阿里云能够持续改进，认真对待好员工、技术、客户，这样才能成为一家伟大的公司！  

### [语雀 23 日故障带给我们的启示](https://mp.weixin.qq.com/s/26cm0QUfoea7PVtxi8Lqng)
- **发布日期**：2023-10-24 21:42  
- **所属合集**：#杂项 #Tech News  
- **摘要**：1024祝大家：代码零 bug，IT 基础设施无故障，国家国泰民安！  



## 小技巧

### [AWK 入门教程：强大的文本处理工具](https://mp.weixin.qq.com/s/Gd8U1bL5S5VHTMAs_jsWRQ)
- **发布日期**：2025-01-02 19:15  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：AWK 是一种强大的文本处理工具，广泛用于 Linux/Unix 系统中对文本文件或数据流进行操作。它能够基于条件筛选、统计字段、重新排列数据等。  

### [Linux FUSE 文件系统的相关一些管理操作](https://mp.weixin.qq.com/s/ZVTdSeF-LtsiSvVeLYsubw)
- **发布日期**：2024-12-02 20:00  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：书接上文(Linux 用户态文件系统 FUSE 简介)，大家学习完 FUSE 文件系统后，实操中可能会遇到一些问题，笔者（博主）整理了与 FUSE 文件系统相关的一些管理操作，供大家参考。  

### [Linux 基础知识 - 软链接 vs. 硬链接](https://mp.weixin.qq.com/s/tdVgBAORr3sSzCbxO85EwA)
- **发布日期**：2024-12-01 22:00  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：一文了解 Linux 的硬链接和软链接！  

### [Linux 小技巧 - 使用 smem 了解内存使用情况](https://mp.weixin.qq.com/s/W0dEXBR0oRuWKD0J9EbN9A)
- **发布日期**：2024-11-29 14:22  
- **所属合集**：#Linux 小技巧 #Linux #系统可观测性  
- **摘要**：smem 是一个命令行工具，它报告每个进程的内存使用情况，与主要显示 RSS 的 top 或 htop 不同，smem 还可以显示 USS，这是评估终止特定进程将释放多少内存的更好指标。  

### [Linux 删除文件或者目录时，出现“Operation not permitted” ，如何解决？](https://mp.weixin.qq.com/s/i1irz1t1BfUpd1jjc2r78w)
- **发布日期**：2024-10-24 08:31  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：用户在对文件做删除，移动等操作，会提示 “Operation not permitted“ 错误，无法操作成功，此时我们就需要检查文件属性了！  

### [Linux 小技巧 - 使用 iftop 监控实时端口流量](https://mp.weixin.qq.com/s/4TTBeinb2_xrAZ-f9w3pUA)
- **发布日期**：2024-05-20 23:00  
- **所属合集**：#Linux #Linux 小技巧  
- **摘要**：iftop 是一个用于实时监控网络流量的命令行工具，有可交互图形界面，可以指定网络接口统计实时流量。  

### [Linux 小技巧 - 使用 ab 命令做性能压测](https://mp.weixin.qq.com/s/qHgusLmiVmuocYdb5OxFlg)
- **发布日期**：2024-05-07 12:28  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：ab 是 Apache 自带的压力测试工具，可以对 Web 服务器进行访问压力测试。ab 命令会创建多个并发线程，模拟多个访问者同时对某一个url地址进行访问，实现压力测试。  

### [Linux 小技巧 - SIGTERM 与 SIGKILL：有什么区别？](https://mp.weixin.qq.com/s/RpRHa0nE-aRC_rS8VVdO3g)
- **发布日期**：2024-03-21 19:30  
- **所属合集**：#Linux 小技巧  
- **摘要**：SIGTERM 和 SIGKILL 都用于终止 Linux 中的进程，我们应该有哪个呢？  

### [Linux 小技巧 - 删除大量文件](https://mp.weixin.qq.com/s/g2nIl_P4sS89Rjp4JWf0Pw)
- **发布日期**：2023-11-15 09:33  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：Linux 系统下删除大量文件  

### [一文让你应对Linux 进程“D”状态](https://mp.weixin.qq.com/s/aZgMvNR5_-qoQztMLXxSJw)
- **发布日期**：2023-10-29 22:07  
- **所属合集**：#Linux 小技巧 #Linux  
- **摘要**：进程长时间处于“D”状态，会导致进程无法响应，系统负载升高，最终导致整个系统响应慢甚至无法响应。那我们就来看看 Red hat 官方是如何来处理的吧！  
