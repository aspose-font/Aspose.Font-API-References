---
title: "System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature method"
linktitle: "VerifySignature"
second_title: "Aspose.Font para C++"
description: "System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature method. Verifica la firma del hash de los datos en C++."
type: docs
weight: 400
url: /es/cpp/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature method


Verifica la firma del hash de datos.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | Hash calculado para los datos. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Firma recibida para los datos. |

### ReturnValue

Verdadero si la firma es válida, falso en caso contrario.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RSAPKCS1SignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Font for C++](../../../)
