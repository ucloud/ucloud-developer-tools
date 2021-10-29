# UCloud Developer Tools

UCloud is a cloud vendor in China. We provide many developer tools to help users manage cloud resources.

## Table of Content

- [Landscape](#Landscape)
- [Introduction](#Introdution)
- Concept
  - [Imperative vs Declarative vs Interactive](./concept/architectural-styles.md)
  - [Code Generation Pipeline](./concept/code-generation-pipeline.md)
- Culture
  - [Open Source and Gift Culture](./culture/open-source.md)
  - [Response Time Maximum for Community](./culture/rtm-for-community.md)
- [Contribution Guideline](#Contribution)
- [Design Documentations](./design)
- [Proposals](./proposals)
- Roadmap

## Landscape

UCloud has developed and contributed to many open-source tools.

![Landscape](./images/landscape.png)

## Introdution

| Categories | Name             | Hosted by | Style       | Document                                               | Repository                                                   | State                                                     |
| ---------- | ---------------- | --------- | ----------- | ------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------------------------- |
| Landing    | Developer Center | Self      | Interactive | ~                                                      | ~                                                            | [Prototyping](./culture/rtm-for-community.md#Prototyping) |
| SaaS       | UAPI             | Self      | Interactive | [Doc](https://docs.ucloud.cn/uapi/README)              | ~                                                            | [Active](./culture/rtm-for-community.md#Active)           |
| SaaS       | CloudShell       | Self      | Interactive | [Doc](https://docs.ucloud.cn/cloudshell/README)        | ~                                                            | [Refactoring](./culture/rtm-for-community.md#Refactoring) |
| CDK        | CDKTF            | Community | Declarative | ~                                                      | [Github](https://github.com/hashicorp/terraform-cdk)         | [Active](./culture/rtm-for-community.md#Active)           |
| CDK        | Pulumi           | Community | Declarative | ~                                                      | [Github](https://github.com/pulumi/pulumi-ucloud)            | [Prototyping](./culture/rtm-for-community.md#Prototyping) |
| CLI        | CLI              | Self      | Mixed       | [Doc](https://docs.ucloud.cn/cli/README)               | [Github](https://github.com/ucloud/cli)                      | [Refactoring](./culture/rtm-for-community.md#Refactoring) |
| CLI        | Terraform        | Community | Declarative | [Doc](https://docs.ucloud.cn/terraform/README)         | [Github](https://github.com/ucloud/terraform-provider-ucloud) | [Active](./culture/rtm-for-community.md#Active)           |
| CLI        | Packer           | Community | Declarative | [Doc](https://docs.ucloud.cn/uhost/guide/image/packer) | [Github](https://github.com/hashicorp/packer/blob/master/website/content/docs/builders/ucloud-uhost.mdx) | [Active](./culture/rtm-for-community.md#Active)           |
| SDK        | Go               | Self      | Imperative  | [Doc](https://docs.ucloud.cn/opensdk-go/)              | [Github](https://github.com/ucloud/ucloud-sdk-go)            | [Active](./culture/rtm-for-community.md#Active)           |
| SDK        | Python           | Self      | Imperative  | [Doc](https://docs.ucloud.cn/opensdk-python/)          | [Github](https://github.com/ucloud/ucloud-sdk-python3)       | [Active](./culture/rtm-for-community.md#Active)           |
| SDK        | Java             | Self      | Imperative  | [Doc](https://docs.ucloud.cn/opensdk-java/)            | [Github](https://github.com/ucloud/ucloud-sdk-java)          | [Active](./culture/rtm-for-community.md#Active)           |
| SDK        | PHP              | Self      | Imperative  | [Doc](https://docs.ucloud.cn/opensdk-php/)             | [Github](https://github.com/ucloud/ucloud-sdk-php)           | [Active](./culture/rtm-for-community.md#Active)           |
| SDK        | JS/TS            | Self      | Imperative  | [Doc](https://docs.ucloud.cn/opensdk-js/)              | [Github](https://github.com/ucloud/ucloud-sdk-js)            | [Active](./culture/rtm-for-community.md#Active)           |

## Contribution

UCloud developer tools is an collection of open source tools. We will publish my design and roadmap into this repository.

If you have any proposal for our tools, create an **issue** for free. We will convert the major inspire as an **proposal** draft, and push it forward.

When any **proposal** done, it will be convert as a **design documentation**. You can see all the documentation at here.
