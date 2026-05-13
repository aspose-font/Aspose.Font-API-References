---
title: "GlyphId"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente les identifiants de glyphes disponibles dans la police."
type: docs
weight: 50
url: /fr/java/com.aspose.font/glyphid/
---
**Inheritance:**
java.lang.Object
```
public abstract class GlyphId
```

Représente les identifiants de glyphes disponibles dans la police. Un identifiant de glyphe est un nombre unique pour un glyphe, dépendant du type de police. Par exemple : l'identifiant de Type1 est un nom de glyphe, instance de la classe ( GlyphStringId ). L'identifiant de TTF est un index entier, instance de la classe ( GlyphUInt32Id ).
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie vrai si deux identifiants de glyphe ne sont pas égaux. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Renvoie le code de hachage de l'objet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(GlyphId obj1, Object obj2)](#op-Equality-com.aspose.font.GlyphId-java.lang.Object-) | Renvoie vrai si deux identifiants de glyphe sont égaux. |
| [op_Inequality(GlyphId obj1, Object obj2)](#op-Inequality-com.aspose.font.GlyphId-java.lang.Object-) | Renvoie vrai si deux identifiants de glyphe ne sont pas égaux. |
| [toGlyphStringId()](#toGlyphStringId--) | Conversion virtuelle en GlyphStringId. |
| [toGlyphUInt32Id()](#toGlyphUInt32Id--) | Conversion virtuelle en GlyphUInt32Id. |
| [toString()](#toString--) | Renvoie la représentation sous forme de chaîne de l'identifiant du glyphe. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie vrai si deux identifiants de glyphe ne sont pas égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Identifiant du glyphe à comparer. |

**Returns:**
booléen - Résultat de la comparaison.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public abstract int hashCode()
```


Renvoie le code de hachage de l'objet.

**Returns:**
int - Code de hachage de l'objet.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(GlyphId obj1, Object obj2) {#op-Equality-com.aspose.font.GlyphId-java.lang.Object-}
```
public static boolean op_Equality(GlyphId obj1, Object obj2)
```


Renvoie vrai si deux identifiants de glyphe sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [GlyphId](../../com.aspose.font/glyphid) | Premier identifiant de glyphe à comparer. |
| obj2 | java.lang.Object | Deuxième identifiant de glyphe à comparer. |

**Returns:**
booléen - Résultat de la comparaison.
### op_Inequality(GlyphId obj1, Object obj2) {#op-Inequality-com.aspose.font.GlyphId-java.lang.Object-}
```
public static boolean op_Inequality(GlyphId obj1, Object obj2)
```


Renvoie vrai si deux identifiants de glyphe ne sont pas égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [GlyphId](../../com.aspose.font/glyphid) | Premier identifiant de glyphe à comparer. |
| obj2 | java.lang.Object | Deuxième identifiant de glyphe à comparer. |

**Returns:**
booléen - Résultat de la comparaison.
### toGlyphStringId() {#toGlyphStringId--}
```
public GlyphStringId toGlyphStringId()
```


Conversion virtuelle en GlyphStringId. GlyphStringId surcharge pour retourner une instance.

**Returns:**
[GlyphStringId](../../com.aspose.font/glyphstringid) - null
### toGlyphUInt32Id() {#toGlyphUInt32Id--}
```
public GlyphUInt32Id toGlyphUInt32Id()
```


Conversion virtuelle en GlyphUInt32Id. GlyphUInt32Id surcharge pour retourner l'instance.

**Returns:**
[GlyphUInt32Id](../../com.aspose.font/glyphuint32id) - null
### toString() {#toString--}
```
public abstract String toString()
```


Renvoie la représentation sous forme de chaîne de l'identifiant du glyphe.

**Returns:**
java.lang.String - identifiant du glyphe
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

