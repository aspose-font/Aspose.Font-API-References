---
title: DecodeToGid
second_title: Aspose.Font for .NET API Referansı
description: Bir karakter kodunun kodunu çözer ve glif kimliğini döndürür. Glif kimliği yazı tipi türüne bağlı olan bir glif için benzersiz bir sayıdır. Örneğin Tür1in kimliği bir glif adıdır örneğin GlyphStringIdaspose.font.glyphs/glyphstringid class. TTFnin kimliği bir int dizinidir örneğin GlyphUInt32Idaspose.font.glyphs/glyphuint32id  class. Not karakter kodu unicode için gerekli değildir. Karakter kodu Font kodlaması table içindeki bir karakter dizinidir.
type: docs
weight: 10
url: /tr/net/aspose.font/ifontencoding/decodetogid/
---
## IFontEncoding.DecodeToGid method

Bir karakter kodunun kodunu çözer ve glif kimliğini döndürür. Glif kimliği, yazı tipi türüne bağlı olan bir glif için benzersiz bir sayıdır. Örneğin: Tür1'in kimliği bir glif adıdır, örneğin ([`GlyphStringId`](../../../aspose.font.glyphs/glyphstringid)) class. TTF'nin kimliği bir int dizinidir, örneğin ([`GlyphUInt32Id`](../../../aspose.font.glyphs/glyphuint32id) ) class. Not: karakter kodu, unicode için gerekli değildir. Karakter kodu, Font kodlaması "table" içindeki bir karakter dizinidir.

```csharp
public GlyphId DecodeToGid(uint charCode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| charCode | UInt32 | Glif tanımlayıcısını almak için karakter kodu. |

### Geri dönüş değeri

charCode ile ilgili glif tanımlayıcısı iletildi.

### Ayrıca bakınız

* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* interface [IFontEncoding](../../ifontencoding)
* ad alanı [Aspose.Font](../../ifontencoding)
* toplantı [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
