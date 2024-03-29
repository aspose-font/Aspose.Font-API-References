---
title: IFontCharactersMerger
second_title: Aspose.Font per Riferimento API .NET
description: Dichiara la funzionalità degli helper per unire i font TrueType. Font passato dal parametro font1 considerato primario. Significa che molte caratteristiche di  relative al font unito finale come metriche struttura di codifica e altro verranno prese da questo font primario.
type: docs
weight: 750
url: /it/net/aspose.font.ttfhelpers/ifontcharactersmerger/
---
## IFontCharactersMerger interface

Dichiara la funzionalità degli helper per unire i font TrueType. Font passato dal parametro font1 considerato primario. Significa che molte caratteristiche di , relative al font unito finale, come metriche, struttura di codifica e altro, verranno prese da questo font primario.

```csharp
public interface IFontCharactersMerger
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [MergeFonts](../../aspose.font.ttfhelpers/ifontcharactersmerger/mergefonts#mergefonts)(GlyphId[], GlyphId[], string) | Unisce i caratteri in base agli elenchi di glifi passati. Cerca un codice carattere per ogni glifo passato e aggiunge il codice carattere trovato con il glifo corrispondente nel nuovo carattere risultante. |
| [MergeFonts](../../aspose.font.ttfhelpers/ifontcharactersmerger/mergefonts#mergefonts_1)(IDictionary&lt;uint, GlyphId&gt;, IDictionary&lt;uint, GlyphId&gt;, string) | Questa versione del metodo progettata per i casi in cui si desidera impostare in modo esplicito i codici dei caratteri per i glifi nel carattere risultante. Non è obbligatorio che il codice per il glifo fornito sia incluso nel carattere originale. Il senso del codice passato è che sarà associato all'identificatore di glifo corrispondente nel font risultante. Quindi, la regola per elaborare ogni coppia passata dal parametro del dizionario [codice, identificatore di glifo] è che solo l'identificatore di glifo sarà preso dal carattere originale e quindi sarà collegato con il codice corrispondente nel carattere risultante. Può essere utile quando alcuni i codici del primo font sono in conflitto con gli stessi codici del secondo font. |
| [MergeFonts](../../aspose.font.ttfhelpers/ifontcharactersmerger/mergefonts#mergefonts_2)(uint[], uint[], string) | Unisce i font in base agli elenchi di codici carattere passati. Per creare il font risultante desiderato, basta passare i codici simbolo dai font originali che vuoi includere nel font risultante. I glifi relativi ai codici passati verranno trovati automaticamente. Ad esempio, se vuoi includere nel font risultante i glifi relativi alle lettere A e B da primo font e glifi, relativi alle lettere C e D dal secondo font, chiama questo metodo come questo: |

### Guarda anche

* spazio dei nomi [Aspose.Font.TtfHelpers](../../aspose.font.ttfhelpers)
* assemblea [Aspose.Font](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
