---
title: "الفئة SweptAreaSolid"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.SweptAreaSolid فئة. يقوم SweptAreaSolid بإنشاء هندسة عن طريق مسح ملف تعريف على طول directrix."
type: docs
weight: 750
url: /ar/net/aspose.threed.entities/sweptareasolid/
---
## SweptAreaSolid class

يقوم `SweptAreaSolid` بإنشاء هندسة عن طريق مسح ملف تعريف على طول directrix.

```csharp
public class SweptAreaSolid : Entity, IMeshConvertible
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [SweptAreaSolid](sweptareasolid/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Directrix](../../aspose.threed.entities/sweptareasolid/directrix/) { get; set; } | الdirectrix الذي يتم مسح المنطقة المتحركة على طولها. |
| [EndPoint](../../aspose.threed.entities/sweptareasolid/endpoint/) { get; set; } | نقطة النهاية للdirectrix. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأصلية الأولى، إذا تم تعيين العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | يحصل على جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتكرار الهندسة. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Shape](../../aspose.threed.entities/sweptareasolid/shape/) { get; set; } | ملف التعريف الأساسي لإنشاء الهندسة. |
| [StartPoint](../../aspose.threed.entities/sweptareasolid/startpoint/) { get; set; } | نقطة البداية للdirectrix. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يجد الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | يحصل على مفتاح عارض الكيان المسجل في العارض |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| [ToMesh](../../aspose.threed.entities/sweptareasolid/tomesh/)() | تحويل الكائن الحالي إلى شبكة |

## أمثلة

الكود التالي يوضح كيفية نمذجة كيان صلب عن طريق مسح شكل C على دائرة.

```csharp
var directrix = new Circle(20);
var shape = new CShape();

var swept = new SweptAreaSolid()
{
  Shape = shape,
  Directrix = directrix,
  StartPoint = EndPoint.FromDegree(0),
  EndPoint = EndPoint.FromDegree(130)
};

var scene = new Scene();
scene.RootNode.CreateChildNode(swept);
scene.Save("swept.obj");
```

### انظر أيضًا

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


