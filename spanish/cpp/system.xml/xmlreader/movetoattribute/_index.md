---
title: "System::Xml::XmlReader::MoveToAttribute método"
linktitle: "MoveToAttribute"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlReader::MoveToAttribute método. Cuando se sobrescribe en una clase derivada, se mueve al atributo con el índice especificado en C++."
type: docs
weight: 3200
url: /es/cpp/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(int32_t) method


Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el índice especificado.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int32_t | El índice del atributo. |

## Ver también

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlReader::MoveToAttribute(String) method


Cuando se sobrescribe en una clase derivada, se mueve al atributo con el valor especificado de [XmlReader::get_Name](../get_name/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | Cadena | El nombre calificado del atributo. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlReader::MoveToAttribute(String, String) method


Cuando se sobrescribe en una clase derivada, se mueve al atributo con los valores especificados de [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | Cadena | El nombre local del atributo. |
| ns | Cadena | El URI del espacio de nombres del atributo. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
