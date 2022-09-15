---
title: FontDefinition
second_title: Référence de l'API Aspose.Font pour .NET
description: Représente la définition du jeu de fichiers de polices. Cette classe contient des champs qui ne sont pas liés aux données internes de la police. Ces champs décrivent le placement de la police et dautres données nécessaires pour charger la police à partir de une source de police fichier mémoire etc..
type: docs
weight: 540
url: /fr/net/aspose.font.sources/fontdefinition/
---
## FontDefinition class

Représente la définition du jeu de fichiers de polices. Cette classe contient des champs qui ne sont pas liés aux données internes de la police. Ces champs décrivent le placement de la police et d'autres données nécessaires pour charger la police à partir de une source de police (fichier, mémoire, etc.).

```csharp
public class FontDefinition
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [FontDefinition](fontdefinition#constructor)(FontType, FontFileDefinition) | Crée une définition de police à fichier unique. |
| [FontDefinition](fontdefinition#constructor_1)(FontType, FontFileDefinition[]) | Crée une définition de police multi-fichiers. |
| [FontDefinition](fontdefinition#constructor_2)(FontType, StreamSource) | Crée une définition de police à fichier unique. |
| [FontDefinition](fontdefinition#constructor_3)(FontType, string, StreamSource) | Crée une définition de police à fichier unique. |
| [FontDefinition](fontdefinition#constructor_6)(string, FontType, FontFileDefinition) | Crée une définition de police à fichier unique. |
| [FontDefinition](fontdefinition#constructor_4)(MultiLanguageString, MultiLanguageString, FontType, FontFileDefinition) | Crée une définition de police multi-fichiers. |
| [FontDefinition](fontdefinition#constructor_5)(MultiLanguageString, MultiLanguageString, FontType, FontFileDefinition[]) | Crée une définition de police multi-fichiers. |
| [FontDefinition](fontdefinition#constructor_7)(string, FontType, string, StreamSource) | Crée une définition de police à fichier unique. |
| [FontDefinition](fontdefinition#constructor_8)(string, string, FontType, FontFileDefinition) | Crée une définition de police à fichier unique. |
| [FontDefinition](fontdefinition#constructor_9)(string, string, FontType, FontFileDefinition[]) | Crée une définition de police multi-fichiers. |

## Propriétés

| Nom | La description |
| --- | --- |
| [FileDefinitions](../../aspose.font.sources/fontdefinition/filedefinitions) { get; } | Obtient la collection de définitions de fichiers. |
| virtual [FontName](../../aspose.font.sources/fontdefinition/fontname) { get; } | Renvoie le nom de la police. |
| virtual [FontNames](../../aspose.font.sources/fontdefinition/fontnames) { get; } | Obtient les noms de police sous forme de[`MultiLanguageString`](../../aspose.font/multilanguagestring) . |
| [FontType](../../aspose.font.sources/fontdefinition/fonttype) { get; } | Obtient le type de police. |
| virtual [PostscriptName](../../aspose.font.sources/fontdefinition/postscriptname) { get; } | Obtient le nom de la police postscript. |
| [PostscriptNames](../../aspose.font.sources/fontdefinition/postscriptnames) { get; } | Obtient les noms de police postscript sous forme de[`MultiLanguageString`](../../aspose.font/multilanguagestring) . |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Open](../../aspose.font.sources/fontdefinition/open#open)(StreamSource, FontType) | Renvoie FontDefinition pour la source du flux de polices et le type de police. |
| static [Open](../../aspose.font.sources/fontdefinition/open#open_1)(string, FontType) | Renvoie FontDefinition pour le fichier de police et le type de police. |

### Voir également

* espace de noms [Aspose.Font.Sources](../../aspose.font.sources)
* Assemblée [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->