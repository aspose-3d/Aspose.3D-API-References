---
title: فئة Scene
second_title: مرجع API Aspose.3D لـ .NET
description: فئة Aspose.ThreeD.Scene. المشهد هو كائن أعلى مستوى يحتوي على العقد الهندسات المواد القوام الرسوم المتحركة الوضعيات المشاهد الفرعية إلخ. يمكن للمشهد أن يحتوي على مشاهد فرعية ويعمل كدعم متعدد المستندات في ملفات مثل collada/blender/fbx. يمكن الوصول إلى هيكل العقد عبر RootNodeLibrary تُستخدم Library للاحتفاظ بإشارة إلى الكائنات غير المرفقة أثناء التسلسل (مثل البيانات الوصفية أو الكائنات المخصصة) بحيث يمكن استخدامها كمكتبة
type: docs
weight: 2500
url: /ar/net/aspose.threed/scene/
---
## Scene class

المشهد هو كائن أعلى مستوى يحتوي على العقد، الهندسات، المواد، القوام، الرسوم المتحركة، الوضعيات، المشاهد الفرعية إلخ. يمكن للمشهد أن يحتوي على مشاهد فرعية، ويعمل كدعم متعدد المستندات في ملفات مثل collada/blender/fbx. يمكن الوصول إلى هيكل العقد عبر [`RootNode`](./rootnode/)[`Library`](./library/) تُستخدم للاحتفاظ بإشارة إلى الكائنات غير المرفقة أثناء التسلسل (مثل البيانات الوصفية أو الكائنات المخصصة) بحيث يمكن استخدامها كمكتبة.

```csharp
public class Scene : SceneObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Scene](scene/#constructor)() | ينشئ مثيلاً جديداً لفئة `Scene`. |
| [Scene](scene/#constructor_1)(Entity) | ينشئ مثيلاً جديداً لفئة `Scene` مع كيان مرفق بعقدة جديدة. |
| [Scene](scene/#constructor_2)(Scene, string) | ينشئ مثيلاً جديداً لفئة `Scene` كمشهد فرعي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnimationClips](../../aspose.threed/scene/animationclips/) { get; } | يحصل على جميع [`AnimationClip`](../../aspose.threed.animation/animationclip/) المعرفة في المشهد. |
| [AssetInfo](../../aspose.threed/scene/assetinfo/) { get; set; } | الحصول أو الضبط لمعلومات الأصل أعلى المستوى |
| [CurrentAnimationClip](../../aspose.threed/scene/currentanimationclip/) { get; set; } | الحصول أو الضبط لـ [`AnimationClip`](../../aspose.threed.animation/animationclip/) النشط |
| [Library](../../aspose.threed/scene/library/) { get; } | الكائنات التي لا تُستخدم مباشرةً في هيكلية المشهد يمكن تعريفها في المكتبة. هذا مفيد عندما تستخدم المشاهد الفرعية وتضع المكونات القابلة لإعادة الاستخدام تحت المشاهد الفرعية. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Poses](../../aspose.threed/scene/poses/) { get; } | يحصل على جميع [`Pose`](../pose/) المستخدمة في هذا المشهد. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | يحصل على مجموعة جميع الخصائص. |
| [RootNode](../../aspose.threed/scene/rootnode/) { get; } | يحصل على عقدة الجذر للمشهد. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [SubScenes](../../aspose.threed/scene/subscenes/) { get; } | يحصل على جميع المشاهد الفرعية |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile)(string) | يفتح المشهد من المسار المحدد |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_3)(string, CancellationToken) | يفتح المشهد من المسار المحدد |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_1)(string, FileFormat, CancellationToken) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_2)(string, LoadOptions, CancellationToken) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_2)(Stream, CancellationToken) | يفتح المشهد من الدفق المحدد |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream)(Stream, FileFormat, CancellationToken) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_1)(Stream, LoadOptions, CancellationToken) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [Clear](../../aspose.threed/scene/clear/)() | يمسح محتوى المشهد ويستعيد الإعدادات الافتراضية. |
| [CreateAnimationClip](../../aspose.threed/scene/createanimationclip/)(string) | دالة مختصرة لإنشاء وتسجيل [`AnimationClip`](../../aspose.threed.animation/animationclip/). سيتم تعيين أول [`AnimationClip`](../../aspose.threed.animation/animationclip/) إلى [`CurrentAnimationClip`](./currentanimationclip/). |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name) |
| [GetAnimationClip](../../aspose.threed/scene/getanimationclip/)(string) | يحصل على [`AnimationClip`](../../aspose.threed.animation/animationclip/) مسمى. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | احصل على قيمة الخاصية المحددة |
| [Open](../../aspose.threed/scene/open/#open)(Stream) | يفتح المشهد من الدفق المحدد |
| [Open](../../aspose.threed/scene/open/#open_4)(string) | يفتح المشهد من المسار المحدد |
| [Open](../../aspose.threed/scene/open/#open_3)(Stream, CancellationToken) | يفتح المشهد من الدفق المحدد |
| [Open](../../aspose.threed/scene/open/#open_8)(string, CancellationToken) | يفتح المشهد من المسار المحدد |
| [Open](../../aspose.threed/scene/open/#open_6)(string, LoadOptions) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [Open](../../aspose.threed/scene/open/#open_1)(Stream, FileFormat, CancellationToken) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [Open](../../aspose.threed/scene/open/#open_2)(Stream, LoadOptions, CancellationToken) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [Open](../../aspose.threed/scene/open/#open_5)(string, FileFormat, CancellationToken) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [Open](../../aspose.threed/scene/open/#open_7)(string, LoadOptions, CancellationToken) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | يزيل خاصية ديناميكية. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [Render](../../aspose.threed/scene/render/#render_2)(Camera, string) | اعرض المشهد في ملف خارجي من منظور الكاميرا المحددة. حجم الإخراج الافتراضي هو 1024x768 وتنسيق الإخراج هو png |
| [Render](../../aspose.threed/scene/render/#render)(Camera, TextureData) | يُصوِّر المشهد إلى صورة نقطية من منظور الكاميرا المحددة. |
| [Render](../../aspose.threed/scene/render/#render_1)(Camera, TextureData, ImageRenderOptions) | يُصوِّر المشهد إلى صورة نقطية من منظور الكاميرا المحددة. |
| [Render](../../aspose.threed/scene/render/#render_3)(Camera, string, Vector2, string) | يُصوِّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة. |
| [Render](../../aspose.threed/scene/render/#render_4)(Camera, string, Vector2, string, ImageRenderOptions) | يُصوِّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة. |
| [Save](../../aspose.threed/scene/save/#save_4)(string) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [Save](../../aspose.threed/scene/save/#save)(Stream, FileFormat) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [Save](../../aspose.threed/scene/save/#save_2)(Stream, SaveOptions) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [Save](../../aspose.threed/scene/save/#save_5)(string, FileFormat) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [Save](../../aspose.threed/scene/save/#save_7)(string, SaveOptions) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [Save](../../aspose.threed/scene/save/#save_1)(Stream, FileFormat, CancellationToken) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [Save](../../aspose.threed/scene/save/#save_3)(Stream, SaveOptions, CancellationToken) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [Save](../../aspose.threed/scene/save/#save_6)(string, FileFormat, CancellationToken) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [Save](../../aspose.threed/scene/save/#save_8)(string, SaveOptions, CancellationToken) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | يضبط قيمة الخاصية المحددة |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [Version](../../aspose.threed/scene/version/) | يحصل على نسخة الإصدار الحالية |

### انظر أيضًا

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


