---
title: "System::Xml::XmlReader::get_Value método"
linktitle: "get_Value"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlReader::get_Value método. Cuando se sobrescribe en una clase derivada, obtiene el valor de texto del nodo actual en C++."
type: docs
weight: 2400
url: /es/cpp/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value method


Cuando se sobrescribe en una clase derivada, obtiene el valor de texto del nodo actual.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### ReturnValue

El valor devuelto depende del valor [XmlReader::get_NodeType](../get_nodetype/) del nodo.
## Observaciones



La tabla siguiente enumera los tipos de nodo que tienen un valor para devolver. Todos los demás tipos de nodo devuelven [String::Empty](../../../system/string/empty/). |||
|-|-|
| Tipo de nodo | Valor |
| Atributo | El valor del atributo. |
| CDATA | El contenido de la sección CDATA. |
| Comentario | El contenido del comentario. |
| TipoDeDocumento | El subconjunto interno. |
| InstrucciónDeProcesamiento | Todo el contenido, excluyendo el objetivo. |
| EspacioEnBlancoSignificativo | El espacio en blanco entre marcas en un modelo de contenido mixto. |
| Text | El contenido del nodo de texto. |
| EspacioEnBlanco | El espacio en blanco entre marcas. |
| XmlDeclaration | El contenido de la declaración. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
