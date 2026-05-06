---
title: "Método System::Xml::XmlReader::get_Name"
linktitle: "get_Name"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlReader::get_Name. Cuando se sobrescribe en una clase derivada, obtiene el nombre calificado del nodo actual en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name method


Cuando se sobrescribe en una clase derivada, obtiene el nombre calificado del nodo actual.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### ReturnValue

El nombre calificado del nodo actual. Por ejemplo, **Name** es **bk:book** para el elemento **<bk:book>**.
## Observaciones



El nombre devuelto depende del valor [XmlReader::get_NodeType](../get_nodetype/) del nodo. Los siguientes tipos de nodo devuelven los valores listados. Todos los demás tipos de nodo devuelven una cadena vacía. |||
|-|-|
| Tipo de nodo | Nombre |
| Atributo | El nombre del atributo. |
| TipoDeDocumento | El nombre del tipo de documento. |
| Elemento | El nombre de la etiqueta. |
| EntityReference | El nombre de la entidad referenciada. |
| InstrucciónDeProcesamiento | El objetivo de la instrucción de procesamiento. |
| XmlDeclaration | La cadena literal xml. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
