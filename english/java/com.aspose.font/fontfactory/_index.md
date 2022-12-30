---
title: FontFactory
second_title: Aspose.Font for Java API Reference
description: Contains functionality for opening fonts of different types and other methods  for creating various objects.
type: docs
weight: 31
url: /java/com.aspose.font/fontfactory/
---
**Inheritance:**
java.lang.Object
```
public class FontFactory
```

Contains functionality for opening fonts of different types and other methods for creating various objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontFactory()](#FontFactory--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [open(FontDefinition fontDefinition)](#open-com.aspose.font.FontDefinition-) | Opens a font, using FontDefinition object. |
| [open(FontType fontType, StreamSource fontStreamSource)](#open-com.aspose.font.FontType-com.aspose.font.StreamSource-) | Opens a font, using font type and stream source. |
| [open(FontType fontType, String fileName)](#open-com.aspose.font.FontType-java.lang.String-) | Opens a font, using font type and font file name. |
| [open(FontType fontType, byte[] fontData)](#open-com.aspose.font.FontType-byte---) | Opens a font, using font type and font data byte array. |
### FontFactory() {#FontFactory--}
```
public FontFactory()
```


Constructor

### open(FontDefinition fontDefinition) {#open-com.aspose.font.FontDefinition-}
```
public Font open(FontDefinition fontDefinition)
```


Opens a font, using FontDefinition object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontDefinition | [FontDefinition](../../com.aspose.font/fontdefinition) | Font definition object. |

**Returns:**
[Font](../../com.aspose.font/font) - Font loaded.
### open(FontType fontType, StreamSource fontStreamSource) {#open-com.aspose.font.FontType-com.aspose.font.StreamSource-}
```
public Font open(FontType fontType, StreamSource fontStreamSource)
```


Opens a font, using font type and stream source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) | Font type. |
| fontStreamSource | [StreamSource](../../com.aspose.font/streamsource) | Stream source for font. |

**Returns:**
[Font](../../com.aspose.font/font) - Font loaded.
### open(FontType fontType, String fileName) {#open-com.aspose.font.FontType-java.lang.String-}
```
public Font open(FontType fontType, String fileName)
```


Opens a font, using font type and font file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) | Font type. |
| fileName | java.lang.String | Font file name. |

**Returns:**
[Font](../../com.aspose.font/font) - Font loaded.
### open(FontType fontType, byte[] fontData) {#open-com.aspose.font.FontType-byte---}
```
public Font open(FontType fontType, byte[] fontData)
```


Opens a font, using font type and font data byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontType | [FontType](../../com.aspose.font/fonttype) | Font type. |
| fontData | byte[] | Byte array to load font from. |

**Returns:**
[Font](../../com.aspose.font/font) - Font loaded.
