# SIG-compliance
简体中文 | [English](./sig_compliance.md)

说明：本SIG的内容遵循OpenHarmony的PMC管理章程 [README](/zh/pmc.md)中描述的约定。
## 概述
随着OpenHarmony社区的蓬勃发展，一方面，开发者向社区提交的代码越来越多；另一方面，社区内引入的第三方开源软件越来越多，这使得OpenHarmony版本发布中带来的潜在合规风险也越来越大，社区当前已经引入或者开发了[开源合规审查工具OAT](https://gitee.com/openharmony-sig/tools_oat)、敏感词扫描工具、片段扫描，棱镜七彩等工具，上解决了基础合规问题，但当前的社区的合规活动中依然存在不少的人为环节和需要大量的人力维护，随着社区规模的上升，这将对社区的合规形成巨大的挑战。因此，我们希望基于OAT的基础上，成立合规SIG，借助SIG组织，加强多方联接与投入，拥抱业界开源最佳实践成果，建立开源合规治理的机制和工程体系，包括标准/规范、流程、装备工具、组织。通过工具和工程方法落地这些规则，提供开源合规治理的解决方案或服务给参与社区的组织和个人。

## SIG组工作目标和范围

### 工作目标
- 建立OpenHarmony的开源合规工程体系
- 拟定OpenHarmony的开源合规治理的规则、规范、流程
- 开发OpenHarmony的开源合规工具
- 提供OpenHarmony的开源合规服务

### 工作范围
本小组首期核心工作聚焦于社区**开源合规治理工程体系及能力的构建**，根据开源软件及社区开发的生命周期，我们将开源合规分为
- **来源可信**  ( 三方开源软件、社区代码贡献）
- **许可证遵从**  ( 三方开源软件许可证兼容、三方开源软件证义务履行、项目许可证)
- **知识产权合规**  ( 版权、专利、商标、术语)
- **版本发布合规**  ( 贸易合规、发布包许可证)

本小组工作**包含**以上分类中
- **工程能力及工具的规划及建设**
- **流程规则的起草及拟定**
- **与社区内及业界组织在工程能力方面协作**
- **合规治理方面最佳实践的引入与对外分享**
- **社区内合规文化与培训**


#### **与开源审查工具OAT项目的关系**：
本小组作为一个伞形项目，包含[开源合规审查工具OAT](https://gitee.com/openharmony-sig/tools_oat)，即OAT是SIG-Compliance中的一个子项目，也是当前最主要的合规审查工具，本小组一方面会持续演进OAT工具，另一方也会引入业界其他最佳实践及工具，将多种能力进行集成，共同打造合规工程体系

#### **与工作委员会下开源合规组的关系**：
原则上，本小组应在开源合规组的指导下完成工程能力的建设，并定期向工作委员会下的开源合规组进行工作汇报

本小组**不包含**
- 社区合规及法务问题的官方口径
- 社区合规及法务问题的最终解释权
- 社区合规治理标准规范的最终审核权


## 代码仓
- 代码仓地址：
  - SIG-Compliance ：https://gitee.com/openharmony/compliance
  - OAT开源审查工具 ：https://gitee.com/openharmony-sig/tools_oat

## SIG组成员

### Leader
- @jalenchen(https://gitee.com/jalenchen)

### Committers列表
- @king-gao (https://gitee.com/king-gao)
- @alec-z (https://gitee.com/alec-z)
- @kubigao (https://gitee.com/kubigao)
- @billwangliang (https://gitee.com/billwangliang)
- @youthdragon (https://gitee.com/youthdragon)
- @jungle8023 (https://gitee.com/jungle8023)
- @yishuangli（https://gitee.com/yishuangli）
- @Rahul Mohan G（rahulmohang@gmail.com）
- @Carlo Piana（ piana@array.eu ）
- @alpianon（https://gitee.com/alpianon） 
- 欢迎加入
### Contributor列表
- 欢迎加入

### 会议
 - 会议时间：公开的会议时间：北京时间，每周五 下午，14:00点~15:00点
 - 会议申报：[OpenHarmony SIG-Compliance Meeting Proposal](https://etherpad.openharmony.cn/p/compliance)
 - 会议链接：[见链接](https://etherpad.openharmony.cn/p/compliance)
 - 会议通知：请[订阅](https://lists.openatom.io/postorius/lists/dev.openharmony.io)邮件列表 dev@openharmony.io 获取会议链接
 - 会议纪要: [归档链接地址](https://gitee.com/openharmony-sig/sig-content)

### 联系方式(可选)

- 邮件列表：dev@openharmony.io
- 邮件列表tag [compliance]
- Zulip群组：https://zulip.openharmony.cn
- 微信群：NA