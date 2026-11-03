---
title: "Aspose.ThreeD"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "مساحة الاسم الأساسية لـ Aspose.3D"
type: docs
weight: 10
url: /ar/net/aspose.threed/
---
مساحة الاسم الأساسية لـ Aspose.3D

## الفئات

| الفئة | الوصف |
| --- | --- |
| [A3DObject](./a3dobject/) | الفئة الأساسية لجميع كائنات Aspose.ThreeD، جميع الفئات الفرعية ستدعم الخصائص الديناميكية. |
| [AssetInfo](./assetinfo/) | معلومات الأصل. يمكن إرفاق معلومات الأصل بـ [`Scene`](../aspose.threed/scene/). يمكن للـ [`Scene`](../aspose.threed/scene/) الفرعي أن يمتلك الـ [`AssetInfo`](../aspose.threed/assetinfo/) الخاص به لتجاوز تعريف الأصل. |
| [AxisSystem](./axissystem/) | نظام المحاور هو مزيج من نظام الإحداثيات، ومتجه الارتفاع، ومتجه الأمام. |
| [BonePose](./bonepose/) | الـ [`BonePose`](../aspose.threed/bonepose/) يحتوي على مصفوفة التحويل لعُقدة العظم. |
| [CustomObject](./customobject/) | البيانات الوصفية أو الكائنات المخصصة المستخدمة في ملفات 3D تُدار بواسطة هذه الفئة. جميع الخصائص المخصصة تُحفظ كخصائص ديناميكية. |
| [Entity](./entity/) | الفئة الأساسية لجميع الكيانات. تمثل الكيان كائنًا ملموسًا يُرفق تحت عقدة مثل [`Light`](../aspose.threed.entities/light/)/[`Geometry`](../aspose.threed.entities/geometry/). |
| [ExportException](./exportexception/) | استثناءات عندما فشل Aspose.3D في تصدير المشهد إلى ملف |
| [FileFormat](./fileformat/) | تعريف تنسيق الملف |
| [FileFormatType](./fileformattype/) | نوع تنسيق الملف |
| [GlobalTransform](./globaltransform/) | التحويل العالمي مشابه للـ [`Transform`](../aspose.threed/transform/) لكنه ثابت بينما يمثل التحويل النهائي المُقيم. يُستخدم نظام الإحداثيات الأيمن أثناء تقييم التحويل العالمي |
| [Group](./group/) | الـ [`Group`](../aspose.threed/group/) يمثل العلاقات المنطقية للـ [`Node`](../aspose.threed/node/). |
| [ImageRenderOptions](./imagerenderoptions/) | خيارات للـ [`Render`](../aspose.threed/scene/render/) و[`Render`](../aspose.threed/scene/render/) |
| [ImportException](./importexception/) | استثناء عندما فشل Aspose.3D في فتح المصدر المحدد |
| [License](./license/) | يوفر طرقًا لترخيص المكوّن. |
| [Metered](./metered/) | يوفر طرقًا لتعيين المفتاح المقنن. |
| [Node](./node/) | يمثل عنصرًا في رسم المشهد. رسم المشهد هو شجرة من كائنات Node. خدمات إدارة الشجرة مدمجة في هذه الفئة. لاحظ أن Aspose.3D SDK لا يتحقق من صحة رسم المشهد المُنشأ. تقع على عاتق المستدعي مسؤولية التأكد من عدم إنشاء رسومات دورية في هيكلية العقد. بالإضافة إلى إدارة الشجرة، تُعرّف هذه الفئة جميع الخصائص المطلوبة لوصف موضع الكائن في المشهد. تشمل هذه المعلومات الخصائص الأساسية للترجمة (Translation)، والدوران (Rotation)، والقياس (Scaling) بالإضافة إلى الخيارات المتقدمة للمحاور، والحدود، وخصائص مفاصل IK مثل الصلابة والتخميد. عند إنشائه لأول مرة، يكون كائن Node "فارغًا" (أي: هو كائن بدون أي تمثيل رسومي يحتوي فقط على معلومات الموضع). في هذه الحالة، يمكن استخدامه لتمثيل الآباء في هيكلية شجرة العقد ولكن ليس أكثر من ذلك. الاستخدام العادي لهذا النوع من الكائنات هو إضافة كيان (Entity) يخصص العقدة (انظر "Entity"). الكيان هو كائن بحد ذاته ومربوط بـ Node. وهذا يعني أيضًا أن نفس الكيان يمكن مشاركته بين عدة عقد. Camera و Light و Mesh وغيرها كلها كيانات وتُشتق جميعها من الفئة الأساسية Entity. |
| [NodeVisitor](./nodevisitor/) | دالة رد نداء للتنقل عبر هيكلية العقد بالكامل. |
| [Pose](./pose/) | يُستخدم الـ pose لتخزين مصفوفة التحويل عندما يكون الشكل مُغطى بالجلد. الـ pose هو مجموعة من [`BonePose`](../aspose.threed/bonepose/)، كل [`BonePose`](../aspose.threed/bonepose/) يحفظ معلومات التحويل الفعلية لعُقدة العظم. |
| [Property](./property/) | فئة لحفظ الخصائص المعرفة من قبل المستخدم. |
| [PropertyCollection](./propertycollection/) | مجموعة الخصائص |
| [Scene](./scene/) | المشهد هو كائن من المستوى الأعلى يحتوي على العقد، والهياكل، والمواد، والملمس، والرسوم المتحركة، والـ poses، والمشاهد الفرعية وما إلى ذلك. يمكن للمشهد أن يحتوي على مشاهد فرعية، ويعمل كدعم متعدد المستندات في ملفات مثل collada/blender/fbx. يمكن الوصول إلى هيكلية العقد عبر [`RootNode`](../aspose.threed/scene/rootnode/). تُستخدم [`Library`](../aspose.threed/scene/library/) للحفاظ على مرجع للكائنات غير المرفقة أثناء التسلسل (مثل البيانات الوصفية أو الكائنات المخصصة) بحيث يمكن استخدامها كمكتبة. |
| [SceneObject](./sceneobject/) | الفئة الجذرية للكائنات التي سيتم تخزينها داخل المشهد. |
| [Transform](./transform/) | التحويل يحتوي على معلومات تسمح بالوصول إلى ترجمة/قياس/دوران الكائن أو مصفوفة التحويل بأقل تكلفة. يُستخدم هذا في التحويل المحلي. |
| [TrialException](./trialexception/) | يتم رفع هذا الاستثناء في Scene.Open/Scene.Save عندما لا يتم تطبيق أي تراخيص. يمكنك إيقاف هذا الاستثناء بتعيين SuppressTrialException إلى true. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [INamedObject](./inamedobject/) | كائن له اسم |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [Axis](./axis/) | محور الإحداثيات. |
| [CoordinateSystem](./coordinatesystem/) | نظام الإحداثيات الأيسر أو الأيمن. |
| [FileContentType](./filecontenttype/) | نوع محتوى الملف |
| [PoseType](./posetype/) | نوع الوضعية. |
| [PropertyFlags](./propertyflags/) | علامات الخاصية |


