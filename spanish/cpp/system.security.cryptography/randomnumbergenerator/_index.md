---
title: "Clase System::Security::Cryptography::RandomNumberGenerator"
linktitle: "RandomNumberGenerator"
second_title: "Aspose.Font para C++"
description: "Clase System::Security::Cryptography::RandomNumberGenerator. Clase abstracta para que los generadores de números aleatorios hereden de ella. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2600
url: /es/cpp/system.security.cryptography/randomnumbergenerator/
---
## RandomNumberGenerator class


Clase abstracta para que los generadores de números aleatorios hereden de ella. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class RandomNumberGenerator : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Create](./create/)() | Crea una instancia de la implementación predeterminada de un generador criptográfico de números aleatorios que puede usarse para generar datos aleatorios. No implementado. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) | Llena los elementos existentes del arreglo con bytes aleatorios. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>, int, int) | Llena la porción existente del arreglo con bytes aleatorios. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) | Llena los elementos de la vista del arreglo existente con bytes aleatorios. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>, int, int) | Llena la porción de la vista del arreglo existente con bytes aleatorios. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Llena los elementos existentes del arreglo de pila con bytes aleatorios. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&, int, int) | Llena la porción existente del arreglo de pila con bytes aleatorios. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) | Llena los elementos existentes del arreglo con bytes aleatorios diferentes de cero. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) | Llena los elementos de la vista del arreglo existente con bytes aleatorios diferentes de cero. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Llena los elementos existentes del arreglo de pila con bytes aleatorios diferentes de cero. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Font for C++](../../)
