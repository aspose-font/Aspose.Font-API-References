---
title: "TtfMaxpTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table maxp du fichier de police TTF"
type: docs
weight: 104
url: /fr/java/com.aspose.font/ttfmaxptable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfMaxpTable extends TtfTableBase
```

Représente la table "maxp" du fichier de police TTF
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxComponentContours()](#getMaxComponentContours--) | Obtient uint16 maxComponentContours contours dans un glyphe composé. |
| [getMaxComponentDepth()](#getMaxComponentDepth--) | Obtient uint16 maxComponentDepth niveaux de récursion, mis à 0 si la police ne contient que des glyphes simples. |
| [getMaxComponentElements()](#getMaxComponentElements--) | Obtient uint16 maxComponentElements nombre de glyphes référencés au niveau supérieur. |
| [getMaxComponentPoints()](#getMaxComponentPoints--) | Obtient uint16 maxComponentPoints points dans un glyphe composé. |
| [getMaxContours()](#getMaxContours--) | Obtient uint16 maxContours contours dans un glyphe non composé. |
| [getMaxFunctionDefs()](#getMaxFunctionDefs--) | Obtient uint16 maxFunctionDefs nombre de FDEFs. |
| [getMaxInstructionDefs()](#getMaxInstructionDefs--) | Obtient uint16 maxInstructionDefs nombre de IDEFs. |
| [getMaxPoints()](#getMaxPoints--) | Obtient uint16 maxPoints points dans un glyphe non composé. |
| [getMaxSizeOfInstructions()](#getMaxSizeOfInstructions--) | Obtient uint16 maxSizeOfInstructions nombre d'octets pour les instructions de glyphe. |
| [getMaxStackElements()](#getMaxStackElements--) | Obtient uint16 maxStackElements profondeur maximale de la pile. |
| [getMaxStorage()](#getMaxStorage--) | Obtient uint16 maxStorage nombre d'emplacements de la zone de stockage. |
| [getMaxTwilightPoints()](#getMaxTwilightPoints--) | Obtient uint16 maxTwilightPoints points utilisés dans la zone Twilight (Z0). |
| [getMaxZones()](#getMaxZones--) | Obtient uint16 maxZones fixé à 2. |
| [getNumGlyphs()](#getNumGlyphs--) | Obtient uint16 numGlyphs le nombre de glyphes dans la police. |
| [getOffset()](#getOffset--) | Obtient le décalage depuis le début du sfnt. |
| [getTableVersion()](#getTableVersion--) | Obtient la version du format. |
| [getTag()](#getTag--) | Obtient le tag de la table. |
| [getTtfTables()](#getTtfTables--) | Référence au référentiel de tables TTF. |
| [getVersion()](#getVersion--) | Obtient la version fixe 0x00010000 si (version 1.0). |
| [hashCode()](#hashCode--) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMaxComponentContours() {#getMaxComponentContours--}
```
public int getMaxComponentContours()
```


Obtient uint16 maxComponentContours contours dans un glyphe composé.

**Returns:**
int - UInt16 maxComponentContours contours dans le glyphe composé.
### getMaxComponentDepth() {#getMaxComponentDepth--}
```
public int getMaxComponentDepth()
```


Obtient uint16 maxComponentDepth niveaux de récursion, mis à 0 si la police ne contient que des glyphes simples.

**Returns:**
int - Uint16 maxComponentDepth niveaux de récursion, définissez à 0 si la police ne contient que des glyphes simples.
### getMaxComponentElements() {#getMaxComponentElements--}
```
public int getMaxComponentElements()
```


Obtient uint16 maxComponentElements nombre de glyphes référencés au niveau supérieur.

**Returns:**
int - UInt16 maxComponentElements nombre de glyphes référencés au niveau supérieur.
### getMaxComponentPoints() {#getMaxComponentPoints--}
```
public int getMaxComponentPoints()
```


Obtient uint16 maxComponentPoints points dans un glyphe composé.

**Returns:**
int - UInt16 maxComponentPoints points dans le glyphe composé.
### getMaxContours() {#getMaxContours--}
```
public int getMaxContours()
```


Obtient uint16 maxContours contours dans un glyphe non composé.

**Returns:**
int - UInt16 maxContours contours dans le glyphe non composé.
### getMaxFunctionDefs() {#getMaxFunctionDefs--}
```
public int getMaxFunctionDefs()
```


Obtient uint16 maxFunctionDefs nombre de FDEFs.

**Returns:**
int - UInt16 maxFunctionDefs nombre de FDEFs.
### getMaxInstructionDefs() {#getMaxInstructionDefs--}
```
public int getMaxInstructionDefs()
```


Obtient uint16 maxInstructionDefs nombre de IDEFs.

**Returns:**
int - UInt16 maxInstructionDefs nombre de IDEFs.
### getMaxPoints() {#getMaxPoints--}
```
public int getMaxPoints()
```


Obtient uint16 maxPoints points dans un glyphe non composé.

**Returns:**
int - UInt16 maxPoints points dans le glyphe non composé.
### getMaxSizeOfInstructions() {#getMaxSizeOfInstructions--}
```
public int getMaxSizeOfInstructions()
```


Obtient uint16 maxSizeOfInstructions nombre d'octets pour les instructions de glyphe.

**Returns:**
int - UInt16 maxSizeOfInstructions nombre d'octets pour les instructions du glyphe.
### getMaxStackElements() {#getMaxStackElements--}
```
public int getMaxStackElements()
```


Obtient uint16 maxStackElements profondeur maximale de la pile.

**Returns:**
int - UInt16 maxStackElements profondeur maximale de la pile.
### getMaxStorage() {#getMaxStorage--}
```
public int getMaxStorage()
```


Obtient uint16 maxStorage nombre d'emplacements de la zone de stockage.

**Returns:**
int - UInt16 maxStorage nombre d'emplacements de la zone de stockage.
### getMaxTwilightPoints() {#getMaxTwilightPoints--}
```
public int getMaxTwilightPoints()
```


Obtient uint16 maxTwilightPoints points utilisés dans la zone Twilight (Z0).

**Returns:**
int - UInt16 maxTwilightPoints points utilisés dans la zone Twilight (Z0).
### getMaxZones() {#getMaxZones--}
```
public int getMaxZones()
```


Obtient uint16 maxZones fixé à 2.

**Returns:**
int - Uint16 maxZones défini à 2.
### getNumGlyphs() {#getNumGlyphs--}
```
public int getNumGlyphs()
```


Obtient uint16 numGlyphs le nombre de glyphes dans la police.

**Returns:**
int - UInt16 numGlyphs le nombre de glyphes dans la police.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtient le décalage depuis le début du sfnt.

**Returns:**
long - Décalage depuis le début du sfnt.
### getTableVersion() {#getTableVersion--}
```
public Version16Dot16 getTableVersion()
```


Obtient la version du format. Utilisez les propriétés MajorNumber et MinorNUmber de l'objet Version16Dot16 en notation hexadécimale pour détecter la version utilisée.

**Returns:**
[Version16Dot16](../../com.aspose.font/version16dot16) - Format version.
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
### getVersion() {#getVersion--}
```
public float getVersion()
```


Obtient la version fixe 0x00010000 si (version 1.0). Obsolète, utilisez la propriété TableVersion à la place.

**Returns:**
float - Version fixe 0x00010000 si (version 1.0).
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

