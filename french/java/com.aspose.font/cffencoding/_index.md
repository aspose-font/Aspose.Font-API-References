---
title: "CffEncoding"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente l'encodage _font CFF."
type: docs
weight: 18
url: /fr/java/com.aspose.font/cffencoding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.IFontEncoding](../../com.aspose.font/ifontencoding), [com.aspose.font.ISupportsNameAddressing](../../com.aspose.font/isupportsnameaddressing)
```
public class CffEncoding implements IFontEncoding, ISupportsNameAddressing
```

Représente le codage \_font CFF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [decodeToGid(long charCode)](#decodeToGid-long-) | Obtient le Gid pour le charCode fourni. |
| [decodeToGidParameterized(IEncodingParameters parameters, long charCode)](#decodeToGidParameterized-com.aspose.font.IEncodingParameters-long-) | Méthode de décodage paramétrée. |
| [encode(long gid, long charCode)](#encode-long-long-) | Encode le glyphe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNameToCharCodeIndex()](#getNameToCharCodeIndex--) | Renvoie la table de correspondance du nom au code de caractère. |
| [getNameToGidIndex()](#getNameToGidIndex--) | Renvoie la table de correspondance du nom au code de caractère. |
| [getNameToSidIndex()](#getNameToSidIndex--) | Renvoie la table de correspondance du nom au code de caractère. |
| [getSidName(int sid)](#getSidName-int-) | Obtient le nom pour le SID spécifié. |
| [gidToUnicode(GlyphId gid)](#gidToUnicode-com.aspose.font.GlyphId-) | Décode Gid en unicode. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unicodeToGid(long unicode)](#unicodeToGid-long-) | Décode un unicode et renvoie l'ID du glyphe. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeToGid(long charCode) {#decodeToGid-long-}
```
public GlyphId decodeToGid(long charCode)
```


Obtient le Gid pour le charCode fourni. Cette méthode est conçue pour les CFF CIDFonts, où le charCode doit être une valeur CID valide. L'identifiant de glyphe est un numéro unique pour un glyphe, qui dépend du type \_font. L'identifiant de glyphe CFF Font peut être une instance de la classe ( GlyphStringId ) ou de la classe ( GlyphUInt32Id ).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| charCode | long | Code de caractère (CID) pour obtenir l'identifiant du glyphe. |

**Returns:**
[GlyphId](../../com.aspose.font/glyphid) - Glyph identifier related to CID passed.
### decodeToGidParameterized(IEncodingParameters parameters, long charCode) {#decodeToGidParameterized-com.aspose.font.IEncodingParameters-long-}
```
public GlyphId decodeToGidParameterized(IEncodingParameters parameters, long charCode)
```


Méthode de décodage paramétrée. Non prise en charge pour le type de police CFF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | [IEncodingParameters](../../com.aspose.font/iencodingparameters) | Implémentation de l'interface  IEncodingParameters . |
| charCode | long | Code de caractère pour obtenir l'identifiant du glyphe. |

**Returns:**
[GlyphId](../../com.aspose.font/glyphid) - Glyph identifier related to charCode passed.
### encode(long gid, long charCode) {#encode-long-long-}
```
public void encode(long gid, long charCode)
```


Encode le glyphe. Non pris en charge pour les types de police CFF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gid | long | Identifiant du glyphe |
| charCode | long | CharCode associé à l'identifiant du glyphe. |

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


Renvoie la table de correspondance nom → code de caractère. Remarque : le code de caractère n'est pas un unicode. Le code de caractère est un indice de caractère dans la \"table\" d'encodage de la police.

**Returns:**
[NameToCodeMap](../../com.aspose.font/nametocodemap) - Name to character code encoding map.
### getNameToGidIndex() {#getNameToGidIndex--}
```
public NameToCodeMap getNameToGidIndex()
```


Renvoie la table de correspondance nom → code de caractère. Remarque : le code de caractère n'est pas un unicode. Le code de caractère est un indice de caractère dans la \"table\" d'encodage de la police.

**Returns:**
[NameToCodeMap](../../com.aspose.font/nametocodemap) - Name to character code encoding map.
### getNameToSidIndex() {#getNameToSidIndex--}
```
public NameToCodeMap getNameToSidIndex()
```


Renvoie la table de correspondance nom → code de caractère. Remarque : le code de caractère n'est pas un unicode. Le code de caractère est un indice de caractère dans la \"table\" d'encodage de la police.

**Returns:**
[NameToCodeMap](../../com.aspose.font/nametocodemap) - Name to character code encoding map.
### getSidName(int sid) {#getSidName-int-}
```
public String getSidName(int sid)
```


Obtient le nom pour le SID spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sid | int | Identifiant de chaîne. |

**Returns:**
java.lang.String - Nom provenant de l'INDEX de chaîne si trouvé.
### gidToUnicode(GlyphId gid) {#gidToUnicode-com.aspose.font.GlyphId-}
```
public long gidToUnicode(GlyphId gid)
```


Décode le Gid en unicode. L'identifiant de glyphe est un numéro unique pour un glyphe, qui dépend du type \_font. L'identifiant de glyphe CFF Font peut être une instance de la classe ( GlyphStringId ) ou de la classe ( GlyphUInt32Id ).

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


Décode un unicode et renvoie l'identifiant du glyphe. L'identifiant du glyphe est un numéro unique pour un glyphe, qui dépend du type \_font. L'identifiant de glyphe CFF Font peut être une instance de la classe ( GlyphStringId ) ou de la classe ( GlyphUInt32Id ).

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

