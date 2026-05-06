---
title: "Aspose::Font::CffDataProviders::CffUpdateStringIndexStrategy enum"
linktitle: "CffUpdateStringIndexStrategy"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::CffDataProviders::CffUpdateStringIndexStrategy enum. Especifica cómo agregar cadenas al almacenamiento CFF String INDEX. Cuando intentamos agregar alguna cadena al CFF String INDEX, puede haber una situación en la que esa cadena ya esté presente en String INDEX. Usando la opción SearchForDuplicates podemos forzar la búsqueda en String INDEX para detectar si esa cadena ya está presente o no. Este enfoque ahorra espacio en la estructura String INDEX, pero requiere más tiempo para agregar la cadena en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.font.cffdataproviders/cffupdatestringindexstrategy/
---
## CffUpdateStringIndexStrategy enum


Especifica cómo agregar cadenas al almacenamiento CFF String INDEX. Cuando intentamos agregar alguna cadena al CFF String INDEX, puede haber una situación en la que esa cadena ya esté presente en String INDEX. Usando la opción [SearchForDuplicates](./) podemos forzar la búsqueda en String INDEX para detectar si esa cadena ya está presente o no. Este enfoque ahorra espacio en la estructura String INDEX, pero requiere más tiempo para agregar la cadena.

```cpp
enum class CffUpdateStringIndexStrategy
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| SearchForDuplicates | 0 | Especifica que la búsqueda de la cadena a agregar debe realizarse en la estructura String INDEX para evitar agregar duplicados. |
| AddStringAsIs | 1 | Especifica que no se deben realizar comprobaciones de duplicados al agregar una cadena. Este enfoque funciona más rápido, pero puede resultar en un uso ineficiente de memoria para String INDEX. |

## Ver también

* Namespace [Aspose::Font::CffDataProviders](../)
* Library [Aspose.Font for C++](../../)
