---
title: Class Metered
second_title: مرجع API Aspose.3D لـ .NET
description: Aspose.ThreeD.Metered class. Provides methods to set metered key
type: docs
weight: 1620
url: /ar/net/aspose.threed/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقاس.

```csharp
public class Metered
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered/)() | يقوم بتهيئة نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetMeteredKey](../../aspose.threed/metered/setmeteredkey/)(string, string) | يضبط المفتاح العام والخاص المقاس. إذا قمت بشراء ترخيص مقاس، عند بدء التطبيق يجب استدعاء هذه الـAPI، عادةً يكون ذلك كافياً. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم؛ لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه الـAPI مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.threed/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.threed/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |

## Examples

In this example, an attempt will be made to set metered public and private key

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

the component jar file:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### انظر أيضًا

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


