---
title: RenderIndependentGlyphPath
second_title: Référence de l'API Aspose.Font pour .NET
description: Rend le glyphe en utilisant un chemin de glyphe indépendant. La famille de fonctions RenderGlyph modifie le chemin du glyphe lors du rendu. Cela conduit alors à la nécessité de recharger à nouveau ce glyphe. Cette fonction utilise une copie du chemin du glyphe et ne modifie pas le chemin du glyphe dorigine de sorte que le même glyphe peut être réutilisé plusieurs fois. Cette version de la fonction est destinée à être utilisée avec le cache de glyphes.
type: docs
weight: 20
url: /fr/net/aspose.font.renderers/glyphrendererbase/renderindependentglyphpath/
---
## GlyphRendererBase.RenderIndependentGlyphPath method

Rend le glyphe en utilisant un chemin de glyphe indépendant. La famille de fonctions RenderGlyph() modifie le chemin du glyphe lors du rendu. Cela conduit alors à la nécessité de recharger à nouveau ce glyphe. Cette fonction utilise une copie du chemin du glyphe et ne modifie pas le chemin du glyphe d'origine, de sorte que le même glyphe peut être réutilisé plusieurs fois. Cette version de la fonction est destinée à être utilisée avec le cache de glyphes.

```csharp
public void RenderIndependentGlyphPath(IFont font, GlyphId glyphId, Glyph glyph, 
    TransformationMatrix glyphPlacementMatrix)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| font | IFont | La police qui contient le glyphe. |
| glyphId | GlyphId | Index de glyphe physique à l'intérieur de la police. Notez qu'il ne s'agit pas d'un unicode. |
| glyph | Glyph | Glyphe à rendre. |
| glyphPlacementMatrix | TransformationMatrix | Matrice appliquée aux coordonnées du glyphe. |

### Voir également

* interface [IFont](../../../aspose.font/ifont)
* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* class [Glyph](../../../aspose.font.glyphs/glyph)
* class [TransformationMatrix](../../../aspose.font/transformationmatrix)
* class [GlyphRendererBase](../../glyphrendererbase)
* espace de noms [Aspose.Font.Renderers](../../glyphrendererbase)
* Assemblée [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->