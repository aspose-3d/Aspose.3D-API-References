---
title: "اسطوانة"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

أسطوانة معلمة. يمكن استخدامها أيضًا لتمثيل المخروط عندما يكون أحد القيم radiusTop/radiusBottom صفرًا.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | يُنشئ مثيلاً جديدًا من الفئة Cylinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(radius, height) | يُنشئ مثيلاً جديدًا من الفئة Cylinder. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| نصف القطر | Number | نصف قطر الغطاء العلوي والسفلي. |
| height | Number | الارتفاع. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| الاسم | الوصف |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | يُنشئ مثيلاً جديدًا من الفئة Cylinder. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| radiusTop | Number | نصف قطر العلوي. |
| radiusBottom | Number | نصف قطر السفلي. |
| height | Number | الارتفاع. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| الاسم | الوصف |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | يُنشئ مثيلاً جديدًا من الفئة Cylinder. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| radiusTop | Number | نصف قطر الغطاء العلوي للأسطوانة. |
| radiusBottom | Number | نصف قطر الغطاء السفلي للأسطوانة. |
| height | Number | ارتفاع الأسطوانة. |
| radialSegments | Number | قطاعات شعاعية لكل من الدائرتين العلوية والسفلية.. |
| heightSegments | Number | مقاطع الارتفاع. |
| openEnded | boolean | إذا تم تعيينه إلى |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| الاسم | الوصف |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | يُنشئ مثيلاً جديدًا من الفئة Cylinder. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | اسم هذا الكائن |
| radiusTop | Number | نصف قطر الغطاء العلوي للأسطوانة. |
| radiusBottom | Number | نصف قطر الغطاء السفلي للأسطوانة. |
| height | Number | ارتفاع الأسطوانة. |
| radialSegments | Number | قطاعات شعاعية لكل من الدائرتين العلوية والسفلية.. |
| heightSegments | Number | مقاطع الارتفاع. |
| openEnded | boolean | إذا تم تعيينه إلى |
| thetaStart | Number | بداية Theta. |
| thetaLength | Number | طول Theta. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| الاسم | الوصف |
| --- | --- |
| getOffsetBottom() | يحصل أو يعيّن إزاحة تحويل الرؤوس للجانب السفلي. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| الاسم | الوصف |
| --- | --- |
| setOffsetBottom(value) | يحصل أو يعيّن إزاحة تحويل الرؤوس للجانب السفلي. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| الاسم | الوصف |
| --- | --- |
| getOffsetTop() | يحصل أو يعيّن إزاحة تحويل الرؤوس للجانب العلوي. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| الاسم | الوصف |
| --- | --- |
| setOffsetTop(value) | يحصل أو يعيّن إزاحة تحويل الرؤوس للجانب العلوي. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| الاسم | الوصف |
| --- | --- |
| getGenerateFanCylinder() | يحصل أو يضبط ما إذا كان سيتم إنشاء أسطوانة على شكل مروحة عندما تكون قيمة ThetaLength أقل من 2π، وإلا لن يتم قطع النموذج. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| الاسم | الوصف |
| --- | --- |
| setGenerateFanCylinder(value) | يحصل أو يضبط ما إذا كان سيتم إنشاء أسطوانة على شكل مروحة عندما تكون قيمة ThetaLength أقل من 2π، وإلا لن يتم قطع النموذج. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| الاسم | الوصف |
| --- | --- |
| getShearBottom() | يحصل أو يضبط تحويل القص للجانب السفلي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0). |

 **Result:**



---


### setShearBottom{#setShearBottom}

| الاسم | الوصف |
| --- | --- |
| setShearBottom(value) | يحصل أو يضبط تحويل القص للجانب السفلي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0). |

 **Result:**



---


### getShearTop{#getShearTop}

| الاسم | الوصف |
| --- | --- |
| getShearTop() | يحصل أو يضبط تحويل القص للجانب العلوي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0). |

 **Result:**



---


### setShearTop{#setShearTop}

