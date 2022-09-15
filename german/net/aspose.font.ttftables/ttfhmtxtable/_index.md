---
title: TtfHmtxTable
second_title: Aspose.Font für .NET-API-Referenz
description: Repräsentiert die hmtxTabelle der TTFSchriftartdatei.
type: docs
weight: 840
url: /de/net/aspose.font.ttftables/ttfhmtxtable/
---
## TtfHmtxTable class

Repräsentiert die „hmtx“-Tabelle der TTF-Schriftartdatei.

```csharp
public class TtfHmtxTable : TtfTableBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdditionalAdvanceWidth](../../aspose.font.ttftables/ttfhmtxtable/additionaladvancewidth) { get; } | In der hmtx-Tabelle können Fälle auftreten, in denen die Gesamtzahl der Glyphen nicht gleich hhea.numberOfHMetrics ist. Für diese Fälle enthält die hmtx-Tabelle zusätzlich array 'leftSideBearing', das der Eigenschaft entspricht[`LeftSidebearings`](./leftsidebearings) . Aber Glyphen mit Indizes von hhea.numOfLongHorMetrics bis maxp.numGlyphs haben auch Breiten. Und diese Breiten gemäß der Spezifikation für die hmtx-Tabelle haben solche Werte: "Hier wird angenommen, dass die advanceWidth die gleiche ist wie die advanceWidth für den letzten Eintrag oben". |
| [HMetrics](../../aspose.font.ttftables/ttfhmtxtable/hmetrics) { get; } | Ruft horizontale Messwerte ab. |
| [LeftSidebearings](../../aspose.font.ttftables/ttfhmtxtable/leftsidebearings) { get; } | Peilung auf der linken Seite. |
| [Offset](../../aspose.font.ttftables/ttftablebase/offset) { get; } | Ruft Offset vom Anfang von sfnt. ab |
| [TtfTables](../../aspose.font.ttftables/ttftablebase/ttftables) { get; } | Verweis auf TTF-Tabellen-Repository. |
| static [Tag](../../aspose.font.ttftables/ttfhmtxtable/tag) { get; } | Ruft Tabellen-Tag ab. |

### Siehe auch

* class [TtfTableBase](../ttftablebase)
* namensraum [Aspose.Font.TtfTables](../../aspose.font.ttftables)
* Montage [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->