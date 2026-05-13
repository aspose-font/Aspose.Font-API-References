---
title: "TtfPostTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table post du fichier de police TTF"
type: docs
weight: 107
url: /fr/java/com.aspose.font/ttfposttable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfPostTable extends TtfTableBase
```

Représente la table "post" du fichier de police TTF
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllGlyphIndexesForGlyphName(String glyphName)](#getAllGlyphIndexesForGlyphName-java.lang.String-) | Obtient le tableau des index de glyphes par nom de glyphe |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Obtient le format fixe (version) de cette table. |
| [getGlyphIndex(String glyphName)](#getGlyphIndex-java.lang.String-) | Obtient l'index du glyphe par nom de glyphe. |
| [getGlyphName(long glyphIndex)](#getGlyphName-long-) | Obtient le nom du glyphe par index de glyphe. |
| [getItalicAngle()](#getItalicAngle--) | Obtient fixed italicAngle Angle italique en degrés. |
| [getMaxMemType1()](#getMaxMemType1--) | Obtient uint32 maxMemType1 Utilisation maximale de la mémoire lorsqu'une TrueType Font est téléchargée en tant que Type 1 Font. |
| [getMaxMemType42()](#getMaxMemType42--) | Obtient uint32 maxMemType42 Utilisation maximale de la mémoire lorsqu'une TrueType font est téléchargée en tant que Type 42 Font. |
| [getMinMemType1()](#getMinMemType1--) | Obtient uint32 minMemType1 Utilisation minimale de la mémoire lorsqu'une TrueType Font est téléchargée en tant que Type 1 Font. |
| [getMinMemType42()](#getMinMemType42--) | Obtient uint32 minMemType42 Utilisation minimale de la mémoire lorsqu'une TrueType font est téléchargée en tant que Type 42 Font. |
| [getOffset()](#getOffset--) | Obtient le décalage depuis le début du sfnt. |
| [getTableFormat()](#getTableFormat--) | Obtient le format fixe (version) de cette table. |
| [getTag()](#getTag--) | Obtient le tag de la table. |
| [getTtfTables()](#getTtfTables--) | Référence au référentiel de tables TTF. |
| [getUnderlinePosition()](#getUnderlinePosition--) | Obtient FWord underlinePosition Position du soulignement. |
| [getUnderlineThickness()](#getUnderlineThickness--) | Obtient FWord underlineThickness Épaisseur du soulignement. |
| [hasNoPostScriptNames()](#hasNoPostScriptNames--) | Indique qu'aucune information de nom PostScript n'est fournie pour les glyphes de ce fichier de police. |
| [hashCode()](#hashCode--) |  |
| [isFixedPitch()](#isFixedPitch--) | Obtient uint32 isFixedPitch. 0 si la police est à espacement proportionnel, non zéro si la Font n'est pas à espacement proportionnel (c.-à-d. à chasse fixe). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
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
### getAllGlyphIndexesForGlyphName(String glyphName) {#getAllGlyphIndexesForGlyphName-java.lang.String-}
```
public long[] getAllGlyphIndexesForGlyphName(String glyphName)
```


Obtient le tableau des index de glyphes par nom de glyphe

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphName | java.lang.String | Nom du glyphe |

**Returns:**
long[] - tableau d'index de glyphes
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFormat() {#getFormat--}
```
public float getFormat()
```


Obtient le format fixe (version) de cette table.

**Returns:**
float - Format fixe (version) de cette table.
### getGlyphIndex(String glyphName) {#getGlyphIndex-java.lang.String-}
```
public long getGlyphIndex(String glyphName)
```


Obtient l'index du glyphe par nom de glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphName | java.lang.String | Nom du glyphe. |

**Returns:**
long - Index du glyphe. Lorsqu'aucune information de nom PostScript n'est fournie pour les glyphes de ce fichier de police, renvoie l'index 0, qui correspond au glyphe indéfini ou au glyphe \".notdef\".
### getGlyphName(long glyphIndex) {#getGlyphName-long-}
```
public String getGlyphName(long glyphIndex)
```


Obtient le nom du glyphe par index de glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphIndex | long | Index de glyphe. |

**Returns:**
java.lang.String - Nom du glyphe. Lorsqu'aucune information de nom PostScript n'est fournie pour les glyphes de ce fichier de police, renvoie null.
### getItalicAngle() {#getItalicAngle--}
```
public float getItalicAngle()
```


Obtient fixed italicAngle Angle italique en degrés.

**Returns:**
float - fixed italicAngle Angle italique en degrés.
### getMaxMemType1() {#getMaxMemType1--}
```
public long getMaxMemType1()
```


Obtient uint32 maxMemType1 Utilisation maximale de la mémoire lorsqu'une TrueType Font est téléchargée en tant que Type 1 Font.

**Returns:**
long - UInt32 maxMemType1 Utilisation maximale de la mémoire lorsqu'une TrueType Font est téléchargée en tant que Type 1 Font.
### getMaxMemType42() {#getMaxMemType42--}
```
public long getMaxMemType42()
```


Obtient uint32 maxMemType42 Utilisation maximale de la mémoire lorsqu'une TrueType font est téléchargée en tant que Type 42 Font.

**Returns:**
long - UInt32 maxMemType42 Utilisation maximale de la mémoire lorsqu'une TrueType font est téléchargée en tant que Type 42 Font.
### getMinMemType1() {#getMinMemType1--}
```
public long getMinMemType1()
```


Obtient uint32 minMemType1 Utilisation minimale de la mémoire lorsqu'une TrueType Font est téléchargée en tant que Type 1 Font.

**Returns:**
long - UInt32 minMemType1 Utilisation minimale de la mémoire lorsqu'une TrueType Font est téléchargée en tant que Type 1 Font.
### getMinMemType42() {#getMinMemType42--}
```
public long getMinMemType42()
```


Obtient uint32 minMemType42 Utilisation minimale de la mémoire lorsqu'une TrueType font est téléchargée en tant que Type 42 Font.

**Returns:**
long - UInt32 minMemType42 Utilisation minimale de la mémoire lorsqu'une TrueType font est téléchargée en tant que Type 42 Font.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtient le décalage depuis le début du sfnt.

**Returns:**
long - Décalage depuis le début du sfnt.
### getTableFormat() {#getTableFormat--}
```
public Version16Dot16 getTableFormat()
```


Obtient le format fixe (version) de cette table. Utilisez les propriétés MajorNumber et MinorNUmber de l'objet Version16Dot16 en notation hexadécimale pour détecter la version utilisée.

**Returns:**
[Version16Dot16](../../com.aspose.font/version16dot16) - Fixed format (version) of this table.
### getTag() {#getTag--}
```
public static String getTag()
```


Obtient le tag de la table.

**Returns:**
java.lang.String - Tag de la table.
### getTtfTables() {#getTtfTables--}
```
public TtfTableRepository getTtfTables()
```


Référence au référentiel de tables TTF.

**Returns:**
[TtfTableRepository](../../com.aspose.font/ttftablerepository) - Reference to TTF table repository.
### getUnderlinePosition() {#getUnderlinePosition--}
```
public short getUnderlinePosition()
```


Obtient FWord underlinePosition Position du soulignement.

**Returns:**
short - FWord underlinePosition Position du soulignement.
### getUnderlineThickness() {#getUnderlineThickness--}
```
public short getUnderlineThickness()
```


Obtient FWord underlineThickness Épaisseur du soulignement.

**Returns:**
short - FWord underlineThickness Épaisseur du soulignement.
### hasNoPostScriptNames() {#hasNoPostScriptNames--}
```
public boolean hasNoPostScriptNames()
```


Indique qu'aucune information de nom PostScript n'est fournie pour les glyphes de ce fichier de police.

**Returns:**
boolean - True, si aucune information de nom PostScript n'est fournie pour les glyphes de ce fichier de police. False, sinon.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFixedPitch() {#isFixedPitch--}
```
public long isFixedPitch()
```


Obtient uint32 isFixedPitch. 0 si la police est à espacement proportionnel, non zéro si la Font n'est pas à espacement proportionnel (c.-à-d. à chasse fixe).

**Returns:**
long - UInt32 isFixedPitch. 0 si la police est à espacement proportionnel, non zéro si la Font n'est pas à espacement proportionnel (c.-à-d. à chasse fixe).
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

