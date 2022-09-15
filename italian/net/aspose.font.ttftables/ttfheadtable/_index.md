---
title: TtfHeadTable
second_title: Aspose.Font per Riferimento API .NET
description: Rappresenta la tabella head del file Font TTF.
type: docs
weight: 820
url: /it/net/aspose.font.ttftables/ttfheadtable/
---
## TtfHeadTable class

Rappresenta la tabella "head" del file Font TTF.

```csharp
public class TtfHeadTable : TtfTableBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CheckSumAdjustment](../../aspose.font.ttftables/ttfheadtable/checksumadjustment) { get; } | Ottiene uint32 checkSumAdjustment. Per calcolare: impostalo a 0, calcola il checksum per la tabella 'head' e mettilo nella directory della tabella, somma l'intero font come uint32, quindi memorizza B1B0AFBA - sum. Il checksum per la tabella 'head' non sarà sbagliato. Va bene. |
| [Created](../../aspose.font.ttftables/ttfheadtable/created) { get; } | Ottiene la data internazionale di creazione longDateTime. |
| [Flags](../../aspose.font.ttftables/ttfheadtable/flags) { get; } | Ottiene flag uint16. |
| [FontDirectionHint](../../aspose.font.ttftables/ttfheadtable/fontdirectionhint) { get; } | Ottiene int16 fontDirectionHint. 0 Glifi direzionali misti; 1 Solo glifi fortemente da sinistra a destra; 2 Come 1 ma contiene anche neutri; -1 Solo glifi fortemente da destra a sinistra; -2 Come -1 ma contiene anche neutri. |
| [FontRevision](../../aspose.font.ttftables/ttfheadtable/fontrevision) { get; } | Ottiene il fontRevision fisso impostato dal produttore del font. |
| [GlyphDataFormat](../../aspose.font.ttftables/ttfheadtable/glyphdataformat) { get; } | Ottiene int16 glyphDataFormat 0 per il formato corrente. |
| [IndexToLocFormat](../../aspose.font.ttftables/ttfheadtable/indextolocformat) { get; } | Ottiene int16 indexToLocFormat 0 per offset brevi, 1 per long. |
| [LowestRecPPEM](../../aspose.font.ttftables/ttfheadtable/lowestrecppem) { get; } | Ottiene uint16 lowerRecPPEM più piccola dimensione leggibile in pixel. |
| [MacStyle](../../aspose.font.ttftables/ttfheadtable/macstyle) { get; } | Ottiene uint16 macStyle. |
| [MagicNumber](../../aspose.font.ttftables/ttfheadtable/magicnumber) { get; } | Ottiene uint32 magicNumber impostato su 0x5F0F3CF5. |
| [Modified](../../aspose.font.ttftables/ttfheadtable/modified) { get; } | Ottiene la data internazionale modificata longDateTime. |
| [Offset](../../aspose.font.ttftables/ttftablebase/offset) { get; } | Ottiene l'offset dall'inizio di sfnt. |
| [TtfTables](../../aspose.font.ttftables/ttftablebase/ttftables) { get; } | Riferimento al repository di tabelle TTF. |
| [UnitsPerEM](../../aspose.font.ttftables/ttfheadtable/unitsperem) { get; } | Ottiene uint16 unitsPerEm range da 64 a 16384. |
| [Version](../../aspose.font.ttftables/ttfheadtable/version) { get; } | Versione fissa 0x00010000 se (versione 1.0). |
| [XMax](../../aspose.font.ttftables/ttfheadtable/xmax) { get; } | Ottiene FWord xMax per tutti i riquadri di delimitazione dei glifi. |
| [XMin](../../aspose.font.ttftables/ttfheadtable/xmin) { get; } | Ottiene FWord xMin per tutti i riquadri di delimitazione dei glifi. |
| [YMax](../../aspose.font.ttftables/ttfheadtable/ymax) { get; } | Ottiene FWord yMax per tutti i riquadri di delimitazione dei glifi. |
| [YMin](../../aspose.font.ttftables/ttfheadtable/ymin) { get; } | Ottiene FWord yMin per tutti i riquadri di delimitazione dei glifi. |
| static [Tag](../../aspose.font.ttftables/ttfheadtable/tag) { get; } | Ottiene il tag tabella. |

### Guarda anche

* class [TtfTableBase](../ttftablebase)
* spazio dei nomi [Aspose.Font.TtfTables](../../aspose.font.ttftables)
* assemblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->