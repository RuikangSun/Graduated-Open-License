
# Graduated Open License (GOL)

一种**随时间逐步放宽**的开源许可证，在保护贡献者权益的同时，最终将作品释放到公共领域。

---

## 这是什么？

**Graduated Open License (GOL)** 是一种渐进式开源许可证。它的核心理念是：

> **新发布的贡献从强 Copyleft 开始，随时间推移逐步放宽，最终进入公共领域。**

大多数开源许可证是一次性的——要么宽松（MIT），要么 Copyleft（GPL），发布即定型。GOL 试图提供一个**中间路径**：

- **短期**：保护贡献者的作品不被他人闭源利用
- **中期**：在若干年后转为宽松许可，让更多人受益
- **长期**：最终进入公共领域，成为全人类的共同财富

---

## 授权时间线

每个 Contribution 的 Day 1 是其**首次公开发布或提交的日期**（UTC）。此后按 UTC 日期逐日递增。

以 **GOLv1** 为例：

| 阶段               | 时间节点    | 授权许可证                  | 含义                                                            |
| :----------------- | :---------- | :-------------------------- | :-------------------------------------------------------------- |
| **第一阶段** | Day 1 起    | **CC BY-SA 4.0**      | 任何人可以自由使用、修改、分发，但衍生作品必须以相同方式共享。  |
| **第二阶段** | Day 1096 起 | **MIT**               | 除 CC BY-SA 4.0 外，同时获得 MIT 许可，可以以更宽松的方式使用。 |
| **第三阶段** | Day 7301 起 | **CC0 1.0 Universal** | 作品进入公共领域，任何人都可以无限制地使用，无需署名。          |

> 后续阶段不会撤销之前已经授予的权利。一旦某个许可证生效，接收者可以继续依据该许可证使用作品。

## 如何使用

### 采用 GOLv1

将 `GOLv1/LICENSE` 复制到你的项目中，并替换 `[YEAR]` 和 `[COPYRIGHT HOLDER]`，例如：

```
Graduated Open License, Version 1.0 (GOLv1)

Copyright (c) 2026 SunRuikang

1. CONTRIBUTIONS AND DATES ... 
```

### 采用 CGOLv1（自定义版本）

CGOLv1 允许你自定义三个阶段使用的许可证和时间节点：

```text
First License: [full name and version]
Second License: [full name and version]
Public-Domain Instrument: [full name and version]
A: [integer greater than 1]
B: [integer greater than A]
```

---

## 许可证

本仓库中的许可证文本采用 [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) 协议发布，你可以自由复制、修改和使用。强烈建议基于本协议衍生的协议使用区别于本协议的名称，避免使用者混淆。

---

## 贡献

目前 GOL 和 CGOL 处于第一个版本，也许它还有很多不足之处，也许后续会应该有v2替代它。欢迎通过 Issue 参与改进：

- 报告许可证文本中的问题或歧义
- 提出兼容性改进建议
- 分享你的使用经验
