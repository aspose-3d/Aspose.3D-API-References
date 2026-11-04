---
title: "Mesh.op_Subtraction"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Mesh. Вычисляет разность двух сеток"
type: docs
weight: 150
url: /ru/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

Вычислить разницу двух сеток

```csharp
public static Mesh operator -(Mesh a, Mesh b)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | Сетка | Первая сетка |
| b | Сетка | Вторая сетка |

### Возвращаемое значение

Результирующая сетка

## Примеры

Следующий код показывает, как вычислить разность двух сеток:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 - box2;
```

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


