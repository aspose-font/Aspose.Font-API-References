---
title: "System::Xml::XmlNodeChangedEventArgs::get_OldParent método"
linktitle: "get_OldParent"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlNodeChangedEventArgs::get_OldParent método. Devuelve el valor de XmlNode::get_ParentNode antes de que la operación comience en C++."
type: docs
weight: 600
url: /es/cpp/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent method


Devuelve el valor de [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) antes de que la operación comience.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### ReturnValue

El valor de **ParentNode** antes de que la operación comience. Este método devuelve **nullptr** si el nodo no tenía un padre. Para nodos de atributo, este método devuelve el valor de [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
