---
title: "System::Xml::Serialization::IXmlSerializable clase"
linktitle: "IXmlSerializable"
second_title: "Aspose.Font para C++"
description: "System::Xml::Serialization::IXmlSerializable clase. Proporciona formato personalizado para la serialización y deserialización XML. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.xml.serialization/ixmlserializable/
---
## IXmlSerializable class


Proporciona formato personalizado para la serialización y deserialización XML. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class IXmlSerializable : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetSchema](./getschema/)() | Un objeto XmlSchema que describe la representación XML del objeto que devuelve el método [WriteXml()](./writexml/) y que acepta el método [ReadXml()](./readxml/). |
| virtual [ReadXml](./readxml/)(System::SharedPtr\<System::Xml::XmlReader\>) | Deserializa el objeto a partir de su representación XML. |
| virtual [WriteXml](./writexml/)(System::SharedPtr\<System::Xml::XmlWriter\>) | Serializa el objeto actual a una representación XML. |
| virtual [~IXmlSerializable](./~ixmlserializable/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.Font for C++](../../)
