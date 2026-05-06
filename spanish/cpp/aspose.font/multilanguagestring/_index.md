---
title: "Aspose::Font::MultiLanguageString clase"
linktitle: "MultiLanguageString"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::MultiLanguageString clase. Representa una cadena multilingüe en C++."
type: docs
weight: 2800
url: /es/cpp/aspose.font/multilanguagestring/
---
## MultiLanguageString class


Representa una cadena multilingüe.

```cpp
class MultiLanguageString : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddLanguageString](./addlanguagestring/)(System::String, int32_t) | Agrega una cadena de un idioma específico. |
| [ContainsString](./containsstring/)(System::String) | Devuelve true si la cadena está presente dentro de todas las cadenas de idioma. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve true si los objetos se consideran iguales. |
| [get_IsEmpty](./get_isempty/)() | True, si [MultiLanguageString](./) no tiene cadenas de idiomas. |
| [GetAllLanguageIds](./getalllanguageids/)() | Obtiene los identificadores de idioma para todas las cadenas o una matriz vacía si no hay cadenas presentes. |
| [GetAllStrings](./getallstrings/)() | Devuelve todas las cadenas de todos los idiomas. |
| [GetEnglishString](./getenglishstring/)() | Devuelve la cadena en inglés si se encuentra. De lo contrario, devuelve la primera cadena que no sea en inglés. |
| [GetHashCode](./gethashcode/)() const override | Implementación de GetHashCode. |
| [GetStringForLanguageId](./getstringforlanguageid/)(int32_t) | Devuelve la cadena relacionada con el identificador de idioma proporcionado, si se encuentra. Cadena vacía en caso contrario. |
| [MultiLanguageString](./multilanguagestring/)() | Crea una cadena multilingüe vacía. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
