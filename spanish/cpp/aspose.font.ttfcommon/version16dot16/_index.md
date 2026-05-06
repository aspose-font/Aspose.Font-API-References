---
title: "Aspose::Font::TtfCommon::Version16Dot16 clase"
linktitle: "Version16Dot16"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::TtfCommon::Version16Dot16 clase. Representa el tipo de datos Version16Dot16 en C++."
type: docs
weight: 100
url: /es/cpp/aspose.font.ttfcommon/version16dot16/
---
## Version16Dot16 class


Representa el tipo de datos [Version16Dot16](./).

```cpp
class Version16Dot16 : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Crea una copia del objeto [Version16Dot16](./). |
| [get_MajorNumber](./get_majornumber/)() const | Obtiene el número de versión mayor. El valor solo tiene sentido en notación hexadecimal, por ejemplo la versión 0.5 para 'maxp' en los archivos de fuentes reales son 4 bytes: {0, 0, 80, 0}, que tiene la representación hexadecimal 0x00005000. Después de leer esta versión del archivo de fuentes, los números mayor y menor para el objeto [Version16Dot16](./) serán 0 y 20480 respectivamente. Y estos valores en forma hexadecimal son 0x0000 y 0x5000. |
| [get_MinorNumber](./get_minornumber/)() const | Obtiene el número de versión menor. El valor solo tiene sentido en notación hexadecimal, por ejemplo la versión 0.5 para 'maxp' en los archivos de fuentes reales son 4 bytes: {0, 0, 80, 0}, que tiene la representación hexadecimal 0x00005000. Después de leer esta versión del archivo de fuentes, los números mayor y menor para el objeto [Version16Dot16](./) serán 0 y 20480 respectivamente. Y estos valores en forma hexadecimal son 0x0000 y 0x5000. |
| [get_RawBytes](./get_rawbytes/)() | Obtiene todos los bits sin procesar del número de versión [Version16Dot16](./) como una matriz de bytes de tamaño 4 bytes. |
| [set_MajorNumber](./set_majornumber/)(uint16_t) | Establece el número de versión mayor. El valor solo tiene sentido en notación hexadecimal, por ejemplo la versión 0.5 para 'maxp' en los archivos de fuentes reales son 4 bytes: {0, 0, 80, 0}, que tiene la representación hexadecimal 0x00005000. Después de leer esta versión del archivo de fuentes, los números mayor y menor para el objeto [Version16Dot16](./) serán 0 y 20480 respectivamente. Y estos valores en forma hexadecimal son 0x0000 y 0x5000. |
| [set_MinorNumber](./set_minornumber/)(uint16_t) | Establece el número de versión menor. El valor solo tiene sentido en notación hexadecimal, por ejemplo la versión 0.5 para 'maxp' en los archivos de fuentes reales son 4 bytes: {0, 0, 80, 0}, que tiene la representación hexadecimal 0x00005000. Después de leer esta versión del archivo de fuentes, los números mayor y menor para el objeto [Version16Dot16](./) serán 0 y 20480 respectivamente. Y estos valores en forma hexadecimal son 0x0000 y 0x5000. |
| [ToString](./tostring/)() const override | Devuelve el valor de la versión como una cadena formateada. Por ejemplo "0.5", "1.1", "3.0", etc. |
| [Version16Dot16](./version16dot16/)() | Constructor. |
| [Version16Dot16](./version16dot16/)(uint16_t, uint16_t) | Constructor. |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Font::TtfCommon](../)
* Library [Aspose.Font for C++](../../)
