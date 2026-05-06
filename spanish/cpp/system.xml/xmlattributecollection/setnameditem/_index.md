---
title: "Método SetNamedItem de System::Xml::XmlAttributeCollection"
linktitle: "SetNamedItem"
second_title: "Aspose.Font para C++"
description: "Método SetNamedItem de System::Xml::XmlAttributeCollection. Añade un XmlNode usando el resultado de su XmlNode::get_Name en C++."
type: docs
weight: 1000
url: /es/cpp/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem method


Añade un [XmlNode](../../xmlnode/) usando el resultado de su [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | SharedPtr\<XmlNode\> | Un nodo de atributo para almacenar en esta colección. El nodo será accesible posteriormente mediante el nombre del nodo. Si ya existe un nodo con ese nombre en la colección, se reemplaza por el nuevo; de lo contrario, el nodo se agrega al final de la colección. |

### ReturnValue

Si el **node** reemplaza a un nodo existente con el mismo nombre, se devuelve el nodo antiguo; de lo contrario, se devuelve el nodo añadido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
