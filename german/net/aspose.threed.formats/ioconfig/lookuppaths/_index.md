---
title: "IOConfig.LookupPaths"
second_title: "Aspose.3D für .NET API-Referenz"
description: "IOConfig-Eigenschaft. Einige Dateien wie OBJ hängen von externen Dateien ab; die Suchpfade ermöglichen Aspose.3D, nach externen Dateien zum Laden zu suchen"
type: docs
weight: 50
url: /de/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen.

```csharp
public List<string> LookupPaths { get; set; }
```

## Beispiele

Der folgende Code zeigt, wie man die Lookup-Texturen manuell angibt, damit der Importer sie finden kann

```csharp
var opt = new ObjLoadOptions();
//Geben Sie die Lookup-Pfade an, damit die Texturen gefunden werden können.
opt.LookupPaths.Add("textures");
var scene = Scene.FromFile("input.obj", opt);
scene.Save("output.glb");
```

### Siehe auch

* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


