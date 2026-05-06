---
title: "System::ComponentModel::Component class"
linktitle: "Component"
second_title: "Aspose.Font para C++"
description: "System::ComponentModel::Component class. Clase ficticia para que el código traducido que usa la clase Component sea compilable. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.componentmodel/component/
---
## Component class


Clase ficticia para que el código traducido que usa la clase [Component](./) sea compilable. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Component : public System::MarshalByRefObject,
                  public System::ComponentModel::IComponent
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Component](./component/)() | Información RTTI. |
| [Dispose](./dispose/)(bool) | Soporte del patrón Disposable; no hace nada. |
| [get_DesignMode](./get_designmode/)() | Comprueba si el componente está en modo de diseño. |
## Ver también

* Class [MarshalByRefObject](../../system/marshalbyrefobject/)
* Class [IComponent](../icomponent/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.Font for C++](../../)
