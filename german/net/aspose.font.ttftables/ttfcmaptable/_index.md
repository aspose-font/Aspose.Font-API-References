---
title: TtfCMapTable
second_title: Aspose.Font für .NET-API-Referenz
description: Repräsentiert die cmapTabelle der TTFSchriftartdatei.
type: docs
weight: 760
url: /de/net/aspose.font.ttftables/ttfcmaptable/
---
## TtfCMapTable class

Repräsentiert die „cmap“-Tabelle der TTF-Schriftartdatei.

```csharp
public class TtfCMapTable : TtfTableBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Offset](../../aspose.font.ttftables/ttftablebase/offset) { get; } | Ruft Offset vom Anfang von sfnt. ab |
| [TtfTables](../../aspose.font.ttftables/ttftablebase/ttftables) { get; } | Verweis auf TTF-Tabellen-Repository. |
| static [Tag](../../aspose.font.ttftables/ttfcmaptable/tag) { get; } | Ruft Tabellen-Tag ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindUnicodeTable](../../aspose.font.ttftables/ttfcmaptable/findunicodetable)() | Sucht Unicode-CMap und gibt sie zurück. wenn ucs-4 CMap vorhanden ist – gibt sie zuerst zurück; andernfalls – gibt alle Unicode-CMaps zurück, die sie finden kann. |
| [GetAllSubtables](../../aspose.font.ttftables/ttfcmaptable/getallsubtables)() | Gibt alle Untertabellen aus der CMap-Tabelle zurück. |
| [GetPlatformTables](../../aspose.font.ttftables/ttfcmaptable/getplatformtables)(ushort, ushort) | Gibt CMap-Untertabellen für planformId und platformSpecificId zurück. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| abstract class [TtfCMapSubtableDescription](ttfcmaptable.ttfcmapsubtabledescription) | Bietet kurze Informationen über die CMap-Untertabelle. |

### Siehe auch

* class [TtfTableBase](../ttftablebase)
* namensraum [Aspose.Font.TtfTables](../../aspose.font.ttftables)
* Montage [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
