---
title: "TriMesh"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

يحتوي TriMesh على بيانات خام يمكن استخدامها مباشرةً بواسطة GPU. هذه الفئة أداة مساعدة للمساعدة في إنشاء شبكة تحتوي فقط على بيانات كل رأس.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(name, declaration) | تهيئة نسخة من TriMesh |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | اسم هذا الـ TriMesh |
| إعلان | VertexDeclaration | إعلان الفيرتكس |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| الاسم | الوصف |
| --- | --- |
| getVertexDeclaration() | تخطيط الفيرتكس للـ TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| الاسم | الوصف |
| --- | --- |
| getVerticesCount() | عدد الفيرتكس في هذا الـ TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| الاسم | الوصف |
| --- | --- |
| getIndicesCount() | عدد الفهارس في هذا TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| الاسم | الوصف |
| --- | --- |
| getUnmergedVerticesCount() | عدد الرؤوس غير المدمجة التي تم تمريرها بواسطة beginVertex() و endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| الاسم | الوصف |
| --- | --- |
| getCapacity() | سعة الرؤوس المخصصة مسبقًا. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| الاسم | الوصف |
| --- | --- |
| getVerticesSizeInBytes() | الحجم الكلي لجميع الرؤوس بالبايت |

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


### fromMesh{#fromMesh}

| الاسم | الوصف |
| --- | --- |
| fromMesh(declaration, mesh) | إنشاء TriMesh من كائن mesh المعطى مع تخطيط الرؤوس المعطى. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | شبكة | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| الاسم | الوصف |
| --- | --- |
| copyFrom(input, vd) | نسخ الـ TriMesh من الإدخال مع تخطيط رؤوس جديد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| input | TriMesh | TriMesh الإدخال للنسخ |
| vd | VertexDeclaration | إعلان الرؤوس الجديد للـ TriMesh الناتج |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| الاسم | الوصف |
| --- | --- |
| fromMesh(mesh, useFloat) | إنشاء TriMesh من كائن mesh المعطى، حيث يعتمد إعلان الرؤوس على بنية mesh الإدخال. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| mes | شبكة | null |
| useFloat | boolean | استخدام نوع float بدلاً من نوع double لكل مكوّن عنصر رأس. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| الاسم | الوصف |
| --- | --- |
| beginVertex() | بدء إضافة رأس |

 **Result:**
رأس


---


### endVertex{#endVertex}

| الاسم | الوصف |
| --- | --- |
| endVertex() | إنهاء إضافة القمة |

 **Result:**
رأس


---


### verticesToArray{#verticesToArray}

| الاسم | الوصف |
| --- | --- |
| verticesToArray() | تحويل بيانات القمم إلى مصفوفة بايت |

 **Result:**
byte[]


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| الاسم | الوصف |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | إنشاء TriMesh من البيانات الخام. TriMesh المُرجع لن ينسخ مصفوفة البايت المدخلة لأداء أفضل، وستنعكس التغييرات الخارجية على المصفوفة على هذه النسخة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| vd | VertexDeclaration | تصريح القمة، يجب أن يحتوي على حقل واحد على الأقل. |
| vertices | byte[] | بيانات القمة المدخلة، الحد الأدنى لطول القمم يجب أن يكون أكبر أو مساوي لحجم تصريح القمة. |
| indices | Number[] | مؤشرات المثلثات |
| generateVertexMapping | boolean | إنشاء |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| الاسم | الوصف |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | تحميل القمم من البايتات، يجب أن يكون طول البايتات مضاعفًا صحيحًا لحجم القمة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| الاسم | الوصف |
| --- | --- |
| readVector4(idx, field) | قراءة حقل vector4 |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| idx | Number | مؤشر القمة للقراءة |
| field | VertexField | الحقل ذو نوع بيانات Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| الاسم | الوصف |
| --- | --- |
| readFVector4(idx, field) | قراءة حقل vector4 |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| idx | Number | مؤشر القمة للقراءة |
| field | VertexField | الحقل ذو نوع بيانات Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| الاسم | الوصف |
| --- | --- |
| readVector3(idx, field) | قراءة حقل vector3 |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| idx | Number | مؤشر القمة للقراءة |
| field | VertexField | الحقل من نوع Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| الاسم | الوصف |
| --- | --- |
| readFVector3(idx, field) | قراءة حقل vector3 |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| idx | Number | مؤشر القمة للقراءة |
| field | VertexField | الحقل من نوع Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| الاسم | الوصف |
| --- | --- |
| readVector2(idx, field) | قراءة حقل vector2 |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| idx | Number | مؤشر القمة للقراءة |
| field | VertexField | الحقل من نوع Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| الاسم | الوصف |
| --- | --- |
| readFVector2(idx, field) | قراءة حقل vector2 |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| idx | Number | مؤشر القمة للقراءة |
| field | VertexField | الحقل من نوع Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| الاسم | الوصف |
| --- | --- |
| readDouble(idx, field) | قراءة حقل double |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| idx | Number | مؤشر القمة للقراءة |
| field | VertexField | الحقل من نوع متوافق مع float/double |

 **Result:**
Number


---


### readFloat{#readFloat}

| الاسم | الوصف |
| --- | --- |
| readFloat(idx, field) | قراءة حقل float |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| idx | Number | مؤشر القمة للقراءة |
| field | VertexField | الحقل من نوع متوافق مع float/double |

 **Result:**
Number


---


### getBoundingBox{#getBoundingBox}

| الاسم | الوصف |
| --- | --- |
| getBoundingBox() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |

 **Result:**
Number


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


### iterator{#iterator}

| الاسم | الوصف |
| --- | --- |
| iterator() | محجوز للاستخدام الداخلي. |

 **Result:**
خاصية


---



