---
title: Encoding
second_title: Aspose.Font لمرجع .NET API
description: يتم تحديد الترميز في ملف المقاييس.
type: docs
weight: 10
url: /ar/net/aspose.font.type1/type1metricfont/encoding/
---
## Type1MetricFont.Encoding property

يتم تحديد الترميز في ملف المقاييس.

```csharp
public override IFontEncoding Encoding { get; }
```

### أمثلة

FontSpecific: يجب على المستخدم توفير التشفير المحدد بالطريقة التالية:  System :: ArrayPtr &lt;System :: String&gt; zapfDingbatsEncoding = System :: MakeArray &lt;System :: String&gt; ({nullptr، nullptr، ...، u "space"، u "a1"، ...})؛ FontEnvironment :: get_Current () -&gt; get_FontSpecificEncodings () -&gt; RegisterEncoding (u "ZapfDingbats"، zapfDingbatsEncoding)؛

```csharp
string[] zapfDingbatsEncoding = new string[256] {null, null, ... , "space", "a1", ...};
FontEnvironment.Current.FontSpecificEncodings.RegisterEncoding("ZapfDingbats", zapfDingbatsEncoding);
```

### أنظر أيضا

* interface [IFontEncoding](../../../aspose.font/ifontencoding)
* class [Type1MetricFont](../../type1metricfont)
* مساحة الاسم [Aspose.Font.Type1](../../type1metricfont)
* المجسم [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
