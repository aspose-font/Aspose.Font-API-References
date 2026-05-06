---
title: "System::Xml::XmlResolver::ResolveUri método"
linktitle: "ResolveUri"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlResolver::ResolveUri método. Cuando se sobrescribe en una clase derivada, resuelve el URI absoluto a partir de los URIs base y relativo en C++."
type: docs
weight: 200
url: /es/cpp/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri method


Cuando se sobrescribe en una clase derivada, resuelve el URI absoluto a partir del base y los URIs relativos.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | El URI base utilizado para resolver el URI relativo. |
| relativeUri | Cadena | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor de **baseUri**. Si es relativo, se combina con **baseUri** para crear un URI absoluto. |

### ReturnValue

El URI absoluto o **nullptr** si no se puede resolver el URI relativo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
