---
title: "GlobalTransform.EulerAngles"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство GlobalTransform. Получает вращение, представленное углами Эйлера, измеренными в градусах"
type: docs
weight: 10
url: /ru/net/aspose.threed/globaltransform/eulerangles/
---
## GlobalTransform.EulerAngles property

Получает вращение, представленное в углах Эйлера, измеряемое в градусах

```csharp
public Vector3 EulerAngles { get; }
```

## Примеры

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"EulerAngles = {tr.EulerAngles}");
```

### См. также

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)


