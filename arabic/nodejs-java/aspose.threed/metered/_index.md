---
title: "Metered"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقيس.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | تهيئة نسخة جديدة من هذه الفئة. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| الاسم | الوصف |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | يضبط المفتاح العام والخاص للترخيص القائم على الاستهلاك. إذا قمت بشراء ترخيص قائم على الاستهلاك، عند بدء التطبيق يجب استدعاء هذه API، عادةً يكون ذلك كافياً. ومع ذلك، إذا فشل دائمًا رفع بيانات الاستهلاك وتجاوز 24 ساعة، سيتم ضبط الترخيص إلى حالة التقييم؛ لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، وإذا كانت في حالة التقييم، استدعِ هذه API مرة أخرى. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| publicKey | String | المفتاح العام |
| privateKey | String | المفتاح الخاص |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| الاسم | الوصف |
| --- | --- |
| getConsumptionQuantity() | يحصل على حجم ملف الاستهلاك |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| الاسم | الوصف |
| --- | --- |
| getConsumptionCredit() | يحصل على رصيد الاستهلاك |

 **Result:**
BigDecimal


---



