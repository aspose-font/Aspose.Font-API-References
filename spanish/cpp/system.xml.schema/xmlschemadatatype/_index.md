---
title: "Clase System::Xml::Schema::XmlSchemaDatatype"
linktitle: "XmlSchemaDatatype"
second_title: "Aspose.Font para C++"
description: "Clase System::Xml::Schema::XmlSchemaDatatype. La clase XmlSchemaDatatype es una clase abstracta para mapear los tipos del lenguaje de definición de esquemas XML (XSD) a tipos en tiempo de ejecución en C++."
type: docs
weight: 2400
url: /es/cpp/system.xml.schema/xmlschemadatatype/
---
## XmlSchemaDatatype class


La clase [XmlSchemaDatatype](./) es una clase abstracta para mapear los tipos del lenguaje de definición XML [Schema](../) (XSD) a tipos en tiempo de ejecución.

```cpp
class XmlSchemaDatatype : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&) | Convierte el valor especificado, cuyo tipo es una de las representaciones válidas del tipo de esquema XML representado por [XmlSchemaDatatype](./), al tipo en tiempo de ejecución especificado. |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Convierte el valor especificado, cuyo tipo es una de las representaciones válidas del tipo de esquema XML representado por [XmlSchemaDatatype](./), al tipo en tiempo de ejecución especificado usando el [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) si [XmlSchemaDatatype](./) representa el tipo **xs:QName** o un tipo derivado de él. |
| virtual [get_TokenizedType](./get_tokenizedtype/)() | Cuando se sobrescribe en una clase derivada, obtiene el tipo para la **string** según lo especificado en el consorcio World Wide [Web](../../system.web/) (W3C) de la especificación XML 1.0. |
| virtual [get_TypeCode](./get_typecode/)() | Devuelve el valor [XmlTypeCode](../xmltypecode/) para el tipo simple. |
| virtual [get_ValueType](./get_valuetype/)() | Cuando se sobrescribe en una clase derivada, obtiene el tipo del elemento. |
| virtual [get_Variety](./get_variety/)() | Devuelve el valor [XmlSchemaDatatypeVariety](../xmlschemadatatypevariety/) para el tipo simple. |
| virtual [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaDatatype\>) | Este método siempre devuelve **false**. |
| virtual [ParseValue](./parsevalue/)(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) | Cuando se sobrescribe en una clase derivada, valida la **string** especificada contra un tipo simple incorporado o definido por el usuario. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.Font for C++](../../)
