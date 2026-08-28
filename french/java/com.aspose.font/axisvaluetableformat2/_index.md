---
title: "AxisValueTableFormat2"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente le format 2 de la table de valeurs d'axe"
type: docs
weight: 14
url: /fr/java/com.aspose.font/axisvaluetableformat2/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.AxisValueTableBase](../../com.aspose.font/axisvaluetablebase)
```
public class AxisValueTableFormat2 extends AxisValueTableBase
```

Représente le format 2 de la table de valeurs d'axe
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AxisValueTableFormat2(int flags, int valueNameId, int axisIndex, float nominalValue, float rangeMinValue, float rangeMaxValue)](#AxisValueTableFormat2-int-int-int-float-float-float-) | Constructeur |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisIndex()](#getAxisIndex--) | Obtient l'index de base zéro dans le tableau d'enregistrements d'axes identifiant l'axe de variation de conception auquel la table de valeurs d'axe s'applique. |
| [getClass()](#getClass--) |  |
| [getFlags()](#getFlags--) | Obtient le champ des indicateurs de la table de valeurs d'axe. |
| [getFormat()](#getFormat--) | Obtient l'identifiant du format (numéro de version). |
| [getNominalValue()](#getNominalValue--) | Une valeur numérique nominale |
| [getRangeMaxValue()](#getRangeMaxValue--) | La valeur maximale pour une plage associée à l'ID de nom spécifié. |
| [getRangeMinValue()](#getRangeMinValue--) | La valeur minimale pour une plage associée à l'ID de nom spécifié. |
| [getValueName()](#getValueName--) | Obtient le nom de la table 'name' qui fournit une chaîne d'affichage pour cette valeur d'attribut. |
| [getValueNameId()](#getValueNameId--) | Obtient l'ID de nom pour les entrées de la table 'name' qui fournissent une chaîne d'affichage pour cette valeur d'attribut. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisValueTableFormat2(int flags, int valueNameId, int axisIndex, float nominalValue, float rangeMinValue, float rangeMaxValue) {#AxisValueTableFormat2-int-int-int-float-float-float-}
```
public AxisValueTableFormat2(int flags, int valueNameId, int axisIndex, float nominalValue, float rangeMinValue, float rangeMaxValue)
```


Constructeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indicateurs | int | Indicateurs |
| valueNameId | int | L'ID de nom pour les entrées de la table 'name' qui fournissent une chaîne d'affichage pour cette valeur d'attribut |
| axisIndex | int | Spéc.: Index Zero-base dans le tableau d'enregistrements d'axes identifiant l'axe de variation de conception auquel la table de valeurs d'axe s'applique. Doit être inférieur à designAxisCount. |
| nominalValue | float | La valeur numérique nominale pour cette valeur d'attribut. |
| rangeMinValue | float | La valeur minimale pour une plage associée à l'ID de nom spécifié. |
| rangeMaxValue | float | La valeur maximale pour une plage associée à l'ID de nom spécifié. |

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
### getAxisIndex() {#getAxisIndex--}
```
public int getAxisIndex()
```


Obtient l'index de base zéro dans le tableau d'enregistrements d'axes identifiant l'axe de variation de conception auquel la table de valeurs d'axe s'applique.

**Returns:**
int - L'index à base zéro dans le tableau d'enregistrements d'axe identifiant l'axe de variation de conception auquel la table de valeurs d'axe s'applique.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtient le champ des indicateurs de la table de valeurs d'axe.

**Returns:**
int - Le champ des indicateurs de la table de valeurs d'axe.
### getFormat() {#getFormat--}
```
public int getFormat()
```


Obtient l'identifiant du format (numéro de version).

**Returns:**
int - L'identifiant de format (numéro de version).
### getNominalValue() {#getNominalValue--}
```
public float getNominalValue()
```


Une valeur numérique nominale

**Returns:**
float - Une valeur numérique nominale
### getRangeMaxValue() {#getRangeMaxValue--}
```
public float getRangeMaxValue()
```


La valeur maximale pour une plage associée à l'ID de nom spécifié.

**Returns:**
float - La valeur maximale pour une plage associée à l'ID de nom spécifié.
### getRangeMinValue() {#getRangeMinValue--}
```
public float getRangeMinValue()
```


La valeur minimale pour une plage associée à l'ID de nom spécifié.

**Returns:**
float - La valeur minimale pour une plage associée à l'ID de nom spécifié.
### getValueName() {#getValueName--}
```
public String getValueName()
```


Obtient le nom de la table 'name' qui fournit une chaîne d'affichage pour cette valeur d'attribut.

**Returns:**
java.lang.String - Le nom provenant de la table 'name' qui fournit une chaîne d'affichage pour cette valeur d'attribut.
### getValueNameId() {#getValueNameId--}
```
public int getValueNameId()
```


Obtient l'ID de nom pour les entrées de la table 'name' qui fournissent une chaîne d'affichage pour cette valeur d'attribut.

**Returns:**
int - L'ID de nom pour les entrées de la table 'name' qui fournissent une chaîne d'affichage pour cette valeur d'attribut.
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

