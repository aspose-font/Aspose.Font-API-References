---
title: UpdateNamesByNameId
second_title: Aspose.Font für .NET-API-Referenz
description: Wählt alle Datensätze aus die sich auf die logische StringKategorie beziehen die durch den Parameter nameId angegeben ist und aktualisiert das Namensfeld StringDaten in diesen Datensätzen. Felder die sich auf die Plattform PlattformID plattformspezifische CodierungsID und die Sprache SprachID beziehen sind von dieser Methode nicht betroffen. Nur Namenszeichenfolgendaten werden durch einen neuen Namen ersetzt. Verwenden Sie diese Methode mit Vorsicht da sie die ursprünglichen Namen für alle Plattformen und Sprachen ersetzt die mit nameId in Verbindung bringen. Es kann zu Konflikten kommen wenn die ursprünglichen Namen unterschiedliche Werte hatten da die Ersetzungsoperation alle diese Werte durch neue einzelne Werte ändert. Und dieser neue Wert kann eine logische Inkonsistenz mit einigen Plattformen und Sprachen haben. Diese Methode ist nützlich für Fälle in denen der ursprüngliche Name eine einzige Darstellung für alle Plattformen und Sprachen hat z. B.  wenn die Daten der Namenszeichenfolge in englischer Sprache vorliegen.
type: docs
weight: 100
url: /de/net/aspose.font.ttftables/ttfnametable/updatenamesbynameid/
---
## TtfNameTable.UpdateNamesByNameId method

Wählt alle Datensätze aus, die sich auf die logische String-Kategorie beziehen, die durch den Parameter nameId angegeben ist, und aktualisiert das Namensfeld (String-Daten) in diesen Datensätzen. Felder, die sich auf die Plattform (Plattform-ID, plattformspezifische Codierungs-ID) und die Sprache (Sprach-ID) beziehen, sind von dieser Methode nicht betroffen. Nur Namenszeichenfolgendaten werden durch einen neuen Namen ersetzt. Verwenden Sie diese Methode mit Vorsicht, da sie die ursprünglichen Namen für alle Plattformen und Sprachen ersetzt, die mit nameId in Verbindung bringen. Es kann zu Konflikten kommen, wenn die ursprünglichen Namen unterschiedliche Werte hatten, da die Ersetzungsoperation alle diese Werte durch neue einzelne Werte ändert. Und dieser neue Wert kann eine logische Inkonsistenz mit einigen Plattformen und Sprachen haben. Diese Methode ist nützlich für Fälle, in denen der ursprüngliche Name eine einzige Darstellung für alle Plattformen und Sprachen hat, z. B. , wenn die Daten der Namenszeichenfolge in englischer Sprache vorliegen.

```csharp
public void UpdateNamesByNameId(NameId nameId, string newName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nameId | NameId | Namensbezeichner, Kategorie der logischen Zeichenfolge, angegeben durch[`NameId`](../../ttfnametable.nameid) Aufzählung |
| newName | String | Neuer Name oder neue Zeichenfolgendaten |

### Siehe auch

* enum [NameId](../../ttfnametable.nameid)
* class [TtfNameTable](../../ttfnametable)
* namensraum [Aspose.Font.TtfTables](../../ttfnametable)
* Montage [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->