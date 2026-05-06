---
title: "Clase System::Text::UTF8Encoding"
linktitle: "UTF8Encoding"
second_title: "Aspose.Font para C++"
description: "Clase System::Text::UTF8Encoding. Codificación UTF-8. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2800
url: /es/cpp/system.text/utf8encoding/
---
## UTF8Encoding class


Codificación UTF-8. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class UTF8Encoding : public System::Text::ICUEncoding
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona el objeto de codificación. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compara con el objeto. |
| [GetHashCode](./gethashcode/)() const override | Obtiene el código hash de la codificación. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Obtenga la cantidad máxima de bytes necesarios para codificar un número especificado de caracteres. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Obtenga la cantidad máxima de caracteres necesarios para decodificar un número especificado de bytes. |
| [GetPreamble](./getpreamble/)() override | Obtenga el preámbulo de la página de códigos. |
| [operator==](./operator==/)(const UTF8Encoding\&) const | Compara los parámetros de las codificaciones. |
| [UTF8Encoding](./utf8encoding/)() | Constructor. |
| [UTF8Encoding](./utf8encoding/)(bool) | Constructor. |
| [UTF8Encoding](./utf8encoding/)(bool, bool) | Constructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Valor predeterminado de la página de códigos. |
| static constexpr [UTF8_CODE_PAGE](./utf8_code_page/) | Información RTTI. |
## Ver también

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.Font for C++](../../)
