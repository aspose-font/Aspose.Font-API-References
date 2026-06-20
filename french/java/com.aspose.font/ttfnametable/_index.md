---
title: "TtfNameTable"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table des noms du fichier de police TTF."
type: docs
weight: 105
url: /fr/java/com.aspose.font/ttfnametable/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfNameTable extends TtfTableBase
```

Représente la table "name" du fichier de police TTF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [addMultiLanguageNames(MultiLanguageString mlNames, PlatformId platformId, int platformSpecificId, NameId nameId)](#addMultiLanguageNames-com.aspose.font.MultiLanguageString-com.aspose.font.PlatformId-int-com.aspose.font.NameId-) | Extrait toutes les chaînes multilingues de l'objet  mlNames  passé et crée la structure NameRecord correspondante pour chaque chaîne extraite en utilisant les paramètres passés  platformId ,  platformSpecificId  et  nameId . |
| [addName(NameId nameId, PlatformId platformId, int platformSpecificId, int languageId, String name)](#addName-com.aspose.font.NameId-com.aspose.font.PlatformId-int-int-java.lang.String-) | Ajoute une entrée dans la table. |
| [deleteRecords(PlatformId platformId, int platformSpecificId)](#deleteRecords-com.aspose.font.PlatformId-int-) | Supprime tous les enregistrements liés à la plateforme spécifiée |
| [deleteRecords(PlatformId platformId, int platformSpecificId, NameId nameId)](#deleteRecords-com.aspose.font.PlatformId-int-com.aspose.font.NameId-) | Supprime tous les enregistrements liés aux paramètres passés |
| [deleteRecords(PlatformId platformId, int platformSpecificId, NameId nameId, int languageId)](#deleteRecords-com.aspose.font.PlatformId-int-com.aspose.font.NameId-int-) | Supprime le(s) enregistrement(s) lié(s) aux paramètres spécifiés |
| [deleteRecordsByNameId(NameId nameId)](#deleteRecordsByNameId-com.aspose.font.NameId-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllNameRecords()](#getAllNameRecords--) | Renvoie toutes les structures  NameRecord  de la table. |
| [getClass()](#getClass--) |  |
| [getMultiLanguageNameById(NameId nameId)](#getMultiLanguageNameById-com.aspose.font.NameId-) | renvoie un nom par nameId |
| [getMultiLanguageNameById(NameId nameId, PlatformId platformId)](#getMultiLanguageNameById-com.aspose.font.NameId-com.aspose.font.PlatformId-) | Renvoie un nom par nameId en utilisant l'identifiant de plateforme passé. |
| [getMultiLanguageNameById(NameId nameId, PlatformId platformId, int platformSpecificId)](#getMultiLanguageNameById-com.aspose.font.NameId-com.aspose.font.PlatformId-int-) | Renvoie un nom sous forme d'objet de type  MultiLanguageString . |
| [getNameById(NameId nameId)](#getNameById-com.aspose.font.NameId-) | Renvoie un nom par nameId s'il est trouvé, null sinon. |
| [getNameRecordsByNameId(NameId nameId)](#getNameRecordsByNameId-com.aspose.font.NameId-) | Renvoie toutes les structures  NameRecord  dont le champ NameId est égal à la valeur  nameId  passée. |
| [getOffset()](#getOffset--) | Obtient le décalage depuis le début du sfnt. |
| [getTag()](#getTag--) | Obtient le tag de la table. |
| [getTtfTables()](#getTtfTables--) | Référence au référentiel de tables TTF. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [updateName(PlatformId platformId, int platformSpecificId, NameId nameId, int languageId, String newName)](#updateName-com.aspose.font.PlatformId-int-com.aspose.font.NameId-int-java.lang.String-) | Met à jour le nom dans le(s) enregistrement(s) liés à la plateforme spécifiée (combinaison de platformId et platformSpecificId), à la catégorie (nameId) et à la langue (languageId). |
| [updateNamesByNameId(NameId nameId, String newName)](#updateNamesByNameId-com.aspose.font.NameId-java.lang.String-) | Sélectionne tous les enregistrements liés à la catégorie de chaîne logique, spécifiée par le paramètre nameId, et met à jour le champ nom (données de chaîne) dans ces enregistrements. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addMultiLanguageNames(MultiLanguageString mlNames, PlatformId platformId, int platformSpecificId, NameId nameId) {#addMultiLanguageNames-com.aspose.font.MultiLanguageString-com.aspose.font.PlatformId-int-com.aspose.font.NameId-}
```
public void addMultiLanguageNames(MultiLanguageString mlNames, PlatformId platformId, int platformSpecificId, NameId nameId)
```


Extrait toutes les chaînes multilingues de l'objet  mlNames  passé et crée la structure NameRecord correspondante pour chaque chaîne extraite en utilisant les paramètres passés  platformId ,  platformSpecificId  et  nameId . La valeur du champ languageID est extraite de l'objet  mlNames . Un nouvel enregistrement fraîchement créé est ajouté à la table. Si un enregistrement qui coïncide avec le nouvellement créé par les champs platformID, platformSpecificID, nameID et, langugeId sera trouvé, alors le nouvel enregistrement ne sera pas ajouté et seules les données de chaîne seront mises à jour pour l'enregistrement existant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mlNames | [MultiLanguageString](../../com.aspose.font/multilanguagestring) | Chaîne multilingue |
| platformId | [PlatformId](../../com.aspose.font/platformid) | Identifiant de plateforme |
| platformSpecificId | int | Identifiant d'encodage spécifique à la plateforme |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom, catégorie de chaîne logique, spécifié par l'énumération  NameId  |

### addName(NameId nameId, PlatformId platformId, int platformSpecificId, int languageId, String name) {#addName-com.aspose.font.NameId-com.aspose.font.PlatformId-int-int-java.lang.String-}
```
public void addName(NameId nameId, PlatformId platformId, int platformSpecificId, int languageId, String name)
```


Ajoute une entrée dans la table. La catégorie de données de chaîne à ajouter est spécifiée par le paramètre  name .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom, catégorie logique de chaîne, spécifiée par l'énumération [NameId](../../com.aspose.font/nameid). |
| platformId | [PlatformId](../../com.aspose.font/platformid) | Identifiant de plateforme. |
| platformSpecificId | int | Identifiant d'encodage spécifique à la plateforme. Veuillez utiliser une valeur provenant de l'une de ces énumérations -  UnicodePlatformSpecificId ,  MacPlatformSpecificId ,  MSPlatformSpecificId . L'énumération à utiliser est définie par le contexte ( paramètre  platformId ). |
| languageId | int | Identifiant de langue. Veuillez utiliser une valeur provenant des énumérations  MSLanguageId  ou  MacLanguageId  selon le contexte, défini par le paramètre  platformId . |
| nom | java.lang.String | Données de chaîne réelles. |

### deleteRecords(PlatformId platformId, int platformSpecificId) {#deleteRecords-com.aspose.font.PlatformId-int-}
```
public void deleteRecords(PlatformId platformId, int platformSpecificId)
```


Supprime tous les enregistrements liés à la plateforme spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| platformId | [PlatformId](../../com.aspose.font/platformid) | Identifiant de plateforme |
| platformSpecificId | int | Identifiant d'encodage spécifique à la plateforme |

### deleteRecords(PlatformId platformId, int platformSpecificId, NameId nameId) {#deleteRecords-com.aspose.font.PlatformId-int-com.aspose.font.NameId-}
```
public void deleteRecords(PlatformId platformId, int platformSpecificId, NameId nameId)
```


Supprime tous les enregistrements liés aux paramètres passés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| platformId | [PlatformId](../../com.aspose.font/platformid) | Identifiant de plateforme |
| platformSpecificId | int | Identifiant d'encodage spécifique à la plateforme |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom, catégorie de chaîne logique, spécifié par l'énumération  NameId  |

### deleteRecords(PlatformId platformId, int platformSpecificId, NameId nameId, int languageId) {#deleteRecords-com.aspose.font.PlatformId-int-com.aspose.font.NameId-int-}
```
public void deleteRecords(PlatformId platformId, int platformSpecificId, NameId nameId, int languageId)
```


Supprime le(s) enregistrement(s) lié(s) aux paramètres spécifiés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| platformId | [PlatformId](../../com.aspose.font/platformid) | Identifiant de plateforme |
| platformSpecificId | int | Identifiant d'encodage spécifique à la plateforme |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom, catégorie de chaîne logique, spécifié par l'énumération  NameId  |
| languageId | int | Identifiant de langue |

### deleteRecordsByNameId(NameId nameId) {#deleteRecordsByNameId-com.aspose.font.NameId-}
```
public void deleteRecordsByNameId(NameId nameId)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nameId | [NameId](../../com.aspose.font/nameid) |  |

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
### getAllNameRecords() {#getAllNameRecords--}
```
public NameRecord[] getAllNameRecords()
```


