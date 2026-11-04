---
title: "Matrix4.Inverse"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Matrix4. Инвертирует этот экземпляр"
type: docs
weight: 260
url: /ru/net/aspose.threed.utilities/matrix4/inverse/
---
## Matrix4.Inverse method

Инвертирует этот экземпляр.

```csharp
public Matrix4 Inverse()
```

### Возвращаемое значение

Обратная матрица4

## Примеры

Следующий код показывает, как инвертировать матрицу

```csharp
var t = Matrix4.Translate(0, 10, 9);
var mat = t.Inverse();
Console.WriteLine($"Inversed Matrix: {mat}");
```

### См. также

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


