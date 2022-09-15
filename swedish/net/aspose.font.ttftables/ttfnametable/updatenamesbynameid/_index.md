---
title: UpdateNamesByNameId
second_title: Aspose.Font för .NET API-referens
description: Väljer alla poster som relaterade till logisk strängkategori specificerad av parameter nameId och uppdaterar namnfältet strängdata i dessa poster. Fält relaterade till plattform plattformsID plattformsspecifikt kodningsID och språk språkID påverkas inte av denna metod. Endast namnsträngsdata ersätts med ett nytt namn. Använd den här metoden med försiktighet eftersom den kommer att ersätta ursprungliga namn för alla plattformar och språk relaterat till nameId. Det kan skapa konflikter för fall då originalnamnen hade olika värden orsakar ersätt operation ändrar alla dessa värden med en ny singel. Och detta nya värde kan ha en logisk inkonsekvens med vissa plattformar och språk. Den här metoden är användbar för fall där originalnamnet har en enda representation för alla plattformar och språk till exempel när namnsträngsdata är på engelska.
type: docs
weight: 100
url: /sv/net/aspose.font.ttftables/ttfnametable/updatenamesbynameid/
---
## TtfNameTable.UpdateNamesByNameId method

Väljer alla poster som relaterade till logisk strängkategori, specificerad av parameter nameId och uppdaterar namnfältet (strängdata) i dessa poster. Fält relaterade till plattform (plattforms-ID, plattformsspecifikt kodnings-ID) och språk (språk-ID) påverkas inte av denna metod. Endast namnsträngsdata ersätts med ett nytt namn. Använd den här metoden med försiktighet, eftersom den kommer att ersätta ursprungliga namn för alla plattformar och språk, relaterat till nameId. Det kan skapa konflikter för fall då originalnamnen hade olika värden, orsakar ersätt operation ändrar alla dessa värden med en ny singel. Och detta nya värde kan ha en logisk inkonsekvens med vissa plattformar och språk. Den här metoden är användbar för fall där originalnamnet har en enda representation för alla plattformar och språk, till exempel när namnsträngsdata är på engelska.

```csharp
public void UpdateNamesByNameId(NameId nameId, string newName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nameId | NameId | Namnidentifierare, logisk strängkategori, specificerad av[`NameId`](../../ttfnametable.nameid) uppräkning |
| newName | String | Nytt namn eller ny strängdata |

### Se även

* enum [NameId](../../ttfnametable.nameid)
* class [TtfNameTable](../../ttfnametable)
* namnutrymme [Aspose.Font.TtfTables](../../ttfnametable)
* hopsättning [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->