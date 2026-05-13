---
title: "TtfEncoding"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente le codage de la police TTF."
type: docs
weight: 92
url: /fr/java/com.aspose.font/ttfencoding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.IFontEncoding](../../com.aspose.font/ifontencoding)
```
public class TtfEncoding implements IFontEncoding
```

Représente le codage de la police TTF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [decodeToGid(long unicode)](#decodeToGid-long-) | L'implémentation DecodeToGlyphId de la police TTF trouve la table unicode et renvoie l'ID du glyphe pour le caractère unicode. |
| [decodeToGidParameterized(IEncodingParameters parameters, long charCode)](#decodeToGidParameterized-com.aspose.font.IEncodingParameters-long-) | La version paramétrée permet d'utiliser une table CMap spécifique (pas unicode). |
| [encode(long gid, long charCode)](#encode-long-long-) | Encode le glyphe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gidToUnicode(GlyphId glyphId)](#gidToUnicode-com.aspose.font.GlyphId-) | Décode l'ID du glyphe en unicode. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unicodeToGid(long unicode)](#unicodeToGid-long-) | Décode un unicode et renvoie l'ID du glyphe. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeToGid(long unicode) {#decodeToGid-long-}
```
public GlyphId decodeToGid(long unicode)
```


L'implémentation DecodeToGlyphId de la police TTF trouve la table unicode et renvoie l'ID du glyphe pour le caractère unicode. L'ID du glyphe est un nombre unique pour un glyphe, dépendant du type de police. Par exemple : l'ID de Type1 est un nom de glyphe, instance de la classe ( GlyphStringId ). L'ID de TTF est un indice entier, instance de la classe ( GlyphUInt32Id ).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| unicode | long | Code de caractère pour obtenir l'identifiant du glyphe. |

**Returns:**
[GlyphId](../../com.aspose.font/glyphid) - Glyph identifier related to character code passed.
### decodeToGidParameterized(IEncodingParameters parameters, long charCode) {#decodeToGidParameterized-com.aspose.font.IEncodingParameters-long-}
```
public GlyphId decodeToGidParameterized(IEncodingParameters parameters, long charCode)
```


La version paramétrée permet d'utiliser une table CMap spécifique (pas unicode).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | [IEncodingParameters](../../com.aspose.font/iencodingparameters) | Implémentation de l'interface  IEncodingParameters . |
| charCode | long | code de caractère pour obtenir l'identifiant du glyphe. |

**Returns:**
[GlyphId](../../com.aspose.font/glyphid) - Glyph identifier related to character code passed.
### encode(long gid, long charCode) {#encode-long-long-}
```
public void encode(long gid, long charCode)
```


Encode le glyphe. Pour les polices TTF, le code de caractère est unicode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gid | long | Identifiant du glyph. |
| charCode | long | Code de caractère. |

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
### gidToUnicode(GlyphId glyphId) {#gidToUnicode-com.aspose.font.GlyphId-}
```
public long gidToUnicode(GlyphId glyphId)
```


Décode l'ID du glyphe en unicode. L'ID du glyphe est un nombre unique pour un glyphe, dépendant du type de police. Par exemple : l'ID de Type1 est un nom de glyphe, instance de la classe ( GlyphStringId ). L'ID de TTF est un indice entier, instance de la classe ( GlyphUInt32Id ).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphId | [GlyphId](../../com.aspose.font/glyphid) | Identifiant du glyphe du symbole à décoder. |

**Returns:**
long - Valeur Unicode liée à l'identifiant du glyphe fourni.
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
### unicodeToGid(long unicode) {#unicodeToGid-long-}
```
public GlyphId unicodeToGid(long unicode)
```


Décode un unicode et renvoie l'ID du glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| unicode | long | Unicode pour obtenir l'identifiant du glyphe. |

**Returns:**
[GlyphId](../../com.aspose.font/glyphid) - Glyph identifier related to unicode passed.
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

