---
title: FontDefinition
second_title: Aspose.Font för .NET API-referens
description: Representerar definition av teckensnittsfiluppsättning. Den här klassen innehåller fält som inte är relaterade till teckensnittets interna data. Dessa fält beskriver teckensnittsplacering och annan data som behövs för att ladda teckensnitt från någon typsnittskälla fil minne etc.
type: docs
weight: 540
url: /sv/net/aspose.font.sources/fontdefinition/
---
## FontDefinition class

Representerar definition av teckensnittsfiluppsättning. Den här klassen innehåller fält som inte är relaterade till teckensnittets interna data. Dessa fält beskriver teckensnittsplacering och annan data som behövs för att ladda teckensnitt från någon typsnittskälla (fil, minne, etc).

```csharp
public class FontDefinition
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [FontDefinition](fontdefinition#constructor)(FontType, FontFileDefinition) | Skapar en typsnittsdefinition för en fil. |
| [FontDefinition](fontdefinition#constructor_1)(FontType, FontFileDefinition[]) | Skapar teckensnittsdefinition för flera filer. |
| [FontDefinition](fontdefinition#constructor_2)(FontType, StreamSource) | Skapar en typsnittsdefinition för en fil. |
| [FontDefinition](fontdefinition#constructor_3)(FontType, string, StreamSource) | Skapar en typsnittsdefinition för en fil. |
| [FontDefinition](fontdefinition#constructor_6)(string, FontType, FontFileDefinition) | Skapar en typsnittsdefinition för en fil. |
| [FontDefinition](fontdefinition#constructor_4)(MultiLanguageString, MultiLanguageString, FontType, FontFileDefinition) | Skapar teckensnittsdefinition för flera filer. |
| [FontDefinition](fontdefinition#constructor_5)(MultiLanguageString, MultiLanguageString, FontType, FontFileDefinition[]) | Skapar teckensnittsdefinition för flera filer. |
| [FontDefinition](fontdefinition#constructor_7)(string, FontType, string, StreamSource) | Skapar en typsnittsdefinition för en fil. |
| [FontDefinition](fontdefinition#constructor_8)(string, string, FontType, FontFileDefinition) | Skapar en typsnittsdefinition för en fil. |
| [FontDefinition](fontdefinition#constructor_9)(string, string, FontType, FontFileDefinition[]) | Skapar teckensnittsdefinition för flera filer. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [FileDefinitions](../../aspose.font.sources/fontdefinition/filedefinitions) { get; } | Hämtar fildefinitionssamling. |
| virtual [FontName](../../aspose.font.sources/fontdefinition/fontname) { get; } | Returnerar teckensnittsnamn. |
| virtual [FontNames](../../aspose.font.sources/fontdefinition/fontnames) { get; } | Hämtar teckensnittsnamn som en[`MultiLanguageString`](../../aspose.font/multilanguagestring) . |
| [FontType](../../aspose.font.sources/fontdefinition/fonttype) { get; } | Hämtar teckensnittstyp. |
| virtual [PostscriptName](../../aspose.font.sources/fontdefinition/postscriptname) { get; } | Får postscript teckensnittsnamn. |
| [PostscriptNames](../../aspose.font.sources/fontdefinition/postscriptnames) { get; } | Får postscript-teckensnittsnamn som en[`MultiLanguageString`](../../aspose.font/multilanguagestring) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Open](../../aspose.font.sources/fontdefinition/open#open)(StreamSource, FontType) | Returnerar FontDefinition för teckensnittsströmkälla och teckensnittstyp. |
| static [Open](../../aspose.font.sources/fontdefinition/open#open_1)(string, FontType) | Returnerar FontDefinition för teckensnittsfil och teckensnittstyp. |

### Se även

* namnutrymme [Aspose.Font.Sources](../../aspose.font.sources)
* hopsättning [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
