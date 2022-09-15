---
title: TtfHeadTable
second_title: Aspose.Font för .NET API-referens
description: Representerar headtabellen för TTF Fontfilen.
type: docs
weight: 820
url: /sv/net/aspose.font.ttftables/ttfheadtable/
---
## TtfHeadTable class

Representerar "head"-tabellen för TTF Font-filen.

```csharp
public class TtfHeadTable : TtfTableBase
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CheckSumAdjustment](../../aspose.font.ttftables/ttfheadtable/checksumadjustment) { get; } | Hämtar uint32 checkSumAdjustment. För att beräkna: ställ in den till 0, beräkna kontrollsumman för 'head'-tabellen och lägg den i tabellkatalogen, summera hela teckensnittet som uint32, lagra sedan B1B0AFBA - summa. Kontrollsumman för "huvud"-tabellen kommer inte att vara fel. Det är okej. |
| [Created](../../aspose.font.ttftables/ttfheadtable/created) { get; } | Får longDateTime skapat internationellt datum. |
| [Flags](../../aspose.font.ttftables/ttfheadtable/flags) { get; } | Får uint16-flaggor. |
| [FontDirectionHint](../../aspose.font.ttftables/ttfheadtable/fontdirectionhint) { get; } | Får int16 fontDirectionHint. 0 Mixed directional glyphs; 1 Endast starkt vänster till höger glyphs; 2 Gillar 1 men innehåller också neutrala; -1 Endast starkt höger till vänster glyphs. |
| [FontRevision](../../aspose.font.ttftables/ttfheadtable/fontrevision) { get; } | Får fast fontRevision inställd av teckensnittstillverkaren. |
| [GlyphDataFormat](../../aspose.font.ttftables/ttfheadtable/glyphdataformat) { get; } | Får int16 glyphDataFormat 0 för nuvarande format. |
| [IndexToLocFormat](../../aspose.font.ttftables/ttfheadtable/indextolocformat) { get; } | Får int16 indexToLocFormat 0 för korta offset, 1 för long. |
| [LowestRecPPEM](../../aspose.font.ttftables/ttfheadtable/lowestrecppem) { get; } | Får uint16 lowestRecPPEM minsta läsbara storlek i pixlar. |
| [MacStyle](../../aspose.font.ttftables/ttfheadtable/macstyle) { get; } | Får uint16 macStyle. |
| [MagicNumber](../../aspose.font.ttftables/ttfheadtable/magicnumber) { get; } | Får uint32 magicNumber satt till 0x5F0F3CF5. |
| [Modified](../../aspose.font.ttftables/ttfheadtable/modified) { get; } | Får longDateTime modifierat internationellt datum. |
| [Offset](../../aspose.font.ttftables/ttftablebase/offset) { get; } | Förskjuts från början av sfnt. |
| [TtfTables](../../aspose.font.ttftables/ttftablebase/ttftables) { get; } | Referens till TTF-tabellförråd. |
| [UnitsPerEM](../../aspose.font.ttftables/ttfheadtable/unitsperem) { get; } | Får uint16 unitsPerEm-intervall från 64 till 16384. |
| [Version](../../aspose.font.ttftables/ttfheadtable/version) { get; } | Fast version 0x00010000 if (version 1.0). |
| [XMax](../../aspose.font.ttftables/ttfheadtable/xmax) { get; } | Får FWord xMax för alla glyph bounding boxes. |
| [XMin](../../aspose.font.ttftables/ttfheadtable/xmin) { get; } | Får FWord xMin för alla glyph bounding boxes. |
| [YMax](../../aspose.font.ttftables/ttfheadtable/ymax) { get; } | Får FWord yMax för alla glyph bounding boxes. |
| [YMin](../../aspose.font.ttftables/ttfheadtable/ymin) { get; } | Hämtar FWord yMin för alla glyph bounding boxes. |
| static [Tag](../../aspose.font.ttftables/ttfheadtable/tag) { get; } | Får tabelltagg. |

### Se även

* class [TtfTableBase](../ttftablebase)
* namnutrymme [Aspose.Font.TtfTables](../../aspose.font.ttftables)
* hopsättning [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->