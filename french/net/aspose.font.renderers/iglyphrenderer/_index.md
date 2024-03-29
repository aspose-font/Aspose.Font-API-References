---
title: IGlyphRenderer
second_title: Référence de l'API Aspose.Font pour .NET
description: Interface utilisée pour rendre les glyphes.
type: docs
weight: 420
url: /fr/net/aspose.font.renderers/iglyphrenderer/
---
## IGlyphRenderer interface

Interface utilisée pour rendre les glyphes.

```csharp
public interface IGlyphRenderer
```

## Méthodes

| Nom | La description |
| --- | --- |
| [RenderGlyph](../../aspose.font.renderers/iglyphrenderer/renderglyph#renderglyph)(IFont, GlyphId) | Rend le glyphe. |
| [RenderGlyph](../../aspose.font.renderers/iglyphrenderer/renderglyph#renderglyph_3)(IFont, uint) | Rend le glyphe. |
| [RenderGlyph](../../aspose.font.renderers/iglyphrenderer/renderglyph#renderglyph_2)(IFont, GlyphId, TransformationMatrix) | Rend le glyphe. |
| [RenderGlyph](../../aspose.font.renderers/iglyphrenderer/renderglyph#renderglyph_4)(IFont, uint, TransformationMatrix) | Rend le glyphe. |
| [RenderGlyph](../../aspose.font.renderers/iglyphrenderer/renderglyph#renderglyph_1)(IFont, GlyphId, Glyph, TransformationMatrix) | Rend le glyphe, un objectif de cette version surchargée - à utiliser avec le cache pour les glyphes. |
| [RenderIndependentGlyphPath](../../aspose.font.renderers/iglyphrenderer/renderindependentglyphpath)(IFont, GlyphId, Glyph, TransformationMatrix) | Rend le glyphe en utilisant un chemin de glyphe indépendant. La famille de fonctions RenderGlyph() modifie le chemin du glyphe lors du rendu. Cela conduit alors à la nécessité de recharger à nouveau ce glyphe. Cette fonction utilise une copie du chemin du glyphe et ne modifie pas le chemin du glyphe d'origine, de sorte que le même glyphe peut être réutilisé plusieurs fois. Cette version de la fonction est destinée à être utilisée avec le cache de glyphes. |

### Voir également

* espace de noms [Aspose.Font.Renderers](../../aspose.font.renderers)
* Assemblée [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
