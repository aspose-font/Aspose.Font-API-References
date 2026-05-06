---
title: "System::Xml::XmlDocument::CreateElement method"
linktitle: "CreateElement"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlDocument::CreateElement method. Crea un elemento con el nombre especificado en C++."
type: docs
weight: 800
url: /es/cpp/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) method


Crea un elemento con el nombre especificado.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const String\& | El nombre calificado del elemento. Si el nombre contiene dos puntos, el valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) refleja la parte del nombre que precede a los dos puntos y el valor [XmlDocument::get_LocalName](../get_localname/) refleja la parte del nombre que sigue a los dos puntos. El nombre calificado no puede incluir un prefijo de **xmlns**. |

### ReturnValue

El nuevo [XmlElement](../../xmlelement/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlDocument::CreateElement(const String\&, const String\&, const String\&) method


Crea un elemento con el [XmlNode::get_Prefix](../../xmlnode/get_prefix/) especificado, el [XmlDocument::get_LocalName](../get_localname/) y el [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const String\& | El prefijo del nuevo elemento (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |
| localName | const String\& | El nombre local del nuevo elemento. |
| namespaceURI | const String\& | El URI del espacio de nombres del nuevo elemento (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |

### ReturnValue

El nuevo [XmlElement](../../xmlelement/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlDocument::CreateElement(const String\&, const String\&) method


Crea un [XmlElement](../../xmlelement/) con el nombre calificado y el [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| qualifiedName | const String\& | El nombre calificado del elemento. Si el nombre contiene dos puntos, el valor de [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflejará la parte del nombre que precede a los dos puntos y el valor de [XmlDocument::get_LocalName](../get_localname/) reflejará la parte del nombre que sigue a los dos puntos. El nombre calificado no puede incluir un prefijo de **xmlns**. |
| namespaceURI | const String\& | El URI del espacio de nombres del elemento. |

### ReturnValue

El nuevo [XmlElement](../../xmlelement/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
