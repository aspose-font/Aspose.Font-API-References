---
title: "System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule método"
linktitle: "CreateFloatingDateRule"
second_title: "Aspose.Font para C++"
description: "System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule método. Construye una instancia de la clase TransitionTime que representa una regla de fecha flotante (cambio de hora que ocurre en un día específico de una semana específica de un mes específico) en C++."
type: docs
weight: 1100
url: /es/cpp/system/timezoneinfo/transitiontime/createfloatingdaterule/
---
## TransitionTime::CreateFloatingDateRule method


Construye una instancia de la clase [TransitionTime](../) que representa una regla de fecha flotante (cambio de hora que ocurre en un día específico de una semana específica de un mes específico).

```cpp
static TransitionTime System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule(DateTime time_of_day, int month, int week, DayOfWeek day_of_week)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| time_of_day | DateTime | La hora específica en la que ocurre el cambio de hora. |
| mes | int | El mes del año en el que ocurre el cambio de hora. |
| semana | int | La semana del mes en la que ocurre el cambio de hora. |
| day_of_week | DayOfWeek | El día de la semana en la que ocurre el cambio de hora. |

### ReturnValue

Una instancia de la clase [TransitionTime](../) que representa el cambio de hora descrito.

## Ver también

* Class [TransitionTime](../)
* Class [DateTime](../../../datetime/)
* Enum [DayOfWeek](../../../dayofweek/)
* Class [TransitionTime](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.Font for C++](../../../../)
