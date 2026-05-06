---
title: "System::Security::Cryptography::ICspAsymmetricAlgorithm clase"
linktitle: "ICspAsymmetricAlgorithm"
second_title: "Aspose.Font para C++"
description: "System::Security::Cryptography::ICspAsymmetricAlgorithm clase. Clase base de algoritmo asimétrico. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2100
url: /es/cpp/system.security.cryptography/icspasymmetricalgorithm/
---
## ICspAsymmetricAlgorithm class


Clase base de algoritmo asimétrico. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ICspAsymmetricAlgorithm : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [ExportCspBlob](./exportcspblob/)(bool) | Exporta el blob con la información de la clave. |
| virtual [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() | Información RTTI. |
| virtual [ImportCspBlob](./importcspblob/)(ByteArrayPtr) | Importa la información de la clave del blob de datos. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Font for C++](../../)
