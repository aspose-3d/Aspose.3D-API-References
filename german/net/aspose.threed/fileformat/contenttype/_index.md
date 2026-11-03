---
title: "FileFormat.ContentType"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FileFormat-Eigenschaft. Gibt den Inhaltstyp des Dateiformats zurück"
type: docs
weight: 500
url: /de/net/aspose.threed/fileformat/contenttype/
---
## FileFormat.ContentType property

Liest den Inhaltstyp des Dateiformats

```csharp
public FileContentType ContentType { get; }
```

## Beispiele

```csharp
var format = FileFormat.MayaBinary;
if (format.ContentType == FileContentType.Binary)
    Console.WriteLine($"{format} is binary format");
else
    Console.WriteLine($"{format} is text-based format");
```

### Siehe auch

* enum [FileContentType](../../filecontenttype/)
* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


