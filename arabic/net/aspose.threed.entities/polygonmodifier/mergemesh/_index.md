---
title: "PolygonModifier.MergeMesh"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة PolygonModifier. تحويل المشهد بالكامل إلى شبكة واحدة محوّلة. عناصر القمم مثل المتجهات العادية/إحداثيات القوام غير مدعومة بعد."
type: docs
weight: 50
url: /ar/net/aspose.threed.entities/polygonmodifier/mergemesh/
---
## MergeMesh(Scene) {#mergemesh_1}

تحويل المشهد بالكامل إلى شبكة محوّلة واحدة. عناصر القمة مثل إحداثيات الـnormal/texture غير مدعومة بعد.

```csharp
public static Mesh MergeMesh(Scene scene)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| scene | Scene | المشهد المراد دمجه |

### قيمة الإرجاع

الشبكة المدمجة

## أمثلة

الكود التالي يوضح كيفية دمج جميع الكائنات من المشهد في شبكة واحدة.

```csharp
//قد يحتوي ملف الإدخال على عدة كائنات
var scene = Scene.FromFile("input.fbx");
//الآن دمجها في شبكة واحدة
Mesh merged = PolygonModifier.MergeMesh(scene);
//ثم نقوم بحفظها في ملف يحتوي على شبكة واحدة فقط
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### انظر أيضًا

* class [Mesh](../../mesh/)
* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(IList&lt;Node&gt;) {#mergemesh_2}

```csharp
public static Mesh MergeMesh(IList<Node> nodes)
```

### انظر أيضًا

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(Node) {#mergemesh}

تحويل عقدة كاملة إلى شبكة محوّلة واحدة. عناصر القمة مثل إحداثيات الـnormal/texture غير مدعومة بعد.

```csharp
public static Mesh MergeMesh(Node node)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة | العقدة المراد دمجها |

### قيمة الإرجاع

شبكة مدمجة

## أمثلة

يعرض الكود التالي كيفية دمج جميع الكائنات من العقد في شبكة واحدة.

```csharp
//قد يحتوي ملف الإدخال على عدة كائنات
var scene = Scene.FromFile("input.fbx");
//الآن دمجها في شبكة واحدة
Mesh merged = PolygonModifier.MergeMesh(scene.RootNode);
//ثم نقوم بحفظها في ملف يحتوي على شبكة واحدة فقط
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### انظر أيضًا

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


