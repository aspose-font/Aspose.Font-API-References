---
title: "System::Xml::ValidationType enum"
linktitle: "ValidationType"
second_title: "Aspose.Font para C++"
description: "System::Xml::ValidationType enum. Especifica el tipo de validación a realizar en C++."
type: docs
weight: 5500
url: /es/cpp/system.xml/validationtype/
---
## ValidationType enum


Especifica el tipo de validación a realizar.

```cpp
enum class ValidationType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | No se realiza ninguna validación, y no se generan errores de validación. Esta configuración crea un analizador sin validación compatible con XML 1.0. |
| Auto | 1 | Valida si se encuentra información DTD o de esquema. |
| DTD | 2 | Valida según el DTD. |
| XDR | 3 | Valida según los esquemas XML-Data Reduced (XDR), incluidos los esquemas XDR en línea. Los esquemas XDR se reconocen mediante el prefijo de espacio de nombres **x-schema** o el valor de [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Valida según los esquemas del lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD), incluidos los esquemas XML en línea. Los esquemas XML se asocian a URIs de espacio de nombres ya sea mediante el atributo **schemaLocation** o los **Schemas** proporcionados. |

## Ver también

* Namespace [System::Xml](../)
* Library [Aspose.Font for C++](../../)
