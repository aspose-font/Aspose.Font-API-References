---
title: "Método System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature"
linktitle: "CreateSignature"
second_title: "Aspose.Font para C++"
description: "Método System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature. Información RTTI en C++."
type: docs
weight: 100
url: /es/cpp/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) method


Información RTTI.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) para calcular el hash. |

### ReturnValue

Firma calculada en forma de matriz de bytes.
## Observaciones


Crea la firma para los datos especificados.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Font for C++](../../../)
## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) method


Crea la firma para el valor hash especificado.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | System::SharedPtr\<HashAlgorithm\> | Algoritmo hash a usar al crear la firma. |

### ReturnValue

Firma calculada en forma de matriz de bytes.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Font for C++](../../../)
