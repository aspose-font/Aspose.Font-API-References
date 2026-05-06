---
title: "Clase Aspose::Font::TtfTables::TtfStatTable"
linktitle: "TtfStatTable"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::TtfTables::TtfStatTable. Representa la tabla de atributos de estilo (STAT) de la fuente OpenType en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.font.ttftables/ttfstattable/
---
## TtfStatTable class


Representa la tabla Style Attributes Table(STAT) de la fuente OpenType.

```cpp
class TtfStatTable : public Aspose::Font::TtfTables::TtfTableBase
```

## Nested classes

* Class [AxisRecord](./axisrecord/)
* Class [AxisValue](./axisvalue/)
* Class [AxisValueTableBase](./axisvaluetablebase/)
* Class [AxisValueTableFormat1](./axisvaluetableformat1/)
* Class [AxisValueTableFormat2](./axisvaluetableformat2/)
* Class [AxisValueTableFormat3](./axisvaluetableformat3/)
* Class [AxisValueTableFormat4](./axisvaluetableformat4/)
## Enums

| Enumeración | Descripción |
| --- | --- |
| [AxisValueTableFlags](./axisvaluetableflags/) | Especifica los indicadores de la tabla de valores de eje. |
## Métodos

| Método | Descripción |
| --- | --- |
| [AddAxisRecord](./addaxisrecord/)(System::SharedPtr\<TtfStatTable::AxisRecord\>) | Agrega una estructura Axis Record a la tabla. |
| [AddAxisValueTable](./addaxisvaluetable/)(System::SharedPtr\<TtfStatTable::AxisValueTableBase\>) | Agrega una estructura Axis Value Table a la tabla. |
| [ClearAxisRecords](./clearaxisrecords/)() | Elimina todos los registros de eje de la tabla. |
| [ClearAxisValueTables](./clearaxisvaluetables/)() | Elimina todas las tablas de valores de eje de la tabla. |
| [get_AxisRecords](./get_axisrecords/)() | Devuelve la matriz de ejes de diseño. La matriz de ejes es una matriz de estructuras del tipo Axis Record. Especificación: el registro de eje proporciona información sobre un solo eje de diseño. |
| [get_AxisValueCount](./get_axisvaluecount/)() | Devuelve el número de tablas de valores de eje. |
| [get_AxisValueTables](./get_axisvaluetables/)() | Devuelve una matriz de Axis Value Tables. Especificación: las Axis Value Tables proporcionan detalles sobre un valor de atributo de estilo específico en algún eje específico de variación de diseño, o una combinación de valores de ejes de variación de diseño, y la relación de esos valores con las etiquetas usadas como elementos en los nombres de subfamilia. |
| [get_DesignAxisCount](./get_designaxiscount/)() | Devuelve el número de registros de eje. Especificación: en una fuente con una tabla 'fvar', este valor debe ser mayor o igual que el valor axisCount en la tabla 'fvar'. En todas las fuentes, debe ser mayor que cero si axisValueCount es mayor que cero. |
| [get_ElidedFallbackName](./get_elidedfallbackname/)() | Especificación: Nombre usado como alternativa cuando la proyección de nombres en un modelo de fuente particular produce un nombre de subfamilia que contiene solo elementos elidibles. |
| [get_ElidedFallbackNameId](./get_elidedfallbacknameid/)() | Especificación: ID de nombre usado como alternativa cuando la proyección de nombres en un modelo de fuente particular produce un nombre de subfamilia que contiene solo elementos elidibles. |
| static [get_Tag](./get_tag/)() | Obtiene la etiqueta de la tabla. |
## Ver también

* Class [TtfTableBase](../ttftablebase/)
* Namespace [Aspose::Font::TtfTables](../)
* Library [Aspose.Font for C++](../../)
