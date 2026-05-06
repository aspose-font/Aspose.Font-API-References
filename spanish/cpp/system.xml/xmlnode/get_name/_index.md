---
title: "System::Xml::XmlNode::get_Name método"
linktitle: "get_Name"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlNode::get_Name método. Devuelve el nombre calificado del nodo, cuando se sobrescribe en una clase derivada en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name method


Devuelve el nombre calificado del nodo, cuando se sobrescribe en una clase derivada.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### ReturnValue

El nombre calificado del nodo.
## Observaciones



El nombre devuelto depende del [XmlNode::get_NodeType](../get_nodetype/) del nodo: |||
|-|-|
| Tipo | Nombre |
| Atributo | El nombre calificado del atributo. |
| CDATA | #cdata-section |
| Comentario | #comment |
| Documento | #document |
| FragmentoDeDocumento | #document-fragment |
| TipoDeDocumento | El nombre del tipo de documento. |
| Elemento | El nombre calificado del elemento. |
| Entidad | El nombre de la entidad. |
| EntityReference | El nombre de la entidad referenciada. |
| Notación | El nombre de la notación. |
| InstrucciónDeProcesamiento | El objetivo de la instrucción de procesamiento. |
| Text | #text |
| EspacioEnBlanco | #whitespace |
| EspacioEnBlancoSignificativo | #significant-whitespace |
| XmlDeclaration | #xml-declaration |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
