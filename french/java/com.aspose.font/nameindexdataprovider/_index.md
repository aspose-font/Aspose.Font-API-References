---
title: "NameIndexDataProvider"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Fournit des paramètres communs aux polices CFF."
type: docs
weight: 68
url: /fr/java/com.aspose.font/nameindexdataprovider/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.ICffIndexDataProvider](../../com.aspose.font/icffindexdataprovider)
```
public abstract class NameIndexDataProvider implements ICffIndexDataProvider
```

Fournit des paramètres communs aux polices CFF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [NameIndexDataProvider()](#NameIndexDataProvider--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addName(String name)](#addName-java.lang.String-) | Ajoute un nom de police à la structure Name INDEX. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Obtient le nom de la police à l'index spécifié. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtient le nombre d'objets dans la structure CFF INDEX. |
| [getName(int index)](#getName-int-) | Obtient le nom de la police à l'index spécifié. |
| [getRawBytes()](#getRawBytes--) | Obtient tous les octets de la structure CFF INDEX. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeName(int index)](#removeName-int-) | Supprime le nom à l'index spécifié. |
| [set(int index, String name)](#set-int-java.lang.String-) | Spécifie le nom de police à l'index spécifié. |
| [setName(String name, int index)](#setName-java.lang.String-int-) | Définit le nom de police à l'index spécifié. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NameIndexDataProvider() {#NameIndexDataProvider--}
```
public NameIndexDataProvider()
```


### addName(String name) {#addName-java.lang.String-}
```
public abstract void addName(String name)
```


Ajoute un nom de police à la structure Name INDEX. Utilisez cette méthode avec prudence car chaque nom de police dans la structure CFF Name INDEX doit avoir une structure DICT correspondante dans l'index Top DICT selon la spécification CFF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

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
### get(int index) {#get-int-}
```
public abstract String get(int index)
```


Obtient le nom de la police à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de police. |

**Returns:**
java.lang.String - Nom de police.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtient le nombre d'objets dans la structure CFF INDEX.

**Returns:**
int
### getName(int index) {#getName-int-}
```
public abstract String getName(int index)
```


Obtient le nom de la police à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de police. |

**Returns:**
java.lang.String - Le nom de police.
### getRawBytes() {#getRawBytes--}
```
public abstract byte[] getRawBytes()
```


Obtient tous les octets de la structure CFF INDEX.

**Returns:**
byte[] - Octets de la structure CFF INDEX
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




### removeName(int index) {#removeName-int-}
```
public abstract void removeName(int index)
```


Supprime le nom à l'index spécifié. Utilisez cette méthode avec prudence car chaque nom de police dans la structure CFF Name INDEX doit avoir une structure DICT correspondante dans l'index Top DICT selon la spécification CFF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de police. |

### set(int index, String name) {#set-int-java.lang.String-}
```
public abstract void set(int index, String name)
```


Spécifie le nom de police à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de police. |
| nom | java.lang.String | Nom de police. |

### setName(String name, int index) {#setName-java.lang.String-int-}
```
public abstract void setName(String name, int index)
```


Définit le nom de police à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de police. |
| index | int | Index de police. |

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

