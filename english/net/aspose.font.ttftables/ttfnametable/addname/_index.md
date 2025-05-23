---
title: TtfNameTable.AddName
second_title: Aspose.Font for .NET API Reference
description: TtfNameTable method. Adds entry into the table. String data category to add is specified by name parameter
type: docs
weight: 20
url: /net/aspose.font.ttftables/ttfnametable/addname/
---
## TtfNameTable.AddName method

Adds entry into the table. String data category to add is specified by *name* parameter.

```csharp
public void AddName(NameId nameId, PlatformId platformId, int platformSpecificId, int languageId, 
    string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| nameId | NameId | Name identifier, logical string category, specified by [`NameId`](../../ttfnametable.nameid/) enumeration |
| platformId | PlatformId | Platform identifier |
| platformSpecificId | Int32 | Platform-specific encoding identifier. Please, use value from one of such enumerations - [`UnicodePlatformSpecificId`](../../ttfnametable.unicodeplatformspecificid/), [`MacPlatformSpecificId`](../../ttfnametable.macplatformspecificid/), [`MSPlatformSpecificId`](../../ttfnametable.msplatformspecificid/). What enumeration to use is defined by context (*platformId* parameter) |
| languageId | Int32 | Language identifier. Please, use value from [`MSLanguageId`](../../ttfnametable.mslanguageid/) or [`MacLanguageId`](../../ttfnametable.maclanguageid/) enumerations depend from context, defined by *platformId* parameter. |
| name | String | Actual string data |

### See Also

* enum [NameId](../../ttfnametable.nameid/)
* enum [PlatformId](../../ttfnametable.platformid/)
* class [TtfNameTable](../)
* namespace [Aspose.Font.TtfTables](../../../aspose.font.ttftables/)
* assembly [Aspose.Font](../../../)


