---
title: "TtcFontFileDefinition"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la définition de fichier pour la police TTC."
type: docs
weight: 79
url: /fr/java/com.aspose.font/ttcfontfiledefinition/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.FontFileDefinition](../../com.aspose.font/fontfiledefinition)
```
public class TtcFontFileDefinition extends FontFileDefinition
```

Représente la définition de fichier pour la police TTC.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TtcFontFileDefinition(int fontIndex, String fileExtension, StreamSource streamSource, long offset)](#TtcFontFileDefinition-int-java.lang.String-com.aspose.font.StreamSource-long-) | Crée une définition de fichier en utilisant uniquement le contenu du fichier. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFileExtension()](#getFileExtension--) | Obtient l'extension du fichier. |
| [getFileName()](#getFileName--) | Obtient le nom du fichier. |
| [getFontIndex()](#getFontIndex--) | Obtient l'index de la police dans la police TTC. |
| [getOffset()](#getOffset--) | Obtient le décalage dans le flux. |
| [getStreamSource()](#getStreamSource--) | Obtient la source du flux. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TtcFontFileDefinition(int fontIndex, String fileExtension, StreamSource streamSource, long offset) {#TtcFontFileDefinition-int-java.lang.String-com.aspose.font.StreamSource-long-}
```
public TtcFontFileDefinition(int fontIndex, String fileExtension, StreamSource streamSource, long offset)
```


Crée une définition de fichier en utilisant uniquement le contenu du fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontIndex | int | Index de la police dans la collection de polices TTC. |
| fileExtension | java.lang.String | Extension de la collection de fichiers de polices. |
| streamSource | [StreamSource](../../com.aspose.font/streamsource) | Source de la collection de fichiers de polices. |
| décalage | long | Décalage vers les données de police dans la collection de fichiers de polices, voir l'en-tête TTC, la table des décalages dans la spécification du fichier de police OpenType. |

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
### getFileExtension() {#getFileExtension--}
```
public String getFileExtension()
```


Obtient l'extension du fichier.

**Returns:**
java.lang.String - Extension de fichier.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Obtient le nom du fichier.

**Returns:**
java.lang.String - Nom de fichier.
### getFontIndex() {#getFontIndex--}
```
public long getFontIndex()
```


Obtient l'index de la police dans la police TTC.

**Returns:**
long - Index de police dans le TTC Font.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtient le décalage dans le flux.

**Returns:**
long - Décalage dans le flux.
### getStreamSource() {#getStreamSource--}
```
public StreamSource getStreamSource()
```


Obtient la source du flux.

**Returns:**
[StreamSource](../../com.aspose.font/streamsource) - The stream source.
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

