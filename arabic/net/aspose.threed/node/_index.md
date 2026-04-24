---
title: الفئة Node
second_title: مرجع API Aspose.3D لـ .NET
description: الفئة Aspose.ThreeD.Node. تمثل عنصرًا في رسم المشهد. رسم المشهد هو شجرة من كائنات Node. خدمات إدارة الشجرة مدمجة في هذه الفئة. لاحظ أن Aspose.3D SDK لا يتحقق من صحة رسم المشهد المُنشأ. تقع مسؤولية المتصل في التأكد من عدم إنشاء رسومات بيانية دورية في هيكلية العقد. بالإضافة إلى إدارة الشجرة، تُعرّف هذه الفئة جميع الخصائص المطلوبة لوصف موضع الكائن في المشهد. تشمل هذه المعلومات الخصائص الأساسية للترجمة (Translation) والدوران (Rotation) والتحجيم (Scaling) والخيارات المتقدمة للمحاور والحدود ومفاصل الـ IK مثل الصلابة والتخميد. عند إنشائها لأول مرة يكون كائن Node فارغًا، أي أنه كائن بدون أي تمثيل رسومي يحتوي فقط على معلومات الموضع. في هذه الحالة يمكن استخدامه لتمثيل الآباء في بنية شجرة العقد ولكن ليس أكثر من ذلك. الاستخدام العادي لهذا النوع من الكائنات هو إضافة كيان (Entity) يخصص العقدة؛ انظر الـ Entity. الكيان هو كائن بحد ذاته ومربوط بـ Node. وهذا يعني أيضًا أن نفس الكيان يمكن مشاركته بين عدة عقد. الكاميرا (Camera) والضوء (Light) والشبكة (Mesh) وغيرها كلها كيانات وتُشتق جميعها من الفئة الأساسية Entity.
type: docs
weight: 1630
url: /ar/net/aspose.threed/node/
---
## Node class

يمثل عنصرًا في رسم المشهد. رسم المشهد هو شجرة من كائنات Node. خدمات إدارة الشجرة مدمجة في هذه الفئة. لاحظ أن Aspose.3D SDK لا يتحقق من صحة رسم المشهد المُنشأ. تقع مسؤولية المتصل في التأكد من عدم توليد رسومات بيانية دورية في تسلسل العقد. بالإضافة إلى إدارة الشجرة، تُعرّف هذه الفئة جميع الخصائص المطلوبة لوصف موضع الكائن في المشهد. تتضمن هذه المعلومات الخصائص الأساسية Translation و Rotation و Scaling والخيارات المتقدمة للمحاور، والحدود، وخصائص مفاصل IK مثل الصلابة والتخميد. عند إنشائها لأول مرة، يكون كائن Node \"empty\" (أي: هو كائن بدون أي تمثيل رسومي يحتوي فقط على معلومات الموضع). في هذه الحالة، يمكن استخدامه لتمثيل الأبواب في هيكل شجرة العقد ولكن ليس أكثر من ذلك. الاستخدام العادي لهذا النوع من الكائنات هو إضافة كيان يخصص العقدة (انظر \"Entity\"). الكيان هو كائن بحد ذاته ومربوط بـ Node. وهذا يعني أيضًا أن نفس الكيان يمكن مشاركته بين عدة عقد. الكاميرا، الضوء، الشبكة، إلخ... كلها كيانات وجميعها مشتقة من الفئة الأساسية Entity.

```csharp
public class Node : SceneObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Node](node/#constructor)() | يُنشئ مثيلًا جديدًا من الفئة `Node`. |
| [Node](node/#constructor_1)(string) | يُنشئ مثيلًا جديدًا من الفئة `Node`. |
| [Node](node/#constructor_2)(string, Entity) | يُنشئ مثيلًا جديدًا من الفئة `Node`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssetInfo](../../aspose.threed/node/assetinfo/) { get; set; } | معلومات الأصول لكل عقدة |
| [ChildNodes](../../aspose.threed/node/childnodes/) { get; } | يحصل على العقد الفرعية. |
| [Entities](../../aspose.threed/node/entities/) { get; } | يحصل على جميع كيانات العقدة. |
| [Entity](../../aspose.threed/node/entity/) { get; set; } | يحصل أو يعيّن الكيان الأول المرفق بهذه العقدة، إذا تم التعيين، سيُمسح الكيانات الأخرى. |
| [Excluded](../../aspose.threed/node/excluded/) { get; set; } | يحصل أو يعيّن ما إذا كان يجب استبعاد هذه العقدة وجميع العقد/الكيانات الفرعية أثناء التصدير. |
| [GlobalTransform](../../aspose.threed/node/globaltransform/) { get; } | يحصل على التحويل العالمي. |
| [Material](../../aspose.threed/node/material/) { get; set; } | يحصل أو يعيّن المادة الأولى المرتبطة بهذه العقدة، إذا تم التعيين، سيُمسح المواد الأخرى |
| [Materials](../../aspose.threed/node/materials/) { get; } | يحصل على المواد المرتبطة بهذه العقدة. |
| [MetaDatas](../../aspose.threed/node/metadatas/) { get; } | يحصل على البيانات الوصفية المعرفة في هذه العقدة. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ParentNode](../../aspose.threed/node/parentnode/) { get; set; } | يحصل أو يعيّن العقدة الأم. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [Transform](../../aspose.threed/node/transform/) { get; } | يحصل على التحويل المحلي. |
| [Visible](../../aspose.threed/node/visible/) { get; set; } | الحصول أو الضبط لإظهار العقدة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accept](../../aspose.threed/node/accept/)(NodeVisitor) | يتجول عبر جميع العقد التابعة (بما في ذلك العقدة الحالية) ويستدعي الزائر مع العقدة. يمكن للزائر إيقاف التجول بإرجاع false |
| [AddChildNode](../../aspose.threed/node/addchildnode/)(Node) | أضف عقدة فرعية إلى هذه العقدة |
| [AddEntity](../../aspose.threed/node/addentity/)(Entity) | أضف كيانًا إلى العقدة. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode)() | ينشئ عقدة فرعية |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_1)(Entity) | إنشاء عقدة فرعية جديدة مع الكيان المحدد مرفق |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_2)(string) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_3)(string, Entity) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_4)(string, Entity, Material) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة، وإرفاق الكيان المحدد ومادة |
| [EvaluateGlobalTransform](../../aspose.threed/node/evaluateglobaltransform/)(bool) | تقييم التحويل العالمي، تضمين التحويل الهندسي أم لا. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetBoundingBox](../../aspose.threed/node/getboundingbox/)() | حساب الصندوق المحيط للعقدة |
| [GetChild](../../aspose.threed/node/getchild/#getchild)(int) | يحصل على العقدة الفرعية عند الفهرس المحدد. |
| [GetChild](../../aspose.threed/node/getchild/#getchild_1)(string) | يحصل على العقدة الفرعية بالاسم المحدد |
| [GetEntity&lt;T&gt;](../../aspose.threed/node/getentity/)() |  |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [Merge](../../aspose.threed/node/merge/)(Node) | فصل كل شيء تحت العقدة وإرفاقه إلى العقدة الحالية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [SelectObjects](../../aspose.threed/node/selectobjects/)(string) | اختيار عدة كائنات تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath. |
| [SelectSingleObject](../../aspose.threed/node/selectsingleobject/)(string) | اختيار كائن واحد تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |
| override [ToString](../../aspose.threed/node/tostring/)() | يحصل على تمثيل النص لهذه العقدة. |

### انظر أيضًا

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


