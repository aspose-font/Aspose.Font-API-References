---
title: TransformationMatrix
second_title: Справочник по API Aspose.Font для .NET
description: Представляет матрицу преобразования 3x3 x7C АБ 0 x7C x7C КД 0 x7C x7C ТХ ТИ 1 x7C. Преобразует координаты следующим образом x1  Ax  Cy  TX y1  Bx  Dy  TY.
type: docs
weight: 570
url: /ru/net/aspose.font/transformationmatrix/
---
## TransformationMatrix class

Представляет матрицу преобразования 3x3 &#x7C; АБ 0 &#x7C; &#x7C; КД 0 &#x7C; &#x7C; ТХ ТИ 1 &#x7C;. Преобразует координаты следующим образом: x1 = A*x + C*y + TX; y1 = B*x + D*y + TY.

```csharp
public class TransformationMatrix : ICloneable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TransformationMatrix](transformationmatrix#constructor)() | Создает стандартную матрицу преобразования 1 в 1: [ABCD TX TY] = [1, 0, 0, 1, 0, 0]. |
| [TransformationMatrix](transformationmatrix#constructor_1)(double[]) | Принимает матрицу преобразования со следующим представлением в виде массива: [ ABCD TX TY ]. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [A](../../aspose.font/transformationmatrix/a) { get; set; } | Получает или задает значение матрицы преобразования A. |
| [B](../../aspose.font/transformationmatrix/b) { get; set; } | Получает или задает значение матрицы преобразования B. |
| [C](../../aspose.font/transformationmatrix/c) { get; set; } | Получает или задает значение матрицы преобразования C. |
| [D](../../aspose.font/transformationmatrix/d) { get; set; } | Получает или задает значение матрицы преобразования D. |
| [Item](../../aspose.font/transformationmatrix/item) { get; } | Предоставляет доступ к базовому массиву. |
| [TX](../../aspose.font/transformationmatrix/tx) { get; set; } | Получает или задает значение матрицы преобразования TX. |
| [TY](../../aspose.font/transformationmatrix/ty) { get; set; } | Получает или задает значение матрицы преобразования TY. |

## Методы

| Имя | Описание |
| --- | --- |
| [Multiply](../../aspose.font/transformationmatrix/multiply)(TransformationMatrix) | Умножает на другую матрицу преобразования. Не изменяет исходную матрицу преобразования, возвращает новый объект TransformationMatrix. |
| [Scale](../../aspose.font/transformationmatrix/scale)(double, double, out double, out double) | Масштабирует x и y с помощью матрицы преобразования: x1 = A*x + C*y; y1 = B*x + D*y. |
| [ToArray](../../aspose.font/transformationmatrix/toarray)() | Выделяет новый массив, копирует матрицу преобразования и возвращает ее. |
| [Transform](../../aspose.font/transformationmatrix/transform)(double, double, out double, out double) | Преобразует x и y с помощью матрицы преобразования: x1 = A*x + C*y + TX; y1 = B*x + D*y + TY. |
| [UnScale](../../aspose.font/transformationmatrix/unscale)(double, double, out double, out double) | Уменьшает x1 и y1 и возвращает x и y перед матрицей преобразования. |
| [UnTransform](../../aspose.font/transformationmatrix/untransform)(double, double, out double, out double) | Преобразует обратно x1 и y1 и возвращает x и y перед матрицей преобразования. |

### Смотрите также

* пространство имен [Aspose.Font](../../aspose.font)
* сборка [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->