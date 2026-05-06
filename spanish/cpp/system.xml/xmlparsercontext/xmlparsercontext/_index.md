---
title: "System::Xml::XmlParserContext::XmlParserContext constructor"
linktitle: "XmlParserContext"
second_title: "Aspose.Font para C++"
description: "System::Xml::XmlParserContext::XmlParserContext constructor. Inicializa una nueva instancia de la clase XmlParserContext con la XmlNameTable, XmlNamespaceManager, URI base, xml:lang, xml:space y los valores del tipo de documento especificados en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con la [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI base, **xml:lang**, **xml:space** y los valores del tipo de documento.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | La [XmlNameTable](../../xmlnametable/) que se usará para atomizar cadenas. Si esto es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) que se usará para buscar información de espacios de nombres, o **nullptr**. |
| docTypeName | const String\& | El nombre de la declaración del tipo de documento. |
| pubId | const String\& | El identificador público. |
| sysId | const String\& | El identificador del sistema. |
| internalSubset | const String\& | El subconjunto interno DTD. El subconjunto DTD se utiliza para la resolución de entidades, no para la validación del documento. |
| baseURI | const String\& | El URI base para el fragmento XML (la ubicación desde la que se cargó el fragmento). |
| xmlLang | const String\& | El alcance de **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Un valor [XmlSpace](../../xmlspace/) que indica el ámbito **xml:space**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con la [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI base, **xml:lang**, **xml:space**, codificación y los valores del tipo de documento.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | La [XmlNameTable](../../xmlnametable/) que se usará para atomizar cadenas. Si esto es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) que se usará para buscar información de espacios de nombres, o **nullptr**. |
| docTypeName | const String\& | El nombre de la declaración del tipo de documento. |
| pubId | const String\& | El identificador público. |
| sysId | const String\& | El identificador del sistema. |
| internalSubset | const String\& | El subconjunto interno DTD. El DTD se utiliza para la resolución de entidades, no para la validación del documento. |
| baseURI | const String\& | El URI base para el fragmento XML (la ubicación desde la que se cargó el fragmento). |
| xmlLang | const String\& | El alcance de **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Un valor [XmlSpace](../../xmlspace/) que indica el ámbito **xml:space**. |
| enc | const SharedPtr\<System::Text::Encoding\>\& | Un objeto Encoding que indica la configuración de codificación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con la [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** y **xml:space**.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | La [XmlNameTable](../../xmlnametable/) que se usará para atomizar cadenas. Si esto es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) que se usará para buscar información de espacios de nombres, o **nullptr**. |
| xmlLang | const String\& | El alcance de **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Un valor [XmlSpace](../../xmlspace/) que indica el ámbito **xml:space**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con la [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** y codificación.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | La [XmlNameTable](../../xmlnametable/) que se usará para atomizar cadenas. Si esto es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) que se usará para buscar información de espacios de nombres, o **nullptr**. |
| xmlLang | const String\& | El alcance de **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Un valor [XmlSpace](../../xmlspace/) que indica el ámbito **xml:space**. |
| enc | const SharedPtr\<System::Text::Encoding\>\& | Un objeto Encoding que indica la configuración de codificación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Font for C++](../../../)
