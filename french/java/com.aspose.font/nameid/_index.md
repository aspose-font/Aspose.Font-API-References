---
title: "NameId"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente l'énumération NameId."
type: docs
weight: 67
url: /fr/java/com.aspose.font/nameid/
---
**Inheritance:**
java.lang.Object
```
public final class NameId
```

Représente l'énumération NameId.
## Champs

| Champ | Description |
| --- | --- |
| [CompatibleFull](#CompatibleFull) | 18 Compatible Full (Macintosh uniquement) ; sur le Macintosh, le nom du menu est construit à l'aide de la ressource de Police. |
| [CopyrightNotice](#CopyrightNotice) | 0 Avis de droit d'auteur. |
| [DarkBackground](#DarkBackground) | Cet ID, s'il est utilisé dans le tableau Palette Labels du tableau CPAL\\u2019s, indique que la palette de couleurs correspondante dans le tableau CPAL est appropriée pour être utilisée avec la police lors de son affichage sur un fond sombre tel que le noir. |
| [Description](#Description) | 10 Description ; description de la police. |
| [DesignerName](#DesignerName) | 9 Designer ; nom du créateur de la police. |
| [FontFamily](#FontFamily) | 1 Famille de police. |
| [FontSubfamily](#FontSubfamily) | 2 Sous-famille de police. |
| [FullName](#FullName) | 4 Nom complet de la police. |
| [LicenseDescription](#LicenseDescription) | 13 Description de la licence ; description de la manière dont la police peut être utilisée légalement, ou différents scénarios d’utilisation sous licence. |
| [LicenseInfoUrl](#LicenseInfoUrl) | 14 URL des informations de licence, où des informations supplémentaires sur la licence peuvent être trouvées. |
| [LightBackground](#LightBackground) | Cet ID, s'il est utilisé dans le tableau des libellés de palette du tableau CPAL, indique que la palette de couleurs correspondante dans le tableau CPAL est appropriée pour être utilisée avec la police lors de son affichage sur un fond clair comme le blanc. |
| [ManufacturerName](#ManufacturerName) | 8 Nom du fabricant. |
| [PostScriptCID](#PostScriptCID) | Sa présence dans une police signifie que le nameID 6 contient un nom de police PostScript destiné à être utilisé avec l’invocation « composefont » afin d’appeler la police dans un interpréteur PostScript. |
| [PostScriptName](#PostScriptName) | 6 Nom PostScript de la police. |
| [PreferredFamily](#PreferredFamily) | 15 Réservé 16 Famille préférée (Windows uniquement) ; sous Windows, le nom de la Famille est affiché dans le menu Police ; le nom de la Sous-famille est présenté comme le nom du Style. |
| [PreferredSubfamily](#PreferredSubfamily) | 17 Sous-famille préférée (Windows uniquement) ; sous Windows, le nom de la Famille est affiché dans le menu Police ; le nom de la Sous-famille est présenté comme le nom du Style. |
| [SampleText](#SampleText) | 19 Texte d’exemple. |
| [TrademarkNotice](#TrademarkNotice) | 7 Avis de marque déposée. |
| [UniqueFontId](#UniqueFontId) | 3 Spécification Apple : identification unique de la sous-famille. 3 Spécification MS : identifiant unique de la police. |
| [UrlDesigner](#UrlDesigner) | 12 URL du créateur de la police (avec protocole, par ex., http://, ftp://) |
| [UrlVendor](#UrlVendor) | 11 URL du fournisseur de la police (avec protocole, par ex., http://, ftp://). |
| [VariationsPostScriptNamePrefix](#VariationsPostScriptNamePrefix) | S’il est présent dans une police variable, il peut être utilisé comme préfixe de famille dans l’algorithme de génération de nom PostScript pour les polices à variations. |
| [Version](#Version) | 5 Version de la table des noms. |
| [WwsFamilyName](#WwsFamilyName) | Utilisé pour fournir un nom de famille conforme au modèle WWS au cas où les entrées des ID 16 et 17 ne respecteraient pas le modèle WWS. |
| [WwsSubfamilyName](#WwsSubfamilyName) | Utilisé conjointement avec l’ID 21, cet ID fournit un nom de sous-famille conforme au modèle WWS (reflétant uniquement les attributs de poids, de largeur et d’inclinaison) au cas où les entrées des ID 16 et 17 ne respecteraient pas le modèle WWS. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromId(int id)](#fromId-int-) | Crée un ID de nom à partir d’une valeur entière. |
| [getClass()](#getClass--) |  |
| [getId()](#getId--) | Obtenez la valeur entière. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CompatibleFull {#CompatibleFull}
```
public static final NameId CompatibleFull
```


18 Nom complet compatible (Macintosh uniquement) ; sur Macintosh, le nom du menu est construit à l’aide de la ressource de police. Cela correspond généralement au Nom complet. Si vous souhaitez que le nom de la police apparaisse différemment du Nom complet, vous pouvez insérer le Nom complet compatible dans l’ID 18. Ce nom n’est pas utilisé par le système Mac OS lui‑même, mais peut être utilisé par les développeurs d’applications (par ex., Adobe).

### CopyrightNotice {#CopyrightNotice}
```
public static final NameId CopyrightNotice
```


0 Avis de droit d'auteur.

### DarkBackground {#DarkBackground}
```
public static final NameId DarkBackground
```


Cet ID, s'il est utilisé dans le tableau Palette Labels du tableau CPAL\\u2019s, indique que la palette de couleurs correspondante dans le tableau CPAL est appropriée pour être utilisée avec la police lors de son affichage sur un fond sombre tel que le noir.

### Description {#Description}
```
public static final NameId Description
```


10 Description ; description de la police. Peut contenir des informations de révision, des recommandations d’utilisation, l’historique, les caractéristiques, etc.

### DesignerName {#DesignerName}
```
public static final NameId DesignerName
```


9 Designer ; nom du créateur de la police.

### FontFamily {#FontFamily}
```
public static final NameId FontFamily
```


1 Famille de police. Cette chaîne est le nom de la famille de police que l’utilisateur voit sur les plateformes Macintosh.

### FontSubfamily {#FontSubfamily}
```
public static final NameId FontSubfamily
```


2 Sous-famille de police. Cette chaîne est la famille de police que l'utilisateur voit sur les plateformes Macintosh.

### FullName {#FullName}
```
public static final NameId FullName
```


4 Nom complet de la police.

### LicenseDescription {#LicenseDescription}
```
public static final NameId LicenseDescription
```


13 Description de la licence ; description de la façon dont la police peut être utilisée légalement, ou différents scénarios d'exemple d'utilisation sous licence. Ce champ doit être rédigé en langage clair, pas en jargon juridique.

### LicenseInfoUrl {#LicenseInfoUrl}
```
public static final NameId LicenseInfoUrl
```


14 URL des informations de licence, où des informations supplémentaires sur la licence peuvent être trouvées.

### LightBackground {#LightBackground}
```
public static final NameId LightBackground
```


Cet ID, s'il est utilisé dans le tableau des libellés de palette du tableau CPAL, indique que la palette de couleurs correspondante dans le tableau CPAL est appropriée pour être utilisée avec la police lors de son affichage sur un fond clair comme le blanc.

### ManufacturerName {#ManufacturerName}
```
public static final NameId ManufacturerName
```


8 Nom du fabricant.

### PostScriptCID {#PostScriptCID}
```
public static final NameId PostScriptCID
```


Sa présence dans une police signifie que le nameID 6 contient un nom de police PostScript destiné à être utilisé avec l’invocation « composefont » afin d’appeler la police dans un interpréteur PostScript.

### PostScriptName {#PostScriptName}
```
public static final NameId PostScriptName
```


6 Nom PostScript de la police. Remarque : une police ne peut avoir qu'un seul nom PostScript et ce nom doit être en ASCII.

### PreferredFamily {#PreferredFamily}
```
public static final NameId PreferredFamily
```


15 Reserved 16 Preferred Family (Windows uniquement) ; sous Windows, le nom de la Family est affiché dans le menu des polices ; le nom de la Subfamily est présenté comme le nom du Style. Pour des raisons historiques, les familles de polices contenaient au maximum quatre styles, mais les concepteurs de polices peuvent regrouper plus de quatre polices dans une même famille. Les identifiants Preferred Family et Preferred Subfamily permettent aux concepteurs de polices d’inclure les groupements de famille/sous‑famille préférés. Ces identifiants ne sont présents que s’ils diffèrent des identifiants 1 et 2.

### PreferredSubfamily {#PreferredSubfamily}
```
public static final NameId PreferredSubfamily
```


17 Preferred Subfamily (Windows uniquement) ; sous Windows, le nom de la Family est affiché dans le menu des polices ; le nom de la Subfamily est présenté comme le nom du Style. Pour des raisons historiques, les familles de polices contenaient au maximum quatre styles, mais les concepteurs de polices peuvent regrouper plus de quatre polices dans une même famille. Les identifiants Preferred Family et Preferred Subfamily permettent aux concepteurs de polices d’inclure les groupements de famille/sous‑famille préférés. Ces identifiants ne sont présents que s’ils diffèrent des identifiants 1 et 2.

### SampleText {#SampleText}
```
public static final NameId SampleText
```


19 Texte d'exemple. Cela peut être le nom de la police, ou tout autre texte que le concepteur estime être le meilleur exemple pour montrer à quoi ressemble la police.

### TrademarkNotice {#TrademarkNotice}
```
public static final NameId TrademarkNotice
```


7 Avis de marque déposée.

### UniqueFontId {#UniqueFontId}
```
public static final NameId UniqueFontId
```


3 Spécification Apple : identification unique de la sous-famille. 3 Spécification MS : identifiant unique de la police.

### UrlDesigner {#UrlDesigner}
```
public static final NameId UrlDesigner
```


12 URL du créateur de la police (avec protocole, par ex., http://, ftp://)

### UrlVendor {#UrlVendor}
```
public static final NameId UrlVendor
```


11 URL du fournisseur de la police (avec protocole, par ex., http://, ftp://). Si un numéro de série unique est intégré dans l'URL, il peut être utilisé pour enregistrer la police.

### VariationsPostScriptNamePrefix {#VariationsPostScriptNamePrefix}
```
public static final NameId VariationsPostScriptNamePrefix
```


S’il est présent dans une police variable, il peut être utilisé comme préfixe de famille dans l’algorithme de génération de nom PostScript pour les polices à variations.

### Version {#Version}
```
public static final NameId Version
```


5 Version de la table des noms.

### WwsFamilyName {#WwsFamilyName}
```
public static final NameId WwsFamilyName
```


Utilisé pour fournir un nom de famille conforme au modèle WWS au cas où les entrées des ID 16 et 17 ne respecteraient pas le modèle WWS.

### WwsSubfamilyName {#WwsSubfamilyName}
```
public static final NameId WwsSubfamilyName
```


Utilisé conjointement avec l’ID 21, cet ID fournit un nom de sous-famille conforme au modèle WWS (reflétant uniquement les attributs de poids, de largeur et d’inclinaison) au cas où les entrées des ID 16 et 17 ne respecteraient pas le modèle WWS.

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
### fromId(int id) {#fromId-int-}
```
public static NameId fromId(int id)
```


Crée un ID de nom à partir d’une valeur entière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | int | Une valeur entière. |

**Returns:**
[NameId](../../com.aspose.font/nameid) - The name id.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getId() {#getId--}
```
public int getId()
```


Obtenez la valeur entière.

**Returns:**
int - La valeur entière.
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

