---
title: "Clase Aspose::Font::AssemblyConstants"
linktitle: "AssemblyConstants"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::AssemblyConstants class. Define las constantes que participan en la verificación de licencia del componente. Estas solían definirse directamente como atributos de ensamblado, pero las trasladé a una clase separada porque en .NET Compact Framework no puedo acceder a los atributos de ensamblado. Ahora el código de licenciamiento, cuando se compila para .NET Compact Framework, usa estas constantes en lugar de los atributos de ensamblado en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font/assemblyconstants/
---
## AssemblyConstants class


Define las constantes que participan en la verificación de licencia del componente. Estas solían definirse directamente como atributos de ensamblado, pero las trasladé a una clase separada porque en .NET Compact Framework no puedo acceder a los atributos de ensamblado. Ahora el código de licenciamiento, cuando se compila para .NET Compact Framework, utiliza estas constantes en lugar de los atributos de ensamblado.

```cpp
class AssemblyConstants
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AssemblyConstants](./assemblyconstants/)() |  |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Family](./family/) |  |
| static [Platform](./platform/) |  |
| static [Product](./product/) | Esto se usa por el código de licencia de **Aspose** para verificar que la licencia es para el producto correcto. |
| static [ReleaseDate](./releasedate/) | Esto se usa por el código de licencia de **Aspose** para comprobar la expiración de la suscripción. Necesitas establecer esto a la fecha en que publiques una versión o una corrección. |
| static [Title](./title/) |  |
| static [Version](./version/) | La versión del ensamblado. |
## Ver también

* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
