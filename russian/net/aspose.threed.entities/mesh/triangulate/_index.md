---
title: "Mesh.Triangulate"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Mesh. Возвращает триангулированную сетку"
type: docs
weight: 120
url: /ru/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Возвращает триангулированную сетку

```csharp
public Mesh Triangulate()
```

### Возвращаемое значение

Текущая сетка, если она уже триангулирована; в противном случае будет вычислена и возвращена новая триангулированная сетка

## Примеры

Следующий код показывает, как триангулировать сетку:

```csharp
//Плоская сетка содержит только один полигон с 4 контрольными точками
var mesh = (new Plane()).ToMesh();
//После триангуляции прямоугольник новой сетки превратится в 2 треугольника.
var triangulated = mesh.Triangulate();
```

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


