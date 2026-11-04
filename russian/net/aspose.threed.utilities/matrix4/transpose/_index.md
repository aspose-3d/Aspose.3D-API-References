---
title: "Matrix4.Transpose"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Matrix4. Транспонирует этот экземпляр"
type: docs
weight: 310
url: /ru/net/aspose.threed.utilities/matrix4/transpose/
---
## Matrix4.Transpose method

Транспонирует этот экземпляр.

```csharp
public Matrix4 Transpose()
```

### Возвращаемое значение

Транспонированная матрица.

## Примеры

Следующий код показывает, как транспонировать матрицу

```csharp
var t = Matrix4.Translate(0, 10, 9);
var mat = t.Transpose();
Console.WriteLine($"Transposed Matrix: {mat}");
```

### См. также

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


