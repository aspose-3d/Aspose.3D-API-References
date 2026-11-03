---
title: "Aspose.ThreeD.Deformers"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "جميع فئات المشوه معرفة في هذه المساحة."
type: docs
weight: 30
url: /ar/net/aspose.threed.deformers/
---
جميع فئات المشوه معرفة في هذه المساحة.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [Bone](./bone/) | العظام تُعرّف الجزء الفرعي من نقاط التحكم في الهندسة، وتحدد وزن المزج لكل نقطة تحكم. لا يمكن استخدام كائن [`Bone`](../aspose.threed.deformers/bone/) مباشرةً، بل يُستخدم مثال [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) لتشويه الهندسة، ويأتي [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) مع مجموعة من العظام، كل عظمة مرتبطة بعقدة. ملاحظة: يمكن ربط نقطة تحكم في الهندسة بأكثر من عظمة واحدة. |
| [Deformer](./deformer/) | الفئة الأساسية لـ [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) و[`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) |
| [MorphTargetChannel](./morphtargetchannel/) | يتم استخدام قناة MorphTargetChannel بواسطة [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) لتنظيم الهندسات الهدفية. بعض صيغ الملفات مثل FBX تدعم قنوات متعددة بالتوازي. |
| [MorphTargetDeformer](./morphtargetdeformer/) | يوفر MorphTargetDeformer تحريكًا لكل رأس. ينظم MorphTargetDeformer جميع الأهداف عبر [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/)، ويمكن لكل قناة تنظيم عدة أهداف. أحد الاستخدامات الشائعة لمشوه الهدف التشكيلي هو تطبيق تعبيرات الوجه على شخصية. يمكن العثور على مزيد من التفاصيل في https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | يحتوي مشوه الجلد على عدة عظام للعمل، حيث تمزج كل عظمة جزءًا من الهندسة وفقًا لأوزان نقاط التحكم. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | وضع ارتباط العظم يشير إلى الطريقة التي يتم بها ربط العظم أو ربطه بعظم الوالد داخل بنية هرمية. |


