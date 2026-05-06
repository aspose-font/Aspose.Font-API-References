---
title: "System::Xml::XmlReader::ReadContentAs método"
linktitle: "ReadContentAs"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlReader::ReadContentAs método. Lee el contenido como un objeto del tipo especificado en C++."
type: docs
weight: 3900
url: /es/cpp/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs method


Lee el contenido como un objeto del tipo especificado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const TypeInfo\& | El tipo del valor a devolver. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Un objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que se utiliza para resolver cualquier prefijo de espacio de nombres relacionado con la conversión de tipos. Por ejemplo, esto puede usarse al convertir un objeto [XmlQualifiedName](../../xmlqualifiedname/) a un **xs:string**. Este valor puede ser **nullptr**. |

### ReturnValue

El contenido de texto concatenado o el valor de atributo convertido al tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
