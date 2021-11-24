# 架构风格

[English](./architectural-styles.md) | 简体中文

1. 通常情况下，云服务提供商向用户所提供的服务，往往由这三类用户接口构成：
   - **命令式**（Imperative）的 API 和工具，常常**以动词来描述如何操作某个具体的资源**，例如创建云主机、开/关机等。RESTFul、Action 等常见的 API 架构风格，都是命令式 API 的一个实例。
   - **声明式**（Declarative）的 API 和工具，则**仅需要描述所期望的资源是什么样子**。而具体执行哪些动作，则由工具或平台自动完成。例如Kubernetes Operator、Terraform 等，工具本身往往需要对比当前实际资源状态和期望状态之间的差异，从而自动化地决策和执行一系列的编排逻辑。
   - **交互式（**Interactive）的工具，**通过一系列的交互设计**，以即时响应的渐进式方式，一步一步**靠近用户最终的目标**。例如 API 调试器可以使用户不断地修改参数、发起请求，直到获得用户想要的结果。

![Architectural Styles](../images/architectural-styles.png)

那么这三类架构风格，本质上都是对**「 如何根据用户的意图，使目标系统收敛至符合期望的状态」**这一问题的抽象。相关的研究包括 [Mark Burgess](https://en.wikipedia.org/wiki/Mark_Burgess_(computer_scientist)) 在配置管理领域**关于[收敛算子]([Configurable immunity for evolving human-computer systems](https://www.sciencedirect.com/science/article/pii/S0167642303000479/pdf?md5=46dcfcb349f21d4d1ffb4525aac49f61&pid=1-s2.0-S0167642303000479-main.pdf))和不动点的理论**，以及后来 Puppet、HashiCorp、CNCF 等组织的一系列相关工程实现。

UCloud 的开发者工具，以命令式的 API 为底座，基于它构建更高层次的其它种类用户接口。每个层次的用户接口，都以开发者工具形态提供，并通过下文中提及的[代码生成流水线](./code-generation-pipeline_CN.md)来自动化构建。
