# UCloud 开发者工具

[English](./README.md) | 简体中文

UCloud 是一家中国的云计算厂商，我们提供诸多开发者工具帮助用户管理云上资源。

## 目录

- [全景图](#全景图)
- [概览](#概览)
- 概念
  - [命令式 vs 声明式 vs 交互式](./concept/architectural-styles_CN.md)
  - [代码生成流水线](./concept/code-generation-pipeline_CN.md)
- 技术文化
  - [开源与礼物文化](./culture/open-source_CN.md)
  - [面向社区的最大响应时间](./culture/rtm-for-community_CN.md)
- [贡献者指南](#贡献)
- [设计文档](./design)
- [提案](./proposals)
- [路线图](https://github.com/ucloud/ucloud-developer-tools/milestone/2)

## 全景图

UCloud 已经开发和贡献了许多开源工具。

![Landscape](./images/landscape.png)

## 概览

| 分类 | 名称             | 持有者 | 架构风格       | 文档                                               | 仓库                                                   | 状态                                                     |
| ---------- | ---------------- | --------- | ----------- | ------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------------------------- |
| 页面    | 开发者中心 | 自身      | 交互式 | ~                                                      | ~                                                            | [原型](./culture/rtm-for-community.md#Prototyping) |
| SaaS       | UAPI             | 自身      | 交互式 | [Doc](https://docs.ucloud.cn/uapi/README)              | ~                                                            | [活跃](./culture/rtm-for-community.md#Active)           |
| SaaS       | CloudShell       | 自身      | 交互式 | [Doc](https://docs.ucloud.cn/cloudshell/README)        | ~                                                            | [重构中](./culture/rtm-for-community.md#Refactoring) |
| CDK        | CDKTF            | 社区 | 声明式 | ~                                                      | [Github](https://github.com/hashicorp/terraform-cdk)         | [活跃](./culture/rtm-for-community.md#Active)           |
| CDK        | Pulumi           | 社区 | 声明式 | ~                                                      | [Github](https://github.com/pulumi/pulumi-ucloud)            | [原型](./culture/rtm-for-community.md#Prototyping) |
| CLI        | CLI              | 自身      | 多范式       | [Doc](https://docs.ucloud.cn/cli/README)               | [Github](https://github.com/ucloud/cli)                      | [重构中](./culture/rtm-for-community.md#Refactoring) |
| CLI        | Terraform        | 社区 | 声明式 | [Doc](https://docs.ucloud.cn/terraform/README)         | [Github](https://github.com/ucloud/terraform-provider-ucloud) | [活跃](./culture/rtm-for-community.md#Active)           |
| CLI        | Packer           | 社区 | 声明式 | [Doc](https://docs.ucloud.cn/uhost/guide/image/packer) | [Github](https://github.com/hashicorp/packer/blob/master/website/content/docs/builders/ucloud-uhost.mdx) | [活跃](./culture/rtm-for-community.md#Active)           |
| SDK        | Go               | 自身      | 交互式  | [Doc](https://docs.ucloud.cn/opensdk-go/)              | [Github](https://github.com/ucloud/ucloud-sdk-go)            | [活跃](./culture/rtm-for-community.md#Active)           |
| SDK        | Python           | 自身      | 交互式  | [Doc](https://docs.ucloud.cn/opensdk-python/)          | [Github](https://github.com/ucloud/ucloud-sdk-python3)       | [活跃](./culture/rtm-for-community.md#Active)           |
| SDK        | Java             | 自身      | 交互式  | [Doc](https://docs.ucloud.cn/opensdk-java/)            | [Github](https://github.com/ucloud/ucloud-sdk-java)          | [重构中](./culture/rtm-for-community.md#Refactoring)           |
| SDK        | PHP              | 自身      | 交互式  | [Doc](https://docs.ucloud.cn/opensdk-php/)             | [Github](https://github.com/ucloud/ucloud-sdk-php)           | [活跃](./culture/rtm-for-community.md#Active)           |
| SDK        | JS/TS            | 自身      | 交互式  | [Doc](https://docs.ucloud.cn/opensdk-js/)              | [Github](https://github.com/ucloud/ucloud-sdk-js)            | [活跃](./culture/rtm-for-community.md#Active)           |

## 贡献

UCloud 开发者工具是一系列的开源工具集合，我们将在当前仓库中公开我们的设计和路线图。

如果您有任何关于我们工具的建议，请创建一个问题（**Issue**）。我们将总结其中关键的思路作为一个提案（**Proposal**）草稿，并持续推进它。

当任意提案（**Proposal**）完成时，我们将其转换为一个设计文档。您可以在此仓库中查看所有的设计文档。
