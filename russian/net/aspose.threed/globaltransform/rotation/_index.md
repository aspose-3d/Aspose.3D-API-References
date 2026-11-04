---
title: "GlobalTransform.Rotation"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство GlobalTransform. Получает вращение, представленное кватернионом"
type: docs
weight: 20
url: /ru/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

Получает вращение, представленное кватернионом.

```csharp
public Quaternion Rotation { get; }
```

## Примеры

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Rotation = {tr.Rotation}");
```

### См. также

* struct [Quaternion](../../../aspose.threed.utilities/quaternion/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)


