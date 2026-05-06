---
title: "clase Aspose::Font::TtfTables::TtfCMapTable"
linktitle: "TtfCMapTable"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::TtfTables::TtfCMapTable. Representa la tabla \"cmap\" del archivo de fuente TTF en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font.ttftables/ttfcmaptable/
---
## TtfCMapTable class


Representa la tabla "cmap" del archivo TTF [Font](../../aspose.font/font/).

```cpp
class TtfCMapTable : public Aspose::Font::TtfTables::TtfTableBase
```

## Nested classes

* Class [TtfCMapSubtableDescription](./ttfcmapsubtabledescription/)
## Métodos

| Método | Descripción |
| --- | --- |
| [FindUnicodeTable](./findunicodetable/)() | Busca y devuelve el CMap unicode. si hay un CMap ucs-4, lo devuelve primero; de lo contrario, devuelve cualquier CMap unicode que pueda encontrar. |
| static [get_Tag](./get_tag/)() | Obtiene la etiqueta de la tabla. |
| [GetAllSubtables](./getallsubtables/)() | Devuelve todas las subtablas de la tabla CMap. |
| [GetPlatformTables](./getplatformtables/)(uint16_t, uint16_t) | Devuelve las subtablas CMap para planformId y platformSpecificId. |
## Ver también

* Class [TtfTableBase](../ttftablebase/)
* Namespace [Aspose::Font::TtfTables](../)
* Library [Aspose.Font for C++](../../)
