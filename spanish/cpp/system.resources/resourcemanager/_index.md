---
title: "System::Resources::ResourceManager clase"
linktitle: "ResourceManager"
second_title: "Aspose.Font para C++"
description: "System::Resources::ResourceManager clase. Proporciona una API para gestionar recursos. No implementado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.resources/resourcemanager/
---
## ResourceManager class


Proporciona una API para gestionar recursos. No implementado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ResourceManager : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetObject__](./getobject__/)(String) | Obtiene un objeto del recurso. El nombre no es GetObject() para manejar el problema de definición de GetObjectA. |
| virtual [GetObject__](./getobject__/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Obtiene un objeto del recurso. El nombre no es GetObject() para manejar el problema de definición de GetObjectA. |
| virtual [GetString](./getstring/)(String) | Obtiene un recurso de cadena. |
| virtual [GetString](./getstring/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Obtiene un recurso de cadena. |
| [ResourceManager](./resourcemanager/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | Información RTTI. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Resources](../)
* Library [Aspose.Font for C++](../../)
