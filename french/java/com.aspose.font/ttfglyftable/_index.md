---
title: "TtfGlyfTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table glyf du fichier de police TTF."
type: docs
weight: 98
url: /fr/java/com.aspose.font/ttfglyftable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfGlyfTable extends TtfTableBase
```

Représente la table "glyf" du fichier de police TTF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [containsGlyph(int glyphIndex)](#containsGlyph-int-) | Renvoie true si la table contient le glyphe avec glyphIndex. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGlyph(long glyphIndex)](#getGlyph-long-) | Renvoie un glyphe par indice de glyphe. |
| [getOffset()](#getOffset--) | Obtient le décalage depuis le début du sfnt. |
| [getTag()](#getTag--) | Obtient le tag de la table. |
| [getTtfTables()](#getTtfTables--) | Référence au référentiel de tables TTF. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsGlyph(int glyphIndex) {#containsGlyph-int-}
```
public boolean containsGlyph(int glyphIndex)
```


Renvoie true si la table contient le glyphe avec glyphIndex.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphIndex | int | Index de glyphe. |

**Returns:**
boolean - True si la table contient le glyphe pour l'indice spécifié, false sinon.
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
### getGlyph(long glyphIndex) {#getGlyph-long-}
```
public Glyph getGlyph(long glyphIndex)
```


Renvoie un glyphe par indice de glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphIndex | long | Index de glyphe. |

**Returns:**
[Glyph](../../com.aspose.font/glyph) - Glyph Glyph related to index specified.
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

