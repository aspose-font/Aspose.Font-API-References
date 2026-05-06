---
title: "clase Aspose::Font::FontEnvironment"
linktitle: "FontEnvironment"
second_title: "Aspose.Font para C++"
description: "clase Aspose::Font::FontEnvironment. Proporciona información sobre el entorno y la plataforma actuales en C++."
type: docs
weight: 600
url: /es/cpp/aspose.font/fontenvironment/
---
## FontEnvironment class


Proporciona información sobre el entorno y la plataforma actuales.

```cpp
class FontEnvironment : public System::Object
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [ParsingStrictness](./parsingstrictness/) | Tipos de rigor de análisis. |
## Métodos

| Método | Descripción |
| --- | --- |
| static [get_CffCommonFontsSettings](./get_cffcommonfontssettings/)() | Configuraciones comunes a fuentes CFF. |
| static [get_Current](./get_current/)() | Obtiene el entorno actual. |
| [get_CurrentPlatformId](./get_currentplatformid/)() | Obtiene el identificador de la plataforma actual. |
| [get_FontSpecificEncodings](./get_fontspecificencodings/)() const | Almacena codificaciones específicas para fuentes conscientes del consumidor. Por ejemplo, los documentos PDF utilizan codificaciones específicas de Adobe Symbol y ZapfDingbats. |
| [get_Strictness](./get_strictness/)() const | Algunas fuentes pueden contener datos inesperados, características no especificadas o pueden estar recortadas de forma aproximada. |
| [set_Strictness](./set_strictness/)(FontEnvironment::ParsingStrictness) | Algunas fuentes pueden contener datos inesperados, características no especificadas o pueden estar recortadas de forma aproximada. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
