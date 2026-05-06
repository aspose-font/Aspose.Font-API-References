---
title: "enumeración System::Xml::WriteState"
linktitle: "WriteState"
second_title: "Aspose.Font para C++"
description: "enumeración System::Xml::WriteState. Especifica el estado del XmlWriter en C++."
type: docs
weight: 5700
url: /es/cpp/system.xml/writestate/
---
## WriteState enum


Especifica el estado del [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Iniciar | 0 | Indica que el método XmlWriter::Write aún no ha sido llamado. |
| Prólogo | 1 | Indica que el prólogo se está escribiendo. |
| Elemento | 2 | Indica que se está escribiendo una etiqueta de inicio de elemento. |
| Atributo | 3 | Indica que se está escribiendo un valor de atributo. |
| Contenido | 4 | Indica que se está escribiendo el contenido del elemento. |
| Closed | 5 | Indica que se ha llamado al método [XmlWriter::Close](../xmlwriter/close/). |
| Error | 6 | Se ha lanzado una excepción, lo que ha dejado al [XmlWriter](../xmlwriter/) en un estado inválido. Puede llamar al método [XmlWriter::Close](../xmlwriter/close/) para colocar al [XmlWriter](../xmlwriter/) en el estado [WriteState::Closed](./). Cualquier otra llamada a un método de [XmlWriter](../xmlwriter/) produce una InvalidOperationException. |

## Ver también

* Namespace [System::Xml](../)
* Library [Aspose.Font for C++](../../)
