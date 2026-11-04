---
title: "BoundingBox.op_Multiply"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод BoundingBox. Перегрузка оператора умножения: минимум и максимум нового ограничивающего прямоугольника преобразуются матрицей."
type: docs
weight: 170
url: /ru/net/aspose.threed.utilities/boundingbox/op_multiply/
---
## BoundingBox Multiply operator

Перегрузка оператора умножения, минимальный и максимальный угол нового ограничивающего прямоугольника будут трансформированы матрицей.

```csharp
public static BoundingBox operator *(BoundingBox bbox, Matrix4 mat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bbox | BoundingBox | Входной ограничивающий прямоугольник. |
| mat | Matrix4 | Матрица, используемая для преобразования углов ограничивающего прямоугольника |

### Возвращаемое значение

Результат умножения ограничивающего прямоугольника на матрицу преобразования.

### См. также

* struct [Matrix4](../../matrix4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


