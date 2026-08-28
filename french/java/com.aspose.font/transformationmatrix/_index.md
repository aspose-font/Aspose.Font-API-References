---
title: "TransformationMatrix"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente une matrice 3x3  A   B   0   C   D   0   TX  TY  1 ."
type: docs
weight: 78
url: /fr/java/com.aspose.font/transformationmatrix/
---
**Inheritance:**
java.lang.Object
```
public class TransformationMatrix
```

Représente une matrice 3x3 | A B 0 | | C D 0 | | TX TY 1 |. Transforme les coordonnées de la manière suivante : x1 = A\*x + C\*y + TX y1 = B\*x + D\*y + TY.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TransformationMatrix()](#TransformationMatrix--) | Crée une matrice standard 1 à 1 : [ A B C D TX TY ] = [ 1, 0, 0, 1, 0, 0] |
| [TransformationMatrix(double[] matrixArray)](#TransformationMatrix-double---) | Accepte une matrice de transformation avec la représentation de tableau suivante : [ A B C D TX TY ] |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Fournit l'accès au tableau sous-jacent. |
| [getA()](#getA--) | Obtient la valeur A de la matrice de transformation. |
| [getB()](#getB--) | Obtient la valeur B de la matrice de transformation. |
| [getC()](#getC--) | Obtient la valeur C de la matrice de transformation. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | Obtient la valeur D de la matrice de transformation. |
| [getTX()](#getTX--) | Obtient la valeur TX de la matrice de transformation. |
| [getTY()](#getTY--) | Obtient la valeur TY de la matrice de transformation. |
| [hashCode()](#hashCode--) |  |
| [multiply(TransformationMatrix matrix)](#multiply-com.aspose.font.TransformationMatrix-) | Multiplie avec une autre matrice de transformation. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(double x, double y, double[] x1, double[] y1)](#scale-double-double-double---double---) | Mise à l'échelle de x et y avec la matrice de transformation : x1 = A\*x + C\*y; y1 = B\*x + D\*y. |
| [setA(double value)](#setA-double-) | Définit la valeur A de la matrice de transformation. |
| [setB(double value)](#setB-double-) | Définit la valeur B de la matrice de transformation. |
| [setC(double value)](#setC-double-) | Définit la valeur C de la matrice de transformation. |
| [setD(double value)](#setD-double-) | Définit la valeur D de la matrice de transformation. |
| [setTX(double value)](#setTX-double-) | Définit la valeur TX de la matrice de transformation. |
| [setTY(double value)](#setTY-double-) | Définit la valeur TY de la matrice de transformation. |
| [toArray()](#toArray--) | Alloue un nouveau tableau, copie la matrice de transformation et le renvoie. |
| [toString()](#toString--) |  |
| [transform(double x, double y, double[] x1, double[] y1)](#transform-double-double-double---double---) | Transforme x et y avec la matrice de transformation : x1 = A\*x + C\*y + TX; y1 = B\*x + D\*y + TY. |
| [unScale(double x1, double y1, double[] x, double[] y)](#unScale-double-double-double---double---) | Ramène x1 et y1 à l'échelle et renvoie x et y avant la matrice de transformation. |
| [unTransform(double x1, double y1, double[] x, double[] y)](#unTransform-double-double-double---double---) | Transforme en sens inverse x1 et y1 et renvoie x et y avant la matrice de transformation. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformationMatrix() {#TransformationMatrix--}
```
public TransformationMatrix()
```


Crée une matrice standard 1 à 1 : [ A B C D TX TY ] = [ 1, 0, 0, 1, 0, 0]

### TransformationMatrix(double[] matrixArray) {#TransformationMatrix-double---}
```
public TransformationMatrix(double[] matrixArray)
```


Accepte une matrice de transformation avec la représentation de tableau suivante : [ A B C D TX TY ]

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrixArray | double[] | Tableau contenant les valeurs de la matrice de transformation, doit contenir 6 éléments. |

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
public double get(int index)
```


Fournit l'accès au tableau sous-jacent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice dans le tableau de la matrice de transformation. |

**Returns:**
double - L'élément du tableau sous-jacent par indice.
### getA() {#getA--}
```
public double getA()
```


Obtient la valeur A de la matrice de transformation.

**Returns:**
double - Une valeur de la matrice de transformation.
### getB() {#getB--}
```
public double getB()
```


Obtient la valeur B de la matrice de transformation.

**Returns:**
double - Valeur B de la matrice de transformation.
### getC() {#getC--}
```
public double getC()
```


Obtient la valeur C de la matrice de transformation.

**Returns:**
double - Valeur C de la matrice de transformation.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public double getD()
```


Obtient la valeur D de la matrice de transformation.

**Returns:**
double - Valeur D de la matrice de transformation.
### getTX() {#getTX--}
```
public double getTX()
```


Obtient la valeur TX de la matrice de transformation.

**Returns:**
double - Valeur TX de la matrice de transformation.
### getTY() {#getTY--}
```
public double getTY()
```


Obtient la valeur TY de la matrice de transformation.

**Returns:**
double - Valeur TY de la matrice de transformation.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiply(TransformationMatrix matrix) {#multiply-com.aspose.font.TransformationMatrix-}
```
public TransformationMatrix multiply(TransformationMatrix matrix)
```


Multiplie avec une autre matrice de transformation. Ne modifie pas la matrice de transformation originale, renvoie un nouvel objet TransformationMatrix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [TransformationMatrix](../../com.aspose.font/transformationmatrix) | Matrice de transformation avec laquelle multiplier. |

**Returns:**
[TransformationMatrix](../../com.aspose.font/transformationmatrix) - New TransformationMatrix object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### scale(double x, double y, double[] x1, double[] y1) {#scale-double-double-double---double---}
```
public void scale(double x, double y, double[] x1, double[] y1)
```


Mise à l'échelle de x et y avec la matrice de transformation : x1 = A\*x + C\*y; y1 = B\*x + D\*y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | Coordonnée x originale |
| y | double | Coordonnée y originale. |
| x1 | double[] | Coordonnée x mise à l'échelle. |
| y1 | double[] | Coordonnée y mise à l'échelle. |

### setA(double value) {#setA-double-}
```
public void setA(double value)
```


Définit la valeur A de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Une valeur de la matrice de transformation. |

### setB(double value) {#setB-double-}
```
public void setB(double value)
```


Définit la valeur B de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur B de la matrice de transformation. |

### setC(double value) {#setC-double-}
```
public void setC(double value)
```


Définit la valeur C de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur C de la matrice de transformation. |

### setD(double value) {#setD-double-}
```
public void setD(double value)
```


Définit la valeur D de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur D de la matrice de transformation. |

### setTX(double value) {#setTX-double-}
```
public void setTX(double value)
```


Définit la valeur TX de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur de la matrice de transformation TX. |

### setTY(double value) {#setTY-double-}
```
public void setTY(double value)
```


Définit la valeur TY de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Valeur de la matrice de transformation TY. |

### toArray() {#toArray--}
```
public double[] toArray()
```


Alloue un nouveau tableau, copie la matrice de transformation et le renvoie.

**Returns:**
double[] - TransformationMatrix sous forme de tableau.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(double x, double y, double[] x1, double[] y1) {#transform-double-double-double---double---}
```
public void transform(double x, double y, double[] x1, double[] y1)
```


Transforme x et y avec la matrice de transformation : x1 = A\*x + C\*y + TX; y1 = B\*x + D\*y + TY.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | Coordonnée x originale. |
| y | double | Coordonnée y originale. |
| x1 | double[] | Coordonnée x transformée. |
| y1 | double[] | Coordonnée y transformée. |

### unScale(double x1, double y1, double[] x, double[] y) {#unScale-double-double-double---double---}
```
public void unScale(double x1, double y1, double[] x, double[] y)
```


Ramène x1 et y1 à l'échelle et renvoie x et y avant la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | double | Coordonnée x1 |
| y1 | double | Coordonnée y1 |
| x | double[] | Coordonnée x remise à l'échelle. |
| y | double[] | Coordonnée y remise à l'échelle. |

### unTransform(double x1, double y1, double[] x, double[] y) {#unTransform-double-double-double---double---}
```
public void unTransform(double x1, double y1, double[] x, double[] y)
```


Transforme en sens inverse x1 et y1 et renvoie x et y avant la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | double | Coordonnée x1. |
| y1 | double | Coordonnée y1. |
| x | double[] | Coordonnée x retransformée. |
| y | double[] | Coordonnée y retransformée. |

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

