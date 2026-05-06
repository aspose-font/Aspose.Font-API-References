---
title: "Método System::Xml::XmlTextReader::ReadChars"
linktitle: "ReadChars"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlTextReader::ReadChars. Lee el contenido de texto de un elemento en un búfer de caracteres. Este método está diseñado para leer flujos grandes de texto incrustado llamándolo sucesivamente en C++."
type: docs
weight: 4600
url: /es/cpp/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars method


Lee el contenido de texto de un elemento en un búfer de caracteres. Este método está diseñado para leer grandes flujos de texto incrustado llamándolo sucesivamente.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const ArrayPtr\<char16_t\>\& | La matriz de caracteres que sirve como búfer al que se escribe el contenido de texto. |
| índice | int32_t | La posición dentro del **buffer** donde el método puede comenzar a escribir el contenido de texto. |
| count | int32_t | El número de caracteres a escribir en el **buffer**. |

### ReturnValue

El número de caracteres leídos. Puede ser 0 si el lector no está posicionado en un elemento o si no hay más contenido de texto que devolver en el contexto actual.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
