---
title: "System::Xml::XmlValidatingReader::get_Value método"
linktitle: "get_Value"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlValidatingReader::get_Value método. Devuelve el valor de texto del nodo actual en C++."
type: docs
weight: 2900
url: /es/cpp/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value method


Devuelve el valor de texto del nodo actual.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```


### ReturnValue

El valor devuelto depende del XmlValidatingReader::NodeType del nodo.
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
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
