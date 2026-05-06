---
title: "System::SmartPtr::operator* method"
linktitle: "operator*"
second_title: "Aspose.Font para C++"
description: "System::SmartPtr::operator* method. Obtiene una referencia al objeto apuntado. Asegura que el puntero no sea nulo en C++."
type: docs
weight: 2500
url: /es/cpp/system/smartptr/operator_/
---
## SmartPtr::operator* method


Obtiene una referencia al objeto apuntado. Afirma que el puntero no es nulo.

```cpp
Pointee_ & System::SmartPtr<T>::operator*() const
```


### ReturnValue

Referencia al objeto apuntado.

## Ver también

* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
---
título: System::SmartPtr::operator< method
título del enlace: operator<
segundo_título: Aspose.Font para C++
descripción: 'System::SmartPtr::operator< method. Proporciona semántica de comparación menor para la clase SmartPtr en C++.'
tipo: documentos
weight: 2700
url: /cpp/system/smartptr/operator_/
---
## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


Proporciona semántica de comparación menor para la clase [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo de puntero con el que comparar el actual. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | SmartPtr\<Y\> const\& | Puntero con el que comparar el actual. |

### ReturnValue

Verdadero si el objeto referenciado por [SmartPtr](../) es 'menor' que x y falso en caso contrario.

## Ver también

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::operator<(Y *) const method


Proporciona semántica de comparación menor para la clase [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo de puntero con el que comparar el actual. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | Y * | Puntero con el que comparar el actual. |

### ReturnValue

Verdadero si el objeto referenciado por [SmartPtr](../) es 'menor' que p y falso en caso contrario.

## Ver también

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
