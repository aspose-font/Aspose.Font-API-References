---
title: FontDefinition
second_title: Aspose.Font per Riferimento API .NET
description: Rappresenta la definizione del set di file di caratteri. Questa classe contiene campi che non sono correlati ai dati interni del font. Questi campi descrivono il posizionamento del font e altri dati necessari per caricare il font da una fonte di font file memoria ecc..
type: docs
weight: 540
url: /it/net/aspose.font.sources/fontdefinition/
---
## FontDefinition class

Rappresenta la definizione del set di file di caratteri. Questa classe contiene campi che non sono correlati ai dati interni del font. Questi campi descrivono il posizionamento del font e altri dati necessari per caricare il font da una fonte di font (file, memoria, ecc.).

```csharp
public class FontDefinition
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FontDefinition](fontdefinition#constructor)(FontType, FontFileDefinition) | Crea la definizione del carattere a file singolo. |
| [FontDefinition](fontdefinition#constructor_1)(FontType, FontFileDefinition[]) | Crea la definizione di font multifile. |
| [FontDefinition](fontdefinition#constructor_2)(FontType, StreamSource) | Crea la definizione del carattere a file singolo. |
| [FontDefinition](fontdefinition#constructor_3)(FontType, string, StreamSource) | Crea la definizione del carattere a file singolo. |
| [FontDefinition](fontdefinition#constructor_6)(string, FontType, FontFileDefinition) | Crea la definizione del carattere a file singolo. |
| [FontDefinition](fontdefinition#constructor_4)(MultiLanguageString, MultiLanguageString, FontType, FontFileDefinition) | Crea la definizione di font multifile. |
| [FontDefinition](fontdefinition#constructor_5)(MultiLanguageString, MultiLanguageString, FontType, FontFileDefinition[]) | Crea la definizione di font multifile. |
| [FontDefinition](fontdefinition#constructor_7)(string, FontType, string, StreamSource) | Crea la definizione del carattere a file singolo. |
| [FontDefinition](fontdefinition#constructor_8)(string, string, FontType, FontFileDefinition) | Crea la definizione del carattere a file singolo. |
| [FontDefinition](fontdefinition#constructor_9)(string, string, FontType, FontFileDefinition[]) | Crea la definizione di font multifile. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FileDefinitions](../../aspose.font.sources/fontdefinition/filedefinitions) { get; } | Ottiene la raccolta delle definizioni dei file. |
| virtual [FontName](../../aspose.font.sources/fontdefinition/fontname) { get; } | Restituisce il nome del carattere. |
| virtual [FontNames](../../aspose.font.sources/fontdefinition/fontnames) { get; } | Ottiene i nomi dei caratteri come a[`MultiLanguageString`](../../aspose.font/multilanguagestring) . |
| [FontType](../../aspose.font.sources/fontdefinition/fonttype) { get; } | Ottiene il tipo di carattere. |
| virtual [PostscriptName](../../aspose.font.sources/fontdefinition/postscriptname) { get; } | Ottiene il nome del carattere postscript. |
| [PostscriptNames](../../aspose.font.sources/fontdefinition/postscriptnames) { get; } | Ottiene i nomi dei caratteri PostScript come a[`MultiLanguageString`](../../aspose.font/multilanguagestring) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Open](../../aspose.font.sources/fontdefinition/open#open)(StreamSource, FontType) | Restituisce FontDefinition per l'origine del flusso di font e il tipo di font. |
| static [Open](../../aspose.font.sources/fontdefinition/open#open_1)(string, FontType) | Restituisce FontDefinition per il file del font e il tipo di font. |

### Guarda anche

* spazio dei nomi [Aspose.Font.Sources](../../aspose.font.sources)
* assemblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->