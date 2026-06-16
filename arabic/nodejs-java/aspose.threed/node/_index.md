---
title: "عقدة"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/node/
---
## Node class

يمثّل عنصرًا في رسم المشهد. رسم المشهد هو شجرة من كائنات Node. خدمات إدارة الشجرة مدمجة في هذه الفئة. لاحظ أن Aspose.3D SDK لا يتحقق من صحة رسم المشهد المُنشأ. تقع على عاتق المستدعي مسؤولية التأكد من عدم توليد رسومات بيانية دورية في هيكلية العقد. بالإضافة إلى إدارة الشجرة، تُعرّف هذه الفئة جميع الخصائص المطلوبة لوصف موقع الكائن في المشهد. تشمل هذه المعلومات الخصائص الأساسية للترجمة (Translation)، والدوران (Rotation)، والقياس (Scaling) بالإضافة إلى الخيارات المتقدمة للمحاور، والحدود، وخصائص مفاصل IK مثل الصلابة والامتصاص. عند إنشائه لأول مرة، يكون كائن Node "فارغًا" (أي: هو كائن بدون أي تمثيل رسومي يحتوي فقط على معلومات الموقع). في هذه الحالة، يمكن استخدامه لتمثيل الآباء في هيكل شجرة العقد ولكن ليس أكثر من ذلك. الاستخدام العادي لهذا النوع من الكائنات هو إضافة كيان (entity) يخصص العقدة (انظر "Entity"). الكيان هو كائن بحد ذاته ومتصّل بـ Node. وهذا يعني أيضًا أن نفس الكيان يمكن مشاركته بين عدة عقد. الكاميرا، الضوء، الشبكة، إلخ... كلها كيانات وتُشتق جميعها من الفئة الأساسية Entity.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | يُنشئ مثيلاً جديدًا من الفئة Node. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(name, entity) | يُنشئ مثيلاً جديدًا من الفئة Node. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم. |
| كيان | كيان | الكيان الافتراضي. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| الاسم | الوصف |
| --- | --- |
| constructor_overload2(name) | يُنشئ مثيلاً جديدًا من الفئة Node. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| الاسم | الوصف |
| --- | --- |
| getAssetInfo() | معلومات الأصل لكل عقدة |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| الاسم | الوصف |
| --- | --- |
| setAssetInfo(value) | معلومات الأصل لكل عقدة |

 **Result:**



---


### getVisible{#getVisible}

| الاسم | الوصف |
| --- | --- |
| getVisible() | يحصل أو يضبط لإظهار العقدة |

 **Result:**



---


### setVisible{#setVisible}

| الاسم | الوصف |
| --- | --- |
| setVisible(value) | يحصل أو يضبط لإظهار العقدة |

 **Result:**



---


### getChildNodes{#getChildNodes}

| الاسم | الوصف |
| --- | --- |
| getChildNodes() | يحصل على عقد الأطفال. العقد. |

 **Result:**



---


### getEntity{#getEntity}

| الاسم | الوصف |
| --- | --- |
| getEntity() | يحصل أو يضبط الكيان الأول المرتبط بهذه العقدة، إذا تم الضبط، سيُمسح الكيانات الأخرى. كيان العقدة. |

 **Result:**



---


### setEntity{#setEntity}

| الاسم | الوصف |
| --- | --- |
| setEntity(value) | يحصل أو يضبط الكيان الأول المرتبط بهذه العقدة، إذا تم الضبط، سيُمسح الكيانات الأخرى. كيان العقدة. |

 **Result:**



---


### getExcluded{#getExcluded}

| الاسم | الوصف |
| --- | --- |
| getExcluded() | يحصل أو يضبط ما إذا كان يجب استبعاد هذه العقدة وجميع عقد/كيانات الأطفال أثناء التصدير. |

 **Result:**



---


### setExcluded{#setExcluded}

| الاسم | الوصف |
| --- | --- |
| setExcluded(value) | يحصل أو يضبط ما إذا كان يجب استبعاد هذه العقدة وجميع عقد/كيانات الأطفال أثناء التصدير. |

 **Result:**



---


### getEntities{#getEntities}

| الاسم | الوصف |
| --- | --- |
| getEntities() | يحصل على جميع كيانات العقدة. كيانات العقدة. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| الاسم | الوصف |
| --- | --- |
| getMetaDatas() | يحصل على البيانات الوصفية المعرفة في هذه العقدة. البيانات الوصفية. |

 **Result:**



---


### getMaterials{#getMaterials}

| الاسم | الوصف |
| --- | --- |
| getMaterials() | يحصل على المواد المرتبطة بهذه العقدة. المواد. |

 **Result:**



---


### getMaterial{#getMaterial}

| الاسم | الوصف |
| --- | --- |
| getMaterial() | يحصل أو يضبط المادة الأولى المرتبطة بهذه العقدة، إذا تم الضبط، سيُمسح المواد الأخرى. المادة. |

 **Result:**



