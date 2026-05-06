---
title: "Método System::Xml::XmlConvert::ToDateTimeOffset"
linktitle: "ToDateTimeOffset"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlConvert::ToDateTimeOffset. Convierte la String proporcionada a un equivalente DateTimeOffset en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) method


Convierte la [String](../../../system/string/) proporcionada a un equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | La cadena a convertir. La cadena debe ajustarse a un subconjunto de la Recomendación W3C para el tipo XML dateTime. Para obtener más información, consulte la sección [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) del [Schema](../../../system.xml.schema/) XML. |

### ReturnValue

El equivalente [DateTimeOffset](../../../system/datetimeoffset/) de la cadena suministrada.

## Ver también

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) method


Convierte la [String](../../../system/string/) proporcionada a un equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | La cadena a convertir. |
| formats | const ArrayPtr\<String\>\& | Una matriz de formatos desde los cuales se puede convertir **s**. Cada formato en **formats** puede ser cualquier subconjunto de la Recomendación W3C para el tipo XML dateTime. Para obtener más información, consulte la sección [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) del [Schema](../../../system.xml.schema/) XML. La cadena **s** se valida contra uno de estos formatos. |

### ReturnValue

El equivalente [DateTimeOffset](../../../system/datetimeoffset/) de la cadena suministrada.

## Ver también

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlConvert::ToDateTimeOffset(const String\&, const String\&) method


Convierte la [String](../../../system/string/) proporcionada a un equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const String\& | La cadena a convertir. |
| format | const String\& | El formato desde el cual se convierte **s**. El parámetro format puede ser cualquier subconjunto de la Recomendación W3C para el tipo XML dateTime. Para obtener más información, consulte la sección [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) del [Schema](../../../system.xml.schema/) XML. La cadena **s** se valida contra este formato. |

### ReturnValue

El equivalente [DateTimeOffset](../../../system/datetimeoffset/) de la cadena suministrada.

## Ver también

* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
