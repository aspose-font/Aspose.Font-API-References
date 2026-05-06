---
title: "Clase System::Text::EncoderFallback"
linktitle: "EncoderFallback"
second_title: "Aspose.Font para C++"
description: "Clase System::Text::EncoderFallback. Proporciona una API de fallback para manejar errores de codificación. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.text/encoderfallback/
---
## EncoderFallback class


Proporciona una API de fallback para manejar errores de codificación. Los objetos de esta clase solo deben asignarse usando [System::MakeObject()](../../system/makeobject/) función. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en [System::SmartPtr](../../system/smartptr/) puntero y use este puntero para pasarlo a funciones como argumento.

```cpp
class EncoderFallback : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [CreateFallbackBuffer](./createfallbackbuffer/)() | Obtiene el búfer asociado con el algoritmo de fallback. |
| static [get_ExceptionFallback](./get_exceptionfallback/)() | Obtiene la implementación predeterminada de excepción fallback. |
| virtual [get_MaxCharCount](./get_maxcharcount/)() const | Obtiene el número máximo de caracteres que pueden ser devueltos por el fallback. |
| static [get_ReplacementFallback](./get_replacementfallback/)() | Obtiene la implementación predeterminada de sustitución fallback. |
| static [get_StandardSafeFallback](./get_standardsafefallback/)() | Obtiene la implementación predeterminada estándar segura de fallback. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.Font for C++](../../)
