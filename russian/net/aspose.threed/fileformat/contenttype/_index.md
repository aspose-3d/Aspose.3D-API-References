---
title: "FileFormat.ContentType"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство FileFormat. Возвращает тип содержимого формата файла"
type: docs
weight: 500
url: /ru/net/aspose.threed/fileformat/contenttype/
---
## FileFormat.ContentType property

Получает тип содержимого формата файла

```csharp
public FileContentType ContentType { get; }
```

## Примеры

```csharp
var format = FileFormat.MayaBinary;
if (format.ContentType == FileContentType.Binary)
    Console.WriteLine($"{format} is binary format");
else
    Console.WriteLine($"{format} is text-based format");
```

### См. также

* enum [FileContentType](../../filecontenttype/)
* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


