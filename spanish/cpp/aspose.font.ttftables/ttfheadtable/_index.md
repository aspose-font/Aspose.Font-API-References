---
title: "Aspose::Font::TtfTables::TtfHeadTable clase"
linktitle: "TtfHeadTable"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfTables::TtfHeadTable clase. Representa la tabla \"head\" del archivo de fuente TTF en C++."
type: docs
weight: 700
url: /es/cpp/aspose.font.ttftables/ttfheadtable/
---
## TtfHeadTable class


Representa la tabla "head" del archivo TTF [Font](../../aspose.font/font/)

```cpp
class TtfHeadTable : public Aspose::Font::TtfTables::TtfTableBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CheckSumAdjustment](./get_checksumadjustment/)() const | Obtiene uint32 checkSumAdjustment. Para calcularlo: establézcalo en 0, calcule la suma de verificación para la tabla 'head' y colóquela en el directorio de tablas, sume toda la fuente como uint32, luego almacene B1B0AFBA - suma. La suma de verificación para la tabla 'head' no será incorrecta. Eso está bien. |
| [get_Created](./get_created/)() const | Obtiene longDateTime fecha internacional de creación. |
| [get_Flags](./get_flags/)() const | Obtiene uint16 flags. |
| [get_FontDirectionHint](./get_fontdirectionhint/)() const | Obtiene int16 fontDirectionHint. 0 Glifos de dirección mixta; 1 Sólo glifos fuertemente de izquierda a derecha; 2 Como 1 pero también contiene neutrales; -1 Sólo glifos fuertemente de derecha a izquierda; -2 Como -1 pero también contiene neutrales. |
| [get_FontRevision](./get_fontrevision/)() const | Obtiene fixed fontRevision establecido por el fabricante de la fuente. |
| [get_GlyphDataFormat](./get_glyphdataformat/)() const | Obtiene int16 glyphDataFormat 0 para el formato actual. |
| [get_IndexToLocFormat](./get_indextolocformat/)() const | Obtiene int16 indexToLocFormat 0 para desplazamientos cortos, 1 para largos. |
| [get_LowestRecPPEM](./get_lowestrecppem/)() const | Obtiene uint16 lowestRecPPEM el tamaño legible más pequeño en píxeles. |
| [get_MacStyle](./get_macstyle/)() const | Obtiene uint16 macStyle. |
| [get_MagicNumber](./get_magicnumber/)() const | Obtiene uint32 magicNumber establecido en 0x5F0F3CF5. |
| [get_Modified](./get_modified/)() const | Obtiene longDateTime fecha internacional de modificación. |
| static [get_Tag](./get_tag/)() | Obtiene la etiqueta de la tabla. |
| [get_UnitsPerEM](./get_unitsperem/)() const | Obtiene uint16 unitsPerEm rango de 64 a 16384. |
| [get_Version](./get_version/)() const | Versión fija 0x00010000 si (versión 1.0). |
| [get_XMax](./get_xmax/)() const | Obtiene FWord xMax para todas las cajas delimitadoras de glifos. |
| [get_XMin](./get_xmin/)() const | Obtiene FWord xMin para todas las cajas delimitadoras de glifos. |
| [get_YMax](./get_ymax/)() const | Obtiene FWord yMax para todas las cajas delimitadoras de glifos. |
| [get_YMin](./get_ymin/)() const | Obtiene FWord yMin para todas las cajas delimitadoras de glifos. |
## Ver también

* Class [TtfTableBase](../ttftablebase/)
* Namespace [Aspose::Font::TtfTables](../)
* Library [Aspose.Font for C++](../../)
