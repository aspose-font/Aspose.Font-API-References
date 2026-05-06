---
title: "System::Web::HttpUtility clase"
linktitle: "HttpUtility"
second_title: "Aspose.Font para C++"
description: "System::Web::HttpUtility clase. Clase de servicio que codifica y decodifica partes de URL hacia y desde fragmentos de escape hexadecimales en C++."
type: docs
weight: 300
url: /es/cpp/system.web/httputility/
---
## HttpUtility class


Clase de servicio que codifica y decodifica partes de URL a y desde fragmentos de escape hexadecimales.

```cpp
class HttpUtility : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [HtmlDecode](./htmldecode/)(const String\&) | Decodifica fragmento HTML. |
| static [HtmlDecode](./htmldecode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Decodifica fragmento HTML. |
| static [HtmlEncode](./htmlencode/)(const String\&) | Codifica fragmento HTML. |
| static [HtmlEncode](./htmlencode/)(const SharedPtr\<Object\>\&) | Codifica fragmento HTML. |
| static [HtmlEncode](./htmlencode/)(const String\&, const SharedPtr\<IO::TextWriter\>\&) | Codifica fragmento HTML. |
| static [UrlDecode](./urldecode/)(String) | Decodifica fragmento URI a partir de una cadena. |
| static [UrlDecode](./urldecode/)(String, System::SharedPtr\<Text::Encoding\>) | Decodifica fragmento URI a partir de una cadena. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) | Decodifica el fragmento URI a partir de una matriz de bytes. |
| static [UrlDecode](./urldecode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) | Decodifica el fragmento URI a partir de una matriz de bytes. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Decodifica el fragmento URI a partir de una matriz de bytes. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&) | Decodifica el fragmento URI a partir de una cadena de bytes. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Decodifica fragmento URI a partir de una cadena. |
| static [UrlDecodeToBytes](./urldecodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Decodifica el fragmento URI a partir de una matriz de bytes. |
| static [UrlEncode](./urlencode/)(String) | Codifica el fragmento URI. |
| static [UrlEncode](./urlencode/)(String, const System::SharedPtr\<Text::Encoding\>\&) | Codifica el fragmento URI. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&) | Codifica el fragmento URI. |
| static [UrlEncode](./urlencode/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Codifica el fragmento URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&) | Codifica el fragmento URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const String\&, const System::SharedPtr\<Text::Encoding\>\&) | Codifica el fragmento URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&) | Codifica el fragmento URI. |
| static [UrlEncodeToBytes](./urlencodetobytes/)(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Codifica el fragmento URI. |
| static [UrlEncodeUnicode](./urlencodeunicode/)(const String\&) | Codifica el fragmento URI usando Unicode. |
| static [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const String\&) | Codifica el fragmento URI usando Unicode. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Web](../)
* Library [Aspose.Font for C++](../../)
