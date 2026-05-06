---
title: "Clase System::Net::Http::HttpMessageInvoker"
linktitle: "HttpMessageInvoker"
second_title: "Aspose.Font para C++"
description: "Clase System::Net::Http::HttpMessageInvoker. Permite a las aplicaciones llamar al método Send en una cadena de manejadores HTTP. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.net.http/httpmessageinvoker/
---
## HttpMessageInvoker class


Permite a las aplicaciones llamar al método Send en una cadena de manejadores HTTP. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpMessageInvoker : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Descarta la instancia actual. Este método también descarta el manejador si es necesario. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>) | Información RTTI. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Construye una nueva instancia. |
| virtual [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) | Envía la solicitud especificada. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.Font for C++](../../)
