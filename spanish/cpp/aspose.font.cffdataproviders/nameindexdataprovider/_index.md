---
title: "Clase Aspose::Font::CffDataProviders::NameIndexDataProvider"
linktitle: "NameIndexDataProvider"
second_title: "Aspose.Font para C++"
description: "Clase Aspose::Font::CffDataProviders::NameIndexDataProvider. Declara la funcionalidad para acceder a la estructura CFF Name INDEX en C++."
type: docs
weight: 500
url: /es/cpp/aspose.font.cffdataproviders/nameindexdataprovider/
---
## NameIndexDataProvider class


Declara funcionalidad para acceder a la estructura CFF Name INDEX.

```cpp
class NameIndexDataProvider : public Aspose::Font::CffDataProviders::ICffIndexDataProvider
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AddName](./addname/)(System::String) | Agrega un nombre de fuente a la estructura Name INDEX. Use este método con precaución porque cada nombre de fuente en la estructura CFF Name INDEX debe tener una estructura DICT correspondiente en el índice Top DICT según la especificación CFF. |
| virtual [get_Count](./get_count/)() | El número de objetos en la estructura CFF INDEX. |
| virtual [GetName](./getname/)(int32_t) | Obtiene el nombre de la fuente en el índice especificado. |
| virtual [GetRawBytes](./getrawbytes/)() | Obtiene todos los bytes de la estructura CFF INDEX. |
| virtual [idx_get](./idx_get/)(int32_t) | Obtiene/establece el nombre de la fuente en el índice especificado. |
| virtual [idx_set](./idx_set/)(int32_t, System::String) | Obtiene/establece el nombre de la fuente en el índice especificado. |
| virtual [RemoveName](./removename/)(int32_t) | Elimina el nombre en el índice especificado. Use este método con precaución porque cada nombre de fuente en la estructura CFF Name INDEX debe tener una estructura DICT correspondiente en el índice Top DICT según la especificación CFF. |
| virtual [SetName](./setname/)(System::String, int32_t) | Establece el nombre de la fuente en el índice especificado. |
## Ver también

* Class [ICffIndexDataProvider](../icffindexdataprovider/)
* Namespace [Aspose::Font::CffDataProviders](../)
* Library [Aspose.Font for C++](../../)
