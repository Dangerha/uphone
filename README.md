<!-- 以下是参考的目录模版，旨在建议产品文档应该包含的内容模块。实际章节划分可根据实际内容进行调整 -->
# 概览

云手机产品主要提供云手机服务器、云手机、手机应用、手机镜像的生命周期管理功能。同时提供Web页面和API调用两种操作方式，用户可批量申购、释放服务器，批量创建、重启云手机，批量上传、安装或卸载云手机应用，对自制的云手机镜像进行批量克隆，以及对服务器和云手机资源负载进行实时监控

#### <center>  [了解](#_1了解)   |   [购买及付费](#_2购买及付费)   |   [云手机相关流程](#_3云手机相关流程)  |   [快速上手](#_4云手机操作指南)  </center>  

## 1.了解

	云手机产品主要提供云手机服务器、云手机、手机应用、手机镜像的生命周期管理功能。同时提供Web页面和API调用两种操作方式，用户可批量申购、释放服务器，批量创建、重启云手机，批量上传、安装或卸载云手机应用，对自制的云手机镜像进行批量克隆，产品支持安卓、iOS和H5多种访问方式

### 功能与优势
#### 即开即玩
无惧终端与场景限制，免下载安装，跨终端游戏进度同步，一个终端所有平台游戏畅玩。
#### 便捷接入
UCloud完善的IaaS资源+合作伙伴PaaS、SaaS能力，集成工业级ARM服务器和工业级GPU渲染等多套技术方案，助力云游戏业务快速成长。
#### 突破算力瓶颈
ARM服务器和GPU渲染，突破传统手机和SoC云手机的硬件瓶颈，客户可基于此设计长期的原生云游戏、元宇宙演进路线。
#### 高灵活度、高利用率
传统SoC（片上系统）架构只能运行2-3个实例，剩余的资源碎片无法使用，而不同帧率和分辨率又无法混跑，进而会产生多种资源池、增大管理复杂度。而ARM服务器架构只需一种规格即可运行所有实例，实例按需使用CPU和GPU资源，多余CPU和GPU算力碎片由内核调度给其他实例使用；而不同分辨率和帧率的实例亦可混跑，实现服务器资源最大利用率，也简化资源管理复杂度。
####  高性能
传统x86 CPU模拟安卓应用的ARM指令会有20-30%开销，还有的采用EmuGL来实现OpenGLES到OpenGL的指令转换，都存在性能损耗大、延迟大、卡顿等体验问题。
UCloud云游戏基于原生ARM CPU、自研安卓虚拟化技术、GPU直通安卓技术、内核调优，高性能运行80-120路游戏。
####  低延迟、低卡顿率、帧率稳定
云游戏最大的延迟是网络延迟，而UCloud十年来深耕云计算领域，具有覆盖全国的机房建设可大幅减少网络传播延迟，而基于GPU直通安卓架构减少渲染延迟，渲染后直接在显存内编码实现零拷贝。加上深度优化RTC减少传输延迟、按键控制和音视频同步延迟，从而将云游戏总增量延迟控制到50ms以内；![img](images/rate.jpg)
####  多数据中心
目前已建设14个三通机房（青岛、镇江、廊坊、杭州、武汉、扬州、娄底、重庆、安顺、沈阳、合肥、咸阳、石家庄、洛阳），100+单线机房，核心数据中心全球有31个

### 应用场景
#### 云手游2C场景
低配玩3A：手游在云端运行，低配手机也能流畅运行大型手游； 不发烫。
客户端：可根据UCloud提供的安卓、iOS、H5等客户端SDK Demo集成到客户的客户端。
调度平台：UCloud提供一站式调度。
#### 云手游2B场景
试玩广告：可将试玩链接嵌入到第三方APP中，将“下载”替换成“试玩”，实现秒级呈现。
微端投放：投放5MB游戏微端下载，也可极大降低下载门槛，进一步引导下载完整客户端，实现游戏获客。
短信推广：短信发送URL，玩家点击URL在微信小程序内可玩游戏，可实现快速传播；也可实现多人同屏。
### [词汇表](/ucgs/_glossary.md)



## 2.购买及付费

* [计费模式](/ucgs/price#计费模式)
* [ARM服务器配置](/ucgs/price#AMR服务器配置)
* [资源删除](/ucgs/price#资源删除)



## 3.云游戏相关流程

传统游戏经过游戏上传、实例创建、SDK开发与上线三步即可轻松接入UCloud云游戏平台，无需对原有的代码做任何的改动即可轻松跨端使用。

  * [云手游2C场景上线流程](/ucgs/user_flow#云手游2C场景上线流程)
  * [云手游微端/H5链接推广流程](/ucgs/user_flow#云手游微端/H5链接推广流程)

