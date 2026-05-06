---
title: "Aspose::Font::Ttf::LicenseFlags clase"
linktitle: "LicenseFlags"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::Ttf::LicenseFlags clase. Representa un contenedor auxiliar para las banderas de incrustación de la tabla ''OS/2'' (campo fsType) en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.ttf/licenseflags/
---
## LicenseFlags class


Representa un contenedor auxiliar para los indicadores de incrustación de la tabla 'OS/2' (campo fsType).

```cpp
class LicenseFlags : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_FSType](./get_fstype/)() const | Obtiene el valor bruto de fsType de la tabla OS/2 o 0 si este campo no existe en la tabla. |
| [get_FSTypeAbsent](./get_fstypeabsent/)() const | Devuelve true si la bandera fsType está ausente en la tabla 'OS/2'. |
| [get_IsBitmapOnlyEmbedding](./get_isbitmaponlyembedding/)() | Detecta si fsType permite la incrustación BitmapOnly. |
| [get_IsEditableEmbedding](./get_iseditableembedding/)() | Detecta si fsType permite incrustación editable. |
| [get_IsInstallableEmbedding](./get_isinstallableembedding/)() | Detecta si fsType es una incrustación instalable. |
| [get_IsNoSubsettingEmbedding](./get_isnosubsettingembedding/)() | Detecta si fsType permite incrustación NoSubsetting. |
| [get_IsPreviewAndPrintEmbedding](./get_ispreviewandprintembedding/)() | Detecta si fsType permite incrustación de vista previa e impresión. |
| [get_IsReservedType](./get_isreservedtype/)() | Detecta si el bit reservado (bit 0) está activado para fsType. |
| [get_IsRestrictedLicenseEmbedding](./get_isrestrictedlicenseembedding/)() | Detecta si fsType es una incrustación restringida [License](../../aspose.font/license/). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font::Ttf](../)
* Library [Aspose.Font for C++](../../)
