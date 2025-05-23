---
title: System::IO::BasicSTDIStreamWrapper::Write method
linktitle: Write
second_title: Aspose.Font for C++
description: 'System::IO::BasicSTDIStreamWrapper::Write method. If wrapping mode is binary, writes to the stream the specified subrange of bytes from the specified byte array, otherwise convert the specified subrange of bytes from the specified byte array to char_type type ant then writes result to the stream. Not supported! in C++.'
type: docs
weight: 700
url: /cpp/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


If wrapping mode is binary, writes to the stream the specified subrange of bytes from the specified byte array, otherwise convert the specified subrange of bytes from the specified byte array to char_type type ant then writes result to the stream. Not supported!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | The array containing the bytes to write. |
| offset | int32_t | A 0-based index of the elemnet in **buffer** at which the subrange to write begins. |
| count | int32_t | The number of elements in the subrange to write. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<uint8_t\>\& | The array view containing the bytes to write |
| offset | int32_t | A 0-based index of the element in **buffer** at which the subrange to write begins |
| count | int32_t | The number of elements in the subrange to write |

## See Also

* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Font for C++](../../../)
