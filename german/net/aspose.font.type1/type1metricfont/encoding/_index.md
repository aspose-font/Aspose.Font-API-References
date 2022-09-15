---
title: Encoding
second_title: Aspose.Font für .NET-API-Referenz
description: Die Kodierung ist in der Metrikdatei definiert. StandardAdobeEncoding die Kodierung wird automatisch ausgefüllt
type: docs
weight: 10
url: /de/net/aspose.font.type1/type1metricfont/encoding/
---
## Type1MetricFont.Encoding property

Die Kodierung ist in der Metrikdatei definiert. StandardAdobeEncoding: die Kodierung wird automatisch ausgefüllt

```csharp
public override IFontEncoding Encoding { get; }
```

### Beispiele

FontSpecific: Benutzer sollten die spezifische Kodierung auf folgende Weise angeben:  System::ArrayPtr&lt;System::String&gt; zapfDingbatsEncoding = System::MakeArray&lt;System::String&gt;({nullptr, nullptr, ..., u"space", u"a1", ...}); FontEnvironment::get_Current()-&gt;get_FontSpecificEncodings()-&gt;RegisterEncoding(u"ZapfDingbats", zapfDingbatsEncoding);

```csharp
string[] zapfDingbatsEncoding = new string[256] {null, null, ... , "space", "a1", ...};
FontEnvironment.Current.FontSpecificEncodings.RegisterEncoding("ZapfDingbats", zapfDingbatsEncoding);
```

### Siehe auch

* interface [IFontEncoding](../../../aspose.font/ifontencoding)
* class [Type1MetricFont](../../type1metricfont)
* namensraum [Aspose.Font.Type1](../../type1metricfont)
* Montage [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->