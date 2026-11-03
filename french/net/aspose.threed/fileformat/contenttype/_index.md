---
title: "FileFormat.ContentType"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété FileFormat. Obtient le type de contenu du format de fichier"
type: docs
weight: 500
url: /fr/net/aspose.threed/fileformat/contenttype/
---
## FileFormat.ContentType property

Obtient le type de contenu du format de fichier

```csharp
public FileContentType ContentType { get; }
```

## Exemples

```csharp
var format = FileFormat.MayaBinary;
if (format.ContentType == FileContentType.Binary)
    Console.WriteLine($"{format} is binary format");
else
    Console.WriteLine($"{format} is text-based format");
```

### Voir aussi

* enum [FileContentType](../../filecontenttype/)
* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


