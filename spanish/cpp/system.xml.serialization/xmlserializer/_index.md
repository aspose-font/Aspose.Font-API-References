---
title: "Clase System::Xml::Serialization::XmlSerializer"
linktitle: "XmlSerializer"
second_title: "Aspose.Font para C++"
description: "Clase System::Xml::Serialization::XmlSerializer. Realiza la serialización y deserialización de objetos hacia y desde documentos XML. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.xml.serialization/xmlserializer/
---
## XmlSerializer class


Realiza la serialización y deserialización de objetos hacia y desde documentos XML. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class XmlSerializer : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [CanDeserialize](./candeserialize/)(System::SharedPtr\<XmlReader\>) | Comprueba si el lector específico está en un estado deserializable. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>) | Deserializa un documento XML en un objeto. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::TextReader\>) | Deserializa un documento XML en un objeto. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>) | Deserializa un documento XML en un objeto. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>, String) | Deserializa un documento XML en un objeto. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) | Serializa el documento en XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) | Serializa el documento en XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) | Serializa el documento en XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serializa el documento en XML. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serializa el documento en XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Serializa el documento en XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) | Serializa el documento en XML. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) | Serializa el documento en XML. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Nombre del espacio de nombres de codificación. |
| static [WsdlNamespace](./wsdlnamespace/) | RTTI. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | Nombre del espacio de nombres de tipos WSDL. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.Font for C++](../../)
