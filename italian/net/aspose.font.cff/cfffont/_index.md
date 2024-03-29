---
title: CffFont
second_title: Aspose.Font per Riferimento API .NET
description: Rappresenta il Compact Font Format CFF.
type: docs
weight: 30
url: /it/net/aspose.font.cff/cfffont/
---
## CffFont class

Rappresenta il Compact Font Format (CFF).

```csharp
public class CffFont : Font
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Encoding](../../aspose.font.cff/cfffont/encoding) { get; } | Ottiene la codifica dei caratteri. |
| override [FontDefinition](../../aspose.font.cff/cfffont/fontdefinition) { get; } | Ottiene la definizione del carattere. |
| override [FontFamily](../../aspose.font.cff/cfffont/fontfamily) { get; set; } | Ottiene la famiglia di caratteri. Il setter della famiglia di caratteri non è ancora implementato. |
| override [FontName](../../aspose.font.cff/cfffont/fontname) { get; set; } | Ottiene il nome del carattere del carattere. Il setter del nome del carattere del carattere non è ancora implementato. |
| override [FontNames](../../aspose.font.cff/cfffont/fontnames) { get; } | Ottieni nomi font. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Ottiene la funzionalità di salvataggio dei caratteri. |
| override [FontStyle](../../aspose.font.cff/cfffont/fontstyle) { get; } | Ottiene lo stile del carattere. Questo è un valore calcolato e rappresentato in tipo generalizzato. |
| override [FontType](../../aspose.font.cff/cfffont/fonttype) { get; } | Ottiene il tipo di carattere. Restituisce il valore FontType.CFF. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Accessorio per glifo dei caratteri. Recupera glifi e identificatori di glifi. |
| override [GlyphIdType](../../aspose.font.cff/cfffont/glyphidtype) { get; } | Ottiene la specifica del tipo di ID glifo. |
| [IsCidKeyedFont](../../aspose.font.cff/cfffont/iscidkeyedfont) { get; } | Ottiene il valore che indica che il carattere è con chiave cid. |
| override [Metrics](../../aspose.font.cff/cfffont/metrics) { get; } | Ottiene le metriche dei caratteri. |
| override [NumGlyphs](../../aspose.font.cff/cfffont/numglyphs) { get; } | Ottiene il numero di glifi nel Font. |
| override [PostscriptNames](../../aspose.font.cff/cfffont/postscriptnames) { get; } | Ottiene i nomi dei caratteri PostScript. |
| override [Style](../../aspose.font.cff/cfffont/style) { get; set; } | Ottiene lo stile del carattere. Questo è un valore di stringa non elaborato fornito dal file del carattere. Il setter di stile non è ancora implementato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Convert](../../aspose.font.cff/cfffont/convert)(FontType) | Converte il carattere in un altro formato. |
| override [GetAllGlyphIds](../../aspose.font.cff/cfffont/getallglyphids)() | Restituisce l'array di tutti gli ID glifi, disponibili in Font. L'ID glifo è un numero univoco per un glifo, che dipende dal tipo di carattere. CFF L'ID glifo del carattere può essere un'istanza di ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) classe o ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |
| override [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid)(GlyphId) | Restituisce glifo per id glifo. L'ID glifo è un numero univoco per un glifo, che dipende dal tipo di carattere. L'ID glifo del carattere CFF può essere un'istanza di ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) classe o ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_1)(string) | Restituisce il glifo in base al nome del glifo. |
| [GetGlyphById](../../aspose.font.cff/cfffont/getglyphbyid#getglyphbyid_2)(uint) | Restituisce glifo per id glifo. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Ottiene la rappresentazione dei glifi per il testo. |
| virtual [Save](../../aspose.font/font/save)(Stream) | Salva il carattere nel formato originale. |
| virtual [Save](../../aspose.font/font/save)(string) | Salva il carattere nel formato originale. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Salva il carattere nel formato specificato. |

### Guarda anche

* class [Font](../../aspose.font/font)
* spazio dei nomi [Aspose.Font.Cff](../../aspose.font.cff)
* assemblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
