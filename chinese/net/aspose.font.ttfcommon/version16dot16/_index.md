---
title: Version16Dot16
second_title: Aspose.Font for .NET API 参考
description: Reresents Version16Dot16 数据类型
type: docs
weight: 730
url: /zh/net/aspose.font.ttfcommon/version16dot16/
---
## Version16Dot16 class

Reresents Version16Dot16 数据类型

```csharp
public class Version16Dot16 : ICloneable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Version16Dot16](version16dot16#constructor)() | 构造函数 |
| [Version16Dot16](version16dot16#constructor_1)(ushort, ushort) | 构造函数 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [MajorNumber](../../aspose.font.ttfcommon/version16dot16/majornumber) { get; set; } | 获取或设置主要版本号。 值仅在十六进制表示法中有意义，例如实际字体文件中 'maxp' 的 版本 0.5 为 4 个字节：{0, 0, 80, 0}，十六进制表示为 0x00005000. 从字体文件中读取此版本后, 对象的主要和次要数字[`Version16Dot16`](../version16dot16)将分别为 0 和 20480。 而这些十六进制形式的值是 0x0000 和 0x5000. |
| [MinorNumber](../../aspose.font.ttfcommon/version16dot16/minornumber) { get; set; } | 获取或设置次要版本号 值仅在十六进制表示中有意义，例如 版本 0.5 for 'maxp' 在实际字体文件中为 4 个字节：{0, 0, 80, 0}，十六进制表示为 0x00005000. 之后从字体文件中读取此版本，对象的主要和次要编号[`Version16Dot16`](../version16dot16)将分别为 0 和 20480。 而这些十六进制形式的值是 0x0000 和 0x5000. |
| [RawBytes](../../aspose.font.ttfcommon/version16dot16/rawbytes) { get; } | 获取 Version16Dot16 版本号的所有原始位作为字节数组，大小为 4 字节。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.font.ttfcommon/version16dot16/clone)() | 创建一个副本[`Version16Dot16`](../version16dot16)对象. |
| override [ToString](../../aspose.font.ttfcommon/version16dot16/tostring)() | 以格式化字符串形式返回版本值 例如“0.5”、“1.1”、“3.0”等 |

### 也可以看看

* 命名空间 [Aspose.Font.TtfCommon](../../aspose.font.ttfcommon)
* 部件 [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->