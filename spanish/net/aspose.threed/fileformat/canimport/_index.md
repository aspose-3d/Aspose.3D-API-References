---
title: "FileFormat.CanImport"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad FileFormat. Obtiene si Aspose.3D admite la importación de escenas desde el formato de archivo actual"
type: docs
weight: 490
url: /es/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

Obtiene si Aspose.3D admite la importación de la escena desde el formato de archivo actual.

```csharp
public bool CanImport { get; }
```

## Ejemplos

El siguiente código muestra cómo comprobar si la importación desde el formato especificado es compatible.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanImport)
    Console.WriteLine($"Can import from {outputFormat}");
```

### Ver también

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


