---
title: "Класс AxisSystem"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.AxisSystem class. Система осей — это комбинация вектора вверх и вектора вперёд координатной системы"
type: docs
weight: 150
url: /ru/net/aspose.threed/axissystem/
---
## AxisSystem class

Система координат представляет собой комбинацию системы координат, вектора вверх и вектора вперёд.

```csharp
public class AxisSystem
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AxisSystem](axissystem/#constructor)(Axis, Axis?) |  |
| [AxisSystem](axissystem/#constructor_1)(CoordinateSystem, Axis) | Создаёт новую систему осей |
| [AxisSystem](axissystem/#constructor_2)(CoordinateSystem, Axis, Axis) | Создаёт новую систему осей |
| [AxisSystem](axissystem/#constructor_3)(CoordinateSystem?, Axis?, Axis?) |  |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateSystem](../../aspose.threed/axissystem/coordinatesystem/) { get; } | Получает координатную систему этой системы осей. |
| [Front](../../aspose.threed/axissystem/front/) { get; } | Получает вектор передней части этой системы осей |
| [Up](../../aspose.threed/axissystem/up/) { get; } | Получает вектор вверх этой системы осей. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromAssetInfo](../../aspose.threed/axissystem/fromassetinfo/)(AssetInfo) | Создать `AxisSystem` из [`AssetInfo`](../assetinfo/) |
| [TransformTo](../../aspose.threed/axissystem/transformto/)(AxisSystem) | Создать матрицу, используемую для преобразования из текущей системы осей в целевую систему осей. |

### См. также

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


