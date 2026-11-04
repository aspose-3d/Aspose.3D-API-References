---
title: "GlobalTransform.Scale"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство GlobalTransform. Возвращает масштаб"
type: docs
weight: 30
url: /ru/net/aspose.threed/globaltransform/scale/
---
## GlobalTransform.Scale property

Получает масштаб

```csharp
public Vector3 Scale { get; }
```

## Примеры

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Scale = {tr.Scale}");
```

### См. также

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)


