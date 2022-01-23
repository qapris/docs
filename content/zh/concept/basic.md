---
title: 基础概念
category: 概念
position: 50
---

## Project

目前每个项目都有两个环境，`dev` 和 `prod`，两个环境中的服务部署是独立的。

链接的域名仅会绑定到 `prod` 环境，同时如果您想要部署到生产频道，请在部署时指定 `--prod`， 例如 `lets deploy --prod`。

## Deployment

每个项目都可以有非常多的部署，同一环境中部署新的服务，会更新掉上一次部署的服务。

## Domain

let.sh 提供了像 `xxx.let.sh` 这样的公共域名，如果该域没有被其他人占用，你可以直接运行 `lets link xxx.let.sh` 来获取任何你想要的域名。

如果您愿意使用您自己的域名，请提前在 let.sh 控制台注册并验证该域的所有权。

## Link

绑定域名到当前项目