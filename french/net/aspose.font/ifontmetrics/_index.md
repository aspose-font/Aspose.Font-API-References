---
title: IFontMetrics
second_title: Référence de l'API Aspose.Font pour .NET
description: Définit une interface pour les outils de mesure des polices.
type: docs
weight: 340
url: /fr/net/aspose.font/ifontmetrics/
---
## IFontMetrics interface

Définit une interface pour les outils de mesure des polices.

```csharp
public interface IFontMetrics
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Ascender](../../aspose.font/ifontmetrics/ascender) { get; set; } | Obtient la valeur ascendante de la police en unités de police. |
| [Descender](../../aspose.font/ifontmetrics/descender) { get; set; } | Obtient la valeur descendante de la police en unités de police. |
| [FontBBox](../../aspose.font/ifontmetrics/fontbbox) { get; } | Obtient la zone de délimitation de la police. |
| [FontMatrix](../../aspose.font/ifontmetrics/fontmatrix) { get; } | Obtient la matrice de transformation de police. |
| [IsFixedPitch](../../aspose.font/ifontmetrics/isfixedpitch) { get; } | Vrai, si la police est à chasse fixe. |
| [LineGap](../../aspose.font/ifontmetrics/linegap) { get; } | Obtient la valeur LineGap de la police en unités de police. |
| [TypoAscender](../../aspose.font/ifontmetrics/typoascender) { get; set; } | Obtient la valeur ascendante typographique de la police en unités de police. |
| [TypoDescender](../../aspose.font/ifontmetrics/typodescender) { get; set; } | Obtient la valeur typographique descendante de la police en unités de police. |
| [TypoLineGap](../../aspose.font/ifontmetrics/typolinegap) { get; } | Obtient la valeur typographique LineGap de la police en unités de police. |
| [UnitsPerEM](../../aspose.font/ifontmetrics/unitsperem) { get; set; } | Obtient des unités par em. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetAscender](../../aspose.font/ifontmetrics/getascender)(double) | Renvoie l'ascendant pour une taille de police spécifique. |
| [GetDescender](../../aspose.font/ifontmetrics/getdescender)(double) | Renvoie le descendant pour une taille de police spécifique. |
| [GetGlyphBBox](../../aspose.font/ifontmetrics/getglyphbbox)(GlyphId) | Renvoie le glyphe BBox. |
| [GetGlyphWidth](../../aspose.font/ifontmetrics/getglyphwidth)(GlyphId) | Renvoie la largeur du glyphe. |
| [GetKerningValue](../../aspose.font/ifontmetrics/getkerningvalue)(GlyphId, GlyphId) | Renvoie la valeur de crénage pour la paire de glyphes. |
| [GetTypoAscender](../../aspose.font/ifontmetrics/gettypoascender)(double) | Renvoie l'ascendant typographique pour une taille de police spécifique. |
| [GetTypoDescender](../../aspose.font/ifontmetrics/gettypodescender)(double) | Renvoie le descendant typographique pour une taille de police spécifique. |
| [GetTypoLineGap](../../aspose.font/ifontmetrics/gettypolinegap)(double) | Renvoie l'interligne pour une taille de police spécifique. |
| [MeasureString](../../aspose.font/ifontmetrics/measurestring)(string, double) | Mesure la chaîne et renvoie la largeur de la chaîne. |

### Voir également

* espace de noms [Aspose.Font](../../aspose.font)
* Assemblée [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
