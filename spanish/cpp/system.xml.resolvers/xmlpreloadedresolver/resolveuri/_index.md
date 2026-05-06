---
title: "System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri método"
linktitle: "ResolveUri"
second_title: "Aspose.Font para C++"
description: "System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri método. Resuelve el URI absoluto a partir de los URIs base y relativo en C++."
type: docs
weight: 600
url: /es/cpp/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri method


Resuelve el URI absoluto a partir de los URIs base y relativo.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | El URI base utilizado para resolver el URI relativo. |
| relativeUri | Cadena | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor de **baseUri**. Si es relativo, se combina con **baseUri** para crear un URI absoluto. |

### ReturnValue

El [Uri](../../../system/uri/) que representa el URI absoluto o **nullptr** si el URI relativo no puede resolverse.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Font for C++](../../../)
