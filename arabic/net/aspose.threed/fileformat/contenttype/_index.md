---
title: "FileFormat.ContentType"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية FileFormat. يحصل على نوع محتوى تنسيق الملف"
type: docs
weight: 500
url: /ar/net/aspose.threed/fileformat/contenttype/
---
## FileFormat.ContentType property

يحصل على نوع محتوى تنسيق الملف

```csharp
public FileContentType ContentType { get; }
```

## أمثلة

```csharp
var format = FileFormat.MayaBinary;
if (format.ContentType == FileContentType.Binary)
    Console.WriteLine($"{format} is binary format");
else
    Console.WriteLine($"{format} is text-based format");
```

### انظر أيضًا

* enum [FileContentType](../../filecontenttype/)
* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


