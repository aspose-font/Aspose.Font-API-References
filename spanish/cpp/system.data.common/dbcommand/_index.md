---
title: "System::Data::Common::DbCommand clase"
linktitle: "DbCommand"
second_title: "Aspose.Font para C++"
description: "System::Data::Common::DbCommand clase. Comando de base de datos. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.data.common/dbcommand/
---
## DbCommand class


Comando de base de datos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class DbCommand : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [ExecuteNonQuery](./executenonquery/)() | Ejecuta un comando que no es de consulta. |
| virtual [ExecuteReader](./executereader/)() | Ejecuta un comando de consulta. |
| virtual [get_CommandText](./get_commandtext/)() const | Información RTTI. |
| virtual [get_Connection](./get_connection/)() const | Obtiene la conexión a la base de datos asociada al comando. |
| virtual [set_CommandText](./set_commandtext/)(String) const | Establece el texto del comando DB. |
| virtual [set_Connection](./set_connection/)(SharedPtr\<System::Data::Common::DbConnection\>) | Obtiene la conexión a la base de datos asociada al comando. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.Font for C++](../../)
