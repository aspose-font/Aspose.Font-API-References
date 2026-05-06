---
title: "System::Globalization::DateTimeStyles enumeración"
linktitle: "DateTimeStyles"
second_title: "Aspose.Font para C++"
description: "System::Globalization::DateTimeStyles enumeración. Define opciones de formato de fecha y hora. Banderas de bits en C++."
type: docs
weight: 3500
url: /es/cpp/system.globalization/datetimestyles/
---
## DateTimeStyles enum


Define opciones de formato de fecha y hora. Banderas de bits.

```cpp
enum class DateTimeStyles : int32_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | Predeterminado. |
| AllowLeadingWhite | 1 | Ignora los espacios en blanco iniciales. |
| AllowTrailingWhite | 2 | Ignora los espacios en blanco finales. |
| AllowInnerWhite | 4 | Ignora los espacios en blanco internos. |
| AllowWhiteSpaces | n/a | Ignorar todos los espacios en blanco. |
| NoCurrentDateDefault | 8 | Al analizar una cadena de fecha/hora, si faltan el año, mes y día, establecer la fecha predeterminada en 0001/1/1, en lugar del año/mes/día actual. |
| AdjustToUniversal | 16 | Al analizar una cadena de fecha/hora, si existe un especificador de zona horaria ("GMT","Z","+xxxx", "-xxxx"), ajustaremos la hora analizada basándonos en GMT. |
| AssumeLocal | 32 | Si no se proporciona zona horaria, usar la zona horaria local. |
| AssumeUniversal | 64 | Si no se proporciona zona horaria, usar UTC. |
| RoundtripKind | 128 | Intentar preservar si la entrada es no especificada, local o UTC. |

## Ver también

* Namespace [System::Globalization](../)
* Library [Aspose.Font for C++](../../)
