---
title: "Método System::Xml::XmlTextReader::ReadContentAsBinHex"
linktitle: "ReadContentAsBinHex"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlTextReader::ReadContentAsBinHex. Lee el contenido y devuelve los bytes binarios decodificados en BinHex en C++."
type: docs
weight: 4800
url: /es/cpp/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex method


Lee el contenido y devuelve los bytes binarios decodificados **BinHex**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | ArrayPtr\<uint8_t\> | El búfer en el que copiar el texto resultante. Este valor no puede ser **nullptr**. |
| índice | int32_t | El desplazamiento en el búfer donde comenzar a copiar el resultado. |
| count | int32_t | El número máximo de bytes a copiar en el búfer. El número real de bytes copiados se devuelve desde este método. |

### ReturnValue

El número de bytes escritos en el búfer.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
