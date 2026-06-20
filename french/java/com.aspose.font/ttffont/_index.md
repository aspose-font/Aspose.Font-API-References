---
title: "TtfFont"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la police TrueType TTF."
type: docs
weight: 94
url: /fr/java/com.aspose.font/ttffont/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.Font](../../com.aspose.font/font)
```
public class TtfFont extends Font
```

Représente la police TrueType (TTF).
## Méthodes

| Méthode | Description |
| --- | --- |
| [convert(FontType fontType)](#convert-com.aspose.font.FontType-) | Convertit la police en un autre format. |
| [convert(FontType fontType, Collection<Integer> limitingCharacterSet)](#convert-com.aspose.font.FontType-java.util.Collection-java.lang.Integer--) | Convertit la police en un autre format avec un jeu de caractères limité  *Note : le type de police TTF n'est désormais pris en charge que.* |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllGlyphIds()](#getAllGlyphIds--) | Renvoie un tableau de tous les identifiants de glyphes disponibles dans la police. |
| [getCffFont()](#getCffFont--) | Obtient la police CFF si elle est présente. |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Obtient l'encodage de la police. |
| [getFontDefinition()](#getFontDefinition--) | Obtient la définition de la police. |
| [getFontFamily()](#getFontFamily--) | Obtient la famille de la police. |
| [getFontName()](#getFontName--) | Obtient le nom de la face de la police. |
| [getFontNames()](#getFontNames--) | Obtient les noms de la police. |
| [getFontSaver()](#getFontSaver--) | Obtient la fonctionnalité d'enregistrement de la police. |
| [getFontStyle()](#getFontStyle--) | Obtient le style de la police. |
| [getFontType()](#getFontType--) | Obtient le type de la police. |
| [getGlyphAccessor()](#getGlyphAccessor--) | Accesseur de glyphes de la police. |
| [getGlyphById(GlyphId id)](#getGlyphById-com.aspose.font.GlyphId-) | Renvoie le glyphe par identifiant de glyphe. |
| [getGlyphById(String glyphName)](#getGlyphById-java.lang.String-) | Renvoie le glyphe par nom de glyphe. |
| [getGlyphById(long id)](#getGlyphById-long-) | Renvoie le glyphe par identifiant de glyphe. |
| [getGlyphComponentsById(GlyphId id, GlyphIdList componentsToPopulate)](#getGlyphComponentsById-com.aspose.font.GlyphId-com.aspose.font.GlyphIdList-) | Obtient un glyphe par l'identifiant de glyphe fourni et remplit la liste d'identifiants de glyphes passée avec les composants de ce glyphe. |
| [getGlyphComponentsById(String glyphName, GlyphIdList componentsToPopulate)](#getGlyphComponentsById-java.lang.String-com.aspose.font.GlyphIdList-) | Obtient un glyphe par le nom de glyphe fourni et remplit la liste d'identifiants de glyphes passée avec les composants de ce glyphe. |
| [getGlyphComponentsById(long id, GlyphIdList componentsToPopulate)](#getGlyphComponentsById-long-com.aspose.font.GlyphIdList-) | Obtient un glyphe par l'index de glyphe fourni et remplit la liste d'identifiants de glyphes passée avec les composants de ce glyphe. |
| [getGlyphIdType()](#getGlyphIdType--) | Obtient la spécification du type d'identifiant de glyphe. |
| [getGlyphsForText(String text)](#getGlyphsForText-java.lang.String-) | Obtient la représentation des glyphes pour le texte. |
| [getMetrics()](#getMetrics--) | Obtient les métriques de la police. |
| [getNumGlyphs()](#getNumGlyphs--) | Obtient le nombre de glyphes dans la police. |
| [getPostscriptNames()](#getPostscriptNames--) | Obtient les noms de police Postscript. |
| [getStyle()](#getStyle--) | Obtient le style de la police. |
| [getTtfTables()](#getTtfTables--) | Obtient les tables TTF. |
| [hashCode()](#hashCode--) |  |
| [isSymbolic()](#isSymbolic--) | Renvoie vrai si la police est symbolique. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(FontDefinition fontDefinition)](#open-com.aspose.font.FontDefinition-) | Ouvre une police en utilisant l'objet FontDefinition. |
| [open(FontType fontType, byte[] fontData)](#open-com.aspose.font.FontType-byte---) | Ouvre une police en utilisant le type de police et le tableau d'octets des données de police. |
| [open(FontType fontType, StreamSource fontStreamSource)](#open-com.aspose.font.FontType-com.aspose.font.StreamSource-) | Ouvre une police en utilisant le type de police et la source du flux. |
| [open(FontType fontType, String fileName)](#open-com.aspose.font.FontType-java.lang.String-) | Ouvre une police en utilisant le type de police et le nom du fichier de police. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Enregistre la police au format original. |
| [save(String fileName)](#save-java.lang.String-) | Enregistre la police au format original. |
| [saveToFormat(OutputStream stream, FontSavingFormats outFormat)](#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-) | Enregistre la police au format spécifié. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Définit la famille de la police. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Définit le nom de la face de la police. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Définit le style de la police. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convert(FontType fontType) {#convert-com.aspose.font.FontType-}
```
public Font convert(FontType fontType)
```


Convertit la police en un autre format. Remarque : le type de police TTF n'est désormais pris en charge que.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) | Type de format de police dans lequel convertir. |

**Returns:**
[Font](../../com.aspose.font/font) - Font converted into new format.
### convert(FontType fontType, Collection<Integer> limitingCharacterSet) {#convert-com.aspose.font.FontType-java.util.Collection-java.lang.Integer--}
```
public Font convert(FontType fontType, Collection<Integer> limitingCharacterSet)
```


Convertit la police en un autre format avec un jeu de caractères limité  *Note : le type de police TTF n'est désormais pris en charge que.*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) | Type de format de police dans lequel convertir. |
| limitingCharacterSet | java.util.Collection<java.lang.Integer> | Ensemble de caractères limitant. |

**Returns:**
[Font](../../com.aspose.font/font) - Font converted into new format.
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
### getAllGlyphIds() {#getAllGlyphIds--}
```
public GlyphId[] getAllGlyphIds()
```


Renvoie un tableau de tous les identifiants de glyphes disponibles dans la police. L'identifiant de glyphe est un nombre unique pour un glyphe, dépendant du type de police. L'identifiant de glyphe d'une police TTF peut être une instance de la classe ( GlyphStringId ) ou de la classe ( GlyphUInt32Id ). L'adressage des glyphes par nom (string) est pris en charge pour les polices TTF via le mappage de la table Post. En cas de police CFF, les structures CFF sont utilisées pour adresser les glyphes par leur nom.

**Returns:**
com.aspose.font.GlyphId[] - Identifiants de glyphes.
### getCffFont() {#getCffFont--}
```
public Font getCffFont()
```


Obtient la police CFF si elle est présente.

**Returns:**
[Font](../../com.aspose.font/font) - CFF Font.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEncoding() {#getEncoding--}
```
public IFontEncoding getEncoding()
```


Obtient l'encodage de la police.

**Returns:**
[IFontEncoding](../../com.aspose.font/ifontencoding) - Font encoding.
### getFontDefinition() {#getFontDefinition--}
```
public FontDefinition getFontDefinition()
```


Obtient la définition de la police.

**Returns:**
[FontDefinition](../../com.aspose.font/fontdefinition) - Font definition.
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Obtient la famille de la police.

**Returns:**
java.lang.String - Famille de police.
### getFontName() {#getFontName--}
```
public String getFontName()
```


Obtient le nom de la face de la police.

**Returns:**
java.lang.String - Nom de la face de police.
### getFontNames() {#getFontNames--}
```
public MultiLanguageString getFontNames()
```


Obtient les noms de la police.

**Returns:**
[MultiLanguageString](../../com.aspose.font/multilanguagestring) - Font names
### getFontSaver() {#getFontSaver--}
```
public IFontSaver getFontSaver()
```


Obtient la fonctionnalité d'enregistrement de la police.

**Returns:**
[IFontSaver](../../com.aspose.font/ifontsaver) - Font save functionality.
### getFontStyle() {#getFontStyle--}
```
public int getFontStyle()
```


Obtient le style de la police. Il s'agit d'une valeur calculée et représentée dans un type généralisé.

**Returns:**
int - Style de police. Généralement, une combinaison de valeurs de drapeaux constants de la classe FontStyle ou 0.
### getFontType() {#getFontType--}
```
public FontType getFontType()
```


Obtient le type de police. Renvoie la valeur FontType.TTF.

**Returns:**
[FontType](../../com.aspose.font/fonttype) - Font type.
### getGlyphAccessor() {#getGlyphAccessor--}
```
public IGlyphAccessor getGlyphAccessor()
```


Accesseur de glyphes de police. Récupère les glyphes et les identifiants de glyphes.

**Returns:**
[IGlyphAccessor](../../com.aspose.font/iglyphaccessor) - Font glyph accessor.
### getGlyphById(GlyphId id) {#getGlyphById-com.aspose.font.GlyphId-}
```
public Glyph getGlyphById(GlyphId id)
```


Renvoie le glyphe par identifiant de glyphe. L'identifiant de glyphe est un nombre unique pour un glyphe, dépendant du type de police. L'identifiant de glyphe d'une police TTF peut être une instance de la classe ( GlyphStringId ) ou de la classe ( GlyphUInt32Id ). L'adressage des glyphes par nom (string) est pris en charge pour les polices TTF via le mappage de la table Post. En cas de police CFF, les structures CFF sont utilisées pour adresser les glyphes par nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | [GlyphId](../../com.aspose.font/glyphid) |  |

**Returns:**
[Glyph](../../com.aspose.font/glyph)
### getGlyphById(String glyphName) {#getGlyphById-java.lang.String-}
```
public Glyph getGlyphById(String glyphName)
```


Renvoie le glyphe par nom de glyphe. L'adressage des glyphes par nom (string) est pris en charge pour les polices TTF via le mappage de la table Post. En cas de police CFF, les structures CFF sont utilisées pour adresser les glyphes par nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphName | java.lang.String | Identifiant de chaîne de glyphe. |

**Returns:**
[Glyph](../../com.aspose.font/glyph) - Glyph.
### getGlyphById(long id) {#getGlyphById-long-}
```
public Glyph getGlyphById(long id)
```


Renvoie le glyphe par identifiant de glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | long | Index de glyphe. |

**Returns:**
[Glyph](../../com.aspose.font/glyph) - Glyph.
### getGlyphComponentsById(GlyphId id, GlyphIdList componentsToPopulate) {#getGlyphComponentsById-com.aspose.font.GlyphId-com.aspose.font.GlyphIdList-}
```
public void getGlyphComponentsById(GlyphId id, GlyphIdList componentsToPopulate)
```


Obtient un glyphe à partir de l'identifiant de glyphe fourni et remplit la liste d'identifiants de glyphes passée avec les composants de ce glyphe. L'identifiant de glyphe est un nombre unique pour un glyphe, dépendant du type de police. L'identifiant de glyphe d'une police TTF peut être une instance de la classe ( GlyphStringId ) ou de la classe ( GlyphUInt32Id ). L'adressage des glyphes par nom (string) est pris en charge pour les polices TTF via le mappage de la table Post. En cas de police CFF, les structures CFF sont utilisées pour adresser les glyphes par nom.

--------------------

Une collection vide componentsToPopulate doit être passée, elle contiendra la liste des identifiants des composants de glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | [GlyphId](../../com.aspose.font/glyphid) | Identifiant de glyphe. |
| componentsToPopulate | [GlyphIdList](../../com.aspose.font/glyphidlist) | Liste des identifiants de glyphes à remplir. |

### getGlyphComponentsById(String glyphName, GlyphIdList componentsToPopulate) {#getGlyphComponentsById-java.lang.String-com.aspose.font.GlyphIdList-}
```
public void getGlyphComponentsById(String glyphName, GlyphIdList componentsToPopulate)
```


Obtient un glyphe par le nom de glyphe fourni et remplit la liste d'identifiants de glyphes passée avec les composants de ce glyphe.

--------------------

Une collection vide componentsToPopulate doit être passée, elle contiendra la liste des identifiants des composants de glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| glyphName | java.lang.String | Nom du glyphe. |
| componentsToPopulate | [GlyphIdList](../../com.aspose.font/glyphidlist) | Liste des identifiants de glyphes à remplir. |

### getGlyphComponentsById(long id, GlyphIdList componentsToPopulate) {#getGlyphComponentsById-long-com.aspose.font.GlyphIdList-}
```
public void getGlyphComponentsById(long id, GlyphIdList componentsToPopulate)
```


Obtient un glyphe par l'index de glyphe fourni et remplit la liste d'identifiants de glyphes passée avec les composants de ce glyphe.

--------------------

Une collection vide componentsToPopulate doit être passée, elle contiendra la liste des identifiants des composants de glyphe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | long | Index de glyphe. |
| componentsToPopulate | [GlyphIdList](../../com.aspose.font/glyphidlist) | Liste des identifiants de glyphes à remplir. |

### getGlyphIdType() {#getGlyphIdType--}
```
public GlyphIdType getGlyphIdType()
```


Obtient la spécification du type d'identifiant de glyphe.

**Returns:**
[GlyphIdType](../../com.aspose.font/glyphidtype) - Glyph id type specification.
### getGlyphsForText(String text) {#getGlyphsForText-java.lang.String-}
```
public GlyphId[] getGlyphsForText(String text)
```


Obtient la représentation des glyphes pour le texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte d'entrée. |

**Returns:**
com.aspose.font.GlyphId[] - tableau GlyphId.
### getMetrics() {#getMetrics--}
```
public IFontMetrics getMetrics()
```


Obtient les métriques de la police.

**Returns:**
[IFontMetrics](../../com.aspose.font/ifontmetrics) - Font metrics.
### getNumGlyphs() {#getNumGlyphs--}
```
public int getNumGlyphs()
```


Obtient le nombre de glyphes dans la police.

**Returns:**
int - Nombre de glyphes dans la police.
### getPostscriptNames() {#getPostscriptNames--}
```
public MultiLanguageString getPostscriptNames()
```


Obtient les noms de police Postscript.

**Returns:**
[MultiLanguageString](../../com.aspose.font/multilanguagestring) - Postscript font names.
### getStyle() {#getStyle--}
```
public String getStyle()
```


Obtient le style de la police. Il s'agit d'une valeur de chaîne brute fournie par le fichier de police.

**Returns:**
java.lang.String - Style de police.
### getTtfTables() {#getTtfTables--}
```
public TtfTableRepository getTtfTables()
```


Obtient les tables TTF.

**Returns:**
[TtfTableRepository](../../com.aspose.font/ttftablerepository) - TTF tables.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isSymbolic() {#isSymbolic--}
```
public boolean isSymbolic()
```


Renvoie vrai si la police est symbolique.

**Returns:**
boolean - Vrai si la police est symbolique.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### open(FontDefinition fontDefinition) {#open-com.aspose.font.FontDefinition-}
```
public static Font open(FontDefinition fontDefinition)
```


Ouvre une police en utilisant l'objet FontDefinition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontDefinition | [FontDefinition](../../com.aspose.font/fontdefinition) | Objet de définition de police. |

**Returns:**
[Font](../../com.aspose.font/font) - Font loaded.
### open(FontType fontType, byte[] fontData) {#open-com.aspose.font.FontType-byte---}
```
public static Font open(FontType fontType, byte[] fontData)
```


Ouvre une police en utilisant le type de police et le tableau d'octets des données de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) | Type de police. |
| fontData | byte[] | Tableau d'octets pour charger la police. |

**Returns:**
[Font](../../com.aspose.font/font) - Font loaded.
### open(FontType fontType, StreamSource fontStreamSource) {#open-com.aspose.font.FontType-com.aspose.font.StreamSource-}
```
public static Font open(FontType fontType, StreamSource fontStreamSource)
```


Ouvre une police en utilisant le type de police et la source du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) | Type de police. |
| fontStreamSource | [StreamSource](../../com.aspose.font/streamsource) | Source de flux pour la police. |

**Returns:**
[Font](../../com.aspose.font/font) - Font loaded.
### open(FontType fontType, String fileName) {#open-com.aspose.font.FontType-java.lang.String-}
```
public static Font open(FontType fontType, String fileName)
```


Ouvre une police en utilisant le type de police et le nom du fichier de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) | Type de police. |
| fileName | java.lang.String | Nom du fichier de police. |

**Returns:**
[Font](../../com.aspose.font/font) - Font loaded.
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Enregistre la police au format original.

--------------------

> ```
> Note: following Font types are supported for saving:
>  New TTF fonts;
>  TTF Font subsets;
>  CFF Font subsets;
>  Type1 Font subsets.
> ```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Flux pour enregistrer la police. |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Enregistre la police au format original.

--------------------

> ```
> Note: following Font types are supported for saving:
>  New TTF fonts;
>  TTF Font subsets;
>  CFF Font subsets;
>  Type1 Font subsets.
> ```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Fichier pour enregistrer la police. |

### saveToFormat(OutputStream stream, FontSavingFormats outFormat) {#saveToFormat-java.io.OutputStream-com.aspose.font.FontSavingFormats-}
```
public void saveToFormat(OutputStream stream, FontSavingFormats outFormat)
```


Enregistre la police au format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | flux pour enregistrer la police |
| outFormat | [FontSavingFormats](../../com.aspose.font/fontsavingformats) | format souhaité |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Définit la famille de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle famille de police. |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Définit le nom de la face de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouveau nom de face de police. |

### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Définit le style de police. Il s'agit d'une valeur de chaîne brute fournie par le fichier de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouveau style de police. |

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

