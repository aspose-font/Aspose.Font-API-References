---
title: "TtfVheaTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table hhea du fichier de police TTF."
type: docs
weight: 112
url: /fr/java/com.aspose.font/ttfvheatable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfVheaTable extends TtfTableBase
```

Représente la table "hhea" du fichier de police TTF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdvanceHeightMax()](#getAdvanceHeightMax--) | Obtient AdvanceHeightMax. |
| [getAscent()](#getAscent--) | Obtient Ascent. |
| [getCaretOffset()](#getCaretOffset--) | Obtient CaretOffset. |
| [getCaretSlopeRise()](#getCaretSlopeRise--) | Obtient CaretSlopeRise. |
| [getCaretSlopeRun()](#getCaretSlopeRun--) | Obtient CaretSlopeRun. |
| [getClass()](#getClass--) |  |
| [getDescent()](#getDescent--) | Obtient Descent. |
| [getLineGap()](#getLineGap--) | Obtient LineGap. |
| [getMetricDataFormat()](#getMetricDataFormat--) | Obtient MetricDataFormat. |
| [getMinBottomSideBearing()](#getMinBottomSideBearing--) | Obtient MinBottomSideBearing. |
| [getMinTopSideBearing()](#getMinTopSideBearing--) | Obtient MinTopSideBearing. |
| [getNumOfLongVerMetrics()](#getNumOfLongVerMetrics--) | Obtient MetricDataFormat. |
| [getOffset()](#getOffset--) | Obtient le décalage depuis le début du sfnt. |
| [getTag()](#getTag--) | Obtient le tag de la table. |
| [getTtfTables()](#getTtfTables--) | Référence au référentiel de tables TTF. |
| [getVersion()](#getVersion--) | Obtient le numéro de version de la table d’en-tête verticale. |
| [getYMaxExtent()](#getYMaxExtent--) | Obtient \_yMaxExtent. |
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
### getAdvanceHeightMax() {#getAdvanceHeightMax--}
```
public short getAdvanceHeightMax()
```


Obtient AdvanceHeightMax. La mesure maximale de la hauteur d’avance en FUnits trouvée dans la police.

**Returns:**
short - Le AdvanceHeightMax.
### getAscent() {#getAscent--}
```
public short getAscent()
```


Obtient Ascent. Distance en FUnits de la ligne centrale à la \_descent de la ligne précédente\\u2019s.

**Returns:**
short - Le Ascent.
### getCaretOffset() {#getCaretOffset--}
```
public short getCaretOffset()
```


Obtient CaretOffset.

**Returns:**
short - Le CaretOffset.
### getCaretSlopeRise() {#getCaretSlopeRise--}
```
public short getCaretSlopeRise()
```


Obtient CaretSlopeRise.

**Returns:**
short - Le CaretSlopeRise.
### getCaretSlopeRun() {#getCaretSlopeRun--}
```
public short getCaretSlopeRun()
```


Obtient CaretSlopeRun.

**Returns:**
short - Le CaretSlopeRun.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescent() {#getDescent--}
```
public short getDescent()
```


Obtient Descent. Distance en FUnits de la ligne centrale à la \_ascent de la ligne suivante\\u2019s.

**Returns:**
short - Le Descent.
### getLineGap() {#getLineGap--}
```
public short getLineGap()
```


Obtient LineGap. L’écart typographique vertical pour cette police.

**Returns:**
short - Le LineGap.
### getMetricDataFormat() {#getMetricDataFormat--}
```
public short getMetricDataFormat()
```


Obtient MetricDataFormat.

**Returns:**
short - Le MetricDataFormat.
### getMinBottomSideBearing() {#getMinBottomSideBearing--}
```
public short getMinBottomSideBearing()
```


Obtient MinBottomSideBearing. La mesure minimale du sidebearing inférieur trouvée dans la police, en FUnits.

**Returns:**
short - Le MinBottomSideBearing.
### getMinTopSideBearing() {#getMinTopSideBearing--}
```
public short getMinTopSideBearing()
```


Obtient MinTopSideBearing. La mesure minimale du sidebearing supérieur trouvée dans la police, en FUnits.

**Returns:**
short - Le MinTopSideBearing.
### getNumOfLongVerMetrics() {#getNumOfLongVerMetrics--}
```
public int getNumOfLongVerMetrics()
```


Obtient MetricDataFormat. Nombre de hauteurs d'avance dans la table des métriques verticales.

**Returns:**
int - Le MetricDataFormat.
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
java.lang.String - Le tag.
### getTtfTables() {#getTtfTables--}
```
public TtfTableRepository getTtfTables()
```


Référence au référentiel de tables TTF.

**Returns:**
[TtfTableRepository](../../com.aspose.font/ttftablerepository) - Reference to TTF table repository.
### getVersion() {#getVersion--}
```
public Version16Dot16 getVersion()
```


Obtient le numéro de version de la table d’en-tête verticale.

**Returns:**
[Version16Dot16](../../com.aspose.font/version16dot16) - The Version number of the vertical header table.
### getYMaxExtent() {#getYMaxExtent--}
```
public short getYMaxExtent()
```


Obtient \_yMaxExtent.

**Returns:**
short - Le \_yMaxExtent.
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

