---
title: "Método System::Xml::XmlUrlResolver::ResolveUri"
linktitle: "ResolveUri"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlUrlResolver::ResolveUri. Resuelve el URI absoluto a partir de los URIs base y relativo en C++."
type: docs
weight: 300
url: /es/cpp/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri method


Resuelve el URI absoluto a partir de los URIs base y relativo.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | El URI base utilizado para resolver el URI relativo. |
| relativeUri | Cadena | El URI a resolver. El URI puede ser absoluto o relativo. Si es absoluto, este valor reemplaza efectivamente el valor de **baseUri**. Si es relativo, se combina con **baseUri** para crear un URI absoluto. |

### ReturnValue

El URI absoluto, o **nullptr** si el URI relativo no puede resolverse.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
