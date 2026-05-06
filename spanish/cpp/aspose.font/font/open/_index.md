---
title: "Aspose::Font::Font::Open method"
linktitle: "Open"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Font::Open method. Abre una fuente, usando el tipo de fuente y la matriz de bytes de datos de la fuente en C++."
type: docs
weight: 2400
url: /es/cpp/aspose.font/font/open/
---
## Font::Open(Aspose::Font::FontType, System::ArrayPtr\<uint8_t\>) method


Abre una fuente, usando el tipo de fuente y la matriz de bytes de datos de la fuente.

```cpp
static System::SharedPtr<Font> Aspose::Font::Font::Open(Aspose::Font::FontType fontType, System::ArrayPtr<uint8_t> fontData)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontType | Aspose::Font::FontType | Tipo de [Font](../). |
| fontData | System::ArrayPtr\<uint8_t\> | Arreglo de bytes para cargar la fuente. |

### ReturnValue

[Font](../) loaded.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Enum [FontType](../../fonttype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Font](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
## Font::Open(Aspose::Font::FontType, System::SharedPtr\<Sources::StreamSource\>) method


Abre una fuente, usando el tipo de fuente y la fuente de flujo.

```cpp
static System::SharedPtr<Font> Aspose::Font::Font::Open(Aspose::Font::FontType fontType, System::SharedPtr<Sources::StreamSource> fontStreamSource)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontType | Aspose::Font::FontType | Tipo de [Font](../). |
| fontStreamSource | System::SharedPtr\<Sources::StreamSource\> | Fuente de flujo para la fuente. |

### ReturnValue

[Font](../) loaded.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Enum [FontType](../../fonttype/)
* Class [StreamSource](../../../aspose.font.sources/streamsource/)
* Class [Font](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
## Font::Open(Aspose::Font::FontType, System::String) method


Abre una fuente, usando el tipo de fuente y el nombre del archivo de fuente.

```cpp
static System::SharedPtr<Font> Aspose::Font::Font::Open(Aspose::Font::FontType fontType, System::String fileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontType | Aspose::Font::FontType | Tipo de [Font](../). |
| fileName | System::String | Nombre de archivo de [Font](../). |

### ReturnValue

[Font](../) loaded.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Enum [FontType](../../fonttype/)
* Class [String](../../../system/string/)
* Class [Font](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
## Font::Open(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) method


Abre una fuente, usando el objeto FontDefinition.

```cpp
static System::SharedPtr<Font> Aspose::Font::Font::Open(System::SharedPtr<Aspose::Font::Sources::FontDefinition> fontDefinition)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontDefinition | System::SharedPtr\<Aspose::Font::Sources::FontDefinition\> | Objeto de definición de [Font](../). |

### ReturnValue

[Font](../) loaded.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontDefinition](../../../aspose.font.sources/fontdefinition/)
* Class [Font](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
