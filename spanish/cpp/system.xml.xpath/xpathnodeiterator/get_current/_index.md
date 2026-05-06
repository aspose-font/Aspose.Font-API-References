---
title: "System::Xml::XPath::XPathNodeIterator::get_Current método"
linktitle: "get_Current"
second_title: "Aspose.Font para C++"
description: "System::Xml::XPath::XPathNodeIterator::get_Current método. Cuando se sobrescribe en una clase derivada, obtiene el objeto XPathNavigator para este XPathNodeIterator, posicionado en el nodo de contexto actual en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current method


Cuando se sobrescribe en una clase derivada, obtiene el objeto [XPathNavigator](../../xpathnavigator/) para este [XPathNodeIterator](../), posicionado en el nodo de contexto actual.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### ReturnValue

Un objeto [XPathNavigator](../../xpathnavigator/) posicionado en el nodo de contexto desde el cual se seleccionó el conjunto de nodos. El método [XPathNodeIterator::MoveNext](../movenext/) debe llamarse para mover el [XPathNodeIterator](../) al primer nodo del conjunto seleccionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../xpathnavigator/)
* Class [XPathNodeIterator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Font for C++](../../../)
