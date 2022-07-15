---
title: FontEnvironment
second_title: Aspose.Font for .NET API 参考
description: 提供有关当前环境和平台的信息
type: docs
weight: 140
url: /zh/net/aspose.font/fontenvironment/
---
## FontEnvironment class

提供有关当前环境和平台的信息。

```csharp
public class FontEnvironment
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Current](../../aspose.font/fontenvironment/current) { get; } | 获取当前环境。 |
| [CurrentPlatformId](../../aspose.font/fontenvironment/currentplatformid) { get; } | 获取当前平台 ID。 |
| [FontSpecificEncodings](../../aspose.font/fontenvironment/fontspecificencodings) { get; } | 存储消费者感知字体的特定编码。 例如，PDF 文档使用 Adobe Symbol 和 ZapfDingbats 特定的编码。 |
| [Strictness](../../aspose.font/fontenvironment/strictness) { get; set; } | 某些字体可能包含意外数据、未指定的功能，或者可能被粗略裁剪。 容错设置推荐给想要打开任何字体而不考虑字体不足的消费者。字体内部结构不保证一致。 对于想要打开大部分有效和实体字体的消费者，建议进行严格设置。 |

### 也可以看看

* 命名空间 [Aspose.Font](../../aspose.font)
* 部件 [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->