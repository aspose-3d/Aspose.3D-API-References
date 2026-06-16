---
title: "Light"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/light/
---
## Light class

الضوء يضيء المشهد. الصيغة لحساب التوهين الكلي للضوء هي: A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | ينشئ مثيلاً جديداً من الفئة Light. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(name) | ينشئ مثيلاً جديداً من الفئة Light. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| الاسم | الوصف |
| --- | --- |
| constructor_overload2(name, type) | ينشئ مثيلاً جديداً من الفئة Light. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |
| type | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| الاسم | الوصف |
| --- | --- |
| getColor() | يسترجع أو يضبط لون الضوء |

 **Result:**



---


### setColor{#setColor}

| الاسم | الوصف |
| --- | --- |
| setColor(value) | يسترجع أو يضبط لون الضوء |

 **Result:**



---


### getLightType{#getLightType}

| الاسم | الوصف |
| --- | --- |
| getLightType() | يسترجع أو يضبط نوع الضوء. قيمة الخاصية هي ثابت عدد صحيح من نوع LightType. |

 **Result:**



---


### setLightType{#setLightType}

| الاسم | الوصف |
| --- | --- |
| setLightType(value) | يسترجع أو يضبط نوع الضوء. قيمة الخاصية هي ثابت عدد صحيح من نوع LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| الاسم | الوصف |
| --- | --- |
| getCastLight() | يسترجع أو يضبط ما إذا كان مثيل الضوء الحالي يمكنه إضاءة الكائنات الأخرى. |

 **Result:**



---


### setCastLight{#setCastLight}

| الاسم | الوصف |
| --- | --- |
| setCastLight(value) | يسترجع أو يضبط ما إذا كان مثيل الضوء الحالي يمكنه إضاءة الكائنات الأخرى. |

 **Result:**



---


### getIntensity{#getIntensity}

| الاسم | الوصف |
| --- | --- |
| getIntensity() | يسترجع أو يضبط شدة الضوء، القيمة الافتراضية هي 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| الاسم | الوصف |
| --- | --- |
| setIntensity(value) | يسترجع أو يضبط شدة الضوء، القيمة الافتراضية هي 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| الاسم | الوصف |
| --- | --- |
| getHotSpot() | يحصل أو يضبط زاوية مخروط النقطة الساخنة(بالدرجات). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| الاسم | الوصف |
| --- | --- |
| setHotSpot(value) | يحصل أو يضبط زاوية مخروط النقطة الساخنة(بالدرجات). |

 **Result:**



---


### getFalloff{#getFalloff}

| الاسم | الوصف |
| --- | --- |
| getFalloff() | يحصل أو يضبط زاوية مخروط الانخفاض (بالدرجات). |

 **Result:**



---


### setFalloff{#setFalloff}

| الاسم | الوصف |
| --- | --- |
| setFalloff(value) | يحصل أو يضبط زاوية مخروط الانخفاض (بالدرجات). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| الاسم | الوصف |
| --- | --- |
| getConstantAttenuation() | يحصل أو يضبط التوهين الثابت لحساب التوهين الكلي للضوء |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| الاسم | الوصف |
| --- | --- |
| setConstantAttenuation(value) | يحصل أو يضبط التوهين الثابت لحساب التوهين الكلي للضوء |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| الاسم | الوصف |
| --- | --- |
| getLinearAttenuation() | يحصل أو يضبط التوهين الخطي لحساب التوهين الكلي للضوء |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| الاسم | الوصف |
| --- | --- |
| setLinearAttenuation(value) | يحصل أو يضبط التوهين الخطي لحساب التوهين الكلي للضوء |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| الاسم | الوصف |
| --- | --- |
| getQuadraticAttenuation() | يحصل أو يضبط التوهين التربيعي لحساب التوهين الكلي للضوء |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| الاسم | الوصف |
| --- | --- |
| setQuadraticAttenuation(value) | يحصل أو يضبط التوهين التربيعي لحساب التوهين الكلي للضوء |

 **Result:**



---


### getCastShadows{#getCastShadows}

