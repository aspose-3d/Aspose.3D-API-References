---
title: "RenderFactory"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory ينشئ جميع الموارد التي تم تمثيلها في خط أنابيب العرض.  @hideconstructor


## الطرق

### createRenderTexture{#createRenderTexture}

| الاسم | الوصف |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | إنشاء هدف تصيير يقوم بالتصيير إلى القوام |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| parameters | RenderParameters | معلمات التصيير لإنشاء قوام التصيير |
| targets | Number | عدد أهداف الإخراج اللونية |
| width | Number | عرض قوام التصيير |
| height | Number | ارتفاع قوام التصيير |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| الاسم | الوصف |
| --- | --- |
| createRenderTexture(parameters, width, height) | إنشاء هدف تصيير يحتوي على هدف واحد يقوم بالتصيير إلى القوام |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| parameters | RenderParameters | معلمات التصيير لإنشاء قوام التصيير |
| width | Number | عرض قوام التصيير |
| height | Number | ارتفاع قوام التصيير |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| الاسم | الوصف |
| --- | --- |
| createDescriptorSet(shader) | إنشاء مجموعة الوصف للبرنامج الظلي المحدد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| shader | ShaderProgram | برنامج الظل |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| الاسم | الوصف |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | إنشاء هدف تصيير يحتوي على قوام مكعب واحد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| parameters | RenderParameters | معلمات التصيير لإنشاء قوام التصيير |
| width | Number | عرض قوام التصيير |
| height | Number | ارتفاع قوام التصيير |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| الاسم | الوصف |
| --- | --- |
| createRenderWindow(parameters, handle) | إنشاء هدف تصيير يقوم بالتصيير إلى النافذة الأصلية. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| parameters | RenderParameters | معلمات التصيير لإنشاء نافذة التصيير |
| handle | WindowHandle | معرف النافذة التي سيتم التصيير فيها |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| الاسم | الوصف |
| --- | --- |
| createVertexBuffer(declaration) | إنشاء مثيل com.aspose.threed.IVertexBuffer لتخزين معلومات رؤوس المضلع. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| الاسم | الوصف |
| --- | --- |
| createIndexBuffer() | إنشاء مثيل com.aspose.threed.IIndexBuffer لتخزين معلومات أوجه المضلع. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| الاسم | الوصف |
| --- | --- |
| createTextureUnit(textureType) | إنشاء وحدة نسيج يمكن الوصول إليها بواسطة المظلّل. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| الاسم | الوصف |
| --- | --- |
| createTextureUnit() | إنشاء وحدة نسيج ثنائية الأبعاد يمكن الوصول إليها بواسطة المظلّل. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| الاسم | الوصف |
| --- | --- |
| createShaderProgram(shaderSource) | إنشاء كائن ShaderProgram |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| shaderSource | مصدر التظليل | كود المصدر للمظلّل |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| الاسم | الوصف |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | إنشاء خط أنابيب رسومي مُكوَّن مسبقًا مع المظلّل/حالة العرض/إعلان الرؤوس وعمليات الرسم المُعدة مسبقًا. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| shader | ShaderProgram | المظلّل المستخدم في العرض |
| renderState | RenderState | حالة العرض المستخدمة في العرض |
| vertexDeclaration | VertexDeclaration | إعلان الرؤوس لبيانات الرؤوس المدخلة |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| الاسم | الوصف |
| --- | --- |
| createUniformBuffer(size) | إنشاء مخزن موحد جديد على جانب وحدة معالجة الرسومات بحجم مخصص مسبقًا. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الحجم | Number | حجم المخزن الموحد |

 **Result:**
IBuffer


---



