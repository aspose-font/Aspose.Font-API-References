---
title: "AxisRecord"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la structure d'enregistrement d'axe."
type: docs
weight: 10
url: /fr/java/com.aspose.font/axisrecord/
---
**Inheritance:**
java.lang.Object
```
public class AxisRecord
```

Représente la structure Axis Record. Spec: le enregistrement d'axe fournit des informations sur un seul axe de conception.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AxisRecord(String tag, int axisNameId, int axisOrdering)](#AxisRecord-java.lang.String-int-int-) | Constructeur |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisNameId()](#getAxisNameId--) | Renvoie le champ axisNameID. |
| [getAxisOrdering()](#getAxisOrdering--) | Renvoie le champ axisOrdering. |
| [getClass()](#getClass--) |  |
| [getTag()](#getTag--) | Renvoie un tag identifiant l'axe de variation de conception. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisRecord(String tag, int axisNameId, int axisOrdering) {#AxisRecord-java.lang.String-int-int-}
```
public AxisRecord(String tag, int axisNameId, int axisOrdering)
```


Constructeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tag | java.lang.String | Tag, spec: un tag identifiant l'axe de variation de conception |
| axisNameId | int | L'ID de nom pour les entrées de la table 'name' qui fournissent une chaîne d'affichage pour cet axe |
| axisOrdering | int | La valeur que les applications peuvent utiliser pour déterminer le tri principal des noms de police, ou pour l'ordre des libellés lors de la composition des noms de famille ou de police. |

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
### getAxisNameId() {#getAxisNameId--}
```
public int getAxisNameId()
```


Renvoie le champ axisNameID. Spec: le champ axisNameID fournit un ID de nom qui peut être utilisé pour obtenir des chaînes de la table 'name' pouvant être utilisées pour désigner l'axe dans les interfaces utilisateur des applications.

**Returns:**
int - le champ axisNameID.
### getAxisOrdering() {#getAxisOrdering--}
```
public int getAxisOrdering()
```


Renvoie le champ axisOrdering. Spec: une valeur que les applications peuvent utiliser pour déterminer le tri principal des noms de police, ou pour l'ordre des libellés lors de la composition des noms de famille ou de police.

**Returns:**
int - le champ axisOrdering.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTag() {#getTag--}
```
public String getTag()
```


Renvoie un tag identifiant l'axe de variation de conception. Spec: chaque enregistrement d'axe possède un tag désignant l'axe. Les valeurs de tag doivent suivre les règles des tags d'axe décrites dans le registre OpenType Design-Variation Axis Tag Registry.

**Returns:**
java.lang.String - un tag identifiant l'axe de variation de conception.
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

