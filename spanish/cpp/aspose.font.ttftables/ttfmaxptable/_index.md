---
title: "Clase Aspose::Font::TtfTables::TtfMaxpTable"
linktitle: "TtfMaxpTable"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::TtfTables::TtfMaxpTable. Representa la tabla \"maxp\" del archivo de fuente TTF en C++."
type: docs
weight: 1200
url: /es/cpp/aspose.font.ttftables/ttfmaxptable/
---
## TtfMaxpTable class


Representa la tabla "maxp" del archivo [Font](../../aspose.font/font/) TTF.

```cpp
class TtfMaxpTable : public Aspose::Font::TtfTables::TtfTableBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_MaxComponentContours](./get_maxcomponentcontours/)() const | Obtiene uint16 maxComponentContours contornos en un glifo compuesto. |
| [get_MaxComponentDepth](./get_maxcomponentdepth/)() const | Obtiene uint16 maxComponentDepth niveles de recursión, establezca a 0 si la fuente solo tiene glifos simples. |
| [get_MaxComponentElements](./get_maxcomponentelements/)() const | Obtiene uint16 maxComponentElements número de glifos referenciados en el nivel superior. |
| [get_MaxComponentPoints](./get_maxcomponentpoints/)() const | Obtiene uint16 maxComponentPoints puntos en un glifo compuesto. |
| [get_MaxContours](./get_maxcontours/)() const | Obtiene uint16 maxContours contornos en un glifo no compuesto. |
| [get_MaxFunctionDefs](./get_maxfunctiondefs/)() const | Obtiene uint16 maxFunctionDefs número de FDEFs. |
| [get_MaxInstructionDefs](./get_maxinstructiondefs/)() const | Obtiene el número uint16 maxInstructionDefs de IDEFs. |
| [get_MaxPoints](./get_maxpoints/)() const | Obtiene uint16 maxPoints puntos en glifo no compuesto. |
| [get_MaxSizeOfInstructions](./get_maxsizeofinstructions/)() const | Obtiene uint16 maxSizeOfInstructions recuento de bytes para instrucciones de glifo. |
| [get_MaxStackElements](./get_maxstackelements/)() const | Obtiene uint16 maxStackElements profundidad máxima de la pila. |
| [get_MaxStorage](./get_maxstorage/)() const | Obtiene uint16 maxStorage número de ubicaciones del Área de Almacenamiento. |
| [get_MaxTwilightPoints](./get_maxtwilightpoints/)() const | Obtiene uint16 maxTwilightPoints puntos usados en la Zona Crepuscular (Z0). |
| [get_MaxZones](./get_maxzones/)() const | Obtiene uint16 maxZones establecido en 2. |
| [get_NumGlyphs](./get_numglyphs/)() const | Obtiene uint16 numGlyphs el número de glifos en el [Font](../../aspose.font/font/). |
| [get_TableVersion](./get_tableversion/)() const | Obtiene la versión del formato. Use las propiedades MajorNumber y MinorNUmber del objeto [Version16Dot16](../) en notación hexadecimal para detectar la versión utilizada. |
| static [get_Tag](./get_tag/)() | Obtiene la etiqueta de la tabla. |
| [get_Version](./get_version/)() const | Obtiene la versión fija 0x00010000 si (versión 1.0). Obsoleto, use la propiedad [TableVersion](../) en su lugar. |
## Ver también

* Class [TtfTableBase](../ttftablebase/)
* Namespace [Aspose::Font::TtfTables](../)
* Library [Aspose.Font for C++](../../)
