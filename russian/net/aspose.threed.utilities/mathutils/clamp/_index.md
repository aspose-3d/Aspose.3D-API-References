---
title: "MathUtils.Clamp"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод MathUtils. Ограничить значение диапазоном min‑max"
type: docs
weight: 20
url: /ru/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

Ограничить значение диапазоном [min, max]

```csharp
public static double Clamp(double val, double min, double max)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| val | Double | Значение для ограничения. |
| min | Double | Минимальное значение. |
| max | Double | Максимальное значение. |

### Возвращаемое значение

Значение между [min, max]

## Примеры

```csharp
var val = 195;
//Ограничить значение до [0, 100]
var clampedValue = MathUtils.Clamp(val, 0, 100);
//Это выведет 100
Console.WriteLine($"Value = {val}");
```

### См. также

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)