---


### setMaterial{#setMaterial}

| الاسم | الوصف |
| --- | --- |
| setMaterial(value) | يحصل أو يضبط المادة الأولى المرتبطة بهذه العقدة، إذا تم الضبط، سيُمسح المواد الأخرى. المادة. |

 **Result:**



---


### getParentNode{#getParentNode}

| الاسم | الوصف |
| --- | --- |
| getParentNode() | يحصل أو يضبط العقدة الأصلية. العقدة الأصلية. |

 **Result:**



---


### setParentNode{#setParentNode}

| الاسم | الوصف |
| --- | --- |
| setParentNode(value) | يحصل أو يضبط العقدة الأصلية. العقدة الأصلية. |

 **Result:**



---


### getTransform{#getTransform}

| الاسم | الوصف |
| --- | --- |
| getTransform() | يحصل على التحويل المحلي. التحويل. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| الاسم | الوصف |
| --- | --- |
| getGlobalTransform() | يحصل على التحويل العالمي. التحويل العالمي. |

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


### createChildNode{#createChildNode}

| الاسم | الوصف |
| --- | --- |
| createChildNode() | ينشئ عقدة فرعية |

 **Result:**
عقدة


---


### merge{#merge}

| الاسم | الوصف |
| --- | --- |
| merge(node) | افصل كل شيء تحت العقدة وأرفقه بالعقدة الحالية. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| nod | عقدة | null |

 **Result:**
عقدة


---


### createChildNode{#createChildNode}

| الاسم | الوصف |
| --- | --- |
| createChildNode(nodeName) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| nodeName | String | اسم العقدة الفرعية الجديدة |

 **Result:**
عقدة


---


### createChildNode{#createChildNode}

| الاسم | الوصف |
| --- | --- |
| createChildNode(entity) | إنشاء عقدة فرعية جديدة مع إرفاق الكيان المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان الافتراضي المرفق بالعقدة |

 **Result:**
عقدة


---


### createChildNode{#createChildNode}

| الاسم | الوصف |
| --- | --- |
| createChildNode(nodeName, entity) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| nodeName | String | اسم العقدة الفرعية الجديدة |
| كيان | كيان | الكيان الافتراضي المرفق بالعقدة |

 **Result:**
عقدة


---


### createChildNode{#createChildNode}

| الاسم | الوصف |
| --- | --- |
| createChildNode(nodeName, entity, material) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة، وإرفاق الكيان المحدد ومادة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| nodeName | String | اسم العقدة الفرعية الجديدة |
| كيان | كيان | الكيان الافتراضي المرفق بالعقدة |
| material | مادة | المادة المرفقة بالعقدة |

 **Result:**
عقدة


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| الاسم | الوصف |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | تقييم التحويل العالمي، تضمين التحويل الهندسي أم لا. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| withGeometricTransform | boolean | ما إذا كان التحويل الهندسي مطلوبًا. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| الاسم | الوصف |
| --- | --- |
| getChild(index) | يحصل على العقدة الفرعية في الفهرس المحدد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الفهرس | Number | الفهرس. |

 **Result:**
عقدة


---


### getChild{#getChild}

| الاسم | الوصف |
| --- | --- |
| getChild(nodeName) | يحصل على العقدة الفرعية بالاسم المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| nodeName | String | اسم العقدة الفرعية للبحث عنه. |

 **Result:**
عقدة


---


### accept{#accept}

| الاسم | الوصف |
| --- | --- |
| accept(visitor) | يتجول عبر جميع العقد التابعة (بما في ذلك العقدة الحالية) ويستدعي الزائر مع العقدة. يمكن للزائر إيقاف التجول بإرجاع false |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الزائر | NodeVisitor | استدعاء الزائر لزيارة العقدة |

 **Result:**
boolean


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يحصل على تمثيل النص لهذه العقدة. |

 **Result:**
String


---


### getBoundingBox{#getBoundingBox}

| الاسم | الوصف |
| --- | --- |
| getBoundingBox() | احسب الصندوق المحيط للعقدة |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| الاسم | الوصف |
| --- | --- |
| addEntity(entity) | أضف كيانًا إلى العقدة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان المراد إرفاقه بالعقدة |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| الاسم | الوصف |
| --- | --- |
| addChildNode(node) | أضف عقدة فرعية إلى هذه العقدة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة | العقدة الفرعية المراد إرفاقها |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| الاسم | الوصف |
| --- | --- |
| selectSingleObject(path) | حدد كائنًا واحدًا تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| pat | String | null |

 **Result:**
Object


---


### selectObjects{#selectObjects}

| الاسم | الوصف |
| --- | --- |
| selectObjects(path) | حدد عدة كائنات تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| pat | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



