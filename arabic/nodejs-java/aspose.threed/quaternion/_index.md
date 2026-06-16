---
title: "كواترنيون"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

غالبًا ما يُستخدم الكواتيرنيون لإجراء الدوران في الرسومات الحاسوبية.


## الخصائص

| الاسم | الوصف |
| --- | --- |
| w | المكوّن w. |
| x | المكوّن x. |
| y | المكوّن y. |
| z | المكوّن z. |
| IDENTITY | الرباعي الهوية. |

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
| constructor_overload(w, x, y, z) | ينشئ مثيلاً جديداً من الفئة Quaternion. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| w | Number | المكوّن w للرباعي |
| x | Number | المكوّن x للرباعي |
| y | Number | المكوّن y للرباعي |
| z | Number | المكوّن z للرباعي |

 **Result:**



---


### getLength{#getLength}

| الاسم | الوصف |
| --- | --- |
| getLength() | يحصل على طول الرباعي |

 **Result:**



---


### equals{#equals}

| الاسم | الوصف |
| --- | --- |
| equals(obj) | تحقق مما إذا كان رباعيان متساويان |

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
| hashCode() | يحصل على رمز التجزئة للرباعي |

 **Result:**
Number


---


### conjugate{#conjugate}

| الاسم | الوصف |
| --- | --- |
| conjugate() | يرجع رباعياً مرافقاً للرباعي الحالي |

 **Result:**
كواترنيون


---


### inverse{#inverse}

| الاسم | الوصف |
| --- | --- |
| inverse() | يرجع رباعياً معكوساً للرباعي الحالي |

 **Result:**
كواترنيون


---


### dot{#dot}

| الاسم | الوصف |
| --- | --- |
| dot(q) | منتج النقاط |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| q | كواترنيون | الرباعي |

 **Result:**
Number


---


### eulerAngles{#eulerAngles}

| الاسم | الوصف |
| --- | --- |
| eulerAngles() | يحوّل الرباعي إلى دوران ممثل بزاويا أويلر جميع المكونات بالراديان |

 **Result:**
Vector3


---


### normalize{#normalize}

| الاسم | الوصف |
| --- | --- |
| normalize() | قم بتطبيع الرباعي |

 **Result:**
كواترنيون


---


### concat{#concat}

| الاسم | الوصف |
| --- | --- |
| concat(rhs) | دمج رباعيتين |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| rh | كواترنيون | null |

 **Result:**
كواترنيون


---


### fromAngleAxis{#fromAngleAxis}

| الاسم | الوصف |
| --- | --- |
| fromAngleAxis(a, axis) | ينشئ رباعياً حول المحور المعطى ويدور في اتجاه عقارب الساعة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| a | Number | دوران باتجاه عقارب الساعة بالراديان |
| محور | Vector3 | محور |

 **Result:**
كواترنيون


---


### fromRotation{#fromRotation}

| الاسم | الوصف |
| --- | --- |
| fromRotation(orig, dest) | ينشئ رباعياً يدور من الاتجاه الأصلي إلى الاتجاه الوجهة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| orig | Vector3 | الاتجاه الأصلي |
| dest | Vector3 | الاتجاه الوجهة |

 **Result:**
كواترنيون


---


### fromEulerAngle{#fromEulerAngle}

| الاسم | الوصف |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | ينشئ رباعياً من زاوية أويلر المعطاة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| pitch | Number | الارتفاع بالراديان |
| yaw | Number | الانحراف بالراديان |
| دوران | Number | دوران بالراديان |

 **Result:**
كواترنيون


---


### fromEulerAngle{#fromEulerAngle}

| الاسم | الوصف |
| --- | --- |
| fromEulerAngle(eulerAngle) | ينشئ رباعياً من زاوية أويلر المعطاة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| eulerAngle | Vector3 | زاوية Euler بالراديان |

 **Result:**
كواترنيون


---


### toMatrix{#toMatrix}

| الاسم | الوصف |
| --- | --- |
| toMatrix() | تحويل الدوران المقدم بواسطة quaternion إلى مصفوفة التحويل. |

 **Result:**
Matrix4


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يحصل على تمثيل quaternion في سلسلة. |

 **Result:**
String


---


### interpolate{#interpolate}

| الاسم | الوصف |
| --- | --- |
| interpolate(t, from, to) | يملأ هذا quaternion بالقيمة المتوسطة بين معاملات quaternion المعطاة عندما تكون t بين from و to. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| t | Number | المعامل للاستيفاء. |
| from | كواترنيون | quaternion المصدر. |
| to | كواترنيون | quaternion الهدف. |

 **Result:**
كواترنيون


---



