---
title: "System::Xml::Schema::XmlSchemaSet::Contains método"
linktitle: "Contains"
second_title: "Aspose.Font para C++"
description: "System::Xml::Schema::XmlSchemaSet::Contains método. Indica si el objeto XmlSchema de lenguaje de definición de esquema XML (XSD) especificado está en el XmlSchemaSet en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) method


Indica si el objeto [XmlSchema](../../xmlschema/) de lenguaje de definición de [Schema](../../) XML (XSD) especificado está en el [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | El objeto [XmlSchema](../../xmlschema/). |

### ReturnValue

**true** if the [XmlSchema](../../xmlschema/) object is in the [XmlSchemaSet](../); otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Font for C++](../../../)
## XmlSchemaSet::Contains(String) method


Indica si un esquema [Schema](../../) de lenguaje de definición XML (XSD) con el URI de espacio de nombres objetivo especificado está en el [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | Cadena | La propiedad **targetNamespace** del esquema. |

### ReturnValue

**true** if a schema with the specified target namespace URI is in the [XmlSchemaSet](../); otherwise, **false**.

## Ver también

* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Font for C++](../../../)
