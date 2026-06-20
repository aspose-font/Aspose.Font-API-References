---
title: "FontMetrics"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente les métriques de la police."
type: docs
weight: 44
url: /fr/java/com.aspose.font/fontmetrics/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.IFontMetrics](../../com.aspose.font/ifontmetrics)
```
public abstract class FontMetrics implements IFontMetrics
```

Représente les métriques de la police.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAscender()](#getAscender--) | Obtient la valeur Ascender. |
| [getAscender(double fontSize)](#getAscender-double-) | Renvoie l'ascender pour une taille de police spécifique. |
| [getClass()](#getClass--) |  |
| [getDescender()](#getDescender--) | Obtient la valeur Descender. |
| [getDescender(double fontSize)](#getDescender-double-) | Renvoie le descender pour une taille de police spécifique. |
| [getFontBBox()](#getFontBBox--) | Obtient la valeur FontBBox. |
| [getFontMatrix()](#getFontMatrix--) | Obtient la valeur FontMatrix. |
| [getGlyphBBox(GlyphId glyphId)](#getGlyphBBox-com.aspose.font.GlyphId-) | Renvoie le glyph Bbox. |
| [getGlyphWidth(GlyphId glyphId)](#getGlyphWidth-com.aspose.font.GlyphId-) | Renvoie la largeur du glyph. |
| [getKerningValue(GlyphId prevGlyphId, GlyphId nextGlyphId)](#getKerningValue-com.aspose.font.GlyphId-com.aspose.font.GlyphId-) | Renvoie la valeur de crénage pour la paire de glyphes. |
| [getLineGap()](#getLineGap--) | Obtient la valeur LineGap. |
| [getTypoAscender()](#getTypoAscender--) | Obtient la valeur TypoAscender. |
| [getTypoAscender(double fontSize)](#getTypoAscender-double-) | Renvoie l'ascendant typographique pour une taille de Font size spécifique. |
| [getTypoDescender()](#getTypoDescender--) | Obtient la valeur TypoDescender. |
| [getTypoDescender(double fontSize)](#getTypoDescender-double-) | Renvoie le descendant typographique pour une taille de font size spécifique. |
| [getTypoLineGap()](#getTypoLineGap--) | Obtient la valeur TypoLineGap. |
| [getTypoLineGap(double fontSize)](#getTypoLineGap-double-) | Renvoie l'écart de ligne pour une taille de Font size spécifique. |
| [getUnitsPerEM()](#getUnitsPerEM--) | Obtient la valeur UnitsPerEM. |
| [hashCode()](#hashCode--) |  |
| [isFixedPitch()](#isFixedPitch--) | Obtient la valeur IsFixedPitch. |
| [measureString(String unicode, double fontSize)](#measureString-java.lang.String-double-) | Mesure la chaîne et renvoie la largeur de la chaîne. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAscender(double value)](#setAscender-double-) | Définit la valeur Ascender. |
| [setDescender(double value)](#setDescender-double-) | Définit la valeur Descender. |
| [setGlyphWidth(GlyphId glyphId, double value)](#setGlyphWidth-com.aspose.font.GlyphId-double-) | Définit la largeur du glyph. |
| [setTypoAscender(double value)](#setTypoAscender-double-) | Définit la valeur TypoAscender. |
| [setTypoDescender(double value)](#setTypoDescender-double-) | Définit la valeur TypoDescender. |
| [setUnitsPerEM(long value)](#setUnitsPerEM-long-) | Définit la valeur UnitsPerEM. |
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
### getAscender() {#getAscender--}
```
public double getAscender()
```


Obtient la valeur Ascender.

**Returns:**
double - valeur Ascender.
### getAscender(double fontSize) {#getAscender-double-}
```
public double getAscender(double fontSize)
```


Renvoie l'ascender pour une taille de police spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize | double | Taille de police. |

**Returns:**
double - valeur Ascender.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescender() {#getDescender--}
```
public double getDescender()
```


Obtient la valeur Descender.

**Returns:**
double - valeur Descender.
### getDescender(double fontSize) {#getDescender-double-}
```
public double getDescender(double fontSize)
```


Renvoie le descender pour une taille de police spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize | double | Taille de police. |

**Returns:**
double - valeur Descender.
### getFontBBox() {#getFontBBox--}
```
public FontBBox getFontBBox()
```


Obtient la valeur FontBBox.

**Returns:**
[FontBBox](../../com.aspose.font/fontbbox) - FontBBox value.
### getFontMatrix() {#getFontMatrix--}
```
public TransformationMatrix getFontMatrix()
```


Obtient la valeur FontMatrix.

**Returns:**
[TransformationMatrix](../../com.aspose.font/transformationmatrix) - FontMatrix value.
### getGlyphBBox(GlyphId glyphId) {#getGlyphBBox-com.aspose.font.GlyphId-}
```
public FontBBox getGlyphBBox(GlyphId glyphId)
```


Renvoie le glyph Bbox. Renvoie FontBBox si le BBox n'était pas défini pour le glyph. Peut être remplacé par des héritiers d'encodage de police spécifiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphId | [GlyphId](../../com.aspose.font/glyphid) | Identifiant du glyph. |

**Returns:**
[FontBBox](../../com.aspose.font/fontbbox) - Glyph BBox.
### getGlyphWidth(GlyphId glyphId) {#getGlyphWidth-com.aspose.font.GlyphId-}
```
public double getGlyphWidth(GlyphId glyphId)
```


Renvoie la largeur du glyphe. Peut être remplacé par des héritiers d'encodage de police spécifiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphId | [GlyphId](../../com.aspose.font/glyphid) | Identifiant du glyph. |

**Returns:**
double - Largeur du glyphe.
### getKerningValue(GlyphId prevGlyphId, GlyphId nextGlyphId) {#getKerningValue-com.aspose.font.GlyphId-com.aspose.font.GlyphId-}
```
public double getKerningValue(GlyphId prevGlyphId, GlyphId nextGlyphId)
```


Renvoie la valeur de crénage pour la paire de glyphes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| prevGlyphId | [GlyphId](../../com.aspose.font/glyphid) | Premier glyphe de la paire. |
| nextGlyphId | [GlyphId](../../com.aspose.font/glyphid) | Taille de police. |

**Returns:**
double - Valeur du crénage.
### getLineGap() {#getLineGap--}
```
public double getLineGap()
```


Obtient la valeur LineGap.

**Returns:**
double - Valeur du LineGap.
### getTypoAscender() {#getTypoAscender--}
```
public double getTypoAscender()
```


Obtient la valeur TypoAscender.

**Returns:**
double - Valeur de TypoAscender.
### getTypoAscender(double fontSize) {#getTypoAscender-double-}
```
public double getTypoAscender(double fontSize)
```


Renvoie l'ascendant typographique pour une taille de Font size spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize | double | Taille de police. |

**Returns:**
double - Valeur de l'ascendant typographique.
### getTypoDescender() {#getTypoDescender--}
```
public double getTypoDescender()
```


Obtient la valeur TypoDescender.

**Returns:**
double - Valeur de TypoDescender.
### getTypoDescender(double fontSize) {#getTypoDescender-double-}
```
public double getTypoDescender(double fontSize)
```


Renvoie le descendant typographique pour une taille de font size spécifique.

param fontSize Taille de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize | double |  |

**Returns:**
double - Valeur du descendant typographique.
### getTypoLineGap() {#getTypoLineGap--}
```
public double getTypoLineGap()
```


Obtient la valeur TypoLineGap.

**Returns:**
double - Valeur de TypoLineGap.
### getTypoLineGap(double fontSize) {#getTypoLineGap-double-}
```
public double getTypoLineGap(double fontSize)
```


Renvoie l'écart de ligne pour une taille de Font size spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize | double | Taille de police. |

**Returns:**
double - Valeur de l'écart de ligne.
### getUnitsPerEM() {#getUnitsPerEM--}
```
public long getUnitsPerEM()
```


Obtient la valeur UnitsPerEM.

**Returns:**
long - Valeur de UnitsPerEM.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFixedPitch() {#isFixedPitch--}
```
public boolean isFixedPitch()
```


Obtient la valeur IsFixedPitch.

**Returns:**
boolean - Valeur de IsFixedPitch.
### measureString(String unicode, double fontSize) {#measureString-java.lang.String-double-}
```
public abstract double measureString(String unicode, double fontSize)
```


Mesure la chaîne et renvoie la largeur de la chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| unicode | java.lang.String | Chaîne Unicode. |
| fontSize | double | Taille de police. |

**Returns:**
double - Largeur de la chaîne.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAscender(double value) {#setAscender-double-}
```
public void setAscender(double value)
```


Définit la valeur Ascender.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur de l'ascendant. |

### setDescender(double value) {#setDescender-double-}
```
public void setDescender(double value)
```


Définit la valeur Descender.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur du descendant. |

### setGlyphWidth(GlyphId glyphId, double value) {#setGlyphWidth-com.aspose.font.GlyphId-double-}
```
public abstract void setGlyphWidth(GlyphId glyphId, double value)
```


Définit la largeur du glyph.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphId | [GlyphId](../../com.aspose.font/glyphid) | Identifiant du glyph. |
| valeur | double | Nouvelle largeur. |

### setTypoAscender(double value) {#setTypoAscender-double-}
```
public void setTypoAscender(double value)
```


Définit la valeur TypoAscender.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur de TypoAscender. |

### setTypoDescender(double value) {#setTypoDescender-double-}
```
public void setTypoDescender(double value)
```


Définit la valeur TypoDescender.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur de TypoDescender. |

### setUnitsPerEM(long value) {#setUnitsPerEM-long-}
```
public void setUnitsPerEM(long value)
```


Définit la valeur UnitsPerEM.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Valeur de UnitsPerEM. |

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

