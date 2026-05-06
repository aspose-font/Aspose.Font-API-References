---
title: "Enumeración System::Reflection::BindingFlags"
linktitle: "BindingFlags"
second_title: "Aspose.Font para C++"
description: "Enumeración System::Reflection::BindingFlags. Define los modos de búsqueda de miembros y tipos y los enlaces en C++."
type: docs
weight: 1100
url: /es/cpp/system.reflection/bindingflags/
---
## BindingFlags enum


Define miembros y modos de búsqueda de tipos y enlaces.

```cpp
enum class BindingFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Predeterminado | 0 | Sin opciones especiales. |
| IgnoreCase | 1 | Ignorar mayúsculas/minúsculas del nombre al buscar el elemento. |
| DeclaredOnly | 2 | Solo buscar miembros declarados en el tipo y no en los tipos base. |
| Instance | 4 | Buscar entre los miembros de instancia. |
| Static | 8 | Buscar entre los miembros estáticos. |
| Public | 16 | Buscar entre los miembros públicos. |
| NonPublic | 32 | Buscar entre los miembros no públicos. |
| FlattenHierarchy | 64 | Buscar entre los miembros estáticos públicos y protegidos del tipo base. |
| InvokeMethod | 256 | Invoca el método. |
| CreateInstance | 512 | Crea una instancia del tipo reflejado. |
| GetField | 1024 | Obtiene el valor del campo. |
| SetField | 2048 | Establece el valor del campo. |
| GetProperty | 4096 | Obtiene el valor de la propiedad. |
| SetProperty | 8192 | Establece el valor de la propiedad. |
| PutDispProperty | 16384 | Establece la propiedad COM. |
| PutRefDispProperty | 32768 | Establece la propiedad de referencia COM. |
| ExactBinding | 65536 | La vinculación de tipo debe ser exacta, sin cambios de tipo. |
| SuppressChangeType | 131072 | No soportado. |
| OptionalParamBinding | 262144 | Selecciona la sobrecarga según la cantidad de argumentos. |
| IgnoreReturn | 16777216 | Ignora el valor de retorno de la interoperabilidad COM. |

## Ver también

* Namespace [System::Reflection](../)
* Library [Aspose.Font for C++](../../)
