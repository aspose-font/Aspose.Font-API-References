---
title: "Version16Dot16"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente le type de données Version16Dot16"
type: docs
weight: 118
url: /fr/java/com.aspose.font/version16dot16/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Version16Dot16 implements Cloneable
```

Représente le type de données Version16Dot16
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Version16Dot16()](#Version16Dot16--) | Constructeur |
| [Version16Dot16(int majorNumber, int minorNumber)](#Version16Dot16-int-int-) | Constructeur |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) | Créer une copie de l'objet Version16Dot16. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMajorNumber()](#getMajorNumber--) | Obtient le numéro de version majeur. |
| [getMinorNumber()](#getMinorNumber--) | Obtient le numéro de version mineur. |
| [getRawBytes()](#getRawBytes--) | Obtient tous les bits bruts du numéro de version Version16Dot16 sous forme de tableau d'octets de taille 4 octets. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMajorNumber(int value)](#setMajorNumber-int-) | Définit le numéro de version majeur. |
| [setMinorNumber(int value)](#setMinorNumber-int-) | Définit le numéro de version mineur. |
| [toString()](#toString--) | Renvoie la valeur de version sous forme de chaîne formatée. Par exemple "0.5", "1.1", "3.0", etc. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Version16Dot16() {#Version16Dot16--}
```
public Version16Dot16()
```


Constructeur

### Version16Dot16(int majorNumber, int minorNumber) {#Version16Dot16-int-int-}
```
public Version16Dot16(int majorNumber, int minorNumber)
```


Constructeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| majorNumber | int | Numéro de version majeur |
| minorNumber | int | Numéro de version mineur |

### clone() {#clone--}
```
public Object clone()
```


Créer une copie de l'objet Version16Dot16.

**Returns:**
java.lang.Object - Objet de type Version16Dot16
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
### getMajorNumber() {#getMajorNumber--}
```
public int getMajorNumber()
```


Obtient le numéro de version majeur. La valeur n'a de sens que dans une notation hexadécimale, par exemple la version 0,5 pour 'maxp' dans les fichiers de police réels est de 4 octets : \{0, 0, 80, 0\}, qui a la représentation hexadécimale 0x00005000. Après avoir lu cette version depuis le fichier de police, les numéros majeur et mineur pour l'objet Version16Dot16 seront respectivement 0 et 20480. Et ces valeurs sous forme hexadécimale sont 0x0000 et 0x5000.

**Returns:**
int - Numéro de version majeur.
### getMinorNumber() {#getMinorNumber--}
```
public int getMinorNumber()
```


Obtient le numéro de version mineur. La valeur n'a de sens que dans une notation hexadécimale, par exemple la version 0,5 pour 'maxp' dans les fichiers de police réels est de 4 octets : \{0, 0, 80, 0\}, qui a la représentation hexadécimale 0x00005000. Après avoir lire cette version depuis le fichier de police, les numéros majeur et mineur pour l'objet Version16Dot16 seront respectivement 0 et 20480. Et ces valeurs sous forme hexadécimale sont 0x0000 et 0x5000.

**Returns:**
int - Numéro de version mineur.
### getRawBytes() {#getRawBytes--}
```
public byte[] getRawBytes()
```


Obtient tous les bits bruts du numéro de version Version16Dot16 sous forme de tableau d'octets de taille 4 octets.

**Returns:**
byte[] - Tous les bits bruts du numéro de version Version16Dot16 sous forme de tableau d'octets de taille 4 octets.
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




### setMajorNumber(int value) {#setMajorNumber-int-}
```
public void setMajorNumber(int value)
```


Définit le numéro de version majeur. La valeur n'a de sens que dans une notation hexadécimale, par exemple la version 0,5 pour 'maxp' dans les fichiers de police réels est de 4 octets : \{0, 0, 80, 0\}, qui a la représentation hexadécimale 0x00005000. Après avoir lu cette version depuis le fichier de police, les numéros majeur et mineur pour l'objet Version16Dot16 seront respectivement 0 et 20480. Et ces valeurs sous forme hexadécimale sont 0x0000 et 0x5000.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Numéro de version majeur. |

### setMinorNumber(int value) {#setMinorNumber-int-}
```
public void setMinorNumber(int value)
```


Définit le numéro de version mineur. La valeur n'a de sens que dans une notation hexadécimale, par exemple la version 0,5 pour 'maxp' dans les fichiers de police réels est de 4 octets : \{0, 0, 80, 0\}, qui a la représentation hexadécimale 0x00005000. Après avoir lu cette version depuis le fichier de police, les numéros majeur et mineur pour l'objet Version16Dot16 seront respectivement 0 et 20480. Et ces valeurs sous forme hexadécimale sont 0x0000 et 0x5000.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Numéro de version mineur. |

### toString() {#toString--}
```
public String toString()
```


Renvoie la valeur de version sous forme de chaîne formatée. Par exemple "0.5", "1.1", "3.0", etc.

**Returns:**
java.lang.String - Objet de type String
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

