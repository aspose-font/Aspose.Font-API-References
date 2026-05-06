---
title: "System::Security::Cryptography::RSA::SignData método"
linktitle: "SignData"
second_title: "Aspose.Font para C++"
description: "Método System::Security::Cryptography::RSA::SignData. Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash y el relleno especificados, y firma el resultado en C++."
type: docs
weight: 1000
url: /es/cpp/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash y el modo de relleno especificados, y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | const ByteArrayPtr\& | Arreglo de datos de entrada. |
| algoritmo_hash | const HashAlgorithmName\& | Algoritmo hash. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Modo de relleno. Devuelve la firma [RSA](../) para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Font for C++](../../../)
## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash y el modo de relleno especificados, y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | const ByteArrayPtr\& | Arreglo de datos de entrada. |
| desplazamiento | int32_t | Desplazamiento en **data**. |
| count | int32_t | Número de bytes a usar como datos de entrada. |
| algoritmo_hash | const HashAlgorithmName\& | Algoritmo hash. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Modo de relleno. Devuelve la firma [RSA](../) para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Font for C++](../../../)
## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method


Calcula el valor hash del flujo binario especificado usando el algoritmo hash y el relleno especificados, y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const StreamPtr\& | Flujo binario. |
| algoritmo_hash | const HashAlgorithmName\& | Algoritmo hash. |
| padding | const SharedPtr\<RSASignaturePadding\>\& | Modo de relleno. Devuelve la firma [RSA](../) para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Font for C++](../../../)
