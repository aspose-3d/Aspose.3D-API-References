---
title: "FileFormat.CanImport"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FileFormat-Eigenschaft. Gibt an, ob Aspose.3D das Importieren einer Szene aus dem aktuellen Dateiformat unterstützt."
type: docs
weight: 490
url: /de/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

Liest, ob Aspose.3D den Import der Szene aus dem aktuellen Dateiformat unterstützt.

```csharp
public bool CanImport { get; }
```

## Beispiele

Der folgende Code zeigt, wie man prüft, ob das Importieren aus dem angegebenen Format unterstützt wird.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanImport)
    Console.WriteLine($"Can import from {outputFormat}");
```

### Siehe auch

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


