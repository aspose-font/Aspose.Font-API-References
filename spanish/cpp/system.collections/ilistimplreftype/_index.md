---
title: "Clase System::Collections::IListImplRefType"
linktitle: "IListImplRefType"
second_title: "Aspose.Font para C++"
description: "Clase System::Collections::IListImplRefType. Stub que implementa la interfaz System::Collections::IList en el objeto System::Collections::Generic::List. Implementación para tipos de referencia en C++."
type: docs
weight: 1100
url: /es/cpp/system.collections/ilistimplreftype/
---
## IListImplRefType class


Stub que implementa la interfaz [System::Collections::IList](../ilist/) en el objeto [System::Collections::Generic::List](../../system.collections.generic/list/). Implementación para tipos de referencia.

```cpp
template<typename T>class IListImplRefType : public virtual System::Collections::IList
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(SharedPtr\<System::Object\>) override | Agrega un elemento al final de la lista. |
| static [BoxValue](./boxvalue/)(System::SharedPtr\<T\>) | Convirtiendo una referencia de tipo en un valor de objeto. |
| [Clear](./clear/)() override | Elimina todos los elementos. |
| [Contains](./contains/)(SharedPtr\<System::Object\>) const override | Comprueba si el elemento está presente en la lista. |
| [get_Count](./get_count/)() const override | [ICollection.get_Count()](../icollection/get_count/) implementación Obtiene el número de elementos en la colección. |
| [GetEnumerator](./getenumerator/)() override | [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) implementación Devuelve un enumerador que recorre una colección. |
| [idx_get](./idx_get/)(int, int) const override | Obtiene el elemento en el índice especificado. |
| [IListImplRefType](./ilistimplreftype/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<T\>\>\>) | Crea una nueva instancia de objeto. |
| [IndexOf](./indexof/)(System::SharedPtr\<System::Object\>) const override | Obtiene el índice de la primera aparición del elemento en el contenedor. |
| [Insert](./insert/)(int, System::SharedPtr\<System::Object\>) override | Inserta el elemento en la posición especificada, desplazando los demás elementos. |
| [Remove](./remove/)(SharedPtr\<System::Object\>) override | Elimina la primera instancia del elemento específico de la lista. |
| [RemoveAt](./removeat/)(int) override | Elimina el elemento en la posición especificada. |
| static [UnboxValue](./unboxvalue/)(System::SharedPtr\<System::Object\>) | Convirtiendo el valor de un objeto en una referencia de tipo particular. |
## Ver también

* Class [IList](../ilist/)
* Namespace [System::Collections](../)
* Library [Aspose.Font for C++](../../)
