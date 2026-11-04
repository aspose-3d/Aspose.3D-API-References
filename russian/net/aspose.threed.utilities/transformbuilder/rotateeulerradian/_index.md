---
title: "TransformBuilder.RotateEulerRadian"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TransformBuilder. Добавить вращение по углам Эйлера в радианах в цепочку"
type: docs
weight: 120
url: /ru/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

Сцепить вращение по углам Эйлера в радианах

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(0, Math.PI, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateEulerRadian(Vector3) {#rotateeulerradian}

Сцепить вращение по углам Эйлера в радианах

```csharp
public TransformBuilder RotateEulerRadian(Vector3 r)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| r | Vector3 |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(new Vector3(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


