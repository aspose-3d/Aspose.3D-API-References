---
title: "FileFormat.ContentType"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "FileFormat propiedad. Obtiene el tipo de contenido del formato de archivo"
type: docs
weight: 500
url: /es/net/aspose.threed/fileformat/contenttype/
---
## FileFormat.ContentType property

Obtiene el tipo de contenido del formato de archivo

```csharp
public FileContentType ContentType { get; }
```

## Ejemplos

```csharp
var format = FileFormat.MayaBinary;
if (format.ContentType == FileContentType.Binary)
    Console.WriteLine($"{format} is binary format");
else
    Console.WriteLine($"{format} is text-based format");
```

### Ver también

* enum [FileContentType](../../filecontenttype/)
* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


