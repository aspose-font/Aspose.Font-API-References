---
title: Class FileSystemStreamSource
second_title: Aspose.Font for .NET API Reference
description: Aspose.Font.Sources.FileSystemStreamSource class. Represents a stream source based on file system
type: docs
weight: 720
url: /net/aspose.font.sources/filesystemstreamsource/
---
## FileSystemStreamSource class

Represents a stream source based on file system.

```csharp
public class FileSystemStreamSource : StreamSource
```

## Constructors

| Name | Description |
| --- | --- |
| [FileSystemStreamSource](filesystemstreamsource/)(string) | Initializes new `FileSystemStreamSource` object. |

## Properties

| Name | Description |
| --- | --- |
| [FileName](../../aspose.font.sources/filesystemstreamsource/filename/) { get; set; } | Gets or sets file name. |
| [Offset](../../aspose.font.sources/streamsource/offset/) { get; set; } | Gets or sets offset inside the source. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.font.sources/filesystemstreamsource/clone/)() | Clones the FileSystemStreamSource object. |
| override [GetFontStream](../../aspose.font.sources/filesystemstreamsource/getfontstream/)() | Returns font file stream. Don't forget to close the stream after use. |
| virtual [MustCloseAfterUse](../../aspose.font.sources/streamsource/mustcloseafteruse/)() | The inheritors may prevent stream from closing. Returns true if the stream source wants the stream to be closed after use. Otherwise returns false. |

### See Also

* class [StreamSource](../streamsource/)
* namespace [Aspose.Font.Sources](../../aspose.font.sources/)
* assembly [Aspose.Font](../../)


