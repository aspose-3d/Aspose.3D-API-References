---
title: "Matrix4.Scale"
second_title: "Справочник API Aspose.3D для .NET"
description: "Matrix4 метод. Создает матрицу, масштабирующую вдоль осей xaxis yaxis и zaxis"
type: docs
weight: 50
url: /ru/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

Создаёт матрицу, масштабирующую вдоль осей x, y и z.

```csharp
public static Matrix4 Scale(Vector3 s)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | Vector3 | Фабрики масштабирования применяются к x-axis, y-axis и z-axis |

## Примеры

Следующий код показывает, как создать матрицу для операции масштабирования.

```csharp
var t = Matrix4.Scale(new Vector3(10, 10, 10));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double) {#scale_1}

Создаёт матрицу, масштабирующую вдоль осей x, y и z.

```csharp
public static Matrix4 Scale(double s)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | Double | Фабрики масштабирования применяются ко всем axex |

## Примеры

Следующий код показывает, как создать матрицу для операции масштабирования.

```csharp
var t = Matrix4.Scale(10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Создаёт матрицу, масштабирующую вдоль осей x, y и z.

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | Double | Масштабирование фабрик применяется к оси x |
| sy | Double | Масштабирование фабрик применяется к оси y |
| sz | Double | Масштабирование фабрик применяется к оси z |

## Примеры

Следующий код показывает, как создать матрицу для операции масштабирования.

```csharp
var t = Matrix4.Scale(10, 20, 10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


