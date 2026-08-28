---
title: "FontCharactersMerger"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Déclare la fonctionnalité de fusionner des polices de différents types."
type: docs
weight: 35
url: /fr/java/com.aspose.font/fontcharactersmerger/
---
**Inheritance:**
java.lang.Object
```
public abstract class FontCharactersMerger
```

Déclare la fonctionnalité de fusionner des polices de différents types. Une paire de polices est nécessaire pour l'opération de fusion. Une police de cette paire est considérée comme principale. Cela signifie que de nombreuses caractéristiques liées à la police fusionnée finale, telles que les métriques, la structure d'encodage et d'autres, seront prises de cette police principale. L'autre police de la paire (secondaire) fournit uniquement les glyphes pour la police fusionnée finale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPrimaryFont()](#getPrimaryFont--) | Obtient la police principale. |
| [getSecondaryFont()](#getSecondaryFont--) | Obtient la police secondaire. |
| [hashCode()](#hashCode--) |  |
| [mergeFonts(GlyphId[] primaryFontGlyphs, GlyphId[] secondaryFontGlyphs, String newFontName)](#mergeFonts-com.aspose.font.GlyphId---com.aspose.font.GlyphId---java.lang.String-) | Fusionne les polices en fonction des listes de glyphes fournies. |
| [mergeFonts(int[] primaryFontCharCodes, int[] secondaryFontCharCodes, String newFontName)](#mergeFonts-int---int---java.lang.String-) | Fusionne les polices en fonction des listes de codes de caractères fournies. |
| [mergeFonts(Map<Integer,GlyphId> primaryFontDict, Map<Integer,GlyphId> secondaryFontDict, String newFontName)](#mergeFonts-java.util.Map-java.lang.Integer-com.aspose.font.GlyphId--java.util.Map-java.lang.Integer-com.aspose.font.GlyphId--java.lang.String-) | Cette version de la méthode est conçue pour les cas où vous souhaitez définir explicitement les codes de caractères pour les glyphes dans la police résultante. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getPrimaryFont() {#getPrimaryFont--}
```
public abstract Font getPrimaryFont()
```


Obtient la police principale.

**Returns:**
[Font](../../com.aspose.font/font) - The primary font.
### getSecondaryFont() {#getSecondaryFont--}
```
public abstract Font getSecondaryFont()
```


Obtient la police secondaire.

**Returns:**
[Font](../../com.aspose.font/font) - The secondary font.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mergeFonts(GlyphId[] primaryFontGlyphs, GlyphId[] secondaryFontGlyphs, String newFontName) {#mergeFonts-com.aspose.font.GlyphId---com.aspose.font.GlyphId---java.lang.String-}
```
public abstract Font mergeFonts(GlyphId[] primaryFontGlyphs, GlyphId[] secondaryFontGlyphs, String newFontName)
```


Fusionne les polices en fonction des listes de glyphes fournies. Recherche un code de caractère pour chaque glyphe fourni et ajoute le code de caractère trouvé avec le glyphe correspondant dans la nouvelle police résultante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| primaryFontGlyphs | [GlyphId\[\]](../../com.aspose.font/glyphid) | Liste des glyphes à prendre de la police principale. |
| secondaryFontGlyphs | [GlyphId\[\]](../../com.aspose.font/glyphid) | Liste des glyphes à prendre de la police secondaire. |
| newFontName | java.lang.String | Nom souhaité pour la police résultante. |

**Returns:**
[Font](../../com.aspose.font/font) - Merged font
### mergeFonts(int[] primaryFontCharCodes, int[] secondaryFontCharCodes, String newFontName) {#mergeFonts-int---int---java.lang.String-}
```
public abstract Font mergeFonts(int[] primaryFontCharCodes, int[] secondaryFontCharCodes, String newFontName)
```


Fusionne les polices en fonction des listes de codes de caractères fournies. Pour créer la police résultante souhaitée, il suffit de fournir les codes de symboles des polices d'origine que vous voulez inclure dans la police résultante. Les glyphes liés aux codes fournis seront trouvés automatiquement. Par exemple, si vous souhaitez inclure les glyphes liés aux lettres A et B de la première police et les glyphes liés aux lettres C et D de la deuxième police, appelez simplement cette méthode ainsi : `mergeFonts(new uint[] { 'A', 'B' }, new uint[] { 'C', 'D' }, "NewFont")`

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| primaryFontCharCodes | int[] | Codes à prendre de la police principale. |
| secondaryFontCharCodes | int[] | Codes à prendre de la police secondaire. |
| newFontName | java.lang.String | Nom souhaité pour la police résultante. |

**Returns:**
[Font](../../com.aspose.font/font) - Merged font.
### mergeFonts(Map<Integer,GlyphId> primaryFontDict, Map<Integer,GlyphId> secondaryFontDict, String newFontName) {#mergeFonts-java.util.Map-java.lang.Integer-com.aspose.font.GlyphId--java.util.Map-java.lang.Integer-com.aspose.font.GlyphId--java.lang.String-}
```
public abstract Font mergeFonts(Map<Integer,GlyphId> primaryFontDict, Map<Integer,GlyphId> secondaryFontDict, String newFontName)
```


Cette version de la méthode est conçue pour les cas où vous souhaitez définir explicitement les codes de caractères pour les glyphes dans la police résultante. Il n'est pas obligatoire que le code du glyphe que vous avez fourni soit présent dans la police d'origine. Le but du code fourni est qu'il soit associé à l'identifiant de glyphe correspondant dans la police résultante. Ainsi, la règle pour traiter chaque paire transmise via le paramètre dictionnaire [code, identifiant de glyphe] est que seul l'identifiant de glyphe sera pris de la police d'origine, puis il sera lié au code correspondant dans la police résultante. Cela peut être utile lorsque certains codes de la première police entrent en conflit avec les mêmes codes de la deuxième police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| primaryFontDict | java.util.Map<java.lang.Integer,com.aspose.font.GlyphId> | Dictionnaire contenant des paires [code de symbole, identifiant de glyphe] provenant de la police principale. |
| secondaryFontDict | java.util.Map<java.lang.Integer,com.aspose.font.GlyphId> | Dictionnaire contenant des paires [code de symbole, identifiant de glyphe] provenant de la police secondaire. |
| newFontName | java.lang.String | Nom souhaité pour la police résultante. |

**Returns:**
[Font](../../com.aspose.font/font) - Merged font.
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

