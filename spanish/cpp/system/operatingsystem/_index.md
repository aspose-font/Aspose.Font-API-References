---
title: "Clase System::OperatingSystem"
linktitle: "OperatingSystem"
second_title: "Aspose.Font para C++"
description: "Clase System::OperatingSystem. Representa un sistema operativo particular y proporciona información sobre él. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 5100
url: /es/cpp/system/operatingsystem/
---
## OperatingSystem class


Representa un sistema operativo particular y proporciona información sobre él. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class OperatingSystem
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Platform](./get_platform/)() const | Devuelve el identificador de plataforma del sistema operativo representado por el objeto actual. |
| [get_ServicePack](./get_servicepack/)() const | Devuelve el nombre del service pack del sistema operativo representado por el objeto actual. |
| [get_Version](./get_version/)() const | Devuelve una referencia constante a un objeto [Version](../version/) que representa la versión del sistema operativo representado por el objeto actual. |
| [get_VersionString](./get_versionstring/)() const | Devuelve la representación en cadena de la versión del sistema operativo representado por el objeto actual. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&) | Construye una instancia que representa un sistema operativo especificado por un identificador de plataforma y una versión particulares. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&, const String\&) | Construye una instancia que representa un sistema operativo especificado por un identificador de plataforma, versión y paquete de servicio particulares. |
| [ToString](./tostring/)() const | Devuelve la representación en cadena de la versión del sistema operativo representado por el objeto actual. |
## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
