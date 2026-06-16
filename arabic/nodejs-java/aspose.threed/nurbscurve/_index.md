---
title: "NurbsCurve"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

منحنى NURBS هو منحنى يُمثَّل بـ NURBS (Non-uniform rational basis spline)، يُعرّف منحنى NURBS بترتيبه، ومجموعة من نقاط Geometry.ControlPoints ذات الوزن، وKnotVectors. يُستخدم المكوّن w في نقطة التحكم كوزن لنقطة التحكم، سواء كان CurveDimension.TWO_DIMENSIONAL أو CurveDimension.THREE_DIMENSIONAL.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | ينشئ مثيلاً جديداً من الفئة NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(name) | ينشئ مثيلاً جديداً من الفئة NurbsCurve. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### getControlPoints{#getControlPoints}

| الاسم | الوصف |
| --- | --- |
| getControlPoints() | يحصل على جميع نقاط التحكم |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| الاسم | الوصف |
| --- | --- |
| getMultiplicity() | يحصل على التعددية. التعددية. |

 **Result:**



---


### getOrder{#getOrder}

| الاسم | الوصف |
| --- | --- |
| getOrder() | يحصل أو يضبط ترتيب منحنى NURBS، يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة على المنحنى. الترتيب. |

 **Result:**



---


### setOrder{#setOrder}

| الاسم | الوصف |
| --- | --- |
| setOrder(value) | يحصل أو يضبط ترتيب منحنى NURBS، يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة على المنحنى. الترتيب. |

 **Result:**



---


### getDimension{#getDimension}

| الاسم | الوصف |
| --- | --- |
| getDimension() | يحصل أو يضبط بُعد المنحنى. قيمة الخاصية هي ثابت عدد صحيح من CurveDimension. بالنسبة لمنحنى CurveDimension.TWO_DIMENSIONAL، مكوّن z في نقطة التحكم غير مستخدم. |

 **Result:**



---


### setDimension{#setDimension}

| الاسم | الوصف |
| --- | --- |
| setDimension(value) | يحصل أو يضبط بُعد المنحنى. قيمة الخاصية هي ثابت عدد صحيح من CurveDimension. بالنسبة لمنحنى CurveDimension.TWO_DIMENSIONAL، مكوّن z في نقطة التحكم غير مستخدم. |

 **Result:**



---


### getCurveType{#getCurveType}

| الاسم | الوصف |
| --- | --- |
| getCurveType() | يحصل أو يضبط نوع المنحنى. قيمة الخاصية هي ثابت عدد صحيح من نوع NurbsType. نوع المنحنى. |

 **Result:**



---


### setCurveType{#setCurveType}

| الاسم | الوصف |
| --- | --- |
| setCurveType(value) | يحصل أو يضبط نوع المنحنى. قيمة الخاصية هي ثابت عدد صحيح من نوع NurbsType. نوع المنحنى. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| الاسم | الوصف |
| --- | --- |
| getKnotVectors() | يحصل على متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS. |

 **Result:**



---


### getRational{#getRational}

| الاسم | الوصف |
| --- | --- |
| getRational() | يحصل أو يضبط ما إذا كان منطقيًا، هذه القيمة تشير إلى ما إذا كان هذا NurbsCurve هو منحنى منطقي أو غير منطقي. الـ B-spline غير المنطقي هو حالة خاصة من الـ B-splines المنطقية. true إذا كان منحنى منطقي؛ وإلا فإن false هو منحنى غير منطقي. |

 **Result:**



---


### setRational{#setRational}

| الاسم | الوصف |
| --- | --- |
| setRational(value) | يحصل أو يضبط ما إذا كان منطقيًا، هذه القيمة تشير إلى ما إذا كان هذا NurbsCurve هو منحنى منطقي أو غير منطقي. الـ B-spline غير المنطقي هو حالة خاصة من الـ B-splines المنطقية. true إذا كان منحنى منطقي؛ وإلا فإن false هو منحنى غير منطقي. |

 **Result:**



---


### getColor{#getColor}

| الاسم | الوصف |
| --- | --- |
| getColor() | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| الاسم | الوصف |
| --- | --- |
| setColor(value) | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض(1, 1, 1) |

 **Result:**



---


### getParentNodes{#getParentNodes}

| الاسم | الوصف |
| --- | --- |
| getParentNodes() | يحصل على جميع العقد الأصلية، يمكن ربط كيان بعدة عقد أصلية لتكرار الهندسة. العقد. |

 **Result:**



---


### getExcluded{#getExcluded}

| الاسم | الوصف |
| --- | --- |
| getExcluded() | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |

 **Result:**



---


### setExcluded{#setExcluded}

| الاسم | الوصف |
| --- | --- |
| setExcluded(value) | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |

 **Result:**



---


### getParentNode{#getParentNode}

| الاسم | الوصف |
| --- | --- |
| getParentNode() | يحصل أو يضبط العقدة الأصلية الأولى، إذا تم ضبط العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. العقدة الأصلية. |

 **Result:**



---


### setParentNode{#setParentNode}

| الاسم | الوصف |
| --- | --- |
| setParentNode(value) | يحصل أو يضبط العقدة الأصلية الأولى، إذا تم ضبط العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. العقدة الأصلية. |

 **Result:**



---


### getScene{#getScene}

| الاسم | الوصف |
| --- | --- |
| getScene() | يحصل على المشهد الذي ينتمي إليه هذا الكائن |

 **Result:**



---


### getName{#getName}

| الاسم | الوصف |
| --- | --- |
| getName() | يحصل أو يضبط الاسم. الاسم. |

 **Result:**



---


### setName{#setName}

| الاسم | الوصف |
| --- | --- |
| setName(value) | يحصل أو يضبط الاسم. الاسم. |

 **Result:**



---


### getProperties{#getProperties}

| الاسم | الوصف |
| --- | --- |
| getProperties() | يحصل على مجموعة جميع الخصائص. |

 **Result:**



---


### evaluate{#evaluate}

| الاسم | الوصف |
| --- | --- |
| evaluate(steps) | تقييم منحنى NURBS |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خطوات | Number | تردد التقييم بين عقدتين متجاورتين، القيمة الافتراضية هي 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| الاسم | الوصف |
| --- | --- |
| evaluateAt(u) | تقييم نقطة المنحنى عند الموضع المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| u | Number | الموضع في المنحنى، بين 0 و 1 |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| الاسم | الوصف |
| --- | --- |
| getEntityRendererKey() | يحصل على مفتاح مُعالج الكيان المسجل في المُعالج |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| الاسم | الوصف |
| --- | --- |
| getBoundingBox() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| الاسم | الوصف |
| --- | --- |
| removeProperty(property) | يزيل خاصية ديناميكية. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خاصية | خاصية | أي خاصية لإزالتها |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| الاسم | الوصف |
| --- | --- |
| removeProperty(property) | إزالة الخاصية المحددة بالاسم |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خاصية | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| الاسم | الوصف |
| --- | --- |
| getProperty(property) | احصل على قيمة الخاصية المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خاصية | String | اسم الخاصية |

 **Result:**
Object


---


### setProperty{#setProperty}

| الاسم | الوصف |
| --- | --- |
| setProperty(property, value) | يضبط قيمة الخاصية المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خاصية | String | اسم الخاصية |
| القيمة | Object | قيمة الخاصية |

 **Result:**
Object


---


### findProperty{#findProperty}

| الاسم | الوصف |
| --- | --- |
| findProperty(propertyName) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty/SetProperty) أو خاصية أصلية (تم التعرف عليها باسمها) |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| propertyName | String | اسم الخاصية. |

 **Result:**
خاصية


---



