---
title: UpdateNamesByNameId
second_title: Aspose.Font for .NET API Referansı
description: nameId parametresi tarafından belirtilen mantıksal dize kategorisiyle ilgili tüm kayıtları seçer ve bu kayıtlarda ad alanını dize verileri günceller. Platform platformID Platforma özgü kodlama kimliği ve dil Dil Kimliği ile ilgili alanlar bu yöntemden etkilenmez. Yalnızca ad dizesi verileri yeni bir adla değiştirilir. Bu yöntemi dikkatli kullanın çünkü ile nameId ile ilgili tüm platformlar ve diller için orijinal adların yerini alacaktır. Orijinal adların farklı değerlere sahip olduğu durumlarda çakışma yapabilir değiştirme işleminin tüm bu değerleri yeni tek bir değerle değiştirmesine neden olabilir. Ve bu yeni değerin bazı platformları ve dilleri ile mantıksal bir tutarsızlığı olabilir. Bu yöntem orijinal adın tüm platformlar ve diller için tek bir temsile sahip olduğu durumlarda örneğin ad dizesi verilerinin İngilizce dilinde olduğu durumlarda yararlıdır.
type: docs
weight: 100
url: /tr/net/aspose.font.ttftables/ttfnametable/updatenamesbynameid/
---
## TtfNameTable.UpdateNamesByNameId method

nameId parametresi tarafından belirtilen mantıksal dize kategorisiyle ilgili tüm kayıtları seçer ve bu kayıtlarda ad alanını (dize verileri) günceller. Platform (platformID, Platforma özgü kodlama kimliği) ve dil (Dil Kimliği) ile ilgili alanlar bu yöntemden etkilenmez. Yalnızca ad dizesi verileri yeni bir adla değiştirilir. Bu yöntemi dikkatli kullanın, çünkü ile nameId ile ilgili tüm platformlar ve diller için orijinal adların yerini alacaktır. Orijinal adların farklı değerlere sahip olduğu durumlarda çakışma yapabilir, değiştirme işleminin tüm bu değerleri yeni tek bir değerle değiştirmesine neden olabilir. Ve bu yeni değerin bazı platformları ve dilleri ile mantıksal bir tutarsızlığı olabilir. Bu yöntem, orijinal adın tüm platformlar ve diller için tek bir temsile sahip olduğu durumlarda, örneğin, ad dizesi verilerinin İngilizce dilinde olduğu durumlarda yararlıdır.

```csharp
public void UpdateNamesByNameId(NameId nameId, string newName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| nameId | NameId | Ad tanımlayıcı, mantıksal dize kategorisi, tarafından belirtilen[`NameId`](../../ttfnametable.nameid) numaralandırma |
| newName | String | Yeni ad veya yeni dize verileri |

### Ayrıca bakınız

* enum [NameId](../../ttfnametable.nameid)
* class [TtfNameTable](../../ttfnametable)
* ad alanı [Aspose.Font.TtfTables](../../ttfnametable)
* toplantı [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->
