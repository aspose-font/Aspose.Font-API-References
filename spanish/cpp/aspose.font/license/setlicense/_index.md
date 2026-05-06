---
title: "Aspose::Font::License::SetLicense método"
linktitle: "SetLicense"
second_title: "Aspose.Font para C++"
description: "Aspose::Font::License::SetLicense método. Licencia el componente en C++."
type: docs
weight: 400
url: /es/cpp/aspose.font/license/setlicense/
---
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Licencia el componente.

```cpp
void Aspose::Font::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | System::SharedPtr\<System::IO::Stream\> | Un flujo que contiene la licencia. |
## Observaciones



Utilice este método para cargar una licencia desde un flujo.

<javaName>void setLicense(java.io.InputStream stream)</javaName>
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [License](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
## License::SetLicense(System::String) method


Licencia el componente.

```cpp
void Aspose::Font::License::SetLicense(System::String licenseName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | System::String | Puede ser un nombre de archivo completo o corto<ms> o el nombre de un recurso incrustado</ms>. Use una cadena vacía para cambiar al modo de evaluación. |
## Observaciones


Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

<ms>

2. La carpeta que contiene el ensamblado del componente **Aspose**.

3. La carpeta que contiene el ensamblado de llamada del cliente.

4. La carpeta que contiene el ensamblado de entrada (inicio).

5. Un recurso incrustado en el ensamblado de llamada del cliente.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ruta explícita.

2. Un recurso incrustado en el ensamblado de llamada del cliente.

</ms>

<java>

2. La carpeta que contiene el archivo JAR del componente **Aspose**.

3. La carpeta que contiene el archivo JAR de llamada del cliente.

</java>

## Ver también

* Class [String](../../../system/string/)
* Class [License](../)
* Namespace [Aspose::Font](../../)
* Library [Aspose.Font for C++](../../../)
