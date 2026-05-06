---
title: "System::Xml::Schema::XmlSchemaSet clase"
linktitle: "XmlSchemaSet"
second_title: "Aspose.Font para C++"
description: "System::Xml::Schema::XmlSchemaSet clase. Contiene una caché de esquemas de lenguaje de definición de XML Schema (XSD) en C++."
type: docs
weight: 5800
url: /es/cpp/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet class


Contiene una caché de esquemas de lenguaje de definición de XML [Schema](../) (XSD).

```cpp
class XmlSchemaSet : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(String, const String\&) | Agrega el esquema de lenguaje de definición de XML [Schema](../) (XSD) en la URL especificada al [XmlSchemaSet](./). |
| [Add](./add/)(String, const SharedPtr\<XmlReader\>\&) | Agrega el esquema de lenguaje de definición de XML [Schema](../) (XSD) contenido en el [XmlReader](../../system.xml/xmlreader/) al [XmlSchemaSet](./). |
| [Add](./add/)(const SharedPtr\<XmlSchemaSet\>\&) | Agrega todos los esquemas de lenguaje de definición de XML [Schema](../) (XSD) del [XmlSchemaSet](./) dado al [XmlSchemaSet](./). |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&) | Agrega el [XmlSchema](../xmlschema/) proporcionado al [XmlSchemaSet](./). |
| [Compile](./compile/)() | Compila los esquemas de lenguaje de definición de XML [Schema](../) (XSD) añadidos al [XmlSchemaSet](./) en un único esquema lógico. |
| [Contains](./contains/)(String) | Indica si un esquema de lenguaje de definición de XML [Schema](../) (XSD) con el URI del espacio de nombres objetivo especificado está en el [XmlSchemaSet](./). |
| [Contains](./contains/)(const SharedPtr\<XmlSchema\>\&) | Indica si el objeto [XmlSchema](../xmlschema/) de XML [Schema](../) (XSD) especificado está en el [XmlSchemaSet](./). |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchema\>\>\&, int32_t) | Copia todos los objetos [XmlSchema](../xmlschema/) del [XmlSchemaSet](./) al arreglo dado, comenzando en el índice especificado. |
| [get_CompilationSettings](./get_compilationsettings/)() | Devuelve la [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) para el [XmlSchemaSet](./). |
| [get_Count](./get_count/)() | Devuelve el número de esquemas lógicos de XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [get_GlobalAttributes](./get_globalattributes/)() | Devuelve todos los atributos globales en todos los esquemas de XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [get_GlobalElements](./get_globalelements/)() | Devuelve todos los elementos globales en todos los esquemas de XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [get_GlobalTypes](./get_globaltypes/)() | Devuelve todos los tipos simples y complejos globales en todos los esquemas de XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [get_IsCompiled](./get_iscompiled/)() | Devuelve un valor que indica si los esquemas de XML [Schema](../) (XSD) en el [XmlSchemaSet](./) han sido compilados. |
| [get_NameTable](./get_nametable/)() | Devuelve la [XmlNameTable](../../system.xml/xmlnametable/) predeterminada utilizada por el [XmlSchemaSet](./) al cargar nuevos esquemas de XML [Schema](../) (XSD). |
| [Remove](./remove/)(const SharedPtr\<XmlSchema\>\&) | Elimina el esquema de XML [Schema](../) (XSD) especificado del [XmlSchemaSet](./). |
| [RemoveRecursive](./removerecursive/)(const SharedPtr\<XmlSchema\>\&) | Elimina el esquema de XML [Schema](../) (XSD) especificado y todos los esquemas que importa del [XmlSchemaSet](./). |
| [Reprocess](./reprocess/)(SharedPtr\<XmlSchema\>) | Reprocesa un esquema de XML [Schema](../) (XSD) que ya existe en el [XmlSchemaSet](./). |
| [Schemas](./schemas/)() | Devuelve una colección de todos los esquemas de XML [Schema](../) (XSD) en el [XmlSchemaSet](./). |
| [Schemas](./schemas/)(String) | Devuelve una colección de todos los esquemas del lenguaje de definición XML [Schema](../) (XSD) en el [XmlSchemaSet](./) que pertenecen al espacio de nombres dado. |
| [set_CompilationSettings](./set_compilationsettings/)(const SharedPtr\<XmlSchemaCompilationSettings\>\&) | Establece la [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) para el [XmlSchemaSet](./). |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Establece el [XmlResolver](../../system.xml/xmlresolver/) utilizado para resolver espacios de nombres o ubicaciones referenciados en los elementos include e import de un esquema. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Agrega un controlador de eventos para recibir información sobre errores de validación de esquemas del lenguaje de definición XML [Schema](../) (XSD). |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Elimina un controlador de eventos para recibir información sobre errores de validación de esquemas del lenguaje de definición XML [Schema](../) (XSD). |
| [XmlSchemaSet](./xmlschemaset/)() | Inicializa una nueva instancia de la clase [XmlSchemaSet](./). |
| [XmlSchemaSet](./xmlschemaset/)(const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlSchemaSet](./) con la [XmlNameTable](../../system.xml/xmlnametable/) especificada. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.Font for C++](../../)
