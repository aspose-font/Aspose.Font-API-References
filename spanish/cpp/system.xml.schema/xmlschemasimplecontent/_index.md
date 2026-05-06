---
title: "System::Xml::Schema::XmlSchemaSimpleContent class"
linktitle: "XmlSchemaSimpleContent"
second_title: "Aspose.Font para C++"
description: "System::Xml::Schema::XmlSchemaSimpleContent class. Representa el elemento simpleContent de XML Schema según lo especificado por el Consorcio World Wide Web (W3C). Esta clase es para tipos simples y complejos con modelo de contenido simple en C++."
type: docs
weight: 5900
url: /es/cpp/system.xml.schema/xmlschemasimplecontent/
---
## XmlSchemaSimpleContent class


Representa el elemento **simpleContent** de XML [Schema](../) según lo especificado por el Consorcio World Wide [Web](../../system.web/) (W3C). Esta clase es para tipos simples y complejos con modelo de contenido simple.

```cpp
class XmlSchemaSimpleContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Content](./get_content/)() override | Devuelve uno de los [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) o [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Devuelve uno de los [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) o [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaContentModel](../xmlschemacontentmodel/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.Font for C++](../../)
