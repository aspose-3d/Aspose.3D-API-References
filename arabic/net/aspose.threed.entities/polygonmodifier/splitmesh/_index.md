---
title: "PolygonModifier.SplitMesh"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة PolygonModifier. تقسيم الشبكة إلى شبكات فرعية باستخدام VertexElementMaterial. كل شبكة فرعية ستستخدم مادة واحدة فقط. تنفيذ تقسيم الشبكة على عقدة."
type: docs
weight: 70
url: /ar/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

تقسيم الشبكة إلى شبكات فرعية باستخدام [`VertexElementMaterial`](../../vertexelementmaterial/). كل شبكة فرعية ستستخدم مادة واحدة فقط. تنفيذ تقسيم الشبكة على عقدة.

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة |  |
| سياسة | SplitMeshPolicy |  |
| createChildNodes | Boolean | إنشاء عقد فرعية لكل شبكة فرعية. |
| removeOldMesh | Boolean | إزالة الشبكة القديمة بعد التقسيم، إذا كان هذا المعامل false، ستتواجد الشبكتان القديمة والجديدة معًا. |

## أمثلة

الكود التالي يوضح كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد.

```csharp
// إنشاء شبكة لصندوق (الصندوق يتكون من 6 مستويات)
Mesh box = (new Box()).ToMesh();
// إنشاء عنصر مادة على هذه الشبكة
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// وتحديد فهرس مادة مختلف لكل مستوى
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// الآن قسّمه إلى 6 شبكات فرعية، حددنا 6 مواد مختلفة على كل سطح، كل سطح سيصبح شبكة فرعية.
// استخدمنا سياسة CloneData، كل سطح سيحصل على نفس معلومات نقطة التحكم أو معلومات عنصر الرأس القائم على نقطة التحكم.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// الآن قسّمه إلى شبكتين فرعيتين، الشبكة الأولى ستحتوي على الأسطح 0/1/2، والشبكة الثانية ستحتوي على الأسطح 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// استخدمنا سياسة CompactData، كل سطح سيحصل على معلومات نقطة التحكم الخاصة به أو معلومات عنصر الرأس القائم على نقطة التحكم.
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

تقسيم الشبكة إلى شبكات فرعية باستخدام [`VertexElementMaterial`](../../vertexelementmaterial/). كل شبكة فرعية ستستخدم مادة واحدة فقط. تنفيذ تقسيم الشبكة على جميع عقد المشهد.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| scene | Scene |  |
| سياسة | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## أمثلة

الكود التالي يوضح كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد.

```csharp
// إنشاء شبكة لصندوق (الصندوق يتكون من 6 مستويات)
Mesh box = (new Box()).ToMesh();
// إنشاء عنصر مادة على هذه الشبكة
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// وتحديد فهرس مادة مختلف لكل مستوى
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// الآن قسّمه إلى 6 شبكات فرعية، حددنا 6 مواد مختلفة على كل سطح، كل سطح سيصبح شبكة فرعية.
// استخدمنا سياسة CloneData، كل سطح سيحصل على نفس معلومات نقطة التحكم أو معلومات عنصر الرأس القائم على نقطة التحكم.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// الآن قسّمه إلى شبكتين فرعيتين، الشبكة الأولى ستحتوي على الأسطح 0/1/2، والشبكة الثانية ستحتوي على الأسطح 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// استخدمنا سياسة CompactData، كل سطح سيحصل على معلومات نقطة التحكم الخاصة به أو معلومات عنصر الرأس القائم على نقطة التحكم.
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

تقسيم الشبكة إلى شبكات فرعية باستخدام [`VertexElementMaterial`](../../vertexelementmaterial/). كل شبكة فرعية ستستخدم مادة واحدة فقط. الشبكة الأصلية لن تتغير.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### قيمة الإرجاع

شبكات مقسمة جديدة

## أمثلة

الكود التالي يوضح كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد.

```csharp
// إنشاء شبكة لصندوق (الصندوق يتكون من 6 مستويات)
Mesh box = (new Box()).ToMesh();
// إنشاء عنصر مادة على هذه الشبكة
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// وتحديد فهرس مادة مختلف لكل مستوى
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// الآن قسّمه إلى 6 شبكات فرعية، حددنا 6 مواد مختلفة على كل سطح، كل سطح سيصبح شبكة فرعية.
// استخدمنا سياسة CloneData، كل سطح سيحصل على نفس معلومات نقطة التحكم أو معلومات عنصر الرأس القائم على نقطة التحكم.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// الآن قسّمه إلى شبكتين فرعيتين، الشبكة الأولى ستحتوي على الأسطح 0/1/2، والشبكة الثانية ستحتوي على الأسطح 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// استخدمنا سياسة CompactData، كل سطح سيحصل على معلومات نقطة التحكم الخاصة به أو معلومات عنصر الرأس القائم على نقطة التحكم.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### انظر أيضًا

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


