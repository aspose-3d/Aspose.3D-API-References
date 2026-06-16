---
title: "Aspose.ThreeD"
second_title: "مرجع Aspose.3D for .NET API"
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
| [AssetInfo](./assetinfo/) | معلومات الأصل. يمكن إرفاق معلومات الأصل بـ [`Scene`](../aspose.threed/scene/). يمكن للـ [`Scene`](../aspose.threed/scene/) الفرعي أن يمتلك [`AssetInfo`](../aspose.threed/assetinfo/) الخاص به لتجاوز تعريف الأصل الأب. |
| [AxisSystem](./axissystem/) | نظام المحاور هو مزيج من نظام الإحداثيات، المتجه العلوي والمتجه الأمامي. |
| [BonePose](./bonepose/) | يحتوي [`BonePose`](../aspose.threed/bonepose/) على مصفوفة التحويل لعقدة العظم |
| [CustomObject](./customobject/) | البيانات الوصفية أو الكائنات المخصصة المستخدمة في ملفات 3D تُدار بواسطة هذه الفئة. جميع الخصائص المخصصة تُحفظ كخصائص ديناميكية. |
| [Entity](./entity/) | الفئة الأساسية لجميع الكيانات. الكيان يمثل كائنًا محددًا يُرفق تحت عقدة مثل [`Light`](../aspose.threed.entities/light/)/[`Geometry`](../aspose.threed.entities/geometry/). |
| [ExportException](./exportexception/) | استثناءات عندما فشل Aspose.3D في تصدير المشهد إلى ملف |
| [FileFormat](./fileformat/) | تعريف تنسيق الملف |
| [FileFormatType](./fileformattype/) | نوع تنسيق الملف |
| [GlobalTransform](./globaltransform/) | التحويل العالمي مشابه لـ [`Transform`](../aspose.threed/transform/) لكنه ثابت بينما يمثل التحويل النهائي المُقيم. يُستخدم نظام الإحداثيات الأيمن أثناء تقييم التحويل العالمي |
| [Group](./group/) | يُمثل [`Group`](../aspose.threed/group/) العلاقات المنطقية لـ [`Node`](../aspose.threed/node/). |
| [ImageRenderOptions](./imagerenderoptions/) | خيارات لـ [`Render`](../aspose.threed/scene/render/) و [`Render`](../aspose.threed/scene/render/) |
| [ImportException](./importexception/) | استثناء عندما فشل Aspose.3D في فتح المصدر المحدد |
| [License](./license/) | يوفر طرقًا لترخيص المكوّن. |
| [Metered](./metered/) | يوفر طرقًا لتعيين المفتاح القابل للقياس. |
| [Node](./node/) | يمثل عنصرًا في رسم المشهد. رسم المشهد هو شجرة من كائنات Node. خدمات إدارة الشجرة مدمجة في هذه الفئة. لاحظ أن Aspose.3D SDK لا يتحقق من صحة رسم المشهد المُنشأ. تقع مسؤولية التأكد من عدم إنشاء رسومات بيانية دورية في تسلسل الهرمي للعقد على عاتق المتصل. بالإضافة إلى إدارة الشجرة، تُعرّف هذه الفئة جميع الخصائص المطلوبة لوصف موضع الكائن في المشهد. تشمل هذه المعلومات الخصائص الأساسية للترجمة (Translation)، والدوران (Rotation)، والتحجيم (Scaling) بالإضافة إلى الخيارات المتقدمة للمحاور، والحدود، وخصائص مفاصل الـ IK مثل الصلابة والتخميد. عندما يتم إنشاؤه لأول مرة، يكون كائن Node "فارغًا" (أي: هو كائن بدون أي تمثيل رسومي يحتوي فقط على معلومات الموضع). في هذه الحالة، يمكن استخدامه لتمثيل الآباء في بنية شجرة العقد ولكن ليس أكثر من ذلك. الاستخدام العادي لهذا النوع من الكائنات هو إضافة كيان يخصص العقدة (انظر "Entity"). الكيان هو كائن بحد ذاته ومربوط بـ Node. وهذا يعني أيضًا أن نفس الكيان يمكن مشاركته بين عدة عقد. الكاميرا، الإضاءة، Mesh، إلخ... كلها كيانات وتُشتق جميعها من الفئة الأساسية Entity. |
| [NodeVisitor](./nodevisitor/) | دالة رد نداء للتنقل عبر التسلسل الهرمي الكامل للعقد. |
| [Pose](./pose/) | يُستخدم الـ pose لتخزين مصفوفة التحويل عندما تكون الهندسة مغطاة. الـ pose هو مجموعة من [`BonePose`](../aspose.threed/bonepose/)، كل [`BonePose`](../aspose.threed/bonepose/) يحفظ معلومات التحويل المحددة لعقدة العظم. |
| [Property](./property/) | فئة لحفظ الخصائص المعرفة من قبل المستخدم. |
| [PropertyCollection](./propertycollection/) | مجموعة الخصائص |
| [Scene](./scene/) | المشهد هو كائن على المستوى الأعلى يحتوي على العقد، والهياكل، والمواد، والملمس، والرسوم المتحركة، والـ poses، والمشاهد الفرعية، وما إلى ذلك. يمكن للمشهد أن يحتوي على مشاهد فرعية، ويعمل كدعم متعدد المستندات في ملفات مثل collada/blender/fbx. يمكن الوصول إلى تسلسل هرمي العقد عبر [`RootNode`](../aspose.threed/scene/rootnode/). يُستخدم [`Library`](../aspose.threed/scene/library/) للاحتفاظ بمرجع للكائنات غير المرفقة أثناء التسلسل (مثل البيانات الوصفية أو الكائنات المخصصة) بحيث يمكن استخدامها كمكتبة. |
| [SceneObject](./sceneobject/) | الفئة الجذرية للكائنات التي سيتم تخزينها داخل المشهد. |
| [Transform](./transform/) | يحتوي التحويل على معلومات تسمح بالوصول إلى ترجمة/تحجيم/دوران الكائن أو مصفوفة التحويل بأقل تكلفة. يُستخدم هذا في التحويل المحلي. |
| [TrialException](./trialexception/) | يتم رفع هذا في Scene.Open/Scene.Save عندما لا تُطبق أي تراخيص. يمكنك إيقاف هذا الاستثناء عن طريق ضبط SuppressTrialException إلى true. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [INamedObject](./inamedobject/) | كائن له اسم |
## التعداد

| التعداد | الوصف |
| --- | --- |
| [Axis](./axis/) | محور الإحداثيات. |
| [CoordinateSystem](./coordinatesystem/) | نظام الإحداثيات الأيسر أو الأيمن. |
| [FileContentType](./filecontenttype/) | نوع محتوى الملف |
| [PoseType](./posetype/) | نوع الـ pose. |
| [PropertyFlags](./propertyflags/) | علامات الخاصية |


