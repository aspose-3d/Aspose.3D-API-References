---
title: Aspose.ThreeD
second_title: مرجع API Aspose.3D لـ .NET
description: مساحة الاسم الأساسية لـ Aspose.3D
type: docs
weight: 10
url: /ar/net/aspose.threed/
---
مساحة الاسم الأساسية لـ Aspose.3D

## الفئات

| الفئة | الوصف |
| --- | --- |
| [A3DObject](./a3dobject/) | الفئة الأساسية لجميع كائنات Aspose.ThreeD، جميع الفئات الفرعية ستدعم الخصائص الديناميكية. |
| [AssetInfo](./assetinfo/) | معلومات الأصل. يمكن إرفاق معلومات الأصل بـ [`Scene`](../aspose.threed/scene/). يمكن للـ [`Scene`](../aspose.threed/scene/) الفرعي أن يمتلك الـ [`AssetInfo`](../aspose.threed/assetinfo/) الخاص به لتجاوز تعريف الأصل الأب. |
| [AxisSystem](./axissystem/) | نظام المحاور هو مزيج من نظام الإحداثيات، المتجه العلوي والمتجه الأمامي. |
| [BonePose](./bonepose/) | يحتوي [`BonePose`](../aspose.threed/bonepose/) على مصفوفة التحويل لعقدة العظم. |
| [CustomObject](./customobject/) | يتم إدارة البيانات الوصفية أو الكائنات المخصصة المستخدمة في ملفات 3D بواسطة هذه الفئة. يتم حفظ جميع الخصائص المخصصة كخصائص ديناميكية. |
| [Entity](./entity/) | الفئة الأساسية لجميع الكيانات. تمثل الكيان (Entity) كائنًا فعليًا يُرفق تحت عقدة مثل [`Light`](../aspose.threed.entities/light/)/[`Geometry`](../aspose.threed.entities/geometry/). |
| [ExportException](./exportexception/) | استثناءات عندما فشل Aspose.3D في تصدير المشهد إلى ملف |
| [FileFormat](./fileformat/) | تعريف تنسيق الملف |
| [FileFormatType](./fileformattype/) | نوع تنسيق الملف |
| [GlobalTransform](./globaltransform/) | التحويل العالمي مشابه لـ [`Transform`](../aspose.threed/transform/)، لكنه ثابت بينما يمثل التحويل النهائي المُقَيَّم. يُستخدم نظام الإحداثيات الأيمن أثناء تقييم التحويل العالمي. |
| [Group](./group/) | يمثل [`Group`](../aspose.threed/group/) العلاقات المنطقية لـ [`Node`](../aspose.threed/node/). |
| [ImageRenderOptions](./imagerenderoptions/) | خيارات لـ [`Render`](../aspose.threed/scene/render/) و[`Render`](../aspose.threed/scene/render/). |
| [ImportException](./importexception/) | استثناء عندما فشل Aspose.3D في فتح المصدر المحدد. |
| [License](./license/) | يوفر طرقًا لترخيص المكوّن. |
| [Metered](./metered/) | يوفر طرقًا لتعيين المفتاح المقاس. |
| [Node](./node/) | يمثل عنصرًا في رسم المشهد. رسم المشهد هو شجرة من كائنات Node. خدمات إدارة الشجرة مدمجة في هذه الفئة. لاحظ أن Aspose.3D SDK لا يتحقق من صحة رسم المشهد المُنشأ. تقع مسؤولية المتصل في التأكد من عدم توليد رسومات بيانية دورية في تسلسل العقد. بالإضافة إلى إدارة الشجرة، تُعرّف هذه الفئة جميع الخصائص المطلوبة لوصف موضع الكائن في المشهد. تتضمن هذه المعلومات الخصائص الأساسية Translation و Rotation و Scaling والخيارات المتقدمة للمحاور، والحدود، وخصائص مفاصل IK مثل الصلابة والتخميد. عند إنشائها لأول مرة، يكون كائن Node \"empty\" (أي: هو كائن بدون أي تمثيل رسومي يحتوي فقط على معلومات الموضع). في هذه الحالة، يمكن استخدامه لتمثيل الأبواب في هيكل شجرة العقد ولكن ليس أكثر من ذلك. الاستخدام العادي لهذا النوع من الكائنات هو إضافة كيان يخصص العقدة (انظر \"Entity\"). الكيان هو كائن بحد ذاته ومربوط بـ Node. وهذا يعني أيضًا أن نفس الكيان يمكن مشاركته بين عدة عقد. الكاميرا، الضوء، الشبكة، إلخ... كلها كيانات وجميعها مشتقة من الفئة الأساسية Entity. |
| [NodeVisitor](./nodevisitor/) | استدعاء رجعي للتنقل عبر شجرة العقد بالكامل. |
| [Pose](./pose/) | يُستخدم الوضع (pose) لتخزين مصفوفة التحويل عندما تكون الهندسة مغطاة. الوضع هو مجموعة من [`BonePose`](../aspose.threed/bonepose/)، كل [`BonePose`](../aspose.threed/bonepose/) يحفظ معلومات التحويل المحددة لعقدة العظم. |
| [Property](./property/) | فئة لاحتواء الخصائص المعرفة من قبل المستخدم. |
| [PropertyCollection](./propertycollection/) | مجموعة الخصائص |
| [Scene](./scene/) | المشهد هو كائن من المستوى الأعلى يحتوي على العقد، والهندسات، والمواد، والأنسجة، والرسوم المتحركة، والأوضاع، والمشاهد الفرعية، إلخ. يمكن للمشهد أن يحتوي على مشاهد فرعية، ويعمل كدعم متعدد المستندات في ملفات مثل collada/blender/fbx. يمكن الوصول إلى تسلسل العقد عبر [`RootNode`](../aspose.threed/scene/rootnode/)[`Library`](../aspose.threed/scene/library/) يُستخدم للاحتفاظ بمرجع للكائنات غير المرفقة أثناء التسلسل (مثل البيانات الوصفية أو الكائنات المخصصة) بحيث يمكن استخدامها كمكتبة. |
| [SceneObject](./sceneobject/) | الفئة الجذرية للكائنات التي سيتم تخزينها داخل المشهد. |
| [Transform](./transform/) | يحتوي التحويل على معلومات تسمح بالوصول إلى إزاحة/تحجيم/دوران الكائن أو مصفوفة التحويل بأقل تكلفة. يُستخدم هذا في التحويل المحلي. |
| [TrialException](./trialexception/) | يتم رفع هذا الاستثناء في Scene.Open/Scene.Save عندما لا يتم تطبيق أي تراخيص. يمكنك إيقاف هذا الاستثناء عن طريق تعيين SuppressTrialException إلى true. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [INamedObject](./inamedobject/) | كائن لديه اسم |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [Axis](./axis/) | محور الإحداثيات. |
| [CoordinateSystem](./coordinatesystem/) | نظام الإحداثيات الأيسر أو الأيمن. |
| [FileContentType](./filecontenttype/) | نوع محتوى الملف |
| [PoseType](./posetype/) | نوع الوضعية. |
| [PropertyFlags](./propertyflags/) | علامات الخاصية |


