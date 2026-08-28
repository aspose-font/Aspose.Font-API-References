---
title: "Type1Encoding"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente l'encodage de police Type1."
type: docs
weight: 114
url: /fr/java/com.aspose.font/type1encoding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.IFontEncoding](../../com.aspose.font/ifontencoding), [com.aspose.font.ISupportsNameAddressing](../../com.aspose.font/isupportsnameaddressing)
```
public class Type1Encoding implements IFontEncoding, ISupportsNameAddressing
```

Représente l'encodage de police Type1.
## Méthodes

| Méthode | Description |
| --- | --- |
| [decodeToGid(long charCode)](#decodeToGid-long-) | Décode Gid en unicode. |
| [decodeToGidParameterized(IEncodingParameters parameters, long charCode)](#decodeToGidParameterized-com.aspose.font.IEncodingParameters-long-) | Méthode de décodage paramétrée. |
| [encode(long gid, long charCode)](#encode-long-long-) | Encode le glyphe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNameToCharCodeIndex()](#getNameToCharCodeIndex--) | Renvoie la table de correspondance du nom au code de caractère. |
| [gidToUnicode(GlyphId gid)](#gidToUnicode-com.aspose.font.GlyphId-) | Décode Gid en Unicode. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unicodeToGid(long unicode)](#unicodeToGid-long-) | Renvoie le GlyphId pour unicode. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeToGid(long charCode) {#decodeToGid-long-}
```
public GlyphId decodeToGid(long charCode)
```


Décode Gid en unicode. Glyph id est un numéro unique pour un glyphe, qui dépend du type de police. Par exemple : l'identifiant de Type1 est un nom de glyphe, instance de la classe ( GlyphStringId ). L'identifiant de TTF est un indice entier, instance de la classe ( GlyphUInt32Id ).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| charCode | long | Code de caractère pour obtenir l'identifiant du glyphe. |

**Returns:**
[GlyphId](../../com.aspose.font/glyphid) - Glyph identifier related to character code passed.
### decodeToGidParameterized(IEncodingParameters parameters, long charCode) {#decodeToGidParameterized-com.aspose.font.IEncodingParameters-long-}
```
public GlyphId decodeToGidParameterized(IEncodingParameters parameters, long charCode)
```


Méthode de décodage paramétrée. Non pris en charge pour le type de police Type1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | [IEncodingParameters](../../com.aspose.font/iencodingparameters) | Non pris en charge pour le type de police Type1. |
| charCode | long | Non pris en charge pour le type de police Type1. |

**Returns:**
[GlyphId](../../com.aspose.font/glyphid) - Not supported for Type1 Font type.
### encode(long gid, long charCode) {#encode-long-long-}
```
public void encode(long gid, long charCode)
```


Encode le glyphe. Pour les polices TTF, le code de caractère est unicode. Non pris en charge pour les types de police Type1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gid | long | Identifiant de glyphe. |
| charCode | long | Code de caractère associé à l'identifiant du glyphe. |

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
### getNameToCharCodeIndex() {#getNameToCharCodeIndex--}
```
public NameToCodeMap getNameToCharCodeIndex()
```


Renvoie la table de correspondance du nom au code de caractère. Remarque : le code de caractère n'est pas un unicode. Le code de caractère est un indice de caractère dans la "table" d'encodage de la police.

**Returns:**
[NameToCodeMap](../../com.aspose.font/nametocodemap) - Name to character code encoding map.
### gidToUnicode(GlyphId gid) {#gidToUnicode-com.aspose.font.GlyphId-}
```
public long gidToUnicode(GlyphId gid)
```


Décode Gid en Unicode. Glyph id est un numéro unique pour un glyphe, qui dépend du type de police. Par exemple : l'identifiant de Type1 est un nom de glyphe, instance de la classe ( GlyphStringId ). L'identifiant de TTF est un indice entier, instance de la classe ( GlyphUInt32Id ).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gid | [GlyphId](../../com.aspose.font/glyphid) | Identifiant du glyphe du symbole à décoder. |

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


Renvoie le GlyphId pour unicode. Ou notdef si la police ne contient pas de glyphe pour l'unicode. Glyph id est un numéro unique pour un glyphe, qui dépend du type de police. Par exemple : l'identifiant de Type1 est un nom de glyphe, instance de la classe ( GlyphStringId ). L'identifiant de TTF est un indice entier, instance de la classe ( GlyphUInt32Id ).

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

