---
title: "Método System::Text::RegularExpressions::Regex::IsMatch"
linktitle: "IsMatch"
second_title: "Aspose.Font para C++"
description: "Método System::Text::RegularExpressions::Regex::IsMatch. Coincide la expresión regular con una cadena en C++."
type: docs
weight: 500
url: /es/cpp/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) method


Coincide la expresión regular contra una cadena.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada | const String\& | Cadena objetivo. |
| startat | int | Índice inicial. |

### ReturnValue

Verdadero si la cadena coincide con la expresión regular, falso en caso contrario.

## Ver también

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Font for C++](../../../)
## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) method


Comprueba si la cadena coincide con el patrón.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada | const String\& | Cadena de entrada. |
| patrón | const String\& | Patrón Regexp. |
| opciones | RegexOptions | Opciones de coincidencia. |
| matchTimeout | TimeSpan | Tiempo de espera. |
| startat | int | [Match](../../match/) posición inicial. |

### ReturnValue

Verdadero si se encuentra una coincidencia, falso en caso contrario.

## Ver también

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Font for C++](../../../)
