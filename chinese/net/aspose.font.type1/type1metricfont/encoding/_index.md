---
title: Encoding
second_title: Aspose.Font for .NET API 参考
description: 编码在度量文件中定义 StandardAdobeEncoding 编码会自动填充
type: docs
weight: 10
url: /zh/net/aspose.font.type1/type1metricfont/encoding/
---
## Type1MetricFont.Encoding property

编码在度量文件中定义。 StandardAdobeEncoding： 编码会自动填充

```csharp
public override IFontEncoding Encoding { get; }
```

### 例子

FontSpecific： 用户应提供具体编码方式如下： &lt;cppcode&gt; System::ArrayPtr&lt;System::String&gt;; zapfDingbatsEncoding = System::MakeArray&lt;System::String&gt;({nullptr, nullptr, ..., u"space", u"a1", ...}); FontEnvironment::get_Current()-&gt;get_FontSpecificEncodings()-&gt;RegisterEncoding(u"ZapfDingbats", zapfDingbatsEncoding); &lt;/cppcode&gt;

```csharp
string[] zapfDingbatsEncoding = new string[256] {null, null, ... , "space", "a1", ...};
FontEnvironment.Current.FontSpecificEncodings.RegisterEncoding("ZapfDingbats", zapfDingbatsEncoding);
```

### 也可以看看

* interface [IFontEncoding](../../../aspose.font/ifontencoding)
* class [Type1MetricFont](../../type1metricfont)
* 命名空间 [Aspose.Font.Type1](../../type1metricfont)
* 部件 [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->