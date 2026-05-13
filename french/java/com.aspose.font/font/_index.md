---
title: "Police"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la classe de base Font."
type: docs
weight: 32
url: /fr/java/com.aspose.font/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.font.IFont](../../com.aspose.font/ifont), [com.aspose.font.IGlyphAccessor](../../com.aspose.font/iglyphaccessor), [com.aspose.font.IFontSaver](../../com.aspose.font/ifontsaver)
```
public abstract class Font implements IFont, IGlyphAccessor, IFontSaver
```

Représente la classe de base Font.
## Méthodes

| Méthode | Description |
| --- | --- |
| [convert(FontType fontType)](#convert-com.aspose.font.FontType-) | Convertit la police en un autre format. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllGlyphIds()](#getAllGlyphIds--) | Renvoie tous les identifiants de glyphes disponibles dans la police. |
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
| [getGlyphById(GlyphId id)](#getGlyphById-com.aspose.font.GlyphId-) | Renvoie le glyphe par ID de glyphe. |
| [getGlyphIdType()](#getGlyphIdType--) | Spécification du type d'ID de glyphe. |
| [getGlyphsForText(String text)](#getGlyphsForText-java.lang.String-) | Obtient la représentation des glyphes pour le texte. |
| [getMetrics()](#getMetrics--) | Obtient les métriques de la police. |
| [getNumGlyphs()](#getNumGlyphs--) | Obtient le nombre de glyphes dans la police. |
| [getPostscriptNames()](#getPostscriptNames--) | Obtient les noms de police PostScript. |
| [getStyle()](#getStyle--) | Obtient le style de la police. |
| [hashCode()](#hashCode--) |  |
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
public abstract Font convert(FontType fontType)
```


Convertit la police en un autre format.

--------------------

> ```
> Note: TTF Font type is now supported only.
> ```

fontType Type de format de police dans lequel convertir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) |  |

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
public abstract GlyphId[] getAllGlyphIds()
```


Renvoie tous les identifiants de glyphes disponibles dans la police. Un identifiant de glyphe est un nombre unique pour un glyphe, dépendant du type de police. Par exemple : l'identifiant de Type1 est un nom de glyphe, instance de la classe ( GlyphStringId ). L'identifiant de TTF est un indice entier, instance de la classe ( GlyphInt32Id ).

**Returns:**
com.aspose.font.GlyphId[] - Identifiants de glyphes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEncoding() {#getEncoding--}
```
public abstract IFontEncoding getEncoding()
```


Obtient l'encodage de la police.

**Returns:**
[IFontEncoding](../../com.aspose.font/ifontencoding) - Font encoding.
### getFontDefinition() {#getFontDefinition--}
```
public abstract FontDefinition getFontDefinition()
```


Obtient la définition de la police.

**Returns:**
[FontDefinition](../../com.aspose.font/fontdefinition) - Font definition.
### getFontFamily() {#getFontFamily--}
```
public abstract String getFontFamily()
```


Obtient la famille de la police.

**Returns:**
java.lang.String - Famille de police.
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Obtient le nom de la face de la police.

**Returns:**
java.lang.String - Nom de la face de police.
### getFontNames() {#getFontNames--}
```
public abstract MultiLanguageString getFontNames()
```


Obtient les noms de la police.

**Returns:**
[MultiLanguageString](../../com.aspose.font/multilanguagestring) - Font names.
### getFontSaver() {#getFontSaver--}
```
public IFontSaver getFontSaver()
```


Obtient la fonctionnalité d'enregistrement de la police.

**Returns:**
[IFontSaver](../../com.aspose.font/ifontsaver) - Font save functionality.
### getFontStyle() {#getFontStyle--}
```
public abstract int getFontStyle()
```


Obtient le style de la police. Il s'agit d'une valeur calculée et représentée dans un type généralisé.

**Returns:**
int - Style de police. Généralement, une combinaison de valeurs de drapeaux constants de la classe FontStyle ou 0.
### getFontType() {#getFontType--}
```
public abstract FontType getFontType()
```


Obtient le type de la police.

--------------------

> ```
> Type1, TrueType etc.
> ```

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
public abstract Glyph getGlyphById(GlyphId id)
```


Renvoie le glyphe par son identifiant. L'identifiant de glyphe est un nombre unique pour un glyphe, dépendant du type de police. GlyphId - objet dérivé. Par exemple : l'identifiant de Type1 est un nom de glyphe, instance de la classe ( GlyphStringId ). L'identifiant de TTF est un indice entier, instance de la classe ( GlyphInt32Id ).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | [GlyphId](../../com.aspose.font/glyphid) | Identifiant de glyphe. |

**Returns:**
[Glyph](../../com.aspose.font/glyph) - Glyph.
### getGlyphIdType() {#getGlyphIdType--}
```
public abstract GlyphIdType getGlyphIdType()
```


Spécification du type d'identifiant de glyphe. Pour les consommateurs qui ont besoin de connaître le vrai type de 'bytes[]'.

**Returns:**
[GlyphIdType](../../com.aspose.font/glyphidtype) - Id type specification
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
public abstract IFontMetrics getMetrics()
```


Obtient les métriques de la police.

**Returns:**
[IFontMetrics](../../com.aspose.font/ifontmetrics) - Font metrics.
### getNumGlyphs() {#getNumGlyphs--}
```
public abstract int getNumGlyphs()
```


Obtient le nombre de glyphes dans la police.

**Returns:**
int - Nombre de glyphes dans la police.
### getPostscriptNames() {#getPostscriptNames--}
```
public abstract MultiLanguageString getPostscriptNames()
```


Obtient les noms de police PostScript.

**Returns:**
[MultiLanguageString](../../com.aspose.font/multilanguagestring) - Postscript font names.
### getStyle() {#getStyle--}
```
public abstract String getStyle()
```


Obtient le style de la police. Il s'agit d'une valeur de chaîne brute fournie par le fichier de police.

**Returns:**
java.lang.String - Style de police.
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
public abstract void setFontFamily(String value)
```


Définit la famille de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle famille de police. |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Définit le nom de la face de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouveau nom de face de police. |

### setStyle(String value) {#setStyle-java.lang.String-}
```
public abstract void setStyle(String value)
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

