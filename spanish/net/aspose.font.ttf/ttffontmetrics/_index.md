---
title: TtfFontMetrics
second_title: Referencia de la API de Aspose.Font para .NET
description: Representa métricas de fuentes TTF.
type: docs
weight: 640
url: /es/net/aspose.font.ttf/ttffontmetrics/
---
## TtfFontMetrics class

Representa métricas de fuentes TTF.

```csharp
public class TtfFontMetrics : FontMetrics
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Ascender](../../aspose.font.ttf/ttffontmetrics/ascender) { get; set; } | Obtiene el valor ascendente. |
| override [Descender](../../aspose.font.ttf/ttffontmetrics/descender) { get; set; } | Obtiene valor descendente. |
| override [FontBBox](../../aspose.font.ttf/ttffontmetrics/fontbbox) { get; } | Obtiene el valor de FontBBox. |
| override [FontMatrix](../../aspose.font.ttf/ttffontmetrics/fontmatrix) { get; } | Obtiene el valor de FontBBox. |
| [IsFixedPitch](../../aspose.font/fontmetrics/isfixedpitch) { get; } | Obtiene el valor IsFixedPitch. |
| override [LineGap](../../aspose.font.ttf/ttffontmetrics/linegap) { get; } | Obtiene el valor LineGap. |
| override [TypoAscender](../../aspose.font.ttf/ttffontmetrics/typoascender) { get; set; } | Obtiene el valor de TypoAscender. |
| override [TypoDescender](../../aspose.font.ttf/ttffontmetrics/typodescender) { get; set; } | Obtiene el valor de TypoDescender. |
| override [TypoLineGap](../../aspose.font.ttf/ttffontmetrics/typolinegap) { get; } | Obtiene el valor TypoLineGap. |
| override [UnitsPerEM](../../aspose.font.ttf/ttffontmetrics/unitsperem) { get; set; } | Obtiene el valor UnitsPerEM. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetAscender](../../aspose.font/fontmetrics/getascender)(double) | Devuelve el ascendente para un tamaño de fuente específico. |
| virtual [GetDescender](../../aspose.font/fontmetrics/getdescender)(double) | Devuelve el descendiente para un tamaño de fuente específico. |
| virtual [GetGlyphBBox](../../aspose.font/fontmetrics/getglyphbbox)(GlyphId) | Devuelve el glifo BBox. Devuelve FontBBox si no se definió BBox para el glifo. Puede ser anulado por herederos de codificación de fuente específicos. |
| override [GetGlyphWidth](../../aspose.font.ttf/ttffontmetrics/getglyphwidth)(GlyphId) | Devuelve el ancho de los glifos por ID de glifo. |
| override [GetKerningValue](../../aspose.font.ttf/ttffontmetrics/getkerningvalue)(GlyphId, GlyphId) | Devuelve el valor de interletraje para el par de glifos. |
| virtual [GetTypoAscender](../../aspose.font/fontmetrics/gettypoascender)(double) | Devuelve el descendiente para un tamaño de fuente específico. |
| virtual [GetTypoDescender](../../aspose.font/fontmetrics/gettypodescender)(double) | Devuelve el descendiente para un tamaño de fuente específico. |
| virtual [GetTypoLineGap](../../aspose.font/fontmetrics/gettypolinegap)(double) | Devuelve el espacio entre líneas para un tamaño de fuente específico. |
| override [MeasureString](../../aspose.font.ttf/ttffontmetrics/measurestring)(string, double) | Mide la cadena y devuelve el ancho de la cadena. |

### Ver también

* class [FontMetrics](../../aspose.font/fontmetrics)
* espacio de nombres [Aspose.Font.Ttf](../../aspose.font.ttf)
* asamblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->