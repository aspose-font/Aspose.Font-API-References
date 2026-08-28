---
title: "StreamSource"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Définit une méthode pour obtenir un flux de fichier lorsqu'il est nécessaire."
type: docs
weight: 74
url: /fr/java/com.aspose.font/streamsource/
---
**Inheritance:**
java.lang.Object
```
public abstract class StreamSource
```

Définit une méthode pour obtenir un flux de fichier lorsqu'il est nécessaire.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StreamSource()](#StreamSource--) | Initialise l'instance du flux source. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clone l'objet du flux source. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFontStream()](#getFontStream--) | Renvoie le flux Font. |
| [getOffset()](#getOffset--) | Obtient le décalage à l'intérieur de la source. |
| [hashCode()](#hashCode--) |  |
| [mustCloseAfterUse()](#mustCloseAfterUse--) | Les classes dérivées peuvent empêcher la fermeture du flux. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Définit le décalage à l'intérieur de la source. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Initialise l'instance du flux source.

### deepClone() {#deepClone--}
```
public abstract Object deepClone()
```


Clone l'objet du flux source.

**Returns:**
java.lang.Object - Copie de l'objet du flux source.
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
### getFontStream() {#getFontStream--}
```
public abstract InputStream getFontStream()
```


Renvoie le flux Font.

**Returns:**
java.io.InputStream - Flux Font.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtient le décalage à l'intérieur de la source.

**Returns:**
long - Décalage à l'intérieur de la source.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mustCloseAfterUse() {#mustCloseAfterUse--}
```
public boolean mustCloseAfterUse()
```


Les classes dérivées peuvent empêcher la fermeture du flux. Renvoie true si le flux source souhaite que le flux soit fermé après utilisation. Sinon renvoie false.

**Returns:**
boolean - True si le flux source souhaite que le flux soit fermé après utilisation, sinon false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Définit le décalage à l'intérieur de la source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Décalage à l'intérieur de la source. |

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

