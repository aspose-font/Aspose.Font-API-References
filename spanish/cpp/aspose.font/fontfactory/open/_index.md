---
title: "Método Aspose::Font::FontFactory::Open"
linktitle: "Open"
second_title: "Aspose.Font para C++"
description: "Método Aspose::Font::FontFactory::Open. Abre una fuente, usando el tipo de fuente y el arreglo de bytes de datos de la fuente en C++."
type: docs
weight: 200
url: /es/cpp/aspose.font/fontfactory/open/
---
## FontFactory::Open(FontType, System::ArrayPtr\<uint8_t\>) method


Abre una fuente, usando el tipo de fuente y la matriz de bytes de datos de la fuente.

```cpp
System::SharedPtr<Font> Aspose::Font::FontFactory::Open(FontType fontType, System::ArrayPtr<uint8_t> fontData)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontType | FontType | [Font](../../font/) tipo. |
| fontData | System::ArrayPtr\<uint8_t\> | Arreglo de bytes para cargar la fuente. |

### ReturnValue

[Font](../../font/) loaded.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Enum [FontType](../../fonttype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FontFactory](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
## FontFactory::Open(FontType, System::SharedPtr\<Sources::StreamSource\>) method


Abre una fuente, usando el tipo de fuente y la fuente de flujo.

```cpp
System::SharedPtr<Font> Aspose::Font::FontFactory::Open(FontType fontType, System::SharedPtr<Sources::StreamSource> fontStreamSource)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontType | FontType | [Font](../../font/) tipo. |
| fontStreamSource | System::SharedPtr\<Sources::StreamSource\> | Fuente de flujo para la fuente. |

### ReturnValue

[Font](../../font/) loaded.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Enum [FontType](../../fonttype/)
* Class [StreamSource](../../../aspose.font.sources/streamsource/)
* Class [FontFactory](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
## FontFactory::Open(FontType, System::String) method


Abre una fuente, usando el tipo de fuente y el nombre del archivo de fuente.

```cpp
System::SharedPtr<Font> Aspose::Font::FontFactory::Open(FontType fontType, System::String fileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontType | FontType | [Font](../../font/) tipo. |
| fileName | System::String | [Font](../../font/) nombre de archivo. |

### ReturnValue

[Font](../../font/) loaded.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Enum [FontType](../../fonttype/)
* Class [String](../../../system/string/)
* Class [FontFactory](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
## FontFactory::Open(System::SharedPtr\<Sources::FontDefinition\>) method


Abre una fuente, usando el objeto FontDefinition.

```cpp
System::SharedPtr<Font> Aspose::Font::FontFactory::Open(System::SharedPtr<Sources::FontDefinition> fontDefinition)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontDefinition | System::SharedPtr\<Sources::FontDefinition\> | [Font](../../font/) objeto de definición. |

### ReturnValue

[Font](../../font/) loaded.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [FontDefinition](../../../aspose.font.sources/fontdefinition/)
* Class [FontFactory](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
