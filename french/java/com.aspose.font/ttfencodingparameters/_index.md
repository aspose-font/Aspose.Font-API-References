---
title: "TtfEncodingParameters"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente les paramètres de codage TTF."
type: docs
weight: 93
url: /fr/java/com.aspose.font/ttfencodingparameters/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.IEncodingParameters](../../com.aspose.font/iencodingparameters)
```
public class TtfEncodingParameters implements IEncodingParameters
```

Représente les paramètres d'encodage TTF. Doit être utilisé pour demander un encodage spécifique à partir de la police TTF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TtfEncodingParameters(int platformId, int platformSpecificId)](#TtfEncodingParameters-int-int-) | Initialise une nouvelle instance de la classe TtfEncodingParameters. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPlatformId()](#getPlatformId--) | Obtient la valeur PlatformId. |
| [getPlatformSpecificId()](#getPlatformSpecificId--) | Obtient la valeur PlatformSpecificId. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPlatformId(int value)](#setPlatformId-int-) | Définit la valeur PlatformId. |
| [setPlatformSpecificId(int value)](#setPlatformSpecificId-int-) | Définit la valeur PlatformSpecificId. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TtfEncodingParameters(int platformId, int platformSpecificId) {#TtfEncodingParameters-int-int-}
```
public TtfEncodingParameters(int platformId, int platformSpecificId)
```


Initialise une nouvelle instance de la classe TtfEncodingParameters. Prend Platform Id et Platform-specific encoding id comme paramètres. Ces paramètres sont utilisés pour demander une sous-table CMap spéciale à partir de la table CMap principale de la police, voir la table 'CMap', 'name' dans la spécification du fichier de police OpenType.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| platformId | int | Identifiant de plateforme. |
| platformSpecificId | int | Identifiant d'encodage spécifique à la plateforme. |

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
### getPlatformId() {#getPlatformId--}
```
public int getPlatformId()
```


Obtient la valeur PlatformId.

**Returns:**
int - valeur PlatformId.
### getPlatformSpecificId() {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```


Obtient la valeur PlatformSpecificId.

**Returns:**
int - valeur PlatformSpecificId.
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




### setPlatformId(int value) {#setPlatformId-int-}
```
public void setPlatformId(int value)
```


Définit la valeur PlatformId.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Valeur PlatformId. |

### setPlatformSpecificId(int value) {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```


Définit la valeur PlatformSpecificId.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Valeur PlatformSpecificId. |

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

