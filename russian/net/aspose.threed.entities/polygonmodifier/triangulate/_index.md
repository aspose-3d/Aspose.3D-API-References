---
title: "PolygonModifier.Triangulate"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PolygonModifier. Преобразовать все полигональные меши в полноценный треугольный меш"
type: docs
weight: 80
url: /ru/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

Преобразуйте все полигональные сетки в полные треугольные сетки

```csharp
public static void Triangulate(Scene scene)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сцена | Сцена | Сцена для обработки |

## Примеры

Следующий код показывает, как объединить все объекты из сцены в один меш.

```csharp
var mesh = new Cylinder().ToMesh();

//Триангулировать этот основанный на квадратах меш в треугольный
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### См. также

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

Преобразуйте полигональную сетку в полную треугольную сетку

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mesh | Сетка | Исходный не‑треугольный меш |

### Возвращаемое значение

Сгенерированный новый треугольный меш

## Примеры

Следующий код показывает, как объединить все объекты из сцены в один меш.

```csharp
var mesh = new Cylinder().ToMesh();

//Триангулировать этот основанный на квадратах меш в треугольный
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### См. также

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) {#triangulate_4}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons, 
    bool generateNormals, out Vector3[] nor_out)
```

### См. также

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) {#triangulate_3}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons)
```

### См. также

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### См. также

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### См. также

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


