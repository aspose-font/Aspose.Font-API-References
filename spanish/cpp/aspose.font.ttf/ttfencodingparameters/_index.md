---
title: "Aspose::Font::Ttf::TtfEncodingParameters class"
linktitle: "TtfEncodingParameters"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Ttf::TtfEncodingParameters class. Representa los parámetros de codificación TTF en C++."
type: docs
weight: 500
url: /es/cpp/aspose.font.ttf/ttfencodingparameters/
---
## TtfEncodingParameters class


Representa los parámetros de codificación TTF.

```cpp
class TtfEncodingParameters : public Aspose::Font::IEncodingParameters
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_PlatformId](./get_platformid/)() const | Obtiene el valor de PlatformId. |
| [get_PlatformSpecificId](./get_platformspecificid/)() const | Obtiene el valor de PlatformSpecificId. |
| [set_PlatformId](./set_platformid/)(uint16_t) | Establece el valor de PlatformId. |
| [set_PlatformSpecificId](./set_platformspecificid/)(uint16_t) | Establece el valor de PlatformSpecificId. |
| [TtfEncodingParameters](./ttfencodingparameters/)(uint16_t, uint16_t) | Inicializa una nueva instancia de la clase [TtfEncodingParameters](./). Toma Platform Id y Platform-specific encoding id como parámetros. Estos parámetros se usan para solicitar una subtabla CMap especial de la tabla CMap principal de la fuente, vea la tabla 'CMap', 'name' en la especificación del archivo OpenType [Font](../../aspose.font/font/). |
## Observaciones


Debe usarse para solicitar una codificación específica de la [Font](../../aspose.font/font/) TTF.
## Ver también

* Class [IEncodingParameters](../../aspose.font/iencodingparameters/)
* Namespace [Aspose::Font::Ttf](../)
* Library [Aspose.Font for C++](../../)
