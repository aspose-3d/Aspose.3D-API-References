---
title: "Mesh.PolygonCount"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Mesh. Возвращает количество полигонов"
type: docs
weight: 40
url: /ru/net/aspose.threed.entities/mesh/polygoncount/
---
## Mesh.PolygonCount property

Получает количество полигонов

```csharp
public int PolygonCount { get; }
```

### Property Value

Количество полигонов.

## Примеры

Следующий код показывает, как получить количество полигонов сетки.

```csharp
var mesh = (new Sphere()).ToMesh();
Console.WriteLine("Mesh's polygon count = " + mesh.PolygonCount);
```

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


