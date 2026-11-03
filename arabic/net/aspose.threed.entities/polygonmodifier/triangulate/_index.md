---
title: "PolygonModifier.Triangulate"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة PolygonModifier. حوّل جميع الشبكات القائمة على المضلعات إلى شبكة مثلثية كاملة"
type: docs
weight: 80
url: /ar/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

حوّل جميع الشبكات القائمة على المضلعات إلى شبكة مثلثية كاملة

```csharp
public static void Triangulate(Scene scene)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المشهد | المشهد | المشهد المراد معالجته |

## أمثلة

يظهر الكود التالي كيفية دمج جميع الكائنات من المشهد في شبكة واحدة.

```csharp
var mesh = new Cylinder().ToMesh();

//تحويل هذه الشبكة القائمة على رباعيات إلى شبكة قائمة على مثلثات 
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

تحويل شبكة قائمة على مضلعات إلى شبكة مثلثية كاملة

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| شبكة | شبكة | الشبكة الأصلية غير المثلثية |

### قيمة الإرجاع

الشكة المثلثية الجديدة التي تم إنشاؤها

## أمثلة

يظهر الكود التالي كيفية دمج جميع الكائنات من المشهد في شبكة واحدة.

```csharp
var mesh = new Cylinder().ToMesh();

//تحويل هذه الشبكة القائمة على رباعيات إلى شبكة قائمة على مثلثات 
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


