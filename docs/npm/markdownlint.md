---
title: markdownlint-config-kayn
categories:
  - 工程规范
tags:
  - 工程规范
---

# markdownlint-config-kayn

:::tip
文档 规范
:::

支持配套的 [markdownlint 可共享配置](https://www.npmjs.com/package/markdownlint#optionsconfig)。

## 安装
需要先全局安装 [markdownlint-cli](https://www.npmjs.com/package/markdownlint-cli)
```bash
npm install -g markdownlint-cli
```

再安装 [markdownlint](https://www.npmjs.com/package/markdownlint)：

```bash
npm install markdownlint-config-kayn markdownlint --save-dev
```

## 使用

在 `.markdownlint.json` 中继承本包:

```json
{
  "extends": "markdownlint-config-kayn"
}
```
