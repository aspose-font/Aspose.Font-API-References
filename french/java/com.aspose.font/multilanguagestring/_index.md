---
title: "MultiLanguageString"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente une chaîne multilingue."
type: docs
weight: 66
url: /fr/java/com.aspose.font/multilanguagestring/
---
**Inheritance:**
java.lang.Object
```
public class MultiLanguageString
```

Représente une chaîne multilingue.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MultiLanguageString()](#MultiLanguageString--) | Crée une chaîne multilingue vide. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addLanguageString(String str, int languageId)](#addLanguageString-java.lang.String-int-) | Ajoute une chaîne d'une langue spécifique |
| [containsString(String str)](#containsString-java.lang.String-) | Renvoie vrai si la chaîne est présente dans toutes les chaînes de langues. |
| [equals(Object objToCompare)](#equals-java.lang.Object-) | Renvoie vrai si les objets sont considérés égaux. |
| [getAllLanguageIds()](#getAllLanguageIds--) | Obtient les identifiants de langue pour toutes les chaînes ou un tableau vide si aucune chaîne n'est présente. |
| [getAllStrings()](#getAllStrings--) | Renvoie toutes les chaînes de toutes les langues. |
| [getClass()](#getClass--) |  |
| [getEnglishString()](#getEnglishString--) | Renvoie la chaîne anglaise si trouvée. |
| [getStringForLanguageId(int languageId)](#getStringForLanguageId-int-) | Renvoie la chaîne liée à l'identifiant de langue fourni, si trouvée. |
| [hashCode()](#hashCode--) | Implémentation de GetHashCode. |
| [isEmpty()](#isEmpty--) | Vrai, si MultiLanguageString n'a pas de chaînes de langues. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(MultiLanguageString obj1, String obj2)](#op-Equality-com.aspose.font.MultiLanguageString-java.lang.String-) | Implémentation de l'opérateur d'égalité. |
| [op_Equality(String obj1, MultiLanguageString obj2)](#op-Equality-java.lang.String-com.aspose.font.MultiLanguageString-) | Implémentation de l'opérateur d'égalité. |
| [op_Inequality(MultiLanguageString obj1, String obj2)](#op-Inequality-com.aspose.font.MultiLanguageString-java.lang.String-) | Implémentation de l'opérateur d'inégalité. |
| [op_Inequality(String obj1, MultiLanguageString obj2)](#op-Inequality-java.lang.String-com.aspose.font.MultiLanguageString-) | Implémentation de l'opérateur d'inégalité. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiLanguageString() {#MultiLanguageString--}
```
public MultiLanguageString()
```


Crée une chaîne multilingue vide.

### addLanguageString(String str, int languageId) {#addLanguageString-java.lang.String-int-}
```
public void addLanguageString(String str, int languageId)
```


Ajoute une chaîne d'une langue spécifique

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| str | java.lang.String | Chaîne à ajouter |
| languageId | int | Identifiant de langue |

### containsString(String str) {#containsString-java.lang.String-}
```
public boolean containsString(String str)
```


Renvoie vrai si la chaîne est présente dans toutes les chaînes de langues.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| str | java.lang.String | Chaîne à vérifier. |

**Returns:**
booléen - Vrai si la chaîne est présente dans toutes les chaînes de langues.
### equals(Object objToCompare) {#equals-java.lang.Object-}
```
public boolean equals(Object objToCompare)
```


Renvoie vrai si les objets sont considérés égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| objToCompare | java.lang.Object | objet à comparer avec |

**Returns:**
boolean - résultat de comparaison
### getAllLanguageIds() {#getAllLanguageIds--}
```
public int[] getAllLanguageIds()
```


Obtient les identifiants de langue pour toutes les chaînes ou un tableau vide si aucune chaîne n'est présente.

**Returns:**
int[] - Tableau avec les identifiants de langue ou tableau vide si aucune chaîne n'est présente.
### getAllStrings() {#getAllStrings--}
```
public String[] getAllStrings()
```


Renvoie toutes les chaînes de toutes les langues.

**Returns:**
java.lang.String[] - Tableau de toutes les chaînes de toutes les langues.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnglishString() {#getEnglishString--}
```
public String getEnglishString()
```


Renvoie la chaîne anglaise si trouvée. Sinon renvoie la première chaîne non-anglaise.

**Returns:**
java.lang.String - Chaîne anglaise si trouvée, sinon première chaîne non-anglaise.
### getStringForLanguageId(int languageId) {#getStringForLanguageId-int-}
```
public String getStringForLanguageId(int languageId)
```


Renvoie la chaîne liée à l'identifiant de langue fourni, si trouvée. Chaîne vide sinon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| languageId | int | Identifiant de langue. |

**Returns:**
java.lang.String - Chaîne liée à l'identifiant de langue fourni, si trouvée. Chaîne vide sinon.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Implémentation de GetHashCode.

**Returns:**
int - code de hachage de l'objet
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Vrai, si MultiLanguageString n'a pas de chaînes de langues.

**Returns:**
boolean - Vrai, si MultiLanguageString ne possède pas de chaînes de langues.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(MultiLanguageString obj1, String obj2) {#op-Equality-com.aspose.font.MultiLanguageString-java.lang.String-}
```
public static boolean op_Equality(MultiLanguageString obj1, String obj2)
```


Implémentation de l'opérateur d'égalité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [MultiLanguageString](../../com.aspose.font/multilanguagestring) | premier objet à comparer |
| obj2 | java.lang.String | deuxième objet à comparer |

**Returns:**
boolean - résultat de comparaison
### op_Equality(String obj1, MultiLanguageString obj2) {#op-Equality-java.lang.String-com.aspose.font.MultiLanguageString-}
```
public static boolean op_Equality(String obj1, MultiLanguageString obj2)
```


Implémentation de l'opérateur d'égalité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | java.lang.String | chaîne à comparer |
| obj2 | [MultiLanguageString](../../com.aspose.font/multilanguagestring) | chaîne multilingue à comparer |

**Returns:**
boolean - résultat de comparaison
### op_Inequality(MultiLanguageString obj1, String obj2) {#op-Inequality-com.aspose.font.MultiLanguageString-java.lang.String-}
```
public static boolean op_Inequality(MultiLanguageString obj1, String obj2)
```


Implémentation de l'opérateur d'inégalité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [MultiLanguageString](../../com.aspose.font/multilanguagestring) | chaîne à comparer |
| obj2 | java.lang.String | chaîne multilingue à comparer |

**Returns:**
boolean - résultat de comparaison
### op_Inequality(String obj1, MultiLanguageString obj2) {#op-Inequality-java.lang.String-com.aspose.font.MultiLanguageString-}
```
public static boolean op_Inequality(String obj1, MultiLanguageString obj2)
```


Implémentation de l'opérateur d'inégalité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | java.lang.String | chaîne à comparer |
| obj2 | [MultiLanguageString](../../com.aspose.font/multilanguagestring) | chaîne multilingue à comparer |

**Returns:**
boolean - résultat de comparaison
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

