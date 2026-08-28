---
title: "GlyphRendererBase"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la classe de base pour les rendus de glyphes."
type: docs
weight: 53
url: /fr/java/com.aspose.font/glyphrendererbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.IGlyphRenderer](../../com.aspose.font/iglyphrenderer)
```
public abstract class GlyphRendererBase implements IGlyphRenderer
```

Représente la classe de base pour les rendus de glyphes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [renderGlyph(IFont font, GlyphId glyphId)](#renderGlyph-com.aspose.font.IFont-com.aspose.font.GlyphId-) | Rend le glyphe. |
| [renderGlyph(IFont font, GlyphId glyphId, Glyph glyph, TransformationMatrix glyphPlacementMatrix)](#renderGlyph-com.aspose.font.IFont-com.aspose.font.GlyphId-com.aspose.font.Glyph-com.aspose.font.TransformationMatrix-) | Rend le glyphe, un objectif de cette version surchargée - à utiliser avec le cache des glyphes. |
| [renderGlyph(IFont font, GlyphId glyphId, TransformationMatrix glyphPlacementMatrix)](#renderGlyph-com.aspose.font.IFont-com.aspose.font.GlyphId-com.aspose.font.TransformationMatrix-) | Rend le glyphe. |
| [renderGlyph(IFont font, long glyphIndex)](#renderGlyph-com.aspose.font.IFont-long-) | Rend le glyphe |
| [renderGlyph(IFont font, long glyphIndex, TransformationMatrix glyphPlacementMatrix)](#renderGlyph-com.aspose.font.IFont-long-com.aspose.font.TransformationMatrix-) | Rend le glyphe. |
| [renderIndependentGlyphPath(IFont font, GlyphId glyphId, Glyph glyph, TransformationMatrix glyphPlacementMatrix)](#renderIndependentGlyphPath-com.aspose.font.IFont-com.aspose.font.GlyphId-com.aspose.font.Glyph-com.aspose.font.TransformationMatrix-) | Rend le glyphe en utilisant un chemin de glyphe indépendant. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### renderGlyph(IFont font, GlyphId glyphId) {#renderGlyph-com.aspose.font.IFont-com.aspose.font.GlyphId-}
```
public void renderGlyph(IFont font, GlyphId glyphId)
```


Rend le glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [IFont](../../com.aspose.font/ifont) | La police qui contient le glyphe. |
| glyphId | [GlyphId](../../com.aspose.font/glyphid) | Indice physique du glyphe dans la police. Notez que ce n'est pas un Unicode. |

### renderGlyph(IFont font, GlyphId glyphId, Glyph glyph, TransformationMatrix glyphPlacementMatrix) {#renderGlyph-com.aspose.font.IFont-com.aspose.font.GlyphId-com.aspose.font.Glyph-com.aspose.font.TransformationMatrix-}
```
public void renderGlyph(IFont font, GlyphId glyphId, Glyph glyph, TransformationMatrix glyphPlacementMatrix)
```


Rend le glyphe, un objectif de cette version surchargée - à utiliser avec le cache des glyphes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [IFont](../../com.aspose.font/ifont) | La police qui contient le glyphe. |
| glyphId | [GlyphId](../../com.aspose.font/glyphid) | Indice physique du glyphe dans la police. Notez que ce n'est pas un Unicode. |
| glyph | [Glyph](../../com.aspose.font/glyph) | Glyphe à rendre. |
| glyphPlacementMatrix | [TransformationMatrix](../../com.aspose.font/transformationmatrix) | Matrice appliquée aux coordonnées du glyphe. |

### renderGlyph(IFont font, GlyphId glyphId, TransformationMatrix glyphPlacementMatrix) {#renderGlyph-com.aspose.font.IFont-com.aspose.font.GlyphId-com.aspose.font.TransformationMatrix-}
```
public void renderGlyph(IFont font, GlyphId glyphId, TransformationMatrix glyphPlacementMatrix)
```


Rend le glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [IFont](../../com.aspose.font/ifont) | La police qui contient le glyphe. |
| glyphId | [GlyphId](../../com.aspose.font/glyphid) | Indice physique du glyphe dans la police. Notez que ce n'est pas un Unicode. |
| glyphPlacementMatrix | [TransformationMatrix](../../com.aspose.font/transformationmatrix) | Matrice appliquée aux coordonnées du glyphe. |

### renderGlyph(IFont font, long glyphIndex) {#renderGlyph-com.aspose.font.IFont-long-}
```
public void renderGlyph(IFont font, long glyphIndex)
```


Rend le glyphe

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [IFont](../../com.aspose.font/ifont) | La police qui contient le glyphe. |
| glyphIndex | long | Indice physique du glyphe dans la police. Notez que ce n'est pas un Unicode. |

### renderGlyph(IFont font, long glyphIndex, TransformationMatrix glyphPlacementMatrix) {#renderGlyph-com.aspose.font.IFont-long-com.aspose.font.TransformationMatrix-}
```
public void renderGlyph(IFont font, long glyphIndex, TransformationMatrix glyphPlacementMatrix)
```


Rend le glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [IFont](../../com.aspose.font/ifont) | La police qui contient le glyphe. |
| glyphIndex | long | Indice physique du glyphe dans la police. Notez que ce n'est pas un Unicode. |
| glyphPlacementMatrix | [TransformationMatrix](../../com.aspose.font/transformationmatrix) | Matrice appliquée aux coordonnées du glyphe. |

### renderIndependentGlyphPath(IFont font, GlyphId glyphId, Glyph glyph, TransformationMatrix glyphPlacementMatrix) {#renderIndependentGlyphPath-com.aspose.font.IFont-com.aspose.font.GlyphId-com.aspose.font.Glyph-com.aspose.font.TransformationMatrix-}
```
public void renderIndependentGlyphPath(IFont font, GlyphId glyphId, Glyph glyph, TransformationMatrix glyphPlacementMatrix)
```


Rendu du glyphe en utilisant un chemin de glyphe indépendant. La famille de fonctions RenderGlyph() modifie le chemin du glyphe lors du rendu. Cela entraîne la nécessité de recharger ce glyphe à nouveau. Cette fonction utilise une copie du chemin du glyphe et ne modifie pas le chemin du glyphe original, de sorte que le même glyphe puisse être réutilisé plusieurs fois. Cette version de la fonction est destinée à être utilisée avec un cache de glyphes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [IFont](../../com.aspose.font/ifont) | La police qui contient le glyphe. |
| glyphId | [GlyphId](../../com.aspose.font/glyphid) | Indice physique du glyphe dans la police. Notez que ce n'est pas un Unicode. |
| glyph | [Glyph](../../com.aspose.font/glyph) | Glyphe à rendre. |
| glyphPlacementMatrix | [TransformationMatrix](../../com.aspose.font/transformationmatrix) | Matrice appliquée aux coordonnées du glyphe. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

