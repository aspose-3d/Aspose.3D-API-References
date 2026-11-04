---
title: "Matrix4.Translate"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Matrix4. Создает матрицу, которая перемещает вдоль оси x, оси y и оси z"
type: docs
weight: 60
url: /ru/net/aspose.threed.utilities/matrix4/translate/
---
## Translate(Vector3) {#translate}

Создаёт матрицу, перемещающую вдоль осей x, y и z

```csharp
public static Matrix4 Translate(Vector3 t)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| t | Vector3 | Смещение трансляции |

## Примеры

Следующий код показывает, как создать матрицу для операции трансляции.

```csharp
var t = Matrix4.Translate(new Vector3(10, 0, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Translate(double, double, double) {#translate_1}

Создаёт матрицу, перемещающую вдоль осей x, y и z

```csharp
public static Matrix4 Translate(double tx, double ty, double tz)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| tx | Double | Смещение координаты X |
| ty | Double | Смещение координаты Y |
| tz | Double | Смещение координаты Z |

## Примеры

Следующий код показывает, как создать матрицу для операции трансляции.

```csharp
var t = Matrix4.Translate(10, 0, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### См. также

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


