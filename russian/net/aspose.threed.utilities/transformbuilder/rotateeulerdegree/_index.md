---
title: "TransformBuilder.RotateEulerDegree"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TransformBuilder. Последовательное применение вращения по углам Эйлера в градусах"
type: docs
weight: 110
url: /ru/net/aspose.threed.utilities/transformbuilder/rotateeulerdegree/
---
## TransformBuilder.RotateEulerDegree method

Сцепить вращение по углам Эйлера в градусах

```csharp
public TransformBuilder RotateEulerDegree(double degX, double degY, double degZ)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| degX | Double |  |
| degY | Double |  |
| degZ | Double |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerDegree(0, 90, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


