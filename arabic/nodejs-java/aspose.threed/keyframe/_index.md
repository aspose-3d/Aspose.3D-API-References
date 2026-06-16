---
title: "KeyFrame"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

الإطار الرئيسي يُعرّف أساسًا بالوقت والقيمة، لبعض أنواع الاستيفاء تُستخدم المماس/التوتر/التحيز/الاستمرارية لحساب القيمة النهائية المُعينة. القيم المُعينة في موضع زمني غير إطار رئيسي تُستَدلّ عليها بواسطة الإطارات الرئيسية بين الإطار السابق واللاحق. القيم قبل/بعد الإطار الرئيسي الأول/الأخير تُحسب بواسطة فئة Extrapolation.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(curve, time) | إنشاء إطار مفتاح جديد على المنحنى المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| curve | KeyframeSequence | المنحنى الذي سيتم إنشاء الإطار الرئيسي عليه |
| الوقت | Number | موضع الوقت للإطار الرئيسي |

 **Result:**



---


### getTime{#getTime}

| الاسم | الوصف |
| --- | --- |
| getTime() | يحصل أو يضبط موضع الوقت لإطار المفتاح list.data[index]، مقاسًا بالثواني. الوقت. |

 **Result:**



---


### setTime{#setTime}

| الاسم | الوصف |
| --- | --- |
| setTime(value) | يحصل أو يضبط موضع الوقت لإطار المفتاح list.data[index]، مقاسًا بالثواني. الوقت. |

 **Result:**



---


### getValue{#getValue}

| الاسم | الوصف |
| --- | --- |
| getValue() | يحصل أو يضبط قيمة الإطار الرئيسي. القيمة. |

 **Result:**



---


### setValue{#setValue}

| الاسم | الوصف |
| --- | --- |
| setValue(value) | يحصل أو يضبط قيمة الإطار الرئيسي. القيمة. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| الاسم | الوصف |
| --- | --- |
| getInterpolation() | يحصل أو يضبط نوع الاستيفاء للمفتاح، list.data[index] يحدد الخوارزمية التي يتم بها حساب القيمة المعيّنة. قيمة الخاصية هي ثابت عدد صحيح Interpolation. الاستيفاء. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| الاسم | الوصف |
| --- | --- |
| setInterpolation(value) | يحصل أو يضبط نوع الاستيفاء للمفتاح، list.data[index] يحدد الخوارزمية التي يتم بها حساب القيمة المعيّنة. قيمة الخاصية هي ثابت عدد صحيح Interpolation. الاستيفاء. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| الاسم | الوصف |
| --- | --- |
| getTangentWeightMode() | يحصل أو يضبط وضع وزن المماس للمفتاح. يمكن تخصيص المماس الخارج أو المماس الداخل التالي عن طريق اختيار WeightedMode الصحيح. قيمة الخاصية هي ثابت عدد صحيح WeightedMode. وضع وزن المماس. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| الاسم | الوصف |
| --- | --- |
| setTangentWeightMode(value) | يحصل أو يضبط وضع وزن المماس للمفتاح. يمكن تخصيص المماس الخارج أو المماس الداخل التالي عن طريق اختيار WeightedMode الصحيح. قيمة الخاصية هي ثابت عدد صحيح WeightedMode. وضع وزن المماس. |

 **Result:**



---


### getStepMode{#getStepMode}

| الاسم | الوصف |
| --- | --- |
| getStepMode() | يحصل أو يضبط وضع خطوة المفتاح. إذا كان نوع الاستيفاء هو Interpolation.CONSTANT، فإن list.data[index] يقرر أي قيمة للإطار الرئيسي ستُستخدم أثناء الاستيفاء. يعني StepMode.PREVIOUS_VALUE أن قيمة الإطار الرئيسي الأيسر ستُستخدم. يعني StepMode.NEXT_VALUE أن قيمة الإطار الرئيسي الأيمن التالي ستُستخدم. قيمة الخاصية هي ثابت عدد صحيح StepMode. وضع الخطوة. |

 **Result:**



---


### setStepMode{#setStepMode}

