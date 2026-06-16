---
title: "PolygonModifier"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

أدوات لتعديل المضلعات  @hideconstructor


## الطرق

### triangulate{#triangulate}

| الاسم | الوصف |
| --- | --- |
| triangulate(scene) | تحويل جميع الشبكات القائمة على المضلع إلى شبكة مثلثية كاملة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| scene | Scene | المشهد المراد معالجته |

 **Result:**



---


### triangulate{#triangulate}

| الاسم | الوصف |
| --- | --- |
| triangulate(mesh) | تحويل شبكة قائمة على المضلع إلى شبكة مثلثية كاملة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| mesh | شبكة | الشبكة الأصلية غير المثلثية |

 **Result:**
شبكة


---


### mergeMesh{#mergeMesh}

| الاسم | الوصف |
| --- | --- |
| mergeMesh(scene) | تحويل المشهد بالكامل إلى شبكة محوّلة واحدة. عناصر Vertex مثل الإحداثيات العادية/الملمسية غير مدعومة بعد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| scene | Scene | المشهد المراد دمجه |

 **Result:**
شبكة


---


### mergeMesh{#mergeMesh}

| الاسم | الوصف |
| --- | --- |
| mergeMesh(node) | تحويل العقدة بالكامل إلى شبكة محوّلة واحدة. عناصر Vertex مثل الإحداثيات العادية/الملمسية غير مدعومة بعد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة | العقدة المراد دمجها |

 **Result:**
شبكة


---


### scale{#scale}

| الاسم | الوصف |
| --- | --- |
| scale(scene, scale) | تحجيم جميع الهندسات (تحجيم نقاط التحكم وليس مصفوفة التحويل) في هذا المشهد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| scene | Scene | المشهد المراد تحجيمه |
| تحجيم | Vector3 | عامل التحجيم |

 **Result:**
شبكة


---


### scale{#scale}

| الاسم | الوصف |
| --- | --- |
| scale(node, scale) | تحجيم جميع الهندسات (تحجيم نقاط التحكم وليس مصفوفة التحويل) في هذه العقدة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة | العقدة المراد تحجيمها |
| تحجيم | Vector3 | عامل التحجيم |

 **Result:**
شبكة


---


### generateNormal{#generateNormal}

| الاسم | الوصف |
| --- | --- |
| generateNormal(mesh) | إنشاء بيانات العادي من تعريف Mesh |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| الاسم | الوصف |
| --- | --- |
| generateUV(mesh, normals) | إنشاء بيانات UV من Mesh الإدخال المعطى والبيانات العادية المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| mesh | شبكة | Mesh الإدخال |
| العادي | VertexElementNormal | بيانات العادي |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| الاسم | الوصف |
| --- | --- |
| generateUV(mesh) | إنشاء بيانات UV من Mesh الإدخال المعطى |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| mesh | شبكة | Mesh الإدخال |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| الاسم | الوصف |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | تقسيم mesh إلى sub-meshes بواسطة VertexElementMaterial. كل sub-mesh سيستخدم مادة واحدة فقط. تنفيذ تقسيم mesh على عقدة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| nod | عقدة | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | إنشاء عقد فرعية لكل sub-mesh. |
| removeOldMesh | boolean | إزالة mesh القديم بعد التقسيم، إذا كان هذا المعامل false، سيستمر وجود mesh القديم والجديد معًا. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| الاسم | الوصف |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | تقسيم mesh إلى sub-meshes بواسطة VertexElementMaterial. كل sub-mesh سيستخدم مادة واحدة فقط. تنفيذ تقسيم mesh على جميع عقد scene. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| scen | Scene | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| الاسم | الوصف |
| --- | --- |
| splitMesh(mesh, policy) | تقسيم mesh إلى sub-meshes بواسطة VertexElementMaterial. كل sub-mesh سيستخدم مادة واحدة فقط. mesh الأصلي لن يتغير. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| الاسم | الوصف |
| --- | --- |
| buildTangentBinormal(scene) | سيقوم هذا بإنشاء tangent و binormal على جميع meshes في المشهد. Normal مطلوب، إذا لم يكن normal موجودًا على mesh، سيقوم أيضًا بإنشاء بيانات normal من الموضع. UV مطلوب أيضًا، سيتم تجاهل mesh إذا لم يتم تعريف UV. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| الاسم | الوصف |
| --- | --- |
| buildTangentBinormal(mesh) | سيقوم هذا بإنشاء tangent و binormal على الـ mesh. Normal مطلوب، إذا لم يكن Normal موجودًا على الـ mesh، سيُنشئ أيضًا بيانات Normal من الموضع. UV مطلوب أيضًا، سيتم رفع استثناء إذا لم يتم العثور على أي UV. |

 **Result:**
Mesh[]


---



