---
title: AddName
second_title: Référence de l'API Aspose.Font pour .NET
description: Ajoute une entrée dans la table. La catégorie de données de chaîne à ajouter est spécifiée parname paramètre.
type: docs
weight: 20
url: /fr/net/aspose.font.ttftables/ttfnametable/addname/
---
## TtfNameTable.AddName method

Ajoute une entrée dans la table. La catégorie de données de chaîne à ajouter est spécifiée par*name* paramètre.

```csharp
public void AddName(NameId nameId, PlatformId platformId, int platformSpecificId, int languageId, 
    string name)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| nameId | NameId | Identificateur de nom, catégorie de chaîne logique, spécifié par[`NameId`](../../ttfnametable.nameid) énumération |
| platformId | PlatformId | Identifiant de la plate-forme |
| platformSpecificId | Int32 | Identifiant d'encodage spécifique à la plate-forme. Veuillez utiliser la valeur de l'une de ces énumérations -[`UnicodePlatformSpecificId`](../../ttfnametable.unicodeplatformspecificid) ,[`MacPlatformSpecificId`](../../ttfnametable.macplatformspecificid) , [`MSPlatformSpecificId`](../../ttfnametable.msplatformspecificid). L'énumération à utiliser est définie par le contexte (*platformId* paramètre) |
| languageId | Int32 | Identificateur de langue. Veuillez utiliser la valeur de[`MSLanguageId`](../../ttfnametable.mslanguageid) ou [`MacLanguageId`](../../ttfnametable.maclanguageid) les énumérations dépendent du contexte, défini par*platformId* paramètre. |
| name | String | Données de chaîne réelles |

### Voir également

* enum [NameId](../../ttfnametable.nameid)
* enum [PlatformId](../../ttfnametable.platformid)
* class [TtfNameTable](../../ttfnametable)
* espace de noms [Aspose.Font.TtfTables](../../ttfnametable)
* Assemblée [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
