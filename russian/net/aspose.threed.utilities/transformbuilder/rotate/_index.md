---
title: "TransformBuilder.Rotate"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TransformBuilder. Последовательное применение вращения с помощью кватерниона"
type: docs
weight: 90
url: /ru/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

Добавьте вращение с помощью кватерниона

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| q | Кватернион |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Rotate(Quaternion.FromEulerAngle(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* struct [Quaternion](../../quaternion/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


