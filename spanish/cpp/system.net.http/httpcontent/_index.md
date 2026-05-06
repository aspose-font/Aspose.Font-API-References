---
title: "Clase System::Net::Http::HttpContent"
linktitle: "HttpContent"
second_title: "Aspose.Font para C++"
description: "Clase System::Net::Http::HttpContent. Representa el contenido de una entidad HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.net.http/httpcontent/
---
## HttpContent class


Representa el contenido de una entidad HTTP. El [Object](../../system/object/) de esta clase solo debe asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class HttpContent : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Descarta la instancia actual. Este método también descarta el flujo que devuelve 'ReadAsStream' y el búfer de memoria si se ha creado. |
| [get_Headers](./get_headers/)() | Devuelve los encabezados de contenido HTTP. |
| [LoadIntoBuffer](./loadintobuffer/)() | Serializa el contenido a un búfer de memoria. |
| [LoadIntoBuffer](./loadintobuffer/)(int64_t) | Serializa el contenido a un búfer de memoria. |
| [ReadAsByteArray](./readasbytearray/)() | Serializa el contenido y devuelve una matriz de bytes. |
| [ReadAsStream](./readasstream/)() | Serializa el contenido y devuelve un flujo. |
| [ReadAsString](./readasstring/)() | Serializa el contenido y devuelve una cadena. |
| virtual [TryComputeLength](./trycomputelength/)(int64_t\&) | Intenta calcular el tamaño del contenido. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultStringEncoding](./defaultstringencoding/) | La codificación predeterminada. |
| static [MaxBufferSize](./maxbuffersize/) | El número máximo de bytes. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.Font for C++](../../)
