# 社区最大响应时间（RTM）

[English](./rtm-for-community.md) | 简体中文

社区最大响应时间 RTM (Response Time Maximum)，是一个借鉴自 [Chef 开源软件最佳实践](https://github.com/chef/chef-oss-practices) 中 [仓库状态](https://github.com/chef/chef-oss-practices/blob/main/repo-management/repo-states.md) 小节的一个概念。

我们扩展并为我们的仓库定义了 5 种状态：

- 活跃（Active）
- 重构（Refactoring）
- 维护（Maintained）
- 原型（Prototyping）
- 弃用（Deprecated）

## 活跃（Active）

仓库处于 Active 状态时，意味着它处于活跃开发中。活跃项目的最大响应时间（RTM）值为 7 天。

## 重构（Refactoring）

仓库处于 Refactoring 状态时，意味着它处于重构过程中，BUG 被正常修复，但新特性将被锁定，直至重构完成。所有的重构中项目都应在路线图中确立一个期望的完成时间。重构中项目的最大响应时间（RTM）值为 7 ～ 30 天。

## 维护（Maintained）

仓库处于 Maintained 状态时，意味着它处于被动维护中，BUG 被正常修复，但不应期待它有新的特性迭代。维护项目的最大响应时间（RTM）值为 1 个月。

## 原型（Prototyping）

仓库处于 Prototyping 状态时，意味着它处于 alpha 或 beta 版本中，不应期待它有新的特性迭代或 BUG 修复，直到该项目被移动到活跃状态。不应期望原型项目具备最大响应时间（RTM）。

## 弃用（Deprecated）

仓库处于 Deprecated 状态时，意味着它不再维护，不应期待它有新的特性迭代或 BUG 修复，也不应期望弃用项目具备最大响应时间（RTM）。

