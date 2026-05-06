---
title: "System::Drawing::Imaging::Encoder class"
linktitle: "Encoder"
second_title: "Aspose.Font para C++"
description: "System::Drawing::Imaging::Encoder class. Representa un GUID que está asociado con un conjunto de parámetros del codificador de imágenes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.drawing.imaging/encoder/
---
## Encoder class


Representa un GUID que está asociado con un conjunto de parámetros del codificador de imágenes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Encoder : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Encoder](./encoder/)(const Guid\&) | Construye una nueva instancia de la clase [Encoder](./). |
| [get_Guid](./get_guid/)() const | Devuelve un GUID que especifica un conjunto de parámetros del codificador de imágenes que representa el objeto actual. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [ChrominanceTable](./chrominancetable/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de tabla de crominancia. |
| static [ColorDepth](./colordepth/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de profundidad de color. |
| static [Compression](./compression/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de compresión. |
| static [LuminanceTable](./luminancetable/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de tabla de luminancia. |
| static [Quality](./quality/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de calidad. |
| static [RenderMethod](./rendermethod/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de método de renderizado. |
| static [SaveFlag](./saveflag/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de bandera de guardado. |
| static [ScanMethod](./scanmethod/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de método de escaneo. |
| static [Transformation](./transformation/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de transformación. |
| static [Version](./version/) | Una instancia de la clase [Encoder](./) que representa la categoría del parámetro de versión. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.Font for C++](../../)
