---
title: CffFont
second_title: Aspose.Font für .NET-API-Referenz
description: steht für Compact Font Format CFF.
type: docs
weight: 30
url: /de/net/aspose.font.cff/cfffont/
---
## CffFont class

steht für Compact Font Format (CFF).

```csharp
public class CffFont : Font
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Encoding](../../aspose.font.cff/cfffont/encoding) { get; } | Ruft die Schriftartcodierung ab. |
| override [FontDefinition](../../aspose.font.cff/cfffont/fontdefinition) { get; } | Ruft die Schriftartdefinition ab. |
| override [FontFamily](../../aspose.font.cff/cfffont/fontfamily) { get; set; } | Ruft die Schriftfamilie ab. Der Setter für die Schriftfamilie ist noch nicht implementiert. |
| override [FontName](../../aspose.font.cff/cfffont/fontname) { get; set; } | Ruft den Namen der Schriftart ab. Der Setter für den Namen der Schriftart ist noch nicht implementiert. |
| override [FontNames](../../aspose.font.cff/cfffont/fontnames) { get; } | Schriftnamen abrufen. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Ruft die Funktion zum Speichern von Schriftarten ab. |
| override [FontStyle](../../aspose.font.cff/cfffont/fontstyle) { get; } | Ruft den Schriftstil ab. Dies ist ein Wert, der in verallgemeinertem Typ berechnet und dargestellt wird. |
| override [FontType](../../aspose.font.cff/cfffont/fonttype) { get; } | Ruft den Schriftarttyp ab. Gibt den FontType.CFF-Wert zurück. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Font-Glyphen-Accessor. Ruft Glyphen und Glyphenkennungen ab. |
| override [GlyphIdType](../../aspose.font.cff/cfffont/glyphidtype) { get; } | Ruft die Spezifikation des Glyphen-ID-Typs ab. |
| [IsCidKeyedFont](../../aspose.font.cff/cfffont/iscidkeyedfont) { get; } | Ruft einen Wert ab, der angibt, dass die Schriftart einen CID-Schlüssel hat. |
| override [Metrics](../../aspose.font.cff/cfffont/metrics) { get; } | Ruft Schriftartmetriken ab. |
| override [NumGlyphs](../../aspose.font.cff/cfffont/numglyphs) { get; } | Ruft die Anzahl der Glyphen in der Schriftart ab. |
| override [PostscriptNames](../../aspose.font.cff/cfffont/postscriptnames) { get; } | Ruft Postscript-Schriftartennamen ab. |
| override [Style](../../aspose.font.cff/cfffont/style) { get; set; } | Ruft den Schriftstil ab. Dies ist ein roher Stringwert, der von der Schriftdatei bereitgestellt wird. Der Style-Setter ist noch nicht implementiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Convert](../../aspose.font.cff/cfffont/convert)(FontType) | Konvertiert die Schriftart in ein anderes Format. |
| override [GetAllGlyphIds](../../aspose.font.cff/cfffont/getallglyphids)() | Gibt ein Array aller Glyphen-IDs zurück, die in der Schriftart verfügbar sind. Die Glyphen-ID ist eine eindeutige Nummer für eine Glyphe, die vom Schriftarttyp abhängig ist. Die Glyphen-ID der CFF-Schriftart kann eine Instanz von sein ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) Klasse oder ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |
| override [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid)(GlyphId) | Gibt Glyphe nach Glyphen-ID zurück. Die Glyphen-ID ist eine eindeutige Nummer für eine Glyphe, die vom Schriftarttyp abhängig ist. Die Glyphen-ID der CFF-Schriftart kann eine Instanz von sein ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) Klasse oder ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) Klasse. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_1)(string) | Gibt Glyphe nach Glyphenname zurück. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_2)(uint) | Gibt Glyphe nach Glyphen-ID zurück. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Ruft Glyphendarstellung für Text ab. |
| virtual [Save](../../aspose.font/font/save)(Stream) | Speichert die Schriftart im Originalformat. |
| virtual [Save](../../aspose.font/font/save)(string) | Speichert die Schriftart im Originalformat. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Speichert die Schriftart im angegebenen Format. |

### Siehe auch

* class [Font](../../aspose.font/font)
* namensraum [Aspose.Font.Cff](../../aspose.font.cff)
* Montage [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->