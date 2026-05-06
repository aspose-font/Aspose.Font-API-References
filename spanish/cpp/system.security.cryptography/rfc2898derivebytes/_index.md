---
title: "System::Security::Cryptography::Rfc2898DeriveBytes clase"
linktitle: "Rfc2898DeriveBytes"
second_title: "Aspose.Font para C++"
description: "Clase System::Security::Cryptography::Rfc2898DeriveBytes. Implementa la derivación de claves basada en contraseña, PBKDF2. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y utilice ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2900
url: /es/cpp/system.security.cryptography/rfc2898derivebytes/
---
## Rfc2898DeriveBytes class


Implementa la derivación de claves basada en contraseña, PBKDF2. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice ese puntero para pasarlo a funciones como argumento.

```cpp
class Rfc2898DeriveBytes : public System::Security::Cryptography::DeriveBytes
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GetBytes](./getbytes/)(int32_t) override | Rellena los elementos existentes del arreglo con bytes de clave pseudoaleatorios. |
| [Reset](./reset/)() override |  |
| [Rfc2898DeriveBytes](./rfc2898derivebytes/)(ArrayPtr\<uint8_t\>, ArrayPtr\<uint8_t\>, int32_t) | Información RTTI. |
## Ver también

* Class [DeriveBytes](../derivebytes/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Font for C++](../../)
