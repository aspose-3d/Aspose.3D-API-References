---
title: "FileFormat.ContentType"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "FileFormat ιδιότητα. Λαμβάνει τύπο περιεχομένου μορφής αρχείου"
type: docs
weight: 500
url: /el/net/aspose.threed/fileformat/contenttype/
---
## FileFormat.ContentType property

Λαμβάνει τον τύπο περιεχομένου της μορφής αρχείου

```csharp
public FileContentType ContentType { get; }
```

## Παραδείγματα

```csharp
var format = FileFormat.MayaBinary;
if (format.ContentType == FileContentType.Binary)
    Console.WriteLine($"{format} is binary format");
else
    Console.WriteLine($"{format} is text-based format");
```

### Δείτε επίσης

* enum [FileContentType](../../filecontenttype/)
* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


