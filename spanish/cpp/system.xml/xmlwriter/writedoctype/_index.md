---
title: "Método System::Xml::XmlWriter::WriteDocType"
linktitle: "WriteDocType"
second_title: "Aspose.Font para C++"
description: "Método System::Xml::XmlWriter::WriteDocType. Cuando se sobrescribe en una clase derivada, escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales en C++."
type: docs
weight: 1700
url: /es/cpp/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType method


Cuando se sobrescribe en una clase derivada, escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | const String\& | El nombre del DOCTYPE. Este debe ser no vacío. |
| pubid | const String\& | Si no es nulo, también escribe PUBLIC \"pubid\" \"sysid\" donde **pubid** y **sysid** son reemplazados con el valor de los argumentos proporcionados. |
| sysid | const String\& | Si **pubid** es **nullptr** y **sysid** no es nulo, escribe SYSTEM \"sysid\" donde **sysid** se reemplaza con el valor de este argumento. |
| subset | const String\& | Si no es nulo escribe [subset] donde subset se reemplaza con el valor de este argumento. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
