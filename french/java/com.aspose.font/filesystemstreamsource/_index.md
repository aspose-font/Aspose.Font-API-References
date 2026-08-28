---
title: "FileSystemStreamSource"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente une source de flux basée sur le système de fichiers."
type: docs
weight: 31
url: /fr/java/com.aspose.font/filesystemstreamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.StreamSource](../../com.aspose.font/streamsource)
```
public class FileSystemStreamSource extends StreamSource
```

Représente une source de flux basée sur le système de fichiers.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileSystemStreamSource(String fileName)](#FileSystemStreamSource-java.lang.String-) | Initialise un nouvel objet FileSystemStreamSource. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clone l'objet FileSystemStreamSource. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFileName()](#getFileName--) | Obtient le nom du fichier. |
| [getFontStream()](#getFontStream--) | Renvoie le flux du fichier de police. |
| [getOffset()](#getOffset--) | Obtient le décalage à l'intérieur de la source. |
| [hashCode()](#hashCode--) |  |
| [mustCloseAfterUse()](#mustCloseAfterUse--) | Les classes dérivées peuvent empêcher la fermeture du flux. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFileName(String value)](#setFileName-java.lang.String-) | Définit le nom du fichier. |
| [setOffset(long value)](#setOffset-long-) | Définit le décalage à l'intérieur de la source. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSystemStreamSource(String fileName) {#FileSystemStreamSource-java.lang.String-}
```
public FileSystemStreamSource(String fileName)
```


Initialise un nouvel objet FileSystemStreamSource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone l'objet FileSystemStreamSource.

**Returns:**
java.lang.Object - Copie de l'objet FileSystemStreamSource.
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
### getFileName() {#getFileName--}
```
public String getFileName()
```


Obtient le nom du fichier.

**Returns:**
java.lang.String - Nom de fichier.
### getFontStream() {#getFontStream--}
```
public InputStream getFontStream()
```


Renvoie le flux du fichier de police. N'oubliez pas de fermer le flux après utilisation.

**Returns:**
java.io.InputStream - Flux du fichier de police.
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




### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Définit le nom du fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nom du fichier. |

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

