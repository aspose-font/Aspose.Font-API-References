---
title: "Clase System::ComponentModel::ProgressChangedEventArgs"
linktitle: "ProgressChangedEventArgs"
second_title: "Aspose.Font para C++"
description: "Clase System::ComponentModel::ProgressChangedEventArgs. Una instancia de esta clase se pasa como argumento al delegado ProgressChangedEventHandler. Los objetos de esta clase deben asignarse únicamente mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni utilizando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y utilice ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1100
url: /es/cpp/system.componentmodel/progresschangedeventargs/
---
## ProgressChangedEventArgs class


Una instancia de esta clase se pasa como argumento al delegado ProgressChangedEventHandler. Los objetos de esta clase deben asignarse únicamente mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni utilizando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice ese puntero para pasarla a funciones como argumento.

```cpp
class ProgressChangedEventArgs : public System::EventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ProgressPercentage](./get_progresspercentage/)() const | Obtiene el porcentaje de progreso de la tarea asíncrona. |
| [get_UserState](./get_userstate/)() const | Obtiene un estado de usuario único. |
| [ProgressChangedEventArgs](./progresschangedeventargs/)(int, System::SharedPtr\<System::Object\>) | Constructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Ver también

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.Font for C++](../../)
