---
title: "FontEnvironment"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Fournit des informations sur l'environnement et la plateforme actuels."
type: docs
weight: 39
url: /fr/java/com.aspose.font/fontenvironment/
---
**Inheritance:**
java.lang.Object
```
public class FontEnvironment
```

Fournit des informations sur l'environnement et la plateforme actuels.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCffCommonFontsSettings()](#getCffCommonFontsSettings--) | Paramètres communs aux polices CFF. |
| [getClass()](#getClass--) |  |
| [getCurrent()](#getCurrent--) | Obtient l'environnement actuel. |
| [getCurrentPlatformId()](#getCurrentPlatformId--) | Obtient l'identifiant de plateforme actuel. |
| [getFontSpecificEncodings()](#getFontSpecificEncodings--) | Stocke les encodages spécifiques pour les polices conscientes du consommateur. |
| [getStrictness()](#getStrictness--) | Certaines polices peuvent contenir des données inattendues, des fonctionnalités non spécifiées, ou être grossièrement découpées. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStrictness(FontEnvironment.ParsingStrictness value)](#setStrictness-com.aspose.font.FontEnvironment.ParsingStrictness-) | Certaines polices peuvent contenir des données inattendues, des fonctionnalités non spécifiées, ou être grossièrement découpées. |
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
### getCffCommonFontsSettings() {#getCffCommonFontsSettings--}
```
public static CffFontsSettings getCffCommonFontsSettings()
```


Paramètres communs aux polices CFF.

**Returns:**
[CffFontsSettings](../../com.aspose.font/cfffontssettings)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrent() {#getCurrent--}
```
public static FontEnvironment getCurrent()
```


Obtient l'environnement actuel.

**Returns:**
[FontEnvironment](../../com.aspose.font/fontenvironment) - Current environment.
### getCurrentPlatformId() {#getCurrentPlatformId--}
```
public int getCurrentPlatformId()
```


Obtient l'identifiant de plateforme actuel.

**Returns:**
int - Identifiant de plateforme actuel.
### getFontSpecificEncodings() {#getFontSpecificEncodings--}
```
public FontSpecificEncodings getFontSpecificEncodings()
```


Stocke les encodages spécifiques pour les polices conscientes du consommateur. Par exemple, PDF utilise les encodages spécifiques Adobe Symbol et ZapfDingbats.

**Returns:**
[FontSpecificEncodings](../../com.aspose.font/fontspecificencodings) - Specific encodings for consumer-aware Fonts.
### getStrictness() {#getStrictness--}
```
public FontEnvironment.ParsingStrictness getStrictness()
```


Certaines polices peuvent contenir des données inattendues, des fonctionnalités non spécifiées, ou être grossièrement découpées. Un réglage tolérant est recommandé pour les consommateurs qui souhaitent ouvrir n'importe quelle police, quelles que soient les éventuelles insuffisances de la police. Les structures internes des polices ne sont pas garanties d'être cohérentes. Un réglage strict est recommandé pour les consommateurs qui souhaitent ouvrir principalement des polices valides et solides.

**Returns:**
[ParsingStrictness](../../com.aspose.font/parsingstrictness) - Strictness.
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




### setStrictness(FontEnvironment.ParsingStrictness value) {#setStrictness-com.aspose.font.FontEnvironment.ParsingStrictness-}
```
public void setStrictness(FontEnvironment.ParsingStrictness value)
```


Certaines polices peuvent contenir des données inattendues, des fonctionnalités non spécifiées, ou être grossièrement découpées. Un réglage tolérant est recommandé pour les consommateurs qui souhaitent ouvrir n'importe quelle police, quelles que soient les éventuelles insuffisances de la police. Les structures internes des polices ne sont pas garanties d'être cohérentes. Un réglage strict est recommandé pour les consommateurs qui souhaitent ouvrir principalement des polices valides et solides.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ParsingStrictness](../../com.aspose.font/parsingstrictness) | Rigueur. |

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

