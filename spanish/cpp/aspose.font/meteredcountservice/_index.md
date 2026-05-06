---
title: "clase Aspose::Font::MeteredCountService"
linktitle: "MeteredCountService"
second_title: "Aspose.Font para C++"
description: "clase Aspose::Font::MeteredCountService. Esta clase interna se usa para manejar los datos de consumo del cliente, la unidad es MB en C++."
type: docs
weight: 2700
url: /es/cpp/aspose.font/meteredcountservice/
---
## MeteredCountService class


Esta clase interna se utiliza para manejar los datos de consumo del cliente, la unidad es MB.

```cpp
class MeteredCountService : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [_IncreaseCount](./_increasecount/)(System::Decimal, bool) |  |
| [_IncreaseCredit](./_increasecredit/)(int64_t, bool) |  |
| [Flush](./flush/)() |  |
| static [get_Instance](./get_instance/)() |  |
| [GetAndResetCount](./getandresetcount/)() | Obtiene y restablece el tamaño del archivo de consumo del cliente. |
| [GetAndResetCredit](./getandresetcredit/)() | Obtiene y restablece el crédito de consumo del cliente. |
| [IncreaseCount](./increasecount/)(double) | Incrementa el tamaño del archivo de consumo del cliente y trata de subir los datos. |
| [IncreaseCount](./increasecount/)(System::Decimal, bool) | Incrementa el tamaño del archivo de consumo del cliente. |
| [IncreaseCredit](./increasecredit/)(int64_t) | Incrementa el crédito de consumo del cliente y trata de subir. |
| [IncreaseCredit](./increasecredit/)(int64_t, bool) | Incrementa el crédito de consumo del cliente. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [MAX_SERVER_INTERNAL_ERROR_TIME_INTERVAL](./max_server_internal_error_time_interval/) |  |
| static [MAX_UPLOAD_FAIL_RESET_NUMBER](./max_upload_fail_reset_number/) |  |
| static [MAX_UPLOAD_FAIL_RESET_TIME_INTERVAL](./max_upload_fail_reset_time_interval/) |  |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Font](../)
* Library [Aspose.Font for C++](../../)
