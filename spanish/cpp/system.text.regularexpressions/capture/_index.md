---
title: "System::Text::RegularExpressions::Capture class"
linktitle: "Capture"
second_title: "Aspose.Font para C++"
description: "System::Text::RegularExpressions::Capture class. Resultado de una coincidencia de subexpresión única. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.text.regularexpressions/capture/
---
## Capture class


Resultado de una coincidencia de subexpresión única. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Capture : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Capture](./capture/)(const UStringPtr\&, int, int) | Constructor. |
| [get_Index](./get_index/)() const | Obtiene el índice de la subcadena capturada. |
| [get_Length](./get_length/)() const | Obtiene la longitud de la subcadena capturada. |
| [get_Value](./get_value/)() const | Obtiene la subcadena capturada. |
| [ToString](./tostring/)() const override | Obtiene la subcadena capturada. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.Font for C++](../../)
