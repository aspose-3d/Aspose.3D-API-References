---
title: "Matrix4.RotateFromEuler"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Matrix4. Создаёт матрицу вращения из угла Эйлера"
type: docs
weight: 40
url: /ru/net/aspose.threed.utilities/matrix4/rotatefromeuler/
---
## RotateFromEuler(Vector3) {#rotatefromeuler}

Создайте матрицу вращения из угла Эйлера

```csharp
public static Matrix4 RotateFromEuler(Vector3 eul)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| eul | Vector3 | Вращение в радианах |

## Примеры

Следующий код показывает, как создать матрицу для операции вращения.

```csharp
var t = Matrix4.RotateFromEuler(new Vector3(0, Math.PI, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## RotateFromEuler(double, double, double) {#rotatefromeuler_1}

Создайте матрицу вращения из угла Эйлера

```csharp
public static Matrix4 RotateFromEuler(double rx, double ry, double rz)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rx | Double | Вращение вокруг оси x в радианах |
| ry | Double | Вращение вокруг оси y в радианах |
| rz | Double | Вращение вокруг оси z в радианах |

## Примеры

Следующий код показывает, как создать матрицу для операции вращения.

```csharp
var t = Matrix4.RotateFromEuler(0, Math.PI, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


