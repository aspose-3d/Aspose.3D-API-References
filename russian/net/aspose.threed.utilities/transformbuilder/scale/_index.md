---
title: "TransformBuilder.Scale"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TransformBuilder. Последовательное применение матрицы масштабирования, где компонент масштабируется на s"
type: docs
weight: 140
url: /ru/net/aspose.threed.utilities/transformbuilder/scale/
---
## Scale(double) {#scale_1}

Сцепить матрицу масштабирующего преобразования, где компонент масштабирован на s

```csharp
public TransformBuilder Scale(double s)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | Double |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Сцепить матрицу масштабирующего преобразования

```csharp
public TransformBuilder Scale(double x, double y, double z)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10, 10, 10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(Vector3) {#scale}

Сцепить масштабирующее преобразование

```csharp
public TransformBuilder Scale(Vector3 s)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | Vector3 |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(new Vector3(10, 10, 10));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


