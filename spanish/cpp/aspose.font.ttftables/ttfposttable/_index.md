---
title: "Clase Aspose::Font::TtfTables::TtfPostTable"
linktitle: "TtfPostTable"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::TtfTables::TtfPostTable. Representa la tabla \"post\" del archivo de fuente TTF en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.font.ttftables/ttfposttable/
---
## TtfPostTable class


Representa la tabla "post" del archivo de [Font](../../aspose.font/font/) TTF.

```cpp
class TtfPostTable : public Aspose::Font::TtfTables::TtfTableBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Format](./get_format/)() | Obtiene el formato fijo (versión) de esta tabla. Obsoleto, use la propiedad [TableFormat](../). |
| [get_HasNoPostScriptNames](./get_hasnopostscriptnames/)() | Indica que no se proporciona información de nombre PostScript para los glifos en este archivo de fuente. |
| [get_IsFixedPitch](./get_isfixedpitch/)() | Obtiene uint32 isFixedPitch. 0 si la fuente tiene espaciado proporcional, distinto de cero si la fuente no tiene espaciado proporcional (es decir, monoespaciada). |
| [get_ItalicAngle](./get_italicangle/)() | Obtiene el ángulo italicAngle fijo. Ángulo en grados. |
| [get_MaxMemType1](./get_maxmemtype1/)() | Obtiene uint32 maxMemType1. Uso máximo de memoria cuando una fuente TrueType se descarga como una [Font](../../aspose.font/font/) Tipo 1. |
| [get_MaxMemType42](./get_maxmemtype42/)() | Obtiene uint32 maxMemType42. Uso máximo de memoria cuando una fuente TrueType se descarga como una [Font](../../aspose.font/font/) Tipo 42. |
| [get_MinMemType1](./get_minmemtype1/)() | Obtiene uint32 minMemType1. Uso mínimo de memoria cuando una fuente TrueType se descarga como una [Font](../../aspose.font/font/) Tipo 1. |
| [get_MinMemType42](./get_minmemtype42/)() | Obtiene uint32 minMemType42. Uso mínimo de memoria cuando una fuente TrueType se descarga como una [Font](../../aspose.font/font/) Tipo 42. |
| [get_TableFormat](./get_tableformat/)() | Obtiene el formato fijo (versión) de esta tabla. Use las propiedades MajorNumber y MinorNUmber del objeto [Version16Dot16](../) en notación hexadecimal para detectar la versión utilizada. |
| static [get_Tag](./get_tag/)() | Obtiene la etiqueta de la tabla. |
| [get_UnderlinePosition](./get_underlineposition/)() | Obtiene el valor FWord underlinePosition. |
| [get_UnderlineThickness](./get_underlinethickness/)() | Obtiene el valor FWord underlineThickness. |
| [GetAllGlyphIndexesForGlyphName](./getallglyphindexesforglyphname/)(System::String) | Obtiene una matriz de índices de glifos por nombre de glifo. |
| [GetGlyphIndex](./getglyphindex/)(System::String) | Obtiene el índice del glifo por nombre de glifo. |
| [GetGlyphName](./getglyphname/)(uint32_t) | Obtiene el nombre del glifo por índice de glifo. |
## Ver también

* Class [TtfTableBase](../ttftablebase/)
* Namespace [Aspose::Font::TtfTables](../)
* Library [Aspose.Font for C++](../../)
