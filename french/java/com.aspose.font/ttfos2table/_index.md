---
title: "TtfOs2Table"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente la table OS/2 du fichier de police TTF."
type: docs
weight: 106
url: /fr/java/com.aspose.font/ttfos2table/
---
**Inheritance:**
java.lang.Object, [com.aspose.font.TtfTableBase](../../com.aspose.font/ttftablebase)
```
public class TtfOs2Table extends TtfTableBase
```

Représente la table "OS/2" du fichier de police TTF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAchVendId()](#getAchVendId--) | Obtient la valeur AchVendId. |
| [getClass()](#getClass--) |  |
| [getFSSelection()](#getFSSelection--) | Contient des informations concernant la nature des motifs de police. |
| [getFSType()](#getFSType--) | Obtient la valeur FSType. |
| [getLicenseFlags()](#getLicenseFlags--) | Obtient des indicateurs incorporés (fsType) dans la représentation d'objet. |
| [getOffset()](#getOffset--) | Obtient le décalage depuis le début du sfnt. |
| [getPanose()](#getPanose--) | Cette série de 10 octets de nombres est utilisée pour décrire les caractéristiques visuelles d'une police donnée. |
| [getSCapHeight()](#getSCapHeight--) | Obtient la valeur SCapHeight. |
| [getSFamilyClass()](#getSFamilyClass--) | Ce paramètre est une classification du design de la famille de polices. |
| [getSTypoAscender()](#getSTypoAscender--) | Obtient la valeur STypoAscender. |
| [getSTypoDescender()](#getSTypoDescender--) | Obtient la valeur STypoDescender. |
| [getSTypoLineGap()](#getSTypoLineGap--) | Obtient la valeur STypoLineGap. |
| [getSXHeight()](#getSXHeight--) | Obtient la valeur SXHeight. |
| [getSupportedTableVersions()](#getSupportedTableVersions--) | Obtient les versions prises en charge de la table OS/2. |
| [getTag()](#getTag--) | Obtient le tag de la table. |
| [getTtfTables()](#getTtfTables--) | Référence au référentiel de tables TTF. |
| [getULCodePageRange()](#getULCodePageRange--) | Obtient la valeur ULCodePageRange. |
| [getULUnicodeRange()](#getULUnicodeRange--) | Obtient la valeur ULUnicodeRange. |
| [getUSBreakChar()](#getUSBreakChar--) | Obtient la valeur USBreakChar. |
| [getUSDefaultChar()](#getUSDefaultChar--) | Obtient la valeur USDefaultChar. |
| [getUSFirstCharIndex()](#getUSFirstCharIndex--) | Obtient la valeur USFirstCharIndex. |
| [getUSLastCharIndex()](#getUSLastCharIndex--) | Obtient la valeur USLastCharIndex. |
| [getUSLowerOpticalPointSize()](#getUSLowerOpticalPointSize--) | Obtient la valeur USLowerOpticalPointSize. |
| [getUSMaxContext()](#getUSMaxContext--) | Obtient la valeur USMaxContext. |
| [getUSUpperOpticalPointSize()](#getUSUpperOpticalPointSize--) | Obtient la valeur USUpperOpticalPointSize. |
| [getUSWeightClass()](#getUSWeightClass--) | Indique le poids visuel (degré de noirceur ou d'épaisseur des traits) des caractères dans la police. |
| [getUSWidthClass()](#getUSWidthClass--) | Indique une variation relative du rapport d'aspect normal (rapport largeur/hauteur) tel que spécifié par le concepteur de police pour les glyphes d'une police. |
| [getUSWinAscent()](#getUSWinAscent--) | Obtient la valeur USWinAscent. |
| [getUSWinDescent()](#getUSWinDescent--) | Obtient la valeur USWinDescent. |
| [getVersion()](#getVersion--) | Obtient la valeur Version. |
| [getXAvgCharWidth()](#getXAvgCharWidth--) | Obtient le paramètre Largeur moyenne des caractères. |
| [getYStrikeoutPosition()](#getYStrikeoutPosition--) | Obtient la valeur YStrikeoutPosition. |
| [getYStrikeoutSize()](#getYStrikeoutSize--) | Obtient la valeur YStrikeoutSize. |
| [getYSubscriptXOffset()](#getYSubscriptXOffset--) | Obtient la valeur YSubscriptXOffset. |
| [getYSubscriptXSize()](#getYSubscriptXSize--) | Obtient la valeur YSubscriptXSize. |
| [getYSubscriptYOffset()](#getYSubscriptYOffset--) | Obtient la valeur YSubscriptYOffset. |
| [getYSubscriptYSize()](#getYSubscriptYSize--) | Obtient la valeur YSubscriptYSize. |
| [getYSuperscriptXOffset()](#getYSuperscriptXOffset--) | Obtient la valeur YSuperscriptXOffset. |
| [getYSuperscriptXSize()](#getYSuperscriptXSize--) | Obtient la valeur YSuperscriptXSize. |
| [getYSuperscriptYOffset()](#getYSuperscriptYOffset--) | Obtient la valeur YSuperscriptYOffset. |
| [getYSuperscriptYSize()](#getYSuperscriptYSize--) | Obtient la valeur YSuperscriptYSize. |
| [hashCode()](#hashCode--) |  |
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
### getAchVendId() {#getAchVendId--}
```
public byte[] getAchVendId()
```


Obtient la valeur AchVendId.

**Returns:**
byte[] - AchVendId valeur.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFSSelection() {#getFSSelection--}
```
public int getFSSelection()
```


Contient des informations concernant la nature des motifs de police.

> ```
> 0	bit 1	ITALIC	Font contains Italic characters, otherwise they are upright.
>  1	 	    UNDERSCORE	Characters are underscored.
>  2	 	    NEGATIVE	Characters have their foreground and background reversed.
>  3	 	    OUTLINED	Outline (hollow) characters, otherwise they are solid.
>  4	 	    STRIKEOUT	Characters are overstruck.
>  5	bit 0	BOLD	Characters are emboldened.
>  6	 	    REGULAR	Characters are in the standard weight/style for the font.
> ```

**Returns:**
int - Les informations.
### getFSType() {#getFSType--}
```
public int getFSType()
```


Obtient la valeur FSType.

--------------------

Indique les droits de licence d'intégration de police pour la Font.

**Returns:**
int - valeur FSType.
### getLicenseFlags() {#getLicenseFlags--}
```
public LicenseFlags getLicenseFlags()
```


Obtient des indicateurs incorporés (fsType) dans la représentation d'objet.

**Returns:**
[LicenseFlags](../../com.aspose.font/licenseflags) - Embedded flags.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtient le décalage depuis le début du sfnt.

**Returns:**
long - Décalage depuis le début du sfnt.
### getPanose() {#getPanose--}
```
public byte[] getPanose()
```


Cette série de 10 octets de nombres est utilisée pour décrire les caractéristiques visuelles d'une police donnée. Ces caractéristiques sont ensuite utilisées pour associer la police à d'autres polices d'apparence similaire portant des noms différents.

**Returns:**
byte[] - Les caractéristiques visuelles d'une police donnée.
### getSCapHeight() {#getSCapHeight--}
```
public short getSCapHeight()
```


Obtient la valeur SCapHeight.

**Returns:**
short - valeur SCapHeight.
### getSFamilyClass() {#getSFamilyClass--}
```
public short getSFamilyClass()
```


Ce paramètre est une classification du design de famille de polices. La classe de police et la sous-classe de police sont des valeurs enregistrées attribuées par IBM à chaque famille de polices. Ce paramètre est destiné à être utilisé pour sélectionner une police alternative lorsque la police demandée n'est pas disponible.

**Returns:**
short - Classification du design de famille de polices.
### getSTypoAscender() {#getSTypoAscender--}
```
public short getSTypoAscender()
```


Obtient la valeur STypoAscender.

**Returns:**
short - valeur STypoAscender.
### getSTypoDescender() {#getSTypoDescender--}
```
public short getSTypoDescender()
```


Obtient la valeur STypoDescender.

**Returns:**
short - valeur STypoDescender.
### getSTypoLineGap() {#getSTypoLineGap--}
```
public short getSTypoLineGap()
```


Obtient la valeur STypoLineGap.

**Returns:**
short - valeur STypoLineGap.
### getSXHeight() {#getSXHeight--}
```
public short getSXHeight()
```


Obtient la valeur SXHeight.

**Returns:**
short - valeur SXHeight.
### getSupportedTableVersions() {#getSupportedTableVersions--}
```
public int[] getSupportedTableVersions()
```


Obtient les versions prises en charge de la table OS/2.

**Returns:**
int[] - Versions prises en charge de la table OS/2.
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
### getULCodePageRange() {#getULCodePageRange--}
```
public long[] getULCodePageRange()
```


Obtient la valeur ULCodePageRange.

**Returns:**
long[] - Valeur ULCodePageRange.
### getULUnicodeRange() {#getULUnicodeRange--}
```
public long[] getULUnicodeRange()
```


Obtient la valeur ULUnicodeRange.

**Returns:**
long[] - Valeur ULUnicodeRange.
### getUSBreakChar() {#getUSBreakChar--}
```
public int getUSBreakChar()
```


Obtient la valeur USBreakChar.

**Returns:**
int - Valeur USBreakChar.
### getUSDefaultChar() {#getUSDefaultChar--}
```
public int getUSDefaultChar()
```


Obtient la valeur USDefaultChar.

**Returns:**
int - Valeur USDefaultChar.
### getUSFirstCharIndex() {#getUSFirstCharIndex--}
```
public int getUSFirstCharIndex()
```


Obtient la valeur USFirstCharIndex.

**Returns:**
int - Valeur USFirstCharIndex.
### getUSLastCharIndex() {#getUSLastCharIndex--}
```
public int getUSLastCharIndex()
```


Obtient la valeur USLastCharIndex.

**Returns:**
int - Valeur USLastCharIndex.
### getUSLowerOpticalPointSize() {#getUSLowerOpticalPointSize--}
```
public int getUSLowerOpticalPointSize()
```


Obtient la valeur USLowerOpticalPointSize.

**Returns:**
int - La valeur USLowerOpticalPointSize.
### getUSMaxContext() {#getUSMaxContext--}
```
public int getUSMaxContext()
```


Obtient la valeur USMaxContext.

**Returns:**
int - Valeur UsMaxContext.
### getUSUpperOpticalPointSize() {#getUSUpperOpticalPointSize--}
```
public int getUSUpperOpticalPointSize()
```


Obtient la valeur USUpperOpticalPointSize.

**Returns:**
int - La valeur USUpperOpticalPointSize.
### getUSWeightClass() {#getUSWeightClass--}
```
public int getUSWeightClass()
```


Indique le poids visuel (degré de noirceur ou d'épaisseur des traits) des caractères dans la police.

**Returns:**
int - Le poids visuel (degré de noirceur ou épaisseur des traits) des caractères dans la Font.
### getUSWidthClass() {#getUSWidthClass--}
```
public int getUSWidthClass()
```


Indique une variation relative du rapport d'aspect normal (rapport largeur/hauteur) tel que spécifié par le concepteur de police pour les glyphes d'une police.

**Returns:**
int - Un changement relatif par rapport au rapport d'aspect normal (rapport largeur/hauteur) tel que spécifié par un concepteur de police pour les glyphes d'une Font.
### getUSWinAscent() {#getUSWinAscent--}
```
public int getUSWinAscent()
```


Obtient la valeur USWinAscent.

**Returns:**
int - Valeur USWinAscent.
### getUSWinDescent() {#getUSWinDescent--}
```
public int getUSWinDescent()
```


Obtient la valeur USWinDescent.

**Returns:**
int - Valeur USWinDescent.
### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient la valeur Version.

**Returns:**
int - Valeur Version.
### getXAvgCharWidth() {#getXAvgCharWidth--}
```
public short getXAvgCharWidth()
```


Obtient le paramètre Largeur moyenne des caractères.

**Returns:**
short - Le paramètre Average Character Width.
### getYStrikeoutPosition() {#getYStrikeoutPosition--}
```
public short getYStrikeoutPosition()
```


Obtient la valeur YStrikeoutPosition.

**Returns:**
short - Valeur YStrikeoutPosition.
### getYStrikeoutSize() {#getYStrikeoutSize--}
```
public short getYStrikeoutSize()
```


Obtient la valeur YStrikeoutSize.

**Returns:**
short - Valeur YStrikeoutSize.
### getYSubscriptXOffset() {#getYSubscriptXOffset--}
```
public short getYSubscriptXOffset()
```


Obtient la valeur YSubscriptXOffset.

**Returns:**
short - Valeur YSubscriptXOffset.
### getYSubscriptXSize() {#getYSubscriptXSize--}
```
public short getYSubscriptXSize()
```


Obtient la valeur YSubscriptXSize.

**Returns:**
short - Valeur YSubscriptXSize.
### getYSubscriptYOffset() {#getYSubscriptYOffset--}
```
public short getYSubscriptYOffset()
```


Obtient la valeur YSubscriptYOffset.

**Returns:**
short - Valeur YSubscriptYOffset.
### getYSubscriptYSize() {#getYSubscriptYSize--}
```
public short getYSubscriptYSize()
```


Obtient la valeur YSubscriptYSize.

**Returns:**
short - Valeur YSubscriptYSize.
### getYSuperscriptXOffset() {#getYSuperscriptXOffset--}
```
public short getYSuperscriptXOffset()
```


Obtient la valeur YSuperscriptXOffset.

**Returns:**
short - Valeur YSuperscriptXOffset.
### getYSuperscriptXSize() {#getYSuperscriptXSize--}
```
public short getYSuperscriptXSize()
```


Obtient la valeur YSuperscriptXSize.

**Returns:**
short - Valeur YSuperscriptXSize.
### getYSuperscriptYOffset() {#getYSuperscriptYOffset--}
```
public short getYSuperscriptYOffset()
```


Obtient la valeur YSuperscriptYOffset.

**Returns:**
short - Valeur YSuperscriptYOffset.
### getYSuperscriptYSize() {#getYSuperscriptYSize--}
```
public short getYSuperscriptYSize()
```


Obtient la valeur YSuperscriptYSize.

**Returns:**
court - valeur YSuperscriptYSize.
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