Renvoie toutes les structures  NameRecord  de la table.

**Returns:**
com.aspose.font.NameRecord[] - Toutes les structures  NameRecord  de la table.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMultiLanguageNameById(NameId nameId) {#getMultiLanguageNameById-com.aspose.font.NameId-}
```
public MultiLanguageString getMultiLanguageNameById(NameId nameId)
```


renvoie un nom par nameId

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom. |

**Returns:**
[MultiLanguageString](../../com.aspose.font/multilanguagestring) - name
### getMultiLanguageNameById(NameId nameId, PlatformId platformId) {#getMultiLanguageNameById-com.aspose.font.NameId-com.aspose.font.PlatformId-}
```
public MultiLanguageString getMultiLanguageNameById(NameId nameId, PlatformId platformId)
```


Renvoie un nom par nameId en utilisant l'identifiant de plateforme passé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom. |
| platformId | [PlatformId](../../com.aspose.font/platformid) | Identifiant de plateforme. |

**Returns:**
[MultiLanguageString](../../com.aspose.font/multilanguagestring) - Name.
### getMultiLanguageNameById(NameId nameId, PlatformId platformId, int platformSpecificId) {#getMultiLanguageNameById-com.aspose.font.NameId-com.aspose.font.PlatformId-int-}
```
public MultiLanguageString getMultiLanguageNameById(NameId nameId, PlatformId platformId, int platformSpecificId)
```


Renvoie un nom sous forme d'objet du type  MultiLanguageString . La méthode collecte toutes les structures NameRecord qui coïncident avec les paramètres passés nameId, platformId et platformSpecificId, puis construit l'objet résultant à partir de cette liste de structures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom. |
| platformId | [PlatformId](../../com.aspose.font/platformid) | Identifiant de plateforme. |
| platformSpecificId | int | Identifiant spécifique à la plateforme. |

**Returns:**
[MultiLanguageString](../../com.aspose.font/multilanguagestring) - Name.
### getNameById(NameId nameId) {#getNameById-com.aspose.font.NameId-}
```
public String getNameById(NameId nameId)
```


Renvoie un nom par nameId s'il est trouvé, null sinon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nameId | [NameId](../../com.aspose.font/nameid) | identifiant de nom |

**Returns:**
java.lang.String - nom
### getNameRecordsByNameId(NameId nameId) {#getNameRecordsByNameId-com.aspose.font.NameId-}
```
public NameRecord[] getNameRecordsByNameId(NameId nameId)
```


Renvoie toutes les structures  NameRecord  dont le champ NameId est égal à la valeur  nameId  passée. Si aucun enregistrement n'est trouvé, un tableau vide sera renvoyé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nameId | [NameId](../../com.aspose.font/nameid) | identifiant de nom |

**Returns:**
com.aspose.font.NameRecord[] - Tableau de structures  NameRecord 
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtient le décalage depuis le début du sfnt.

**Returns:**
long - Décalage depuis le début du sfnt.
### getTag() {#getTag--}
```
public static String getTag()
```


Obtient le tag de la table.

**Returns:**
java.lang.String - Tag de la table.
### getTtfTables() {#getTtfTables--}
```
public TtfTableRepository getTtfTables()
```


Référence au référentiel de tables TTF.

**Returns:**
[TtfTableRepository](../../com.aspose.font/ttftablerepository) - Reference to TTF table repository.
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
### updateName(PlatformId platformId, int platformSpecificId, NameId nameId, int languageId, String newName) {#updateName-com.aspose.font.PlatformId-int-com.aspose.font.NameId-int-java.lang.String-}
```
public void updateName(PlatformId platformId, int platformSpecificId, NameId nameId, int languageId, String newName)
```


Met à jour le nom dans le(s) enregistrement(s) liés à la plateforme spécifiée (combinaison de platformId et platformSpecificId), à la catégorie (nameId) et à la langue (languageId).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| platformId | [PlatformId](../../com.aspose.font/platformid) | Identifiant de plateforme |
| platformSpecificId | int | Identifiant d'encodage spécifique à la plateforme |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom, catégorie de chaîne logique, spécifié par l'énumération  NameId  |
| languageId | int | Identifiant de langue |
| newName | java.lang.String | Nouveau nom ou nouvelles données de chaîne |

### updateNamesByNameId(NameId nameId, String newName) {#updateNamesByNameId-com.aspose.font.NameId-java.lang.String-}
```
public void updateNamesByNameId(NameId nameId, String newName)
```


Sélectionne tous les enregistrements liés à la catégorie logique de chaîne, spécifiée par le paramètre nameId, et met à jour le champ name (données de chaîne) dans ces enregistrements. Les champs liés à la plateforme (platformID, Platform-specific encoding ID) et à la langue (Language ID) ne sont pas affectés par cette méthode. Seules les données de chaîne du nom sont remplacées par un nouveau nom. Utilisez cette méthode avec prudence, car elle remplacera les noms originaux pour toutes les plateformes et langues associées à nameId. Elle peut engendrer des conflits dans les cas où les noms originaux avaient des valeurs différentes, car l'opération de remplacement change toutes ces valeurs par une seule nouvelle. Et cette nouvelle valeur peut présenter une incohérence logique avec certaines plateformes et langues. Cette méthode est utile lorsque le nom original a une représentation unique pour toutes les plateformes et langues, par exemple lorsque les données de chaîne du nom sont en anglais.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nameId | [NameId](../../com.aspose.font/nameid) | Identifiant de nom, catégorie de chaîne logique, spécifié par l'énumération  NameId  |
| newName | java.lang.String | Nouveau nom ou nouvelles données de chaîne |

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

