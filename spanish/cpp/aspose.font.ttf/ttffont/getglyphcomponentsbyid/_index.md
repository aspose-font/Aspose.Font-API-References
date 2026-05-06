---
title: "Aspose::Font::Ttf::TtfFont::GetGlyphComponentsById method"
linktitle: "GetGlyphComponentsById"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Ttf::TtfFont::GetGlyphComponentsById method. Obtiene un glifo mediante el identificador de glifo proporcionado y llena la lista de identificadores de glifos proporcionada con los componentes de este glifo. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo de una fuente TTF puede ser una instancia de la clase (GlyphStringId) o de la clase (GlyphUInt32Id). La dirección de glifos por nombre (string) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de que haya una fuente CFF dentro, se utilizan las estructuras CFF para direccionar glifos por nombre en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.font.ttf/ttffont/getglyphcomponentsbyid/
---
## TtfFont::GetGlyphComponentsById(System::SharedPtr\<Glyphs::GlyphId\>, System::SharedPtr\<Glyphs::GlyphIdList\>) method


Obtiene un glifo mediante el identificador de glifo proporcionado y llena la lista de identificadores de glifos proporcionada con los componentes de este glifo. El id del glifo es un número único para un glifo, que depende del tipo de fuente. El id de glifo de una fuente TTF [Font](../../../aspose.font/font/) puede ser una instancia de la clase ([GlyphStringId](../)) o de la clase ([GlyphUInt32Id](../)). La dirección de glifos por nombre (string) es compatible con fuentes TTF mediante el mapeo de la tabla Post. En caso de que haya una fuente CFF [Font](../../../aspose.font/font/) dentro, se utilizan las estructuras CFF para direccionar glifos por nombre.

```cpp
virtual void Aspose::Font::Ttf::TtfFont::GetGlyphComponentsById(System::SharedPtr<Glyphs::GlyphId> id, System::SharedPtr<Glyphs::GlyphIdList> componentsToPopulate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | System::SharedPtr\<Glyphs::GlyphId\> | Id del glifo. |
| componentsToPopulate | System::SharedPtr\<Glyphs::GlyphIdList\> | Lista de identificadores de glifos a llenar. |
## Observaciones


Se debe pasar una colección vacía componentsToPopulate que contendrá la lista de ids de componentes de glifos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphId](../../../aspose.font.glyphs/glyphid/)
* Class [GlyphIdList](../../../aspose.font.glyphs/glyphidlist/)
* Class [TtfFont](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
## TtfFont::GetGlyphComponentsById(System::String, System::SharedPtr\<Glyphs::GlyphIdList\>) method


Obtiene un glifo por el nombre de glifo proporcionado y llena la lista de identificadores de glifos pasada con los componentes de este glifo.

```cpp
void Aspose::Font::Ttf::TtfFont::GetGlyphComponentsById(System::String glyphName, System::SharedPtr<Glyphs::GlyphIdList> componentsToPopulate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| glyphName | System::String | Nombre del glifo. |
| componentsToPopulate | System::SharedPtr\<Glyphs::GlyphIdList\> | Lista de identificadores de glifos a llenar. |
## Observaciones


Se debe pasar una colección vacía componentsToPopulate que contendrá la lista de ids de componentes de glifos.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphIdList](../../../aspose.font.glyphs/glyphidlist/)
* Class [TtfFont](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
## TtfFont::GetGlyphComponentsById(uint32_t, System::SharedPtr\<Glyphs::GlyphIdList\>) method


Obtiene un glifo por el índice de glifo proporcionado y llena la lista de identificadores de glifos pasada con los componentes de este glifo.

```cpp
void Aspose::Font::Ttf::TtfFont::GetGlyphComponentsById(uint32_t id, System::SharedPtr<Glyphs::GlyphIdList> componentsToPopulate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | uint32_t | Índice del glifo. |
| componentsToPopulate | System::SharedPtr\<Glyphs::GlyphIdList\> | Lista de identificadores de glifos a llenar. |
## Observaciones


Se debe pasar una colección vacía componentsToPopulate que contendrá la lista de ids de componentes de glifos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GlyphIdList](../../../aspose.font.glyphs/glyphidlist/)
* Class [TtfFont](../)
* Namespace [Aspose::Font::Ttf](../../)
* Library [Aspose.Font for C++](../../../)
