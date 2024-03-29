---
title: GetGlyphComponentsById
second_title: Aspose.Font för .NET API-referens
description: Får en glyf efter glyfidentifierare godkänd och fyller godkänd lista med glyfidentifierare med komponenterna av denna glyph. Glyfid är ett unikt nummer för en glyf vilket är teckensnittsberoende. TTF TeckensnittsglyphidGlyphStringIdaspose.font.glyphs/glyphstringid klass eller GlyphUInt32Idaspose.font.glyphs/glyphuint32id  class. Namn sträng glyphadressering stöds för TTFteckensnitt via Posttabellmappning. Om CFFteckensnittet är inuti används CFFstrukturerna för att adressera glyfer efter namn.
type: docs
weight: 190
url: /sv/net/aspose.font.ttf/ttffont/getglyphcomponentsbyid/
---
## GetGlyphComponentsById(GlyphId, GlyphIdList) {#getglyphcomponentsbyid}

Får en glyf efter glyfidentifierare godkänd och fyller godkänd lista med glyfidentifierare med komponenterna av denna glyph. Glyf-id är ett unikt nummer för en glyf, vilket är teckensnittsberoende. TTF Teckensnittsglyph-id[`GlyphStringId`](../../../aspose.font.glyphs/glyphstringid)) klass eller ([`GlyphUInt32Id`](../../../aspose.font.glyphs/glyphuint32id) ) class. Namn (sträng) glyph-adressering stöds för TTF-teckensnitt via Post-tabellmappning. Om CFF-teckensnittet är inuti, används CFF-strukturerna för att adressera glyfer efter namn.

```csharp
public virtual void GetGlyphComponentsById(GlyphId id, GlyphIdList componentsToPopulate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | GlyphId | Glyf-id. |
| componentsToPopulate | GlyphIdList | Lista över glyfidentifierare att fylla. |

### Anmärkningar

Tomma samlingskomponenterToPopulate ska skickas som kommer att innehålla id-lista för glyfkomponenter.

### Se även

* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* class [GlyphIdList](../../../aspose.font.glyphs/glyphidlist)
* class [TtfFont](../../ttffont)
* namnutrymme [Aspose.Font.Ttf](../../ttffont)
* hopsättning [Aspose.Font](../../../)

---

## GetGlyphComponentsById(string, GlyphIdList) {#getglyphcomponentsbyid_1}

Får en glyf efter glyfnamn skickad och fyller godkänd lista med glyfidentifierare med komponenterna av denna glyf.

```csharp
public void GetGlyphComponentsById(string glyphName, GlyphIdList componentsToPopulate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| glyphName | String | Glyfnamn. |
| componentsToPopulate | GlyphIdList | Lista över glyfidentifierare att fylla. |

### Anmärkningar

Tomma samlingskomponenterToPopulate ska skickas som kommer att innehålla id-lista för glyfkomponenter.

### Se även

* class [GlyphIdList](../../../aspose.font.glyphs/glyphidlist)
* class [TtfFont](../../ttffont)
* namnutrymme [Aspose.Font.Ttf](../../ttffont)
* hopsättning [Aspose.Font](../../../)

---

## GetGlyphComponentsById(uint, GlyphIdList) {#getglyphcomponentsbyid_2}

Får en glyf efter glyfindex godkänd och fyller godkänd lista med glyfidentifierare med komponenterna av denna glyf.

```csharp
public void GetGlyphComponentsById(uint id, GlyphIdList componentsToPopulate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | UInt32 | Glyfindex. |
| componentsToPopulate | GlyphIdList | Lista över glyfidentifierare att fylla. |

### Anmärkningar

Tomma samlingskomponenterToPopulate ska skickas som kommer att innehålla id-lista för glyfkomponenter.

### Se även

* class [GlyphIdList](../../../aspose.font.glyphs/glyphidlist)
* class [TtfFont](../../ttffont)
* namnutrymme [Aspose.Font.Ttf](../../ttffont)
* hopsättning [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
