---
title: "Aspose::Font::TtfTables::TtfHmtxTable::get_AdditionalAdvanceWidth method"
linktitle: "get_AdditionalAdvanceWidth"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfHmtxTable::get_AdditionalAdvanceWidth method. En la tabla hmtx pueden existir casos en los que el número total de glifos no es igual a hhea.numberOfHMetrics. Para estos casos la tabla hmtx contiene una matriz adicional ''leftSideBearing'' que corresponde a la propiedad LeftSidebearings. Pero los glifos con índices desde hhea.numOfLongHorMetrics hasta maxp.numGlyphs también tienen anchuras. Y estas anchuras, de acuerdo con la especificación de la tabla hmtx, tienen los siguientes valores: \"Here the advanceWidth is assumed to be the same as the advanceWidth for the last entry above\" en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.ttftables/ttfhmtxtable/get_additionaladvancewidth/
---
## TtfHmtxTable::get_AdditionalAdvanceWidth method


En la tabla hmtx pueden existir casos en los que el número total de glifos no sea igual a hhea.numberOfHMetrics. Para estos casos la tabla hmtx contiene una matriz adicional 'leftSideBearing' que corresponde a la propiedad [LeftSidebearings](../). Pero los glifos con índices desde hhea.numOfLongHorMetrics hasta maxp.numGlyphs también tienen anchuras. Y estas anchuras, de acuerdo con la especificación de la tabla hmtx, tienen los siguientes valores: "Aquí se asume que advanceWidth es el mismo que el advanceWidth de la última entrada anterior".

```cpp
uint16_t Aspose::Font::TtfTables::TtfHmtxTable::get_AdditionalAdvanceWidth()
```

## Ver también

* Class [TtfHmtxTable](../)
* Namespace [Aspose::Font::TtfTables](../../)
* Library [Aspose.Font for C++](../../../)
