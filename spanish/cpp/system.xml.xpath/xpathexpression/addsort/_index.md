---
title: "Método System::Xml::XPath::XPathExpression::AddSort"
linktitle: "AddSort"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XPath::XPathExpression::AddSort. Cuando se sobrescribe en una clase derivada, ordena los nodos seleccionados por la expresión XPath según el objeto IComparer especificado en C++."
type: docs
weight: 100
url: /es/cpp/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) method


Cuando se sobrescribe en una clase derivada, ordena los nodos seleccionados por la expresión [XPath](../../) según el objeto IComparer especificado.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | SharedPtr\<Object\> | Un objeto que representa la clave de ordenación. Puede ser el valor **string** del nodo o un objeto [XPathExpression](../) con una expresión [XPath](../../) compilada. |
| comparador | SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\> | Un objeto IComparer que proporciona comparaciones de tipos de datos específicos para comparar dos objetos en busca de equivalencia. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Font for C++](../../../)
## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) method


Cuando se sobrescribe en una clase derivada, ordena los nodos seleccionados por la expresión [XPath](../../) según los parámetros suministrados.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | SharedPtr\<Object\> | Un objeto que representa la clave de ordenación. Puede ser el valor **string** del nodo o un objeto [XPathExpression](../) con una expresión [XPath](../../) compilada. |
| order | XmlSortOrder | Un valor [XmlSortOrder](../../xmlsortorder/) que indica el orden de clasificación. |
| caseOrder | XmlCaseOrder | Un valor [XmlCaseOrder](../../xmlcaseorder/) que indica cómo ordenar las letras mayúsculas y minúsculas. |
| lang | String | El idioma a usar para la comparación. Utiliza la clase [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) que puede pasarse al método [String::Compare](../../../system/string/compare/) para los tipos de idioma, por ejemplo, "us-en" para inglés de EE. UU. Si se especifica una cadena vacía, se utiliza el entorno del sistema para determinar el [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | XmlDataType | Un valor [XmlDataType](../../xmldatatype/) que indica el orden de clasificación para el tipo de datos. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Class [String](../../../system/string/)
* Enum [XmlDataType](../../xmldatatype/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Font for C++](../../../)
