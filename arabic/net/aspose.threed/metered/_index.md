---
title: "فئة Metered"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Metered. توفر طرقًا لتعيين المفتاح المقيس"
type: docs
weight: 1620
url: /ar/net/aspose.threed/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح القابل للقياس.

```csharp
public class Metered
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered/)() | يُهيئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetMeteredKey](../../aspose.threed/metered/setmeteredkey/)(string, string) | يعيّن المفتاح العام والخاص المقيس. إذا قمت بشراء ترخيص مقيس، عند بدء التطبيق يجب استدعاء هذه الواجهة البرمجية، عادةً يكون ذلك كافيًا. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم؛ لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.threed/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.threed/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |

## أمثلة

في هذا المثال، سيتم محاولة ضبط المفتاح العام والخاص المقيس

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

ملف jar المكوّن:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### انظر أيضًا

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


