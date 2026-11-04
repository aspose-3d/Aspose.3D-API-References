---
title: "Класс NurbsDirection"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.NurbsDirection. 3D NurbsSurface имеет два направления — U и V, класс NurbsDirection определяет данные для каждого направления. Направление представляет собой кривую NURBS, что означает, что оно также определяется своим Order, KnotVectors и набором взвешенных контрольных точек, определённых в NurbsSurface."
type: docs
weight: 530
url: /ru/net/aspose.threed.entities/nurbsdirection/
---
## NurbsDirection class

3D [`NurbsSurface`](../nurbssurface/) имеет два направления — [`U`](../nurbssurface/u/) и [`V`](../nurbssurface/v/), `NurbsDirection` определяет данные для каждого направления. Направление представляет собой кривую NURBS, что означает, что оно также определяется своим [`Order`](./order/), [`KnotVectors`](./knotvectors/) и набором взвешенных контрольных точек (определённых в [`NurbsSurface`](../nurbssurface/)).

```csharp
public class NurbsDirection
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NurbsDirection](nurbsdirection/)() | Создать новый экземпляр `NurbsDirection` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.threed.entities/nurbsdirection/count/) { get; set; } | Получает или задает количество контрольных точек в текущем направлении. |
| [Degree](../../aspose.threed.entities/nurbsdirection/degree/) { get; set; } | Получает или задает степень NURBS‑кривой, степень определяется как Порядок - 1 |
| [Divisions](../../aspose.threed.entities/nurbsdirection/divisions/) { get; set; } | Получает или задаёт количество делений между соседними контрольными точками в текущем направлении. |
| [KnotVectors](../../aspose.threed.entities/nurbsdirection/knotvectors/) { get; } | Получает вектор узлов; это последовательность параметрических значений, определяющая, где и как контрольные точки влияют на NURBS‑кривую. |
| [Multiplicity](../../aspose.threed.entities/nurbsdirection/multiplicity/) { get; } | Получает мультипликативность. |
| [Order](../../aspose.threed.entities/nurbsdirection/order/) { get; set; } | Получает или задает порядок NURBS‑кривой; он определяет количество соседних контрольных точек, влияющих на любую точку кривой. |
| [Type](../../aspose.threed.entities/nurbsdirection/type/) { get; set; } | Получает или задаёт тип текущего направления. |

### См. также

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


