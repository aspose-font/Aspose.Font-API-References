---
title: "Método System::Xml::XmlReader::get_LocalName"
linktitle: "get_LocalName"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlReader::get_LocalName. Cuando se sobrescribe en una clase derivada, obtiene el nombre local del nodo actual en C++."
type: docs
weight: 1400
url: /es/cpp/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName method


Cuando se sobrescribe en una clase derivada, obtiene el nombre local del nodo actual.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### ReturnValue

El nombre del nodo actual sin el prefijo. Por ejemplo, **LocalName** es **book** para el elemento **<bk:book>**. Para tipos de nodo que no tienen nombre (como **[Text](../../../system.text/)**, **Comment**, etc.), este método devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
