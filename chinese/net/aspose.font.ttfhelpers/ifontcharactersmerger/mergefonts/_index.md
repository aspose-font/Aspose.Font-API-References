---
title: MergeFonts
second_title: Aspose.Font for .NET API 参考
description: 根据传递的字形列表合并字体 为传递的每个字形搜索字符代码并将找到的字符代码与对应的字形 添加到生成的新字体中
type: docs
weight: 10
url: /zh/net/aspose.font.ttfhelpers/ifontcharactersmerger/mergefonts/
---
## MergeFonts(GlyphId[], GlyphId[], string) {#mergefonts}

根据传递的字形列表合并字体。 为传递的每个字形搜索字符代码，并将找到的字符代码与对应的字形 添加到生成的新字体中。

```csharp
public TtfFont MergeFonts(GlyphId[] font1Glyphs, GlyphId[] font2Glyphs, string newFontName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| font1Glyphs | GlyphId[] | 第一个字体的字形列表 |
| font2Glyphs | GlyphId[] | 第二种字体的字形列表 |
| newFontName | String | 结果字体的所需名称 |

### 返回值

合并字体

### 也可以看看

* class [TtfFont](../../../aspose.font.ttf/ttffont)
* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* interface [IFontCharactersMerger](../../ifontcharactersmerger)
* 命名空间 [Aspose.Font.TtfHelpers](../../ifontcharactersmerger)
* 部件 [Aspose.Font](../../../)

---

## MergeFonts(uint[], uint[], string) {#mergefonts_2}

根据传递的字符代码列表合并字体。 要创建所需的结果字体，只需将要包含 的原始字体的符号代码传递到结果字体中。将自动找到与传递的代码相关的字形。 例如，如果您想将 中与字母A和B相关的字形包含到结果字体中，以及与第二个字体中的字母C和D相关的字形中，只需调用此方法这个：

```csharp
MergeFonts(new uint[] { 'A', 'B' }, new uint[] { 'C', 'D' }, "NewFont")
```

```csharp
public TtfFont MergeFonts(uint[] font1CharCodes, uint[] font2CharCodes, string newFontName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| font1CharCodes | UInt32[] | 从第一个字体获取的代码 |
| font2CharCodes | UInt32[] | 从第二种字体中获取的代码 |
| newFontName | String | 结果字体的所需名称 |

### 返回值

合并字体

### 也可以看看

* class [TtfFont](../../../aspose.font.ttf/ttffont)
* interface [IFontCharactersMerger](../../ifontcharactersmerger)
* 命名空间 [Aspose.Font.TtfHelpers](../../ifontcharactersmerger)
* 部件 [Aspose.Font](../../../)

---

## MergeFonts(IDictionary&lt;uint, GlyphId&gt;, IDictionary&lt;uint, GlyphId&gt;, string) {#mergefonts_1}

此方法版本专为您要明确设置结果字体中的字形字符代码的情况而设计。 您提供的字形代码不一定包含在原始字体中。传递 的代码的意义在于它将与结果字体中对应的字形标识符相关联。因此，处理字典参数 [code, glyph ideitifier] 传递的每个 对的规则是，只会从 原始字体中获取字形标识符，然后将其与结果字体中的对应代码链接。 在某些情况下会有所帮助第一种字体的代码与第二种字体的相同代码冲突。

```csharp
public TtfFont MergeFonts(IDictionary<uint, GlyphId> font1Dict, 
    IDictionary<uint, GlyphId> font2Dict, string newFontName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| font1Dict | IDictionary`2 | 字典与第一个字体的对[符号代码，字形标识符] |
| font2Dict | IDictionary`2 | 字典与来自第二种字体的对[符号代码，字形标识符] |
| newFontName | String | 结果字体的所需名称 |

### 返回值

合并字体

### 也可以看看

* class [TtfFont](../../../aspose.font.ttf/ttffont)
* class [GlyphId](../../../aspose.font.glyphs/glyphid)
* interface [IFontCharactersMerger](../../ifontcharactersmerger)
* 命名空间 [Aspose.Font.TtfHelpers](../../ifontcharactersmerger)
* 部件 [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
