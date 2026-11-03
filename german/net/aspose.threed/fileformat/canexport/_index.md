---
title: "FileFormat.CanExport"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FileFormat Eigenschaft. Gibt an, ob Aspose.3D den Export einer Szene in das aktuelle Dateiformat unterstützt"
type: docs
weight: 480
url: /de/net/aspose.threed/fileformat/canexport/
---
## FileFormat.CanExport property

Liest, ob Aspose.3D den Export der Szene in das aktuelle Dateiformat unterstützt.

```csharp
public bool CanExport { get; }
```

## Beispiele

Der folgende Code zeigt, wie geprüft wird, ob das Exportieren in das angegebene Format unterstützt wird.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanExport)
    Console.WriteLine($"Can export to {outputFormat}");
```

### Siehe auch

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


