---
title: "PlatformId"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente l'énumération PlatformId."
type: docs
weight: 141
url: /fr/java/com.aspose.font/platformid/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PlatformId extends Enum<PlatformId>
```

Représente l'énumération PlatformId.
## Champs

| Champ | Description |
| --- | --- |
| [ISO](#ISO) | Valeur2 spécification Apple : (réservé ; ne pas utiliser) spécification MS : encodage ISO. |
| [Macintosh](#Macintosh) | Valeur 1 code du gestionnaire de scripts Macintosh. |
| [Microsoft](#Microsoft) | Valeur 3 encodage Microsoft. |
| [Unicode](#Unicode) | Valeur 0 Unicode |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ISO {#ISO}
```
public static final PlatformId ISO
```


Valeur2 spécification Apple : (réservé ; ne pas utiliser) spécification MS : encodage ISO. Notez que l’ID de plateforme 2 (ISO) a été déprécié depuis la spécification OpenType v1.3. Il était destiné à représenter ISO/IEC 10646, par opposition à Unicode ; les deux normes ont des attributions de codes de caractères identiques.

### Macintosh {#Macintosh}
```
public static final PlatformId Macintosh
```


Valeur 1 code du gestionnaire de scripts Macintosh.

### Microsoft {#Microsoft}
```
public static final PlatformId Microsoft
```


Valeur 3 encodage Microsoft.

### Unicode {#Unicode}
```
public static final PlatformId Unicode
```


Valeur 0 Unicode

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PlatformId valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[PlatformId](../../com.aspose.font/platformid)
### values() {#values--}
```
public static PlatformId[] values()
```




**Returns:**
com.aspose.font.PlatformId[]
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

