---
title: "System::Security::Cryptography::RSACryptoServiceProvider::SignHash method"
linktitle: "SignHash"
second_title: "Aspose.Font para C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::SignHash method. Calcula la firma para el valor hash especificado en C++."
type: docs
weight: 1700
url: /es/cpp/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) method


Calcula la firma para el valor hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | ByteArrayPtr | Valor hash. |
| algoritmo_hash | HashAlgorithmName | Algoritmo hash. |
| padding | SharedPtr\<RSASignaturePadding\> | Modo de relleno. devuelve la firma [RSA](../../rsa/) para el hash especificado. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Font for C++](../../../)
## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) method


Calcula la firma del valor de entrada especificado. No implementado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb_hash | const ByteArrayPtr\& | Valor hash de los datos a firmar. |
| str | const String\& | Identificador del algoritmo de hash utilizado para crear el hash. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Font for C++](../../../)
