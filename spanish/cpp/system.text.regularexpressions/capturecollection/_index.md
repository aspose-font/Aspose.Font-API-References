---
title: "System::Text::RegularExpressions::CaptureCollection class"
linktitle: "CaptureCollection"
second_title: "Aspose.Font para C++"
description: "Clase System::Text::RegularExpressions::CaptureCollection. Lista de capturas realizadas por un único grupo de captura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.text.regularexpressions/capturecollection/
---
## CaptureCollection class


Lista de capturas realizadas por un único grupo de captura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class CaptureCollection : public System::Collections::Generic::List<CapturePtr>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const CapturePtr\&) override | Desactiva la enmienda de la colección. |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Método de servicio para agregar una captura a la colección. |
| [Clear](./clear/)() override | Desactiva la limpieza de la colección. |
| [get_Count](./get_count/)() const override | Obtiene el número de capturas. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Marca la colección como solo lectura. |
| [get_IsSynchronized](./get_issynchronized/)() const | Marca la colección como no sincronizada. |
| [idx_get](./idx_get/)(int) const override | Accesor [Capture](../capture/). |
| [operator[]](./operator[]/)(int) | Accesor [Capture](../capture/). |
| [operator[]](./operator[]/)(int) const | Accesor [Capture](../capture/). |
| [Remove](./remove/)(const CapturePtr\&) override | Desactiva la enmienda de la colección. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Base](./base/) | Tipo [Base](./base/). |
## Ver también

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.Font for C++](../../)
