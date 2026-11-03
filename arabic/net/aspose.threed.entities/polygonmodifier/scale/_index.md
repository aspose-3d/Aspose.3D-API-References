---
title: "PolygonModifier.Scale"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة PolygonModifier. قم بتكبير جميع الأشكال (Scale) نقاط التحكم وليس مصفوفة التحويل في هذا المشهد"
type: docs
weight: 60
url: /ar/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

تكبير جميع الأشكال (Scale نقاط التحكم وليس مصفوفة التحويل) في هذا المشهد

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المشهد | المشهد | المشهد المراد تكبيره |
| تحجيم | Vector3 | عامل التكبير |

## أمثلة

الكود التالي يوضح كيفية تكبير جميع الأشكال في المشهد بمقدار 10 مرات.

```csharp
//تحميل ملف اختبار للتكبير
var scene = Scene.FromFile("input.fbx");
//قُم بتكبير جميع الهندسات 10 مرات.
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

قُم بتكبير جميع الهندسات(قُم بتكبير نقاط التحكم وليس مصفوفة التحويل) في هذه العقدة

```csharp
public static void Scale(Node node, Vector3 scale)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| العقدة | Node | العقدة المراد تكبيرها |
| تحجيم | Vector3 | عامل التكبير |

## أمثلة

الكود التالي يوضح كيفية تكبير جميع الأشكال في المشهد بمقدار 10 مرات.

```csharp
//تحميل ملف اختبار للتكبير
var scene = Scene.FromFile("input.fbx");
//قُم بتكبير جميع الهندسات 10 مرات.
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### انظر أيضًا

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


