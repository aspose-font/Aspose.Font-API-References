---
title: "Clase System::IO::TextReader"
linktitle: "TextReader"
second_title: "Aspose.Font para C++"
description: "Clase System::IO::TextReader. Una clase base para clases que representan lectores que leen secuencias de caracteres de diferentes fuentes. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2600
url: /es/cpp/system.io/textreader/
---
## TextReader class


Una clase base para clases que representan lectores que leen secuencias de caracteres de diferentes fuentes. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class TextReader : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Close](./close/)() | Cierra el flujo y libera los recursos adquiridos. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| virtual [Peek](./peek/)() | Lee un solo carácter del flujo sin cambiar el cursor de lectura del flujo. |
| virtual [Read](./read/)() | Lee un solo carácter del flujo. |
| virtual [Read](./read/)(ArrayPtr\<char_t\>, int, int) | Lee la cantidad especificada de caracteres del flujo y los escribe en la matriz de caracteres especificada comenzando en la posición especificada. |
| virtual [ReadBlock](./readblock/)(ArrayPtr\<char_t\>, int, int) | Lee el número máximo especificado de caracteres del lector de texto actual y escribe los datos en un búfer, comenzando en el índice especificado. |
| virtual [ReadLine](./readline/)() | Lee caracteres del flujo hasta el final de la línea actual. |
| virtual [ReadToEnd](./readtoend/)() | Lee caracteres del flujo hasta el final del flujo. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.Font for C++](../../)
