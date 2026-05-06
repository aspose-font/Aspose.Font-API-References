---
title: "Método System::Xml::XmlEntity::CloneNode"
linktitle: "CloneNode"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlEntity::CloneNode. Crea una copia de este nodo. Los nodos de entidad no pueden ser clonados. Llamar a este método sobre un objeto XmlEntity lanza una excepción en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode method


Crea una copia de este nodo. Los nodos de entidad no pueden ser clonados. Llamar a este método sobre un objeto [XmlEntity](../) lanza una excepción.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| profundo | bool | **true** para clonar recursivamente el subárbol bajo el nodo especificado; **false** para clonar solo el nodo mismo. |

### ReturnValue

Una copia del [XmlNode](../../xmlnode/) desde el cual se llama al método.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntity](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
