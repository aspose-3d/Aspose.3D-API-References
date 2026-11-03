---
title: "PolygonModifier.SplitMesh"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة PolygonModifier. تقسيم الشبكة إلى شبكات فرعية حسب VertexElementMaterial. كل شبكة فرعية ستستخدم مادة واحدة فقط. تنفيذ تقسيم الشبكة على عقدة"
type: docs
weight: 70
url: /ar/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

تقسيم الشبكة إلى شبكات فرعية حسب [`VertexElementMaterial`](../../vertexelementmaterial/). كل شبكة فرعية ستستخدم مادة واحدة فقط. تنفيذ تقسيم الشبكة على عقدة

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| العقدة | Node |  |
| سياسة | SplitMeshPolicy |  |
| createChildNodes | Boolean | إنشاء عقد فرعية لكل sub-mesh. |
| removeOldMesh | Boolean | إزالة mesh القديمة بعد الانقسام، إذا كان هذا المعامل خاطئًا، فإن mesh القديمة والجديدة ستتواجدان معًا. |

## أمثلة

الكود التالي يوضح كيفية تقسيم صندوق إلى sub meshes باستخدام مؤشرات المواد.

```csharp
// إنشاء mesh لصندوق (الصندوق يتكون من 6 مستويات)
Mesh box = (new Box()).ToMesh();
// إنشاء عنصر مادة على هذا mesh
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// وتحديد مؤشر مادة مختلف لكل مستوى
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// الآن نقسمه إلى 6 sub meshes، لقد حددنا 6 مواد مختلفة لكل مستوى، كل مستوى سيصبح sub mesh.
// استخدمنا سياسة CloneData، كل مستوى سيحصل على نفس معلومات نقطة التحكم أو معلومات عنصر القمة المستندة إلى نقطة التحكم.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// الآن نقسمه إلى 2 sub meshes، الشبكة الأولى ستحتوي على المستويات 0/1/2، والشبكة الثانية ستحتوي على المستويات 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// استخدمنا سياسة CompactData، كل مستوى سيحصل على معلومات نقطة التحكم الخاصة به أو معلومات عنصر القمة المستندة إلى نقطة التحكم.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### انظر أيضًا

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

تقسيم mesh إلى sub-meshes باستخدام [`VertexElementMaterial`](../../vertexelementmaterial/). كل sub-mesh سيستخدم مادة واحدة فقط. تنفيذ تقسيم mesh على جميع العقد في المشهد.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المشهد | المشهد |  |
| سياسة | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## أمثلة

الكود التالي يوضح كيفية تقسيم صندوق إلى sub meshes باستخدام مؤشرات المواد.

```csharp
// إنشاء mesh لصندوق (الصندوق يتكون من 6 مستويات)
Mesh box = (new Box()).ToMesh();
// إنشاء عنصر مادة على هذا mesh
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// وتحديد مؤشر مادة مختلف لكل مستوى
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// الآن نقسمه إلى 6 sub meshes، لقد حددنا 6 مواد مختلفة لكل مستوى، كل مستوى سيصبح sub mesh.
// استخدمنا سياسة CloneData، كل مستوى سيحصل على نفس معلومات نقطة التحكم أو معلومات عنصر القمة المستندة إلى نقطة التحكم.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// الآن نقسمه إلى 2 sub meshes، الشبكة الأولى ستحتوي على المستويات 0/1/2، والشبكة الثانية ستحتوي على المستويات 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// استخدمنا سياسة CompactData، كل مستوى سيحصل على معلومات نقطة التحكم الخاصة به أو معلومات عنصر القمة المستندة إلى نقطة التحكم.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### انظر أيضًا

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

تقسيم mesh إلى sub-meshes باستخدام [`VertexElementMaterial`](../../vertexelementmaterial/). كل sub-mesh سيستخدم مادة واحدة فقط. mesh الأصلي لن يتغير.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### قيمة الإرجاع

شبكات مقسمة جديدة

## أمثلة

الكود التالي يوضح كيفية تقسيم صندوق إلى sub meshes باستخدام مؤشرات المواد.

```csharp
// إنشاء mesh لصندوق (الصندوق يتكون من 6 مستويات)
Mesh box = (new Box()).ToMesh();
// إنشاء عنصر مادة على هذا mesh
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// وتحديد مؤشر مادة مختلف لكل مستوى
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// الآن نقسمه إلى 6 sub meshes، لقد حددنا 6 مواد مختلفة لكل مستوى، كل مستوى سيصبح sub mesh.
// استخدمنا سياسة CloneData، كل مستوى سيحصل على نفس معلومات نقطة التحكم أو معلومات عنصر القمة المستندة إلى نقطة التحكم.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// الآن نقسمه إلى 2 sub meshes، الشبكة الأولى ستحتوي على المستويات 0/1/2، والشبكة الثانية ستحتوي على المستويات 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// استخدمنا سياسة CompactData، كل مستوى سيحصل على معلومات نقطة التحكم الخاصة به أو معلومات عنصر القمة المستندة إلى نقطة التحكم.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### انظر أيضًا

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


