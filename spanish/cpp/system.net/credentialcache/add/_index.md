---
title: "System::Net::CredentialCache::Add método"
linktitle: "Add"
second_title: "Aspose.Font para C++"
description: "System::Net::CredentialCache::Add método. Añade las credenciales de red especificadas a la caché en C++."
type: docs
weight: 400
url: /es/cpp/system.net/credentialcache/add/
---
## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) method


Agrega las credenciales de red especificadas a la caché.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Cadena | El nombre de host con el que están asociadas las credenciales. |
| puerto | int32_t | El número de puerto. |
| authenticationType | Cadena | El esquema de autenticación. |
| credencial | System::SharedPtr\<NetworkCredential\> | Las credenciales a añadir. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Font for C++](../../../)
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) method


Agrega las credenciales de red especificadas a la caché.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | El prefijo URI del recurso con el que se asocian las credenciales. |
| authenticationType | Cadena | El esquema de autenticación. |
| credencial | System::SharedPtr\<NetworkCredential\> | Las credenciales a añadir. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Font for C++](../../../)
