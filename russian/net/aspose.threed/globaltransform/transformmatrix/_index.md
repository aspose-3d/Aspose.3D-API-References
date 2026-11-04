---
title: "GlobalTransform.TransformMatrix"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство GlobalTransform. Возвращает матрицу преобразования"
type: docs
weight: 40
url: /ru/net/aspose.threed/globaltransform/transformmatrix/
---
## GlobalTransform.TransformMatrix property

Получает матрицу преобразования.

```csharp
public Matrix4 TransformMatrix { get; }
```

## Примеры

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Matrix = {tr.TransformMatrix}");
```

### См. также

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)


