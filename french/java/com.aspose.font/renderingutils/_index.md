---
title: "RenderingUtils"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Fournit des méthodes utilitaires pour le rendu."
type: docs
weight: 72
url: /fr/java/com.aspose.font/renderingutils/
---
**Inheritance:**
java.lang.Object
```
public class RenderingUtils
```

Fournit des méthodes utilitaires pour le rendu.
## Méthodes

| Méthode | Description |
| --- | --- |
| [drawText(Font font, GlyphId[] glyphIds, double fontSize)](#drawText-com.aspose.font.Font-com.aspose.font.GlyphId---double-) | Rendu du texte dans un BitMap. |
| [drawText(Font font, GlyphId[] glyphIds, double fontSize, RenderingUtils.LineSpacingType lineSpacingType, int lineSpacingValue, int maxWidth)](#drawText-com.aspose.font.Font-com.aspose.font.GlyphId---double-com.aspose.font.RenderingUtils.LineSpacingType-int-int-) | Rendu du texte dans un BitMap. |
| [drawText(Font font, String text, double fontSize)](#drawText-com.aspose.font.Font-java.lang.String-double-) | Rendu du texte dans un BitMap. |
| [drawText(Font font, String text, double fontSize, RenderingUtils.LineSpacingType lineSpacingType, int lineSpacingValue, int maxWidth)](#drawText-com.aspose.font.Font-java.lang.String-double-com.aspose.font.RenderingUtils.LineSpacingType-int-int-) | Rendu du texte dans un BitMap. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### drawText(Font font, GlyphId[] glyphIds, double fontSize) {#drawText-com.aspose.font.Font-com.aspose.font.GlyphId---double-}
```
public static InputStream drawText(Font font, GlyphId[] glyphIds, double fontSize)
```


Rendu du texte dans un BitMap. Retourne le résultat au format PNG sous forme de flux d'octets

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.font/font) | Police |
| glyphIds | [GlyphId\[\]](../../com.aspose.font/glyphid) | Texte représenté comme un tableau d'identifiants de glyphes |
| fontSize | double | Taille de la police |

**Returns:**
java.io.InputStream - Image au format PNG sous forme de flux d'octets
### drawText(Font font, GlyphId[] glyphIds, double fontSize, RenderingUtils.LineSpacingType lineSpacingType, int lineSpacingValue, int maxWidth) {#drawText-com.aspose.font.Font-com.aspose.font.GlyphId---double-com.aspose.font.RenderingUtils.LineSpacingType-int-int-}
```
public static InputStream drawText(Font font, GlyphId[] glyphIds, double fontSize, RenderingUtils.LineSpacingType lineSpacingType, int lineSpacingValue, int maxWidth)
```


Rendu du texte dans un BitMap. Retourne le résultat au format PNG sous forme de flux d'octets

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.font/font) | Police |
| glyphIds | [GlyphId\[\]](../../com.aspose.font/glyphid) | Texte représenté comme un tableau d'identifiants de glyphes |
| fontSize | double | Taille de la police |
| lineSpacingType | [LineSpacingType](../../com.aspose.font/linespacingtype) | Type d'interligne. Nombre de pixels ou pourcentage de la hauteur de la police |
| lineSpacingValue | int | Valeur de l'interligne |
| maxWidth | int | Largeur maximale en pixels pour l'image |

**Returns:**
java.io.InputStream - Image au format PNG sous forme de flux d'octets
### drawText(Font font, String text, double fontSize) {#drawText-com.aspose.font.Font-java.lang.String-double-}
```
public static InputStream drawText(Font font, String text, double fontSize)
```


Rendu du texte dans un BitMap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.font/font) | La police. |
| text | java.lang.String | Le texte. |
| fontSize | double | La taille de la police. |

**Returns:**
java.io.InputStream - L'image PNG contenant le texte sous forme de flux d'octets.
### drawText(Font font, String text, double fontSize, RenderingUtils.LineSpacingType lineSpacingType, int lineSpacingValue, int maxWidth) {#drawText-com.aspose.font.Font-java.lang.String-double-com.aspose.font.RenderingUtils.LineSpacingType-int-int-}
```
public static InputStream drawText(Font font, String text, double fontSize, RenderingUtils.LineSpacingType lineSpacingType, int lineSpacingValue, int maxWidth)
```


Rendu du texte dans un BitMap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.font/font) | La police. |
| text | java.lang.String | Le texte. |
| fontSize | double | La taille de la police. |
| lineSpacingType | [LineSpacingType](../../com.aspose.font/linespacingtype) | Le type d'interligne. Nombre de pixels ou pourcentage de la hauteur de la police. |
| lineSpacingValue | int | La valeur de l'interligne. |
| maxWidth | int | La largeur maximale en pixels pour l'image résultante. |

**Returns:**
java.io.InputStream - L'image PNG contenant le texte sous forme de flux d'octets.
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

