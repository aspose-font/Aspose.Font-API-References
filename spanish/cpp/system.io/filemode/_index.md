---
title: "System::IO::FileMode enum"
linktitle: "FileMode"
second_title: "Aspose.Font para C++"
description: "System::IO::FileMode enum. Especifica cómo debe abrirse un archivo en C++."
type: docs
weight: 3100
url: /es/cpp/system.io/filemode/
---
## FileMode enum


Especifica cómo debe abrirse un archivo.

```cpp
enum class FileMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| CreateNew | 1 | Crea un archivo nuevo. Si el archivo ya existe, se lanza una excepción. |
| Create | 2 | Crear un nuevo archivo. Si el archivo ya existe, se sobrescribe. |
| Open | 3 | Abrir un archivo existente. Si el archivo no existe, se lanza una excepción. |
| OpenOrCreate | 4 | Abrir un archivo existente o crear uno nuevo si no existe. |
| Truncar | 5 | Abrir un archivo existente y truncarlo para que quede vacío. Si el archivo no existe, se lanza una excepción. |
| Agregar | 6 | Abrir un archivo existente y buscar hasta el final o crear uno nuevo si no existe. |

## Ver también

* Namespace [System::IO](../)
* Library [Aspose.Font for C++](../../)
