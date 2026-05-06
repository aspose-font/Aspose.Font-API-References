---
title: "System::ComponentModel::PropertyChangedEventArgs clase"
linktitle: "PropertyChangedEventArgs"
second_title: "Aspose.Font para C++"
description: "System::ComponentModel::PropertyChangedEventArgs clase. Argumentos del evento PropertyChanged. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.componentmodel/propertychangedeventargs/
---
## PropertyChangedEventArgs class


Argumentos del evento PropertyChanged. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class PropertyChangedEventArgs : public System::EventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_PropertyName](./get_propertyname/)() | Información RTTI. |
| [PropertyChangedEventArgs](./propertychangedeventargs/)(const String\&) | Inicializa los argumentos del evento PropertyChanged. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Ver también

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.Font for C++](../../)
