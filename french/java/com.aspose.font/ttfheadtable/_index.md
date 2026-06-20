---
title: "TtfHeadTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table d'en-tête du fichier de police TTF."
type: docs
weight: 99
url: /fr/java/com.aspose.font/ttfheadtable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfHeadTable extends TtfTableBase
```

Représente la table "head" du fichier de police TTF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckSumAdjustment()](#getCheckSumAdjustment--) | Obtient uint32 checkSumAdjustment. |
| [getClass()](#getClass--) |  |
| [getCreated()](#getCreated--) | Obtient longDateTime créé date internationale. |
| [getFlags()](#getFlags--) | Obtient uint16 flags. |
| [getFontDirectionHint()](#getFontDirectionHint--) | Obtient int16 fontDirectionHint. 0 Glyphes à direction mixte ; 1 Seulement des glyphes fortement de gauche à droite ; 2 Comme 1 mais contient également des neutres ; -1 Seulement des glyphes fortement de droite à gauche ; -2 Comme -1 mais contient également des neutres. |
| [getFontRevision()](#getFontRevision--) | Obtient le fontRevision fixe défini par le fabricant de police. |
| [getGlyphDataFormat()](#getGlyphDataFormat--) | Obtient int16 glyphDataFormat 0 pour le format actuel. |
| [getIndexToLocFormat()](#getIndexToLocFormat--) | Obtient int16 indexToLocFormat 0 pour les décalages courts, 1 pour les longs. |
| [getLowestRecPPEM()](#getLowestRecPPEM--) | Obtient uint16 lowestRecPPEM plus petite taille lisible en pixels. |
| [getMacStyle()](#getMacStyle--) | Obtient uint16 macStyle. |
| [getMagicNumber()](#getMagicNumber--) | Obtient uint32 magicNumber défini à 0x5F0F3CF5. |
| [getModified()](#getModified--) | Obtient longDateTime modifié date internationale. |
| [getOffset()](#getOffset--) | Obtient le décalage depuis le début du sfnt. |
| [getTag()](#getTag--) | Obtient le tag de la table. |
| [getTtfTables()](#getTtfTables--) | Référence au référentiel de tables TTF. |
| [getUnitsPerEM()](#getUnitsPerEM--) | Obtient uint16 unitsPerEM plage de 64 à 16384. |
| [getVersion()](#getVersion--) | Version fixe 0x00010000 si (version 1.0). |
| [getXMax()](#getXMax--) | Obtient FWord xMax pour toutes les boîtes englobantes de glyphes. |
| [getXMin()](#getXMin--) | Obtient FWord xMin pour toutes les boîtes englobantes de glyphes. |
| [getYMax()](#getYMax--) | Obtient FWord yMax pour toutes les boîtes englobantes de glyphes. |
| [getYMin()](#getYMin--) | Obtient FWord yMin pour toutes les boîtes englobantes de glyphes. |
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
### getCheckSumAdjustment() {#getCheckSumAdjustment--}
```
public long getCheckSumAdjustment()
```


Obtient uint32 checkSumAdjustment. Pour calculer : le définir à 0, calculer la somme de contrôle pour la table 'head' et la placer dans le répertoire de tables, sommer l'ensemble de la police en tant que uint32, puis stocker B1B0AFBA - somme. La somme de contrôle pour la table 'head' ne sera pas incorrecte. C'est correct.

**Returns:**
long - Uint32 checkSumAdjustment.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreated() {#getCreated--}
```
public Date getCreated()
```


Obtient longDateTime créé date internationale.

**Returns:**
java.util.Date - LongDateTime créé date internationale.
### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtient uint16 flags.

**Returns:**
int - UInt16 flags.
### getFontDirectionHint() {#getFontDirectionHint--}
```
public short getFontDirectionHint()
```


Obtient int16 fontDirectionHint. 0 Glyphes à direction mixte ; 1 Seulement des glyphes fortement de gauche à droite ; 2 Comme 1 mais contient également des neutres ; -1 Seulement des glyphes fortement de droite à gauche ; -2 Comme -1 mais contient également des neutres.

**Returns:**
short - Int16 fontDirectionHint.
### getFontRevision() {#getFontRevision--}
```
public float getFontRevision()
```


Obtient le fontRevision fixe défini par le fabricant de police.

**Returns:**
float - Fixed fontRevision défini par le fabricant de police.
### getGlyphDataFormat() {#getGlyphDataFormat--}
```
public short getGlyphDataFormat()
```


Obtient int16 glyphDataFormat 0 pour le format actuel.

**Returns:**
short - Int16 glyphDataFormat 0 pour le format actuel.
### getIndexToLocFormat() {#getIndexToLocFormat--}
```
public short getIndexToLocFormat()
```


Obtient int16 indexToLocFormat 0 pour les décalages courts, 1 pour les longs.

**Returns:**
short - Int16 indexToLocFormat 0 pour les décalages courts, 1 pour les longs.
### getLowestRecPPEM() {#getLowestRecPPEM--}
```
public int getLowestRecPPEM()
```


Obtient uint16 lowestRecPPEM plus petite taille lisible en pixels.

**Returns:**
int - UInt16 lowestRecPPEM la plus petite taille lisible en pixels.
### getMacStyle() {#getMacStyle--}
```
public int getMacStyle()
```


Obtient uint16 macStyle.

**Returns:**
int - UInt16 macStyle.
### getMagicNumber() {#getMagicNumber--}
```
public long getMagicNumber()
```


Obtient uint32 magicNumber défini à 0x5F0F3CF5.

**Returns:**
long - UInt32 magicNumber défini à 0x5F0F3CF5.
### getModified() {#getModified--}
```
public Date getModified()
```


Obtient longDateTime modifié date internationale.

**Returns:**
java.util.Date - LongDateTime date internationale modifiée.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtient le décalage depuis le début du sfnt.

**Returns:**
long - Décalage depuis le début du sfnt.
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
### getUnitsPerEM() {#getUnitsPerEM--}
```
public long getUnitsPerEM()
```


Obtient uint16 unitsPerEM plage de 64 à 16384.

**Returns:**
long - UInt16 unitsPerEM plage de 64 à 16384.
### getVersion() {#getVersion--}
```
public float getVersion()
```


Version fixe 0x00010000 si (version 1.0).

**Returns:**
float - Version fixe 0x00010000 si (version 1.0).
### getXMax() {#getXMax--}
```
public short getXMax()
```


Obtient FWord xMax pour toutes les boîtes englobantes de glyphes.

**Returns:**
short - FWord xMax pour toutes les boîtes englobantes des glyphes.
### getXMin() {#getXMin--}
```
public short getXMin()
```


Obtient FWord xMin pour toutes les boîtes englobantes de glyphes.

**Returns:**
short - FWord xMin pour toutes les boîtes englobantes des glyphes.
### getYMax() {#getYMax--}
```
public short getYMax()
```


Obtient FWord yMax pour toutes les boîtes englobantes de glyphes.

**Returns:**
short - FWord yMax pour toutes les boîtes englobantes des glyphes.
### getYMin() {#getYMin--}
```
public short getYMin()
```


Obtient FWord yMin pour toutes les boîtes englobantes de glyphes.

**Returns:**
short - FWord yMin pour toutes les boîtes englobantes des glyphes.
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