| الاسم | الوصف |
| --- | --- |
| setShearTop(value) | يحصل أو يضبط تحويل القص للجانب العلوي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0). |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| الاسم | الوصف |
| --- | --- |
| getRadiusTop() | يحصل أو يضبط نصف قطر غطاء أعلى الأسطوانة. نصف قطر الغطاء العلوي. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| الاسم | الوصف |
| --- | --- |
| setRadiusTop(value) | يحصل أو يضبط نصف قطر غطاء أعلى الأسطوانة. نصف قطر الغطاء العلوي. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| الاسم | الوصف |
| --- | --- |
| getRadiusBottom() | يحصل أو يضبط نصف قطر غطاء أسفل الأسطوانة. نصف قطر الغطاء السفلي. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| الاسم | الوصف |
| --- | --- |
| setRadiusBottom(value) | يحصل أو يضبط نصف قطر غطاء أسفل الأسطوانة. نصف قطر الغطاء السفلي. |

 **Result:**



---


### getHeight{#getHeight}

| الاسم | الوصف |
| --- | --- |
| getHeight() | يحصل أو يضبط ارتفاع الأسطوانة. الارتفاع. |

 **Result:**



---


### setHeight{#setHeight}

| الاسم | الوصف |
| --- | --- |
| setHeight(value) | يحصل أو يضبط ارتفاع الأسطوانة. الارتفاع. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| الاسم | الوصف |
| --- | --- |
| getRadialSegments() | يحصل أو يضبط القطاعات الشعاعية. القطاعات الشعاعية. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| الاسم | الوصف |
| --- | --- |
| setRadialSegments(value) | يحصل أو يضبط القطاعات الشعاعية. القطاعات الشعاعية. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| الاسم | الوصف |
| --- | --- |
| getHeightSegments() | يحصل أو يضبط مقاطع الارتفاع. مقاطع الارتفاع. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| الاسم | الوصف |
| --- | --- |
| setHeightSegments(value) | يحصل أو يضبط مقاطع الارتفاع. مقاطع الارتفاع. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| الاسم | الوصف |
| --- | --- |
| getOpenEnded() | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه الأسطوانة مفتوحة النهاية. القيمة الافتراضية هي false. true إذا كانت مفتوحة النهاية؛ وإلا فإن أغطية الأعلى/الأسفل موجودة. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| الاسم | الوصف |
| --- | --- |
| setOpenEnded(value) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه الأسطوانة مفتوحة النهاية. القيمة الافتراضية هي false. true إذا كانت مفتوحة النهاية؛ وإلا فإن أغطية الأعلى/الأسفل موجودة. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| الاسم | الوصف |
| --- | --- |
| getThetaStart() | يحصل أو يضبط بداية الثيتا. القيمة الافتراضية هي 0. بداية الثيتا. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| الاسم | الوصف |
| --- | --- |
| setThetaStart(value) | يحصل أو يضبط بداية الثيتا. القيمة الافتراضية هي 0. بداية الثيتا. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| الاسم | الوصف |
| --- | --- |
| getThetaLength() | يحصل أو يضبط طول الثيتا. القيمة الافتراضية هي 2π. طول الثيتا. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| الاسم | الوصف |
| --- | --- |
| setThetaLength(value) | يحصل أو يضبط طول الثيتا. القيمة الافتراضية هي 2π. طول الثيتا. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| الاسم | الوصف |
| --- | --- |
| getCastShadows() | يحصل أو يضبط ما إذا كانت هذه الهندسة يمكنها إلقاء الظل |

 **Result:**



---


### setCastShadows{#setCastShadows}

| الاسم | الوصف |
| --- | --- |
| setCastShadows(value) | يحصل أو يضبط ما إذا كانت هذه الهندسة يمكنها إلقاء الظل |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| الاسم | الوصف |
| --- | --- |
| getReceiveShadows() | يحصل أو يضبط ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| الاسم | الوصف |
| --- | --- |
| setReceiveShadows(value) | يحصل أو يضبط ما إذا كانت هذه الهندسة يمكنها استقبال الظل. |

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


### toMesh{#toMesh}

| الاسم | الوصف |
| --- | --- |
| toMesh() | تحويل الكائن الحالي إلى mesh |

 **Result:**
شبكة


---


### getBoundingBox{#getBoundingBox}

| الاسم | الوصف |
| --- | --- |
| getBoundingBox() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |

 **Result:**
شبكة


---


### getEntityRendererKey{#getEntityRendererKey}

| الاسم | الوصف |
| --- | --- |
| getEntityRendererKey() | يحصل على مفتاح مُعالج الكيان المسجل في المُعالج |

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



