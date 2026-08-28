---
title: "TtfHmtxTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table hmtx du fichier de police TTF."
type: docs
weight: 101
url: /fr/java/com.aspose.font/ttfhmtxtable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfHmtxTable extends TtfTableBase
```

Représente la table "hmtx" du fichier de police TTF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdditionalAdvanceWidth()](#getAdditionalAdvanceWidth--) | Dans la table hmtx, il peut y avoir des cas où le nombre total de glyphes n’est pas égal à hhea.numberOfHMetrics. |
| [getClass()](#getClass--) |  |
| [getHMetrics()](#getHMetrics--) | Obtient les métriques horizontales. |
| [getLeftSidebearings()](#getLeftSidebearings--) | Obtient les marges latérales gauche. |
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
### getAdditionalAdvanceWidth() {#getAdditionalAdvanceWidth--}
```
public int getAdditionalAdvanceWidth()
```


Dans la table hmtx, il peut y avoir des cas où le nombre total de glyphes n’est pas égal à hhea.numberOfHMetrics. Pour ces cas, la table hmtx contient un tableau supplémentaire 'leftSideBearing' qui correspond à la propriété LeftSidebearings. Mais les glyphes dont les index vont de hhea.numOfLongHorMetrics à maxp.numGlyphs ont également des largeurs. Et ces largeurs, conformément à la spécification de la table hmtx, ont les valeurs suivantes : "Here the advanceWidth is assumed to be the same as the advanceWidth for the last entry above".

**Returns:**
int - Largeur d'avance supplémentaire.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHMetrics() {#getHMetrics--}
```
public TtfHmtxTable.MetricList getHMetrics()
```


Obtient les métriques horizontales.

**Returns:**
[MetricList](../../com.aspose.font/metriclist) - Horizontal metrics.
### getLeftSidebearings() {#getLeftSidebearings--}
```
public short[] getLeftSidebearings()
```


Obtient les marges latérales gauche.

**Returns:**
short[] - Marges latérales gauche.
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

