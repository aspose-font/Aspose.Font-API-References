---
title: "ClosePath"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente l'opération ClosePath."
type: docs
weight: 24
url: /fr/java/com.aspose.font/closepath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.IPathSegment](../../com.aspose.font/ipathsegment)
```
public class ClosePath implements IPathSegment
```

Représente l'opération ClosePath.
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) | Crée un nouvel objet qui est une copie de l'instance actuelle. |
| [copy()](#copy--) | Crée une copie de l'objet segment. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getX()](#getX--) | Obtient la coordonnée x. |
| [getY()](#getY--) | Obtient la coordonnée y. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [shift(double dx, double dy)](#shift-double-double-) | Effectue un décalage selon les coordonnées x et y. |
| [toString()](#toString--) |  |
| [transform(TransformationMatrix matrix)](#transform-com.aspose.font.TransformationMatrix-) | Transforme les coordonnées avec la matrice de transformation. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clone() {#clone--}
```
public Object clone()
```


Crée un nouvel objet qui est une copie de l'instance actuelle.

**Returns:**
java.lang.Object - Un nouvel objet qui est une copie de cette instance.
### copy() {#copy--}
```
public IPathSegment copy()
```


Crée une copie de l'objet segment.

**Returns:**
[IPathSegment](../../com.aspose.font/ipathsegment) - Copy of the segment object.
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
### getX() {#getX--}
```
public double getX()
```


Obtient la coordonnée x.

**Returns:**
double - Coordonnée x.
### getY() {#getY--}
```
public double getY()
```


Obtient la coordonnée y.

**Returns:**
double - Coordonnée y.
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




### shift(double dx, double dy) {#shift-double-double-}
```
public void shift(double dx, double dy)
```


Effectue un décalage selon les coordonnées x et y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | double | Valeur dx. |
| dy | double | Valeur dy. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(TransformationMatrix matrix) {#transform-com.aspose.font.TransformationMatrix-}
```
public void transform(TransformationMatrix matrix)
```


Transforme les coordonnées avec la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [TransformationMatrix](../../com.aspose.font/transformationmatrix) | Matrice de transformation. |

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

