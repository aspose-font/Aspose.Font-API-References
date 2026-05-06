---
title: "Aspose::Font::TtfTables::TtfHmtxTable clase"
linktitle: "TtfHmtxTable"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::TtfTables::TtfHmtxTable. Representa la tabla \"hmtx\" del archivo de fuente TTF en C++."
type: docs
weight: 900
url: /es/cpp/aspose.font.ttftables/ttfhmtxtable/
---
## TtfHmtxTable class


Representa la tabla "hmtx" del archivo de [Font](../../aspose.font/font/) TTF.

```cpp
class TtfHmtxTable : public Aspose::Font::TtfTables::TtfTableBase
```

## Nested classes

* Class [LongHorMetric](./longhormetric/)
* Class [MetricList](./metriclist/)
## Métodos

| Método | Descripción |
| --- | --- |
| [get_AdditionalAdvanceWidth](./get_additionaladvancewidth/)() | En la tabla hmtx pueden existir casos en los que el número total de glifos no sea igual a hhea.numberOfHMetrics. Para estos casos la tabla hmtx contiene una matriz adicional 'leftSideBearing' que corresponde a la propiedad [LeftSidebearings](../). Pero los glifos con índices desde hhea.numOfLongHorMetrics hasta maxp.numGlyphs también tienen anchuras. Y estas anchuras, de acuerdo con la especificación de la tabla hmtx, tienen los siguientes valores: "Aquí se asume que advanceWidth es el mismo que el advanceWidth de la última entrada anterior". |
| [get_HMetrics](./get_hmetrics/)() | Obtiene métricas horizontales. |
| [get_LeftSidebearings](./get_leftsidebearings/)() | Obtiene los bearings laterales izquierdos. |
| static [get_Tag](./get_tag/)() | Obtiene la etiqueta de la tabla. |
## Ver también

* Class [TtfTableBase](../ttftablebase/)
* Namespace [Aspose::Font::TtfTables](../)
* Library [Aspose.Font for C++](../../)
