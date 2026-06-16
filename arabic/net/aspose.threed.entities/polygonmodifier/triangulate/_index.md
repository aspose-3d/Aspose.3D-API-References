---
title: "PolygonModifier.Triangulate"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة PolygonModifier. تحويل جميع الشبكات القائمة على المضلع إلى شبكة مثلثية كاملة"
type: docs
weight: 80
url: /ar/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

حوّل جميع الشبكات المبنية على مضلعات إلى شبكة مثلثية كاملة

```csharp
public static void Triangulate(Scene scene)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| scene | Scene | المشهد المراد معالجته |

## أمثلة

الكود التالي يوضح كيفية دمج جميع الكائنات من المشهد في شبكة واحدة.

```csharp
var mesh = new Cylinder().ToMesh();

//قم بتحويل هذه الشبكة القائمة على رباعيات إلى شبكة قائمة على مثلثات
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### انظر أيضًا

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

حوّل شبكة مبنية على مضلعات إلى شبكة مثلثية كاملة

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| شبكة | Mesh | الشبكة الأصلية غير المثلثية |

### قيمة الإرجاع

الشبكة المثلثية الجديدة المولدة

## أمثلة

الكود التالي يوضح كيفية دمج جميع الكائنات من المشهد في شبكة واحدة.

```csharp
var mesh = new Cylinder().ToMesh();

//قم بتحويل هذه الشبكة القائمة على رباعيات إلى شبكة قائمة على مثلثات
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### انظر أيضًا

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

### انظر أيضًا

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

### انظر أيضًا

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### انظر أيضًا

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### انظر أيضًا

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


