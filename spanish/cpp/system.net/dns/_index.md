---
title: "System::Net::Dns class"
linktitle: "Dns"
second_title: "Aspose.Font para C++"
description: "System::Net::Dns class. Proporciona métodos para trabajar con DNS en C++."
type: docs
weight: 700
url: /es/cpp/system.net/dns/
---
## Dns class


Proporciona métodos para trabajar con DNS.

```cpp
class Dns : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [BeginGetHostAddresses](./begingethostaddresses/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry-class usando la cadena especificada que contiene un nombre de host o una dirección IP. |
| static [BeginGetHostByName](./begingethostbyname/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry-class usando el nombre de host especificado. |
| static [BeginGetHostEntry](./begingethostentry/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry-class usando la cadena especificada que contiene un nombre de host o una dirección IP. |
| static [BeginGetHostEntry](./begingethostentry/)(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry-class usando la dirección IP especificada. |
| static [BeginResolve](./beginresolve/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry-class usando el nombre de host especificado. |
| [Dns](./dns/)() | El constructor predeterminado eliminado. |
| static [EndGetHostAddresses](./endgethostaddresses/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación asíncrona especificada para crear una nueva instancia de la clase IPHostEntry-class se complete. |
| static [EndGetHostByName](./endgethostbyname/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación asíncrona especificada para crear una nueva instancia de la clase IPHostEntry-class se complete. |
| static [EndGetHostEntry](./endgethostentry/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación asíncrona especificada para crear una nueva instancia de la clase IPHostEntry-class se complete. |
| static [EndResolve](./endresolve/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación asíncrona especificada para crear una nueva instancia de la clase IPHostEntry-class se complete. |
| static [GetHostAddresses](./gethostaddresses/)(String) | Devuelve una colección de direcciones IP del nombre de host o dirección IP especificados. |
| static [GetHostByAddress](./gethostbyaddress/)(String) | Crea una nueva instancia de la clase IPHostEntry-class usando la representación en cadena especificada de una dirección IP. |
| static [GetHostByAddress](./gethostbyaddress/)(System::SharedPtr\<IPAddress\>) | Crea una nueva instancia de la clase IPHostEntry-class usando la dirección IP especificada. |
| static [GetHostByName](./gethostbyname/)(String) | Información RTTI. |
| static [GetHostEntry](./gethostentry/)(String) | Crea una nueva instancia de la clase IPHostEntry-class usando la cadena especificada que contiene un nombre de host o una dirección IP. |
| static [GetHostEntry](./gethostentry/)(System::SharedPtr\<IPAddress\>) | Crea una nueva instancia de la clase IPHostEntry-class usando la dirección IP especificada. |
| static [GetHostName](./gethostname/)() | Devuelve el nombre de host de la máquina local. |
| static [Resolve](./resolve/)(String) | Crea una nueva instancia de la clase IPHostEntry usando el nombre de host especificado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.Font for C++](../../)
