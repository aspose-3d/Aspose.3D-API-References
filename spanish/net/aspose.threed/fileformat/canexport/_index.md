---
title: "FileFormat.CanExport"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "FileFormat propiedad. Obtiene si Aspose.3D soporta exportar la escena al formato de archivo actual"
type: docs
weight: 480
url: /es/net/aspose.threed/fileformat/canexport/
---
## FileFormat.CanExport property

Obtiene si Aspose.3D admite la exportación de la escena al formato de archivo actual.

```csharp
public bool CanExport { get; }
```

## Ejemplos

El siguiente código muestra cómo comprobar si la exportación al formato especificado es compatible.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanExport)
    Console.WriteLine($"Can export to {outputFormat}");
```

### Ver también

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


