---
title: Type1Font
second_title: Aspose.Font für .NET-API-Referenz
description: steht für Type1 Font.
type: docs
weight: 1060
url: /de/net/aspose.font.type1/type1font/
---
## Type1Font class

steht für Type1 Font.

```csharp
public class Type1Font : Font
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Encoding](../../aspose.font.type1/type1font/encoding) { get; } | Ruft die Schriftartcodierung ab. |
| override [FontDefinition](../../aspose.font.type1/type1font/fontdefinition) { get; } | Ruft die Schriftartdefinition ab. |
| override [FontFamily](../../aspose.font.type1/type1font/fontfamily) { get; set; } | Ruft die Schriftfamilie ab. Der Setter für die Schriftfamilie ist noch nicht implementiert. |
| override [FontName](../../aspose.font.type1/type1font/fontname) { get; set; } | Ruft den Namen der Schriftart ab. Der Setter für den Namen der Schriftart ist noch nicht implementiert. |
| override [FontNames](../../aspose.font.type1/type1font/fontnames) { get; } | Ruft Schriftnamen ab. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Ruft die Funktion zum Speichern von Schriftarten ab. |
| override [FontStyle](../../aspose.font.type1/type1font/fontstyle) { get; } | Ruft den Schriftstil ab. Dies ist ein Wert, der in verallgemeinertem Typ berechnet und dargestellt wird. |
| override [FontType](../../aspose.font.type1/type1font/fonttype) { get; } | Ruft den Schriftarttyp ab. Gibt den FontType.Type1-Wert zurück. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Font-Glyphen-Accessor. Ruft Glyphen und Glyphenkennungen ab. |
| override [GlyphIdType](../../aspose.font.type1/type1font/glyphidtype) { get; } | Spezifikation des Glyphen-ID-Typs. |
| override [Metrics](../../aspose.font.type1/type1font/metrics) { get; } | Ruft Schriftartmetriken ab. |
| override [NumGlyphs](../../aspose.font.type1/type1font/numglyphs) { get; } | Ruft die Anzahl der Glyphen in der Schriftart ab. |
| override [PostscriptNames](../../aspose.font.type1/type1font/postscriptnames) { get; } | Ruft Postscript-Schriftartennamen ab. |
| override [Style](../../aspose.font.type1/type1font/style) { get; set; } | Ruft den Schriftstil ab. Dies ist ein roher Stringwert, der von der Schriftdatei bereitgestellt wird. Der Style-Setter ist noch nicht implementiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Convert](../../aspose.font.type1/type1font/convert)(FontType) | Konvertiert die Schriftart in ein anderes Format. |
| override [GetAllGlyphIds](../../aspose.font.type1/type1font/getallglyphids)() | Gibt ein Array aller Glyphen-IDs zurück, die in der Schriftart verfügbar sind. Die Glyphen-ID ist eine eindeutige Nummer für eine Glyphe, die vom Schriftarttyp abhängig ist. Type1 Schriftart-Glyphen-ID kann eine Instanz von sein ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) Klasse oder ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |
| override [GetGlyphById](../../aspose.font.type1/type1font/getglyphbyid#getglyphbyid)(GlyphId) | Gibt Glyphe nach Glyphen-ID zurück. Die Glyphen-ID ist eine eindeutige Nummer für eine Glyphe, die vom Schriftarttyp abhängig ist. Typ1 Schriftart-Glyphen-ID kann eine Instanz von sein ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) Klasse oder ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |
| virtual [GetGlyphById](../../aspose.font.type1/type1font/getglyphbyid#getglyphbyid_1)(string) | Gibt Glyphe nach Glyphen-ID zurück. |
| [GetGlyphById](../../aspose.font.type1/type1font/getglyphbyid#getglyphbyid_2)(uint) | Gibt Glyphe nach Glyphen-ID zurück. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Ruft Glyphendarstellung für Text ab. |
| virtual [Save](../../aspose.font/font/save)(Stream) | Speichert die Schriftart im Originalformat. |
| virtual [Save](../../aspose.font/font/save)(string) | Speichert die Schriftart im Originalformat. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Speichert die Schriftart im angegebenen Format. |

### Siehe auch

* class [Font](../../aspose.font/font)
* namensraum [Aspose.Font.Type1](../../aspose.font.type1)
* Montage [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