| الاسم | الوصف |
| --- | --- |
| setStepMode(value) | يحصل أو يضبط وضع خطوة المفتاح. إذا كان نوع الاستيفاء هو Interpolation.CONSTANT، فإن list.data[index] يقرر أي قيمة للإطار الرئيسي ستُستخدم أثناء الاستيفاء. يعني StepMode.PREVIOUS_VALUE أن قيمة الإطار الرئيسي الأيسر ستُستخدم. يعني StepMode.NEXT_VALUE أن قيمة الإطار الرئيسي الأيمن التالي ستُستخدم. قيمة الخاصية هي ثابت عدد صحيح StepMode. وضع الخطوة. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| الاسم | الوصف |
| --- | --- |
| getNextInTangent() | يحصل أو يضبط المماس الداخل التالي (اليسار) لهذا الإطار الرئيسي. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| الاسم | الوصف |
| --- | --- |
| setNextInTangent(value) | يحصل أو يضبط المماس الداخل التالي (اليسار) لهذا الإطار الرئيسي. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| الاسم | الوصف |
| --- | --- |
| getOutTangent() | يحصل أو يضبط المماس الخارج (اليمين) لهذا الإطار الرئيسي. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| الاسم | الوصف |
| --- | --- |
| setOutTangent(value) | يحصل أو يضبط المماس الخارج (اليمين) لهذا الإطار الرئيسي. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| الاسم | الوصف |
| --- | --- |
| getOutWeight() | يحصل أو يضبط الوزن الخارج (اليمين) لهذا الإطار الرئيسي. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| الاسم | الوصف |
| --- | --- |
| setOutWeight(value) | يحصل أو يضبط الوزن الخارج (اليمين) لهذا الإطار الرئيسي. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| الاسم | الوصف |
| --- | --- |
| getNextInWeight() | يحصل أو يضبط الوزن التالي (الداخل) على هذا الإطار الرئيسي. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| الاسم | الوصف |
| --- | --- |
| setNextInWeight(value) | يحصل أو يضبط الوزن التالي (الداخل) على هذا الإطار الرئيسي. |

 **Result:**



---


### getTension{#getTension}

| الاسم | الوصف |
| --- | --- |
| getTension() | يحصل أو يضبط التوتر المستخدم في منحنى TCB |

 **Result:**



---


### setTension{#setTension}

| الاسم | الوصف |
| --- | --- |
| setTension(value) | يحصل أو يضبط التوتر المستخدم في منحنى TCB |

 **Result:**



---


### getContinuity{#getContinuity}

| الاسم | الوصف |
| --- | --- |
| getContinuity() | يحصل أو يضبط الاستمرارية المستخدمة في منحنى TCB |

 **Result:**



---


### setContinuity{#setContinuity}

| الاسم | الوصف |
| --- | --- |
| setContinuity(value) | يحصل أو يضبط الاستمرارية المستخدمة في منحنى TCB |

 **Result:**



---


### getBias{#getBias}

| الاسم | الوصف |
| --- | --- |
| getBias() | يحصل أو يضبط الانحياز المستخدم في منحنى TCB |

 **Result:**



---


### setBias{#setBias}

| الاسم | الوصف |
| --- | --- |
| setBias(value) | يحصل أو يضبط الانحياز المستخدم في منحنى TCB |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| الاسم | الوصف |
| --- | --- |
| getIndependentTangent() | يحصل أو يضبط أن المماس الخارجي والمماس التالي الداخلي مستقلان. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| الاسم | الوصف |
| --- | --- |
| setIndependentTangent(value) | يحصل أو يضبط أن المماس الخارجي والمماس التالي الداخلي مستقلان. |

 **Result:**



---


### getFlat{#getFlat}

| الاسم | الوصف |
| --- | --- |
| getFlat() | احصل أو اضبط ما إذا كان الإطار الرئيسي مسطحًا. يجب أن يكون الإطار الرئيسي مسطحًا إذا كان الإطار التالي أو السابق له نفس القيمة. الإطار الرئيسي المسطح له مساومات مسطحة وتداخل ثابت. |

 **Result:**



---


### setFlat{#setFlat}

| الاسم | الوصف |
| --- | --- |
| setFlat(value) | احصل أو اضبط ما إذا كان الإطار الرئيسي مسطحًا. يجب أن يكون الإطار الرئيسي مسطحًا إذا كان الإطار التالي أو السابق له نفس القيمة. الإطار الرئيسي المسطح له مساومات مسطحة وتداخل ثابت. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| الاسم | الوصف |
| --- | --- |
| getTimeIndependentTangent() | يحصل أو يضبط أن المماس غير معتمد على الوقت. |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| الاسم | الوصف |
| --- | --- |
| setTimeIndependentTangent(value) | يحصل أو يضبط أن المماس غير معتمد على الوقت. |

 **Result:**



---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يحصل على تمثيل النص للإطار الرئيسي |

 **Result:**
String


---



