---
title: "Vector3"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

متجه ذو ثلاثة مكوّنات.


## الخصائص

| الاسم | الوصف |
| --- | --- |
| x | المكوّن x. |
| y | المكوّن y. |
| z | المكوّن z. |
| ORIGIN | يحصل على موضع الأصل. الأصل. |
| UNIT_SCALE | يحصل على متجه مقياس الوحدة. |
| X_AXIS | يحصل على محور X. محور X. |
| Y_AXIS | يحصل على محور Y. محور Y. |
| Z_AXIS | يحصل على محور Z. محور Z. |

## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(x, y, z) | ينشئ مثيلاً جديداً من بنية Vector3. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| x | Number | الإحداثي x. |
| y | Number | الإحداثي y. |
| z | Number | الإحداثي z. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| الاسم | الوصف |
| --- | --- |
| constructor_overload2(vec) | ينشئ مثيلاً جديداً من بنية Vector3. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| vec | FVector3 | الإحداثي x. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| الاسم | الوصف |
| --- | --- |
| constructor_overload3(v) | ينشئ مثيلاً جديداً من بنية Vector3. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| v | Number | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| الاسم | الوصف |
| --- | --- |
| constructor_overload4(vec4) | ينشئ مثيلاً جديداً من بنية Vector3. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| الاسم | الوصف |
| --- | --- |
| getLength2() | يحصل على مربع الطول. الطول2. |

 **Result:**



---


### getLength{#getLength}

| الاسم | الوصف |
| --- | --- |
| getLength() | يحصل على طول هذا المتجه. الطول. |

 **Result:**



---


### equals{#equals}

| الاسم | الوصف |
| --- | --- |
| equals(obj) | تحقق مما إذا كان vector3 يساوي |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| obj | Object | الكائن للتحقق من المساواة. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| الاسم | الوصف |
| --- | --- |
| hashCode() | يحصل على رمز التجزئة لـ Vector3 |

 **Result:**
Number


---


### dot{#dot}

| الاسم | الوصف |
| --- | --- |
| dot(rhs) | يحصل على حاصل الضرب النقطي لمتجهين |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| rhs | Vector3 | قيمة الطرف الأيمن. |

 **Result:**
Number


---


### normalize{#normalize}

| الاسم | الوصف |
| --- | --- |
| normalize() | يقوم بتطبيع هذه الحالة. |

 **Result:**
Vector3


---


### sin{#sin}

| الاسم | الوصف |
| --- | --- |
| sin() | يحساب جيب الزاوية لكل مكوّن |

 **Result:**
Vector3


---


### cos{#cos}

| الاسم | الوصف |
| --- | --- |
| cos() | يحساب جيب التمام لكل مكوّن |

 **Result:**
Vector3


---


### cross{#cross}

| الاسم | الوصف |
| --- | --- |
| cross(rhs) | حاصل الضرب المتقاطع لمتجهين |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| rhs | Vector3 | قيمة الطرف الأيمن. |

 **Result:**
Vector3


---


### set{#set}

| الاسم | الوصف |
| --- | --- |
| set(newX, newY, newZ) | يضبط مكوّنات x/y/z في استدعاء واحد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| newX | Number | المكوّن x. |
| newY | Number | المكوّن y. |
| newZ | Number | المكوّن z. |

 **Result:**
Vector3


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يرجع java.lang.String الذي يمثل المتجه Vector3 الحالي. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| الاسم | الوصف |
| --- | --- |
| angleBetween(dir, up) | احسب الزاوية الداخلية بين اتجاهين. يمكن أن يكون الاتجاهان متجهات غير مُعَدَّلة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| dir | Vector3 | متجه الاتجاه للمقارنة معه |
| up | Vector3 | متجه الصعود للمستوى المشترك للاتجاهين |

 **Result:**
Number


---


### angleBetween{#angleBetween}

| الاسم | الوصف |
| --- | --- |
| angleBetween(dir) | احسب الزاوية الداخلية بين اتجاهين. يمكن أن يكون الاتجاهان متجهات غير مُعَدَّلة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| dir | Vector3 | متجه الاتجاه للمقارنة معه |

 **Result:**
Number


---


### compareTo{#compareTo}

| الاسم | الوصف |
| --- | --- |
| compareTo(other) | قارن المتجه الحالي بمثيل آخر. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Number


---



