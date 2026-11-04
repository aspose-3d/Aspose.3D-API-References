---
title: "Matrix4.Concatenate"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Matrix4. Объединяет две матрицы"
type: docs
weight: 240
url: /ru/net/aspose.threed.utilities/matrix4/concatenate/
---
## Matrix4.Concatenate method

Объединяет две матрицы

```csharp
public Matrix4 Concatenate(Matrix4 m2)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

### Возвращаемое значение

Новая matrix4

## Примеры

```csharp
var t = Matrix4.Translate(0, 10, 9);
var s = Matrix4.Scale(10, 10, 10);
var transform = t.Concatenate(s);
var pos = new Vector3(10, 0, -1);
var transformed = transform * pos;
```

### См. также

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


