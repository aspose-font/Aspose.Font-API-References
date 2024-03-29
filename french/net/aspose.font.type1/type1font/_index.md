---
title: Type1Font
second_title: Référence de l'API Aspose.Font pour .NET
description: Représente la police Type1.
type: docs
weight: 1060
url: /fr/net/aspose.font.type1/type1font/
---
## Type1Font class

Représente la police Type1.

```csharp
public class Type1Font : Font
```

## Propriétés

| Nom | La description |
| --- | --- |
| override [Encoding](../../aspose.font.type1/type1font/encoding) { get; } | Obtient l'encodage de la police. |
| override [FontDefinition](../../aspose.font.type1/type1font/fontdefinition) { get; } | Obtient la définition de la police. |
| override [FontFamily](../../aspose.font.type1/type1font/fontfamily) { get; set; } | Obtient la famille de polices. Le setter de famille de polices n'est pas encore implémenté. |
| override [FontName](../../aspose.font.type1/type1font/fontname) { get; set; } | Obtient le nom de la police. Le paramètre de nom de police n'est pas encore implémenté. |
| override [FontNames](../../aspose.font.type1/type1font/fontnames) { get; } | Obtient les noms de police. |
| [FontSaver](../../aspose.font/font/fontsaver) { get; } | Obtient la fonctionnalité d'enregistrement des polices. |
| override [FontStyle](../../aspose.font.type1/type1font/fontstyle) { get; } | Obtient le style de police. Il s'agit d'une valeur calculée et représentée en type généralisé. |
| override [FontType](../../aspose.font.type1/type1font/fonttype) { get; } | Obtient le type de police. Renvoie la valeur FontType.Type1. |
| [GlyphAccessor](../../aspose.font/font/glyphaccessor) { get; } | Accesseur de glyphe de police. Récupère les glyphes et les identifiants de glyphe. |
| override [GlyphIdType](../../aspose.font.type1/type1font/glyphidtype) { get; } | Spécification du type d'identifiant de glyphe. |
| override [Metrics](../../aspose.font.type1/type1font/metrics) { get; } | Obtient les métriques de police. |
| override [NumGlyphs](../../aspose.font.type1/type1font/numglyphs) { get; } | Obtient le nombre de glyphes dans la police. |
| override [PostscriptNames](../../aspose.font.type1/type1font/postscriptnames) { get; } | Obtient les noms de police postscript. |
| override [Style](../../aspose.font.type1/type1font/style) { get; set; } | Obtient le style de police. Il s'agit d'une valeur de chaîne brute fournie par le fichier de police. Le paramètre de style n'est pas encore implémenté. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Convert](../../aspose.font.type1/type1font/convert)(FontType) | Convertit la police dans un autre format. |
| override [GetAllGlyphIds](../../aspose.font.type1/type1font/getallglyphids)() | Renvoie un tableau de tous les identifiants de glyphe, disponibles dans la police. L'identifiant de glyphe est un numéro unique pour un glyphe, qui dépend du type de police. Type1 L'identifiant de glyphe de police peut être une instance de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) classe ou ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |
| override [GetGlyphById](../../aspose.font.type1/type1font/getglyphbyid#getglyphbyid)(GlyphId) | Renvoie le glyphe par identifiant de glyphe. L'identifiant de glyphe est un numéro unique pour un glyphe, qui dépend du type de police. Type1 L'identifiant de glyphe de police peut être une instance de ([`GlyphStringId`](../../aspose.font.glyphs/glyphstringid)) classe ou ([`GlyphUInt32Id`](../../aspose.font.glyphs/glyphuint32id) classe. |
| virtual [GetGlyphById](../../aspose.font.type1/type1font/getglyphbyid#getglyphbyid_1)(string) | Renvoie glyphe par identifiant de glyphe. |
| [GetGlyphById](../../aspose.font.type1/type1font/getglyphbyid#getglyphbyid_2)(uint) | Renvoie glyphe par identifiant de glyphe. |
| virtual [GetGlyphsForText](../../aspose.font/font/getglyphsfortext)(string) | Obtient la représentation des glyphes pour le texte. |
| virtual [Save](../../aspose.font/font/save)(Stream) | Enregistre la police dans son format d'origine. |
| virtual [Save](../../aspose.font/font/save)(string) | Enregistre la police dans son format d'origine. |
| [SaveToFormat](../../aspose.font/font/savetoformat)(Stream, FontSavingFormats) | Enregistre la police dans le format spécifié. |

### Voir également

* class [Font](../../aspose.font/font)
* espace de noms [Aspose.Font.Type1](../../aspose.font.type1)
* Assemblée [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
