---
title: "System::SmartPtrInfo class"
linktitle: "SmartPtrInfo"
second_title: "Aspose.Font para C++"
description: "System::SmartPtrInfo class. Clase de servicio para probar y modificar el contenido de SmartPtr''s sin conocer el tipo final. Utilizada para la recolección de basura y detección de referencias cíclicas, etc. Piense en ella como un ''puntero a puntero''. No podemos usar el tipo base de SmartPtr''s ya que no tiene ninguno; en su lugar, usamos esta clase ''info'' en C++."
type: docs
weight: 5600
url: /es/cpp/system/smartptrinfo/
---
## SmartPtrInfo class


Clase de servicio para probar y modificar el contenido de [SmartPtr](../smartptr/)'s sin conocer el tipo final. Utilizada para la recolección de basura y detección de referencias cíclicas, etc. Piense en ella como un 'puntero a puntero'. No podemos usar el tipo base de [SmartPtr](../smartptr/)'s ya que no tiene ninguno; en su lugar, usamos esta clase 'info'.

```cpp
class SmartPtrInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| [getInternalPtr](./getinternalptr/)() const | Obtiene el objeto bruto al que apunta el puntero referenciado. |
| [getObject](./getobject/)() const | Obtiene el objeto al que apunta el puntero referenciado. |
| [getOwned](./getowned/)() const | Obtiene el puntero propietario del objeto. |
| [operator bool](./operatorbool/)() const | Comprueba si el objeto info apunta a un puntero no nulo. |
| [operator!](./operator!/)() const | Comprueba si el objeto info no apunta a un puntero no nulo. |
| [operator->](./operator-_/)() const | Permite llamar a los métodos de [Object](../object/) apuntado por el puntero referenciado. |
| [operator<](./operator_/)(const SmartPtrInfo\&) const | Compara menores los valores de los punteros referenciados por dos objetos info. |
| [SmartPtrInfo](./smartptrinfo/)() | Crea un objeto [SmartPtrInfo](./) vacío. |
| explicit [SmartPtrInfo](./smartptrinfo/)(const SmartPtr\<T\>\&) | Crea un objeto [SmartPtrInfo](./) con información sobre un puntero inteligente específico. |
## Ver también

* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
