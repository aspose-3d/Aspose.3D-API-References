---
title: "PolygonModifier.Scale"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة PolygonModifier. تكبير جميع الأشكال. تكبير نقاط التحكم وليس مصفوفة التحويل في هذا المشهد."
type: docs
weight: 60
url: /ar/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

قُم بتكبير جميع الأشكال (قم بتكبير نقاط التحكم وليس مصفوفة التحويل) في هذا المشهد

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| scene | Scene | المشهد المراد تكبيره |
| تحجيم | Vector3 | عامل التكبير |

## أمثلة

يعرض الكود التالي كيفية تكبير جميع الأشكال الهندسية في المشهد بمقدار 10 أضعاف.

```csharp
//تحميل ملف اختبار للتكبير
var scene = Scene.FromFile("input.fbx");
//تكبير جميع الأشكال الهندسية 10 أضعاف.
PolygonModifier.Scale(scene, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### انظر أيضًا

* class [Scene](../../../aspose.threed/scene/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Scale(Node, Vector3) {#scale_1}

قُم بتكبير جميع الأشكال الهندسية (قم بتكبير نقاط التحكم وليس مصفوفة التحويل) في هذه العقدة.

```csharp
public static void Scale(Node node, Vector3 scale)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة | العقدة المراد تكبيرها |
| تحجيم | Vector3 | عامل التكبير |

## أمثلة

يعرض الكود التالي كيفية تكبير جميع الأشكال الهندسية في المشهد بمقدار 10 أضعاف.

```csharp
//تحميل ملف اختبار للتكبير
var scene = Scene.FromFile("input.fbx");
//تكبير جميع الأشكال الهندسية 10 أضعاف.
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### انظر أيضًا

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


