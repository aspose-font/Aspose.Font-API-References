---
title: AddMultiLanguageNames
second_title: Aspose.Font لمرجع .NET API
description: استخراج كافة السلاسل متعددة اللغات من تمريرmlNames الكائن و ينشئ بنية NameRecord متوافقة لكل سلسلة مستخرجة باستخدام معلمات التي تم تمريرهاplatformId وplatformSpecificId وnameId . قيمة الحقل languageID مستخرجة منmlNames هدف. يتم إضافة سجل جديد تم إنشاؤه للتو إلى الجدول. إذا تم العثور على السجل الذي يتزامن مع الحقل الذي تم إنشاؤه للتو بواسطة معرف النظام الأساسي  معرّف النظام الأساسي  معرّف الاسم  واللغة ID  فلن تتم إضافة سجل جديد تم إنشاؤه وسيتم تحديث بيانات السلسلة فقط للسجل الحالي.
type: docs
weight: 10
url: /ar/net/aspose.font.ttftables/ttfnametable/addmultilanguagenames/
---
## TtfNameTable.AddMultiLanguageNames method

استخراج كافة السلاسل متعددة اللغات من تمرير*mlNames* الكائن و ينشئ بنية NameRecord متوافقة لكل سلسلة مستخرجة باستخدام معلمات التي تم تمريرها*platformId* و*platformSpecificId* و*nameId* . قيمة الحقل languageID مستخرجة من*mlNames* هدف. يتم إضافة سجل جديد تم إنشاؤه للتو إلى الجدول. إذا تم العثور على السجل الذي يتزامن مع الحقل الذي تم إنشاؤه للتو بواسطة معرف النظام الأساسي ، معرّف النظام الأساسي ، معرّف الاسم ، واللغة ID ، فلن تتم إضافة سجل جديد تم إنشاؤه وسيتم تحديث بيانات السلسلة فقط للسجل الحالي.

```csharp
public void AddMultiLanguageNames(MultiLanguageString mlNames, PlatformId platformId, 
    ushort platformSpecificId, NameId nameId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| mlNames | MultiLanguageString | سلسلة متعددة اللغات |
| platformId | PlatformId | معرّف النظام الأساسي |
| platformSpecificId | UInt16 | معرّف الترميز الخاص بالمنصة |
| nameId | NameId | معرف الاسم ، فئة السلسلة المنطقية ، محدد بواسطة[`NameId`](../../ttfnametable.nameid) تعداد |

### أنظر أيضا

* class [MultiLanguageString](../../../aspose.font/multilanguagestring)
* enum [PlatformId](../../ttfnametable.platformid)
* enum [NameId](../../ttfnametable.nameid)
* class [TtfNameTable](../../ttfnametable)
* مساحة الاسم [Aspose.Font.TtfTables](../../ttfnametable)
* المجسم [Aspose.Font](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Font.dll -->