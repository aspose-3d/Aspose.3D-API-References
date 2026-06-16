---
title: "شكل"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/shape/
---
## Shape class

الشكل يصف التشوه على مجموعة من نقاط التحكم، وهو مشابه لمُشوه التجمع في Maya. على سبيل المثال، يمكننا إضافة شكل إلى هيكلية مُنشأة. والشكّل والهيكلية لديهما نفس المعلومات الطوبولوجية لكن بمواقع مختلفة لنقاط التحكم. مع اختلاف مقدار التأثير، تُجري الهيكلية تأثير تشوه.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | ينشئ مثيلًا جديدًا من الفئة Shape. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(name) | ينشئ مثيلًا جديدًا من الفئة Shape. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### getIndices{#getIndices}

| الاسم | الوصف |
| --- | --- |
| getIndices() | يحصل على الفهارس. الفهارس. |

 **Result:**



---


### getVisible{#getVisible}

| الاسم | الوصف |
| --- | --- |
| getVisible() | يحصل أو يضبط ما إذا كانت الهندسة مرئية |

 **Result:**



---


### setVisible{#setVisible}

| الاسم | الوصف |
| --- | --- |
| setVisible(value) | يحصل أو يضبط ما إذا كانت الهندسة مرئية |

 **Result:**



---


### getDeformers{#getDeformers}

| الاسم | الوصف |
| --- | --- |
| getDeformers() | يحصل على جميع المشوهات المرتبطة بهذه الهندسة. المشوهات. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| الاسم | الوصف |
| --- | --- |
| getControlPoints() | يحصل على جميع نقاط التحكم |

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


### getVertexElements{#getVertexElements}

| الاسم | الوصف |
| --- | --- |
| getVertexElements() | يحصل على جميع عناصر الرؤوس |

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


### fromControlPoints{#fromControlPoints}

| الاسم | الوصف |
| --- | --- |
| fromControlPoints(controlPoints) | أنشئ شكلًا بنقاط تحكم محددة مع فهارس افتراضية. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| controlPoint | Vector3[] | null |

 **Result:**
شكل


---


### getElement{#getElement}

| الاسم | الوصف |
| --- | --- |
| getElement(type) | يحصل على عنصر رأس بالنوع المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| الاسم | الوصف |
| --- | --- |
| getVertexElementOfUV(textureMapping) | يحصل على نسخة VertexElementUV بالنوع المحدد لتعيين القوام |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| الاسم | الوصف |
| --- | --- |
| createElement(type) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. إذا كان النوع VertexElementType.UV، سيتم إنشاء VertexElementUV بنوع تعيين القوام إلى TextureMapping.DIFFUSE. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| الاسم | الوصف |
| --- | --- |
| addElement(element) | يضيف عنصر رأس موجود إلى الهندسة الحالية |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| element | VertexElement | عنصر الرأس للإضافة |

 **Result:**
VertexElement


---


### createElement{#createElement}

| الاسم | الوصف |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. إذا كان النوع VertexElementType.UV، سيتم إنشاء VertexElementUV بنوع تعيين القوام إلى TextureMapping.DIFFUSE. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| الاسم | الوصف |
| --- | --- |
| createElementUV(uvMapping) | ينشئ VertexElementUV بنوع تخطيط القوام المعطى. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| الاسم | الوصف |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | ينشئ VertexElementUV بنوع تخطيط القوام المعطى. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| الاسم | الوصف |
| --- | --- |
| getBoundingBox() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |

 **Result:**
VertexElementUV


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



