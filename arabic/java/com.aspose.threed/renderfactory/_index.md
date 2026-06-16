---
title: "RenderFactory"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "RenderFactory ينشئ جميع الموارد التي تم تمثيلها في خط أنابيب العرض."
type: docs
weight: 148
url: /ar/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory ينشئ جميع الموارد التي تم تمثيلها في خط أنابيب العرض.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | إنشاء هدف عرض يحتوي على قوام مكعب واحد |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | إنشاء مجموعة الوصف للبرنامج الظلّي المحدد. |
| [createIndexBuffer()](#createIndexBuffer--) | إنشاء مثيل [IIndexBuffer](../../com.aspose.threed/iindexbuffer) لتخزين معلومات وجوه المضلع. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | إنشاء خط أنابيب رسومي مُعد مسبقًا مع ظل/حالة عرض/إعلان رأس مُعد مسبقًا وعمليات الرسم. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | إنشاء هدف عرض يحتوي على هدف واحد يرسم إلى القوام |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | إنشاء هدف عرض يرسم إلى القوام |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | إنشاء هدف عرض يرسم إلى النافذة الأصلية. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | إنشاء كائن [ShaderProgram](../../com.aspose.threed/shaderprogram) |
| [createTextureUnit()](#createTextureUnit--) | إنشاء وحدة قوام ثنائية الأبعاد يمكن للظل الوصول إليها. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | إنشاء وحدة قوام يمكن للظل الوصول إليها. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | إنشاء مخزن موحد جديد على جانب GPU بحجم مُخصص مسبقًا. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | إنشاء مثيل [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) لتخزين معلومات رؤوس المضلع. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderFactory() {#RenderFactory--}
```
public RenderFactory()
```


### createCubeRenderTexture(RenderParameters parameters, int width, int height) {#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createCubeRenderTexture(RenderParameters parameters, int width, int height)
```


إنشاء هدف عرض يحتوي على قوام مكعب واحد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | معلمات العرض لإنشاء قوام العرض |
| العرض | int | عرض قوام العرض |
| الارتفاع | int | ارتفاع قوام العرض |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


إنشاء مجموعة الوصف للبرنامج الظلّي المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | برنامج المُظلل. |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


إنشاء مثيل [IIndexBuffer](../../com.aspose.threed/iindexbuffer) لتخزين معلومات وجوه المضلع.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


إنشاء خط أنابيب رسومي مُعد مسبقًا مع ظل/حالة عرض/إعلان رأس مُعد مسبقًا وعمليات الرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | الظل المستخدم في العرض |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | حالة العرض المستخدمة في العرض |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | إعلان الرأس لبيانات الرأس المدخلة |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | عملية الرسم |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


إنشاء هدف عرض يحتوي على هدف واحد يرسم إلى القوام

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | معلمات العرض لإنشاء قوام العرض |
| العرض | int | عرض قوام العرض |
| الارتفاع | int | ارتفاع قوام العرض |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


إنشاء هدف عرض يرسم إلى القوام

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | معلمات العرض لإنشاء قوام العرض |
| الأهداف | int | كم عدد أهداف الإخراج اللونية |
| العرض | int | عرض قوام العرض |
| الارتفاع | int | ارتفاع قوام العرض |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


إنشاء هدف عرض يرسم إلى النافذة الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | معلمات العرض لإنشاء نافذة العرض |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | معرّف النافذة للعرض |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


إنشاء كائن [ShaderProgram](../../com.aspose.threed/shaderprogram)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | الكود المصدري للـ shader |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


إنشاء وحدة قوام ثنائية الأبعاد يمكن للظل الوصول إليها.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


إنشاء وحدة قوام يمكن للظل الوصول إليها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | نوع الملمس |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


إنشاء مخزن موحد جديد على جانب GPU بحجم مُخصص مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الحجم | int | حجم المخزن الموحد |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


إنشاء مثيل [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) لتخزين معلومات رؤوس المضلع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

