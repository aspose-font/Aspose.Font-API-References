---
title: "System::Xml::XmlReader::ReadToFollowing método"
linktitle: "ReadToFollowing"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlReader::ReadToFollowing método. Lee hasta que se encuentre un elemento con el nombre local y el URI de espacio de nombres especificados en C++."
type: docs
weight: 7200
url: /es/cpp/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String, String) method


Lee hasta que se encuentre un elemento con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | Cadena | El nombre local del elemento. |
| namespaceURI | Cadena | El URI del espacio de nombres del elemento. |

### ReturnValue

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlReader::ReadToFollowing(String) method


Lee hasta que se encuentre un elemento con el nombre calificado especificado.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | Cadena | El nombre calificado del elemento. |

### ReturnValue

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
