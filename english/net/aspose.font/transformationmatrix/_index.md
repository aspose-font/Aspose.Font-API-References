---
title: Class TransformationMatrix
second_title: Aspose.Font for .NET API Reference
description: Aspose.Font.TransformationMatrix class. Represents 3x3 transformation matrix  A B 0   C D 0   TX TY 1 . Transforms coordinates in the following way x1  Ax  Cy  TX y1  Bx  Dy  TY
type: docs
weight: 810
url: /net/aspose.font/transformationmatrix/
---
## TransformationMatrix class

Represents 3x3 transformation matrix &#x7C; A B 0 &#x7C; &#x7C; C D 0 &#x7C; &#x7C; TX TY 1 &#x7C;. Transforms coordinates in the following way: x1 = A*x + C*y + TX; y1 = B*x + D*y + TY.

```csharp
public class TransformationMatrix : ICloneable
```

## Constructors

| Name | Description |
| --- | --- |
| [TransformationMatrix](transformationmatrix/#constructor)() | Creates standard 1 to 1 transformation matrix: [ A B C D TX TY ] = [ 1, 0, 0, 1, 0, 0]. |
| [TransformationMatrix](transformationmatrix/#constructor_2)(double[]) | Accepts a transformation matrix with following array representation: [ A B C D TX TY ]. |
| [TransformationMatrix](transformationmatrix/#constructor_1)(double, double, double, double, double, double) | Creates transformation matrix [ A B C D TX TY ] |

## Properties

| Name | Description |
| --- | --- |
| [A](../../aspose.font/transformationmatrix/a/) { get; set; } | Gets or sets A transformation matrix value. |
| [B](../../aspose.font/transformationmatrix/b/) { get; set; } | Gets or sets B transformation matrix value. |
| [C](../../aspose.font/transformationmatrix/c/) { get; set; } | Gets or sets C transformation matrix value. |
| [D](../../aspose.font/transformationmatrix/d/) { get; set; } | Gets or sets D transformation matrix value. |
| [Item](../../aspose.font/transformationmatrix/item/) { get; } | Provides access to underlying array. |
| [TX](../../aspose.font/transformationmatrix/tx/) { get; set; } | Gets or sets TX transformation matrix value. |
| [TY](../../aspose.font/transformationmatrix/ty/) { get; set; } | Gets or sets TY transformation matrix value. |

## Methods

| Name | Description |
| --- | --- |
| [Multiply](../../aspose.font/transformationmatrix/multiply/)(TransformationMatrix) | Multiplies with another transformation matrix. Doesn't change original transformation matrix, returns a new TransformationMatrix object. |
| [Scale](../../aspose.font/transformationmatrix/scale/)(double, double, out double, out double) | Scales x and y with the transformation matrix: x1 = A*x + C*y; y1 = B*x + D*y. |
| [ToArray](../../aspose.font/transformationmatrix/toarray/)() | Allocates new array, copies the transformation matrix and returns it. |
| [Transform](../../aspose.font/transformationmatrix/transform/)(double, double, out double, out double) | Transforms x and y with the transformation matrix: x1 = A*x + C*y + TX; y1 = B*x + D*y + TY. |
| [UnScale](../../aspose.font/transformationmatrix/unscale/)(double, double, out double, out double) | Scales back x1 and y1 and returns x and y before the transformation matrix. |
| [UnTransform](../../aspose.font/transformationmatrix/untransform/)(double, double, out double, out double) | Transforms back x1 and y1 and returns x and y before the transformation matrix. |

### See Also

* namespace [Aspose.Font](../../aspose.font/)
* assembly [Aspose.Font](../../)


