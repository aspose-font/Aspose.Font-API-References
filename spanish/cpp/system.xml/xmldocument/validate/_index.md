---
title: "System::Xml::XmlDocument::Validate método"
linktitle: "Validar"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlDocument::Validate método. Valida el XmlDocument contra los esquemas del Lenguaje de Definición de Esquemas XML (XSD) contenidos en la lista XmlDocument::get_Schemas en C++."
type: docs
weight: 4300
url: /es/cpp/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) method


Valida el [XmlDocument](../) contra los esquemas del Lenguaje de Definición de Esquemas XML (XSD) contenidos en la lista [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| validationEventHandler | Schema::ValidationEventHandler | El objeto [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) que recibe información sobre advertencias y errores de validación de esquemas. |

## Ver también

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) method


Valida el objeto [XmlNode](../../xmlnode/) especificado contra los esquemas del Lenguaje de Definición de Esquemas XML (XSD) en la lista [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| validationEventHandler | Schema::ValidationEventHandler | El objeto [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) que recibe información sobre advertencias y errores de validación de esquemas. |
| nodeToValidate | const SharedPtr\<XmlNode\>\& | El objeto [XmlNode](../../xmlnode/) creado a partir de un [XmlDocument](../) para validar. |

## Ver también

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
