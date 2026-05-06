---
title: "System::IConvertible clase"
linktitle: "IConvertible"
second_title: "Aspose.Font para C++"
description: "System::IConvertible clase. Define métodos que convierten el valor del tipo de referencia o valor que implementa a un tipo de tiempo de ejecución de lenguaje común que tiene un valor equivalente. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3400
url: /es/cpp/system/iconvertible/
---
## IConvertible class


Define métodos que convierten el valor del tipo de referencia o valor que implementa a un tipo de tiempo de ejecución de lenguaje común que tiene un valor equivalente. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class IConvertible : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetTypeCode](./gettypecode/)() | Devuelve el código de tipo de esta instancia. |
| virtual [ToBoolean](./toboolean/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un valor [Boolean](../boolean/) equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToByte](./tobyte/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un entero uint32_teger de 8 bits equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToChar](./tochar/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un carácter Unicode equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToDateTime](./todatetime/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un [System::DateTime](../datetime/) equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToDecimal](./todecimal/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un número [System::Decimal](../decimal/) equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToDouble](./todouble/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un número de punto flotante de doble precisión equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToInt16](./toint16/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un entero con signo de 16 bits equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToInt32](./toint32/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un entero con signo de 32 bits equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToInt64](./toint64/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un entero con signo de 64 bits equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToSByte](./tosbyte/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un entero con signo de 8 bits equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToSingle](./tosingle/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un número de punto flotante de precisión simple equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToString](./tostring/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un [System::String](../string/) equivalente utilizando la información de formato específica de la cultura especificada. |
| virtual [ToString](./tostring/)() const | Análogo del método C# [Object.ToString()](../object/tostring/). Permite convertir objetos personalizados a cadena. |
| virtual [ToType](./totype/)(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un [System::Object](../object/) del System::Type especificado que tiene un valor equivalente, utilizando la información de formato específica de la cultura especificada. |
| virtual [ToUInt16](./touint16/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un uint32_teger de 16 bits equivalente usando la información de formato específica de cultura proporcionada. |
| virtual [ToUInt32](./touint32/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un uint32_teger de 32 bits equivalente usando la información de formato específica de cultura proporcionada. |
| virtual [ToUInt64](./touint64/)(System::SharedPtr\<System::IFormatProvider\>) | Convierte el valor de esta instancia a un uint32_teger de 64 bits equivalente usando la información de formato específica de cultura proporcionada. |
## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.Font for C++](../../)
