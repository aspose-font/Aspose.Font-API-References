---
title: "Clase System::Web::Services::Protocols::SoapHttpClientProtocol"
linktitle: "SoapHttpClientProtocol"
second_title: "Aspose.Font para C++"
description: "Clase System::Web::Services::Protocols::SoapHttpClientProtocol. Los servicios de proxy cliente deben heredar esta clase cuando se utiliza SOAP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol class


Los servicios de proxy cliente deben heredar esta clase cuando se utiliza SOAP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Discover](./discover/)() | Vincula la instancia actual al servicio XML [Web](../../system.web/). |
| [get_SoapVersion](./get_soapversion/)() | Obtiene la versión SOAP. |
| [InitializeSerializers](./initializeserializers/)(const System::TypeInfo\&, System::SharedPtr\<System::Xml::Serialization::XmlSerializerImplementation\>, String) | Inicializa los campos internos. |
| [set_SoapVersion](./set_soapversion/)(SoapProtocolVersion) | Establece la versión SOAP. |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | Construye una nueva instancia. |
## Ver también

* Class [HttpWebClientProtocol](../httpwebclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.Font for C++](../../)
