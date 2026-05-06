---
title: "Aspose::Font::TtfTables::TtfStatTable::AxisValueTableFlags enum"
linktitle: "AxisValueTableFlags"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfStatTable::AxisValueTableFlags enum. Especifica los indicadores de tabla de valores de eje en C++."
type: docs
weight: 1200
url: /es/cpp/aspose.font.ttftables/ttfstattable/axisvaluetableflags/
---
## AxisValueTableFlags enum


Especifica los indicadores de la tabla de valores de eje.

```cpp
enum class AxisValueTableFlags : uint16_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| OlderSiblingFontAttribute | n/a | Si se establece, esta tabla de valores de eje proporciona información de valor de eje que es aplicable a otras fuentes dentro de la misma familia de fuentes. Se utiliza si las otras fuentes se publicaron antes y no incluían información sobre valores para algún eje. Si versiones más recientes de las otras fuentes incluyen la información por sí mismas y están presentes, entonces esta tabla se ignora. |
| ElidableAxisValueName | n/a | Si se establece, indica que el valor del eje representa el valor “normal” del eje y puede omitirse al componer cadenas de nombres. |
| Reservado | n/a | Reservado para uso futuro. |

## Ver también

* Class [TtfStatTable](../)
* Namespace [Aspose::Font::TtfTables](../../)
* Library [Aspose.Font for C++](../../../)
