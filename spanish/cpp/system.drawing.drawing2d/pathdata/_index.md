---
title: "System::Drawing::Drawing2D::PathData clase"
linktitle: "PathData"
second_title: "Aspose.Font para C++"
description: "System::Drawing::Drawing2D::PathData clase. Contiene los datos gráficos que representan una ruta. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1100
url: /es/cpp/system.drawing.drawing2d/pathdata/
---
## PathData class


Contiene los datos gráficos que representan una ruta. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class PathData : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Points](./get_points/)() | Devuelve un arreglo que contiene los puntos que forman una ruta. |
| [get_Types](./get_types/)() | Devuelve un arreglo que contiene los valores que especifican los tipos de los puntos correspondientes en el arreglo **Points**. |
| [PathData](./pathdata/)() | Construye un objeto [PathData](./) vacío. |
| [set_Points](./set_points/)(const ArrayPtr\<PointF\>\&) | Establece un arreglo que contiene los puntos que forman una ruta. |
| [set_Types](./set_types/)(const ArrayPtr\<uint8_t\>\&) | Establece una matriz que contiene los valores que especifican los tipos de los puntos correspondientes en la matriz **Points**. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Font for C++](../../)
