---
title: "TtfGaspTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table gasp du fichier de police TTF."
type: docs
weight: 97
url: /fr/java/com.aspose.font/ttfgasptable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfGaspTable extends TtfTableBase
```

Représente la table "gasp" du fichier de police TTF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGaspRanges()](#getGaspRanges--) | Obtient la liste des enregistrements GaspRange qui fournit des comportements recommandés pour diverses tailles ppem. |
| [getNumRanges()](#getNumRanges--) | Obtient les enregistrements GaspRange. |
| [getOffset()](#getOffset--) | Obtient le décalage depuis le début du sfnt. |
| [getTag()](#getTag--) | Obtient le tag de la table. |
| [getTtfTables()](#getTtfTables--) | Référence au référentiel de tables TTF. |
| [getVersion()](#getVersion--) | Obtient la version de la table. |
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
### getGaspRanges() {#getGaspRanges--}
```
public List<GaspRange> getGaspRanges()
```


Obtient la liste des enregistrements GaspRange qui fournit des comportements recommandés pour diverses tailles ppem.

**Returns:**
java.util.List<com.aspose.font.GaspRange> - La liste des GaspRange.
### getNumRanges() {#getNumRanges--}
```
public int getNumRanges()
```


Obtient les enregistrements GaspRange.

**Returns:**
int - Enregistrements GaspRange.
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
java.lang.String - Le tag de la table.
### getTtfTables() {#getTtfTables--}
```
public TtfTableRepository getTtfTables()
```


Référence au référentiel de tables TTF.

**Returns:**
[TtfTableRepository](../../com.aspose.font/ttftablerepository) - Reference to TTF table repository.
### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient la version de la table.

**Returns:**
int - La version de la table.
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

