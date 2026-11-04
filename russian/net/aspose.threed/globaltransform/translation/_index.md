---
title: "GlobalTransform.Translation"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство GlobalTransform. Получает трансляцию"
type: docs
weight: 50
url: /ru/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

Получает трансляцию

```csharp
public Vector3 Translation { get; }
```

## Примеры

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Translation = {tr.Translation}");
```

### См. также

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)


