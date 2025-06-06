---
title: System::Threading::WaitHandle::WaitAny method
linktitle: WaitAny
second_title: Aspose.Font for C++
description: 'System::Threading::WaitHandle::WaitAny method. Waits for any of the handles to fire in C++.'
type: docs
weight: 200
url: /cpp/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


Waits for any of the handles to fire.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Handles to wait for. |

### ReturnValue

True when every element in waitHandles has received a signal; otherwise the method never returns.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


Waits for any of the handles to fire.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Handles to wait for. |
| millisecondsTimeout | int | [Timeout](../../timeout/) to wait for, in milliseconds; -1 means infinite waiting, 0 means check-and-return, positive values are timeouts. |

### ReturnValue

True if any handle fired, false if timeout exceeded.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


Waits for any of the handles to fire.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Handles to wait for. |
| timeout | TimeSpan | A [System::TimeSpan](../../../system/timespan/) that represents the number of milliseconds to wait, or a [System::TimeSpan](../../../system/timespan/) that represents -1 milliseconds to wait indefinitely. |

### ReturnValue

True if any handle fired, false if timeout exceeded.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Font for C++](../../../)
