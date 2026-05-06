---
title: "System::IO::FileOptions enum"
linktitle: "FileOptions"
second_title: "Aspose.Font para C++"
description: "System::IO::FileOptions enum. Representa opciones avanzadas para crear un objeto FileStream en C++."
type: docs
weight: 3200
url: /es/cpp/system.io/fileoptions/
---
## FileOptions enum


Representa opciones avanzadas para crear un objeto [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | No hay opciones adicionales. |
| Cifrado | 16384 | El archivo está encriptado. NO IMPLEMENTADO. |
| DeleteOnClose | 67108864 | El archivo debe eliminarse automáticamente cuando ya no esté en uso. |
| SequentialScan | 134217728 | El archivo debe ser accedido secuencialmente. |
| RandomAccess | 268435456 | El archivo se accede de forma aleatoria. |
| Asynchronous | 1073741824 | El archivo puede usarse para operaciones de E/S asíncronas. |
| WriteThrough | n/a | Todas las escrituras deben ir directamente al disco, evitando cualquier caché intermedia. |

## Ver también

* Namespace [System::IO](../)
* Library [Aspose.Font for C++](../../)