| الاسم | الوصف |
| --- | --- |
| getCastShadows() | يحصل أو يضبط ما إذا كان الضوء يمكنه إلقاء الظلال على الكائنات الأخرى. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| الاسم | الوصف |
| --- | --- |
| setCastShadows(value) | يحصل أو يضبط ما إذا كان الضوء يمكنه إلقاء الظلال على الكائنات الأخرى. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| الاسم | الوصف |
| --- | --- |
| getShadowColor() | يحصل أو يضبط لون الظل. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| الاسم | الوصف |
| --- | --- |
| setShadowColor(value) | يحصل أو يضبط لون الظل. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| الاسم | الوصف |
| --- | --- |
| getRotationMode() | يحصل أو يضبط وضعية توجيه القَطْع المخروطي. هذه الخاصية تعمل فقط عندما يكون Target يساوي null. إذا كانت القيمة هي RotationMode.FIXED_TARGET، فإن الاتجاه يُحسب دائمًا بواسطة الخاصية LookAt. وإلا فإن LookAt يُحسب دائمًا بواسطة Direction. قيمة الخاصية هي ثابت عدد صحيح RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| الاسم | الوصف |
| --- | --- |
| setRotationMode(value) | يحصل أو يضبط وضعية توجيه القَطْع المخروطي. هذه الخاصية تعمل فقط عندما يكون Target يساوي null. إذا كانت القيمة هي RotationMode.FIXED_TARGET، فإن الاتجاه يُحسب دائمًا بواسطة الخاصية LookAt. وإلا فإن LookAt يُحسب دائمًا بواسطة Direction. قيمة الخاصية هي ثابت عدد صحيح RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| الاسم | الوصف |
| --- | --- |
| getNearPlane() | يحصل أو يضبط مسافة المستوى القريب للقَطْع المخروطي. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| الاسم | الوصف |
| --- | --- |
| setNearPlane(value) | يحصل أو يضبط مسافة المستوى القريب للقَطْع المخروطي. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| الاسم | الوصف |
| --- | --- |
| getFarPlane() | يحصل أو يضبط مسافة المستوى البعيد للمقَطع. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| الاسم | الوصف |
| --- | --- |
| setFarPlane(value) | يحصل أو يضبط مسافة المستوى البعيد للمقَطع. |

 **Result:**



---


### getAspect{#getAspect}

| الاسم | الوصف |
| --- | --- |
| getAspect() | يحصل أو يضبط نسبة العرض إلى الارتفاع للمقَطع |

 **Result:**



---


### setAspect{#setAspect}

| الاسم | الوصف |
| --- | --- |
| setAspect(value) | يحصل أو يضبط نسبة العرض إلى الارتفاع للمقَطع |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| الاسم | الوصف |
| --- | --- |
| getOrthoHeight() | يحصل أو يضبط الارتفاع عندما يكون المقَطع في الإسقاط المتعامد. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| الاسم | الوصف |
| --- | --- |
| setOrthoHeight(value) | يحصل أو يضبط الارتفاع عندما يكون المقَطع في الإسقاط المتعامد. |

 **Result:**



---


### getUp{#getUp}

| الاسم | الوصف |
| --- | --- |
| getUp() | يحصل أو يضبط اتجاه الصعود للكاميرا |

 **Result:**



---


### setUp{#setUp}

| الاسم | الوصف |
| --- | --- |
| setUp(value) | يحصل أو يضبط اتجاه الصعود للكاميرا |

 **Result:**



---


### getLookAt{#getLookAt}

| الاسم | الوصف |
| --- | --- |
| getLookAt() | يحصل أو يضبط الموقع المستهدف الذي تنظر إليه الكاميرا. |

 **Result:**



---


### setLookAt{#setLookAt}

| الاسم | الوصف |
| --- | --- |
| setLookAt(value) | يحصل أو يضبط الموقع المستهدف الذي تنظر إليه الكاميرا. |

 **Result:**



---


### getDirection{#getDirection}

| الاسم | الوصف |
| --- | --- |
| getDirection() | يحصل أو يضبط الاتجاه الذي تنظر إليه الكاميرا. التغييرات على هذه الخاصية ستؤثر أيضًا على LookAt و Target. |

 **Result:**



---


### setDirection{#setDirection}

| الاسم | الوصف |
| --- | --- |
| setDirection(value) | يحصل أو يضبط الاتجاه الذي تنظر إليه الكاميرا. التغييرات على هذه الخاصية ستؤثر أيضًا على LookAt و Target. |

 **Result:**



---


### getTarget{#getTarget}

| الاسم | الوصف |
| --- | --- |
| getTarget() | يحصل أو يضبط الهدف الذي تنظر إليه الكاميرا. إذا كان المستخدم يدعم هذه الخاصية، يجب أن تكون قبل خاصية LookAt. |

 **Result:**



---


### setTarget{#setTarget}

| الاسم | الوصف |
| --- | --- |
| setTarget(value) | يحصل أو يضبط الهدف الذي تنظر إليه الكاميرا. إذا كان المستخدم يدعم هذه الخاصية، يجب أن تكون قبل خاصية LookAt. |

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


### getBoundingBox{#getBoundingBox}

| الاسم | الوصف |
| --- | --- |
| getBoundingBox() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |

 **Result:**



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



