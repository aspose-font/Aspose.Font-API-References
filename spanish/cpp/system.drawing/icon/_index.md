---
title: "Clase System::Drawing::Icon"
linktitle: "Icon"
second_title: "Aspose.Font para C++"
description: "Clase System::Drawing::Icon. Representa un icono de Windows. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1100
url: /es/cpp/system.drawing/icon/
---
## Icon class


Representa un icono de [Windows](../../system.windows/). Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Icon : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Height](./get_height/)() const | Devuelve la altura del icono. |
| [get_Width](./get_width/)() const | Devuelve el ancho del icono. |
| [Icon](./icon/)(const String\&) | Construye una nueva instancia de la clase [Icon](./) que representa un icono del archivo especificado. |
| [ToBitmap](./tobitmap/)() | Convierte el objeto actual a un objeto [Bitmap](../bitmap/). |
| virtual [~Icon](./~icon/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.Font for C++](../../)
