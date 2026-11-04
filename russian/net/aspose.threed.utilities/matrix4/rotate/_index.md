---
title: "Matrix4.Rotate"
second_title: "Справочник API Aspose.3D для .NET"
description: "Matrix4 method. Создает матрицу вращения по углу вращения и оси"
type: docs
weight: 30
url: /ru/net/aspose.threed.utilities/matrix4/rotate/
---
## Rotate(double, Vector3) {#rotate_1}

Создайте матрицу вращения по углу вращения и оси

```csharp
public static Matrix4 Rotate(double angle, Vector3 axis)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | Double | Угол вращения в радианах |
| ось | Vector3 | Ось вращения |

## Примеры

Следующий код показывает, как создать матрицу для операции вращения.

```csharp
var t = Matrix4.Rotate(Math.PI, new Vector3(0, 1, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Rotate(Quaternion) {#rotate}

Создайте матрицу вращения из кватерниона

```csharp
public static Matrix4 Rotate(Quaternion q)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| q | Кватернион | Кватернион вращения |

## Примеры

Следующий код показывает, как создать матрицу для операции вращения.

```csharp
var t = Matrix4.Rotate(Quaternion.FromAngleAxis(Math.PI, Vector3.YAxis));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Quaternion](../../quaternion/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


