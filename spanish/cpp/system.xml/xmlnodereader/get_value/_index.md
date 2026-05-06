---
title: "Método System::Xml::XmlNodeReader::get_Value"
linktitle: "get_Value"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlNodeReader::get_Value. Devuelve el valor de texto del nodo actual en C++."
type: docs
weight: 2100
url: /es/cpp/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value method


Devuelve el valor de texto del nodo actual.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### ReturnValue

El valor devuelto depende del [XmlNodeReader::get_NodeType](../get_nodetype/) del nodo.
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
