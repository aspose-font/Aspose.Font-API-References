---
title: "Clase System::Net::Http::HttpResponseMessage"
linktitle: "HttpResponseMessage"
second_title: "Aspose.Font para C++"
description: "Clase System::Net::Http::HttpResponseMessage. Representa un mensaje de respuesta HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.net.http/httpresponsemessage/
---
## HttpResponseMessage class


Representa un mensaje de respuesta HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpResponseMessage : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Libera la instancia actual. Este método también libera el contenido de la respuesta HTTP. |
| [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | Comprueba el código de estado. Se lanzará [HttpRequestException](../httprequestexception/) cuando el código de estado no pertenezca al rango 2xx. |
| [get_Content](./get_content/)() const | Obtiene el contenido de la respuesta HTTP. |
| [get_Headers](./get_headers/)() const | Devuelve los encabezados de contenido HTTP. |
| [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | Comprueba si el código de estado indica que la acción solicitada por el cliente fue recibida, comprendida y aceptada. |
| [get_ReasonPhrase](./get_reasonphrase/)() const | Obtiene la frase de razón (Reason-Phrase) que los servidores envían junto con el código de estado. |
| [get_RequestMessage](./get_requestmessage/)() const | Obtiene el mensaje de solicitud HTTP. |
| [get_StatusCode](./get_statuscode/)() const | Obtiene el código de estado HTTP. |
| [get_Version](./get_version/)() const | Información RTTI. |
| [HttpResponseMessage](./httpresponsemessage/)() | Construye una nueva instancia. |
| [HttpResponseMessage](./httpresponsemessage/)(HttpStatusCode) | Construye una nueva instancia. |
| [set_Content](./set_content/)(System::SharedPtr\<HttpContent\>) | Establece el contenido de la respuesta HTTP. |
| [set_ReasonPhrase](./set_reasonphrase/)(String) | Establece la frase de razón (Reason-Phrase) que los servidores envían junto con el código de estado. |
| [set_RequestMessage](./set_requestmessage/)(System::SharedPtr\<HttpRequestMessage\>) | Establece el mensaje de solicitud HTTP. |
| [set_StatusCode](./set_statuscode/)(HttpStatusCode) | Establece el código de estado HTTP. |
| [set_Version](./set_version/)(System::Version) | Establece la versión HTTP. |
| [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.Font for C++](../../)
