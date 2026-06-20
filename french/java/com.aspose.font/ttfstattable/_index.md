---
title: "TtfStatTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: 
type: docs
weight: 109
url: /fr/java/com.aspose.font/ttfstattable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfStatTable extends TtfTableBase
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [addAxisRecord(AxisRecord axisRecord)](#addAxisRecord-com.aspose.font.AxisRecord-) | Ajoute une structure Axis Record à la table. |
| [addAxisValueTable(AxisValueTableBase axisValueTable)](#addAxisValueTable-com.aspose.font.AxisValueTableBase-) | Ajoute une structure Axis Value Table à la table. |
| [clearAxisRecords()](#clearAxisRecords--) | Supprime tous les enregistrements d'axe de la table. |
| [clearAxisValueTables()](#clearAxisValueTables--) | Supprime toutes les tables de valeurs d'axe de la table. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisRecords()](#getAxisRecords--) | Renvoie le tableau des axes de conception. |
| [getAxisValueCount()](#getAxisValueCount--) | Renvoie le nombre de tables de valeurs d'axe. |
| [getAxisValueTables()](#getAxisValueTables--) | Renvoie le tableau des tables de valeurs d'axe. |
| [getClass()](#getClass--) |  |
| [getDesignAxisCount()](#getDesignAxisCount--) | Renvoie le nombre d'enregistrements d'axe. |
| [getElidedFallbackName()](#getElidedFallbackName--) | Spec: Nom utilisé comme solution de repli lorsque la projection des noms dans un modèle de police particulier produit un nom de sous-famille ne contenant que des éléments élidables. |
| [getElidedFallbackNameId()](#getElidedFallbackNameId--) | Spec: ID de nom utilisé comme solution de repli lorsque la projection des noms dans un modèle de police particulier produit un nom de sous-famille ne contenant que des éléments élidables. |
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
### addAxisRecord(AxisRecord axisRecord) {#addAxisRecord-com.aspose.font.AxisRecord-}
```
public void addAxisRecord(AxisRecord axisRecord)
```


Ajoute une structure Axis Record à la table.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| axisRecord | [AxisRecord](../../com.aspose.font/axisrecord) | Structure AxisRecord |

### addAxisValueTable(AxisValueTableBase axisValueTable) {#addAxisValueTable-com.aspose.font.AxisValueTableBase-}
```
public void addAxisValueTable(AxisValueTableBase axisValueTable)
```


Ajoute une structure Axis Value Table à la table.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| axisValueTable | [AxisValueTableBase](../../com.aspose.font/axisvaluetablebase) | Structure Axis value table |

### clearAxisRecords() {#clearAxisRecords--}
```
public void clearAxisRecords()
```


Supprime tous les enregistrements d'axe de la table.

### clearAxisValueTables() {#clearAxisValueTables--}
```
public void clearAxisValueTables()
```


Supprime toutes les tables de valeurs d'axe de la table.

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
### getAxisRecords() {#getAxisRecords--}
```
public AxisRecord[] getAxisRecords()
```


Renvoie le tableau des axes de conception. Le tableau des axes est un tableau de structures de type Axis Record. Spec: l'enregistrement d'axe fournit des informations sur un seul axe de conception.

**Returns:**
com.aspose.font.AxisRecord[] - Le tableau des axes de conception.
### getAxisValueCount() {#getAxisValueCount--}
```
public int getAxisValueCount()
```


Renvoie le nombre de tables de valeurs d'axe.

**Returns:**
int - Le nombre de tables de valeurs d'axe.
### getAxisValueTables() {#getAxisValueTables--}
```
public AxisValueTableBase[] getAxisValueTables()
```


Renvoie le tableau des tables de valeurs d'axe. Spec: Les tables de valeurs d'axe fournissent des détails concernant une valeur d'attribut de style spécifique sur un axe particulier de variation de conception, ou une combinaison de valeurs d'axes de variation de conception, ainsi que la relation de ces valeurs avec les libellés utilisés comme éléments dans les noms de sous-famille.

**Returns:**
com.aspose.font.AxisValueTableBase[] - Le tableau des tables de valeurs d'axe.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDesignAxisCount() {#getDesignAxisCount--}
```
public int getDesignAxisCount()
```


Renvoie le nombre d'enregistrements d'axe. Spéc: dans une police contenant une table 'fvar', cette valeur doit être supérieure ou égale à la valeur axisCount dans la table 'fvar'. Dans toutes les polices, elle doit être supérieure à zéro si axisValueCount est supérieur à zéro.

**Returns:**
int - Le nombre d'enregistrements d'axe.
### getElidedFallbackName() {#getElidedFallbackName--}
```
public String getElidedFallbackName()
```


Spec: Nom utilisé comme solution de repli lorsque la projection des noms dans un modèle de police particulier produit un nom de sous-famille ne contenant que des éléments élidables.

**Returns:**
java.lang.String - Le nom utilisé comme valeur de secours lorsque la projection des noms dans un modèle de police particulier produit un nom de sous-famille ne contenant que des éléments éliminables.
### getElidedFallbackNameId() {#getElidedFallbackNameId--}
```
public int getElidedFallbackNameId()
```


Spec: ID de nom utilisé comme solution de repli lorsque la projection des noms dans un modèle de police particulier produit un nom de sous-famille ne contenant que des éléments élidables.

**Returns:**
int - L'ID du nom.
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

