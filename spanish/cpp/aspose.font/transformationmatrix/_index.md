---
title: "Aspose::Font::TransformationMatrix clase"
linktitle: "TransformationMatrix"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TransformationMatrix clase. Representa la matriz de transformación 3x3 | A B 0 | | C D 0 | | TX TY 1 | en C++."
type: docs
weight: 3000
url: /es/cpp/aspose.font/transformationmatrix/
---
## TransformationMatrix class


Representa la matriz de transformación 3x3 | A B 0 | | C D 0 | | TX TY 1 |.

```cpp
class TransformationMatrix : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_A](./get_a/)() const | Obtiene el valor A de la matriz de transformación. |
| [get_B](./get_b/)() const | Obtiene el valor B de la matriz de transformación. |
| [get_C](./get_c/)() const | Obtiene el valor C de la matriz de transformación. |
| [get_D](./get_d/)() const | Obtiene el valor D de la matriz de transformación. |
| [get_TX](./get_tx/)() const | Obtiene el valor TX de la matriz de transformación. |
| [get_TY](./get_ty/)() const | Obtiene el valor TY de la matriz de transformación. |
| [idx_get](./idx_get/)(int32_t) | Proporciona acceso a la matriz subyacente. |
| [Multiply](./multiply/)(const System::SharedPtr\<TransformationMatrix\>\&) | Multiplica con otra matriz de transformación. No cambia la matriz de transformación original, devuelve un nuevo objeto [TransformationMatrix](./). |
| [Scale](./scale/)(double, double, double\&, double\&) | Escala x e y con la matriz de transformación: x1 = A*x + C*y; y1 = B*x + D*y. |
| [set_A](./set_a/)(double) | Establece el valor A de la matriz de transformación. |
| [set_B](./set_b/)(double) | Establece el valor B de la matriz de transformación. |
| [set_C](./set_c/)(double) | Establece el valor C de la matriz de transformación. |
| [set_D](./set_d/)(double) | Establece el valor D de la matriz de transformación. |
| [set_TX](./set_tx/)(double) | Establece el valor TX de la matriz de transformación. |
| [set_TY](./set_ty/)(double) | Establece el valor TY de la matriz de transformación. |
| [ToArray](./toarray/)() | Reserva una nueva matriz, copia la matriz de transformación y la devuelve. |
| [Transform](./transform/)(double, double, double\&, double\&) | Transforma x e y con la matriz de transformación: x1 = A*x + C*y + TX; y1 = B*x + D*y + TY. |
| [TransformationMatrix](./transformationmatrix/)() | Crea una matriz de transformación estándar 1 a 1: [ A B C D TX TY ] = [ 1, 0, 0, 1, 0, 0]. |
| [TransformationMatrix](./transformationmatrix/)(const System::ArrayPtr\<double\>\&) | Acepta una matriz de transformación con la siguiente representación de arreglo: [ A B C D TX TY ]. |
| [TransformationMatrix](./transformationmatrix/)(double, double, double, double, double, double) | Crea una matriz de transformación [ A B C D TX TY ]. |
| [UnScale](./unscale/)(double, double, double\&, double\&) | Escala de nuevo x1 y y1 y devuelve x e y antes de la matriz de transformación. |
| [UnTransform](./untransform/)(double, double, double\&, double\&) | Transforma de nuevo x1 y y1 y devuelve x e y antes de la matriz de transformación. |
## Observaciones


Transforma coordenadas de la siguiente manera: x1 = A*x + C*y + TX; y1 = B*x + D*y + TY.
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
