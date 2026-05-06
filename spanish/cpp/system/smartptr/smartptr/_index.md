---
title: "Constructor de System::SmartPtr::SmartPtr"
linktitle: "SmartPtr"
second_title: "Aspose.Font para C++"
description: "System::SmartPtr::SmartPtr constructor. Convierte el tipo del array referenciado creando un nuevo array de tipo diferente. Útil si en C# hay una conversión de tipo de array que no está soportada en C++."
type: docs
weight: 100
url: /es/cpp/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor


Convierte el tipo del arreglo referenciado creando un nuevo arreglo de tipo diferente. Útil si en C# existe una conversión de tipo de arreglo que no está soportada en C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo del array origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const SmartPtr\<Array\<Y\>\>\& | Puntero al array del cual crear una copia, pero con un tipo de elementos diferente. |
| mode | SmartPtrMode | Modo de puntero. |

## Ver también

* Class [SmartPtr](../)
* Class [Array](../../array/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor


Construye un [SmartPtr](../) que comparte la información de propiedad con el valor inicial de ptr, pero contiene un puntero no relacionado y no administrado p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const SmartPtr\<P\>\& | Otro puntero inteligente para compartir la propiedad con la del anterior. |
| p | Pointee_ * | Puntero a un objeto a gestionar. |
| mode | SmartPtrMode | Modo de puntero. |

## Ver también

* Class [SmartPtr](../)
* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor


Construye por copia un objeto [SmartPtr](../). Ambos punteros apuntan al mismo objeto después. Realiza conversión de tipo si está permitida.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del objeto apuntado por x. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Puntero a copiar. |
| mode | SmartPtrMode | Modo de puntero. |

## Ver también

* Class [SmartPtr](../)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) constructor


Construye por copia un objeto [SmartPtr](../). Ambos punteros apuntan al mismo objeto después.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Puntero a copiar. |
| mode | SmartPtrMode | Modo de puntero. |

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::SmartPtr(const Y\&) constructor


Inicializa un arreglo vacío. Se usa para traducir algunas construcciones de código C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


| Parámetro | Descripción |
| --- | --- |
| Y | Marcador de posición del tipo EmptyArrayInitializer. |

## Ver también

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor


Crea un [SmartPtr](../) que apunta al objeto especificado, o convierte un puntero crudo a [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objeto | Pointee_ * | Pointee. |
| mode | SmartPtrMode | Modo de puntero. |

## Ver también

* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructor


Construye por movimiento un objeto [SmartPtr](../). Efectivamente, intercambia dos punteros, si ambos están en el mismo modo. x puede quedar inutilizable después de la llamada.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | SmartPtr_\&& | Puntero a mover. |
| mode | SmartPtrMode | Modo de puntero. |

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Crea un objeto [SmartPtr](../) del modo requerido.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | SmartPtrMode | Modo de puntero. |

## Ver también

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Crea un objeto [SmartPtr](../) nulo del modo requerido.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | std::nullptr_t | Modo de puntero. |

## Ver también

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Font for C++](../../../)
