---
title: "Renderer"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "السياق المتعلق بالعارض."
type: docs
weight: 152
url: /ar/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

السياق المتعلق بالعارض.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clearCache()](#clearCache--) | امسح الذاكرة المؤقتة يدويًا. |
| [close()](#close--) | تخلص من [Renderer](../../com.aspose.threed/renderer) وجميع الموارد المرتبطة. |
| [createRenderer()](#createRenderer--) | ينشئ [Renderer](../../com.aspose.threed/renderer) جديدًا باستخدام الملف التعريفي الافتراضي. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | نفّذ معالجة لاحقة على هدف العرض المحدد. |
| [getAssetDirectories()](#getAssetDirectories--) | الأدلة التي تخزن الأصول الخارجية. |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | يحصل على ما إذا كان يجب تمكين الظلال. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | يحصل على عارض الكيان الاحتياطي عندما لا يكون للكيان عارض خاص معرف. |
| [getFrustum()](#getFrustum--) | يحصل على المخروط الذي كان يُستخدم لتوفير مصفوفة العرض. |
| [getMaterial()](#getMaterial--) | يحصل على المادة التي كانت تُستخدم لتوفير معلومات المادة التي يستخدمها المظللون. |
| [getNode()](#getNode--) | يحصل على مثيل [getNode](../../com.aspose.threed/renderer\#getNode) المستخدم لتوفير مصفوفة تحويل العالم. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | يحصل على معالج لاحق مدمج يدعمه العارض. |
| [getPostProcessings()](#getPostProcessings--) | سلسلة المعالجة اللاحقة النشطة |
| [getPresetShaders()](#getPresetShaders--) | يحصل على مجموعة المظلل المسبقة الإعداد |
| [getRenderFactory()](#getRenderFactory--) | يحصل على المصنع لبناء الكائنات المتعلقة بالعرض. |
| [getRenderStage()](#getRenderStage--) | يحصل على مرحلة العرض الحالية. |
| [getRenderTarget()](#getRenderTarget--) | حدد هدف العرض الذي ستُجرى عليه عمليات العرض التالية. |
| [getShader()](#getShader--) | يحصل على مثيل المظلل المستخدم لعرض الهندسة. |
| [getShaderSet()](#getShaderSet--) | يحصل على مجموعة المظلل التي كانت تُستخدم لعرض المشهد |
| [getVariables()](#getVariables--) | الوصول إلى المتغيرات الداخلية المستخدمة للعرض |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | سجّل عارض الكيان للكيان المحدد |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | اعرض الهدف المحدد |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | يضبط ما إذا كان يجب تمكين الظلال. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | يضبط عارض الكيان الاحتياطي عندما لا يكون للكيان عارض خاص معرف. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | يضبط المخروط الذي كان يُستخدم لتوفير مصفوفة العرض. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | يضبط المادة التي كانت تُستخدم لتوفير معلومات المادة التي يستخدمها المظللون. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | يضبط مثيل [getNode](../../com.aspose.threed/renderer\#getNode) المستخدم لتوفير مصفوفة تحويل العالم. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | يضبط مجموعة المظلل المسبقة الإعداد |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | يضبط مثيل المظلل المستخدم لعرض الهندسة. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | يضبط مجموعة المظلل التي كانت تُستخدم لعرض المشهد |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


امسح الذاكرة المؤقتة يدويًا. سيقوم Aspose.3D بتخزين بعض الكائنات مثل المواد/الهياكل في أنواع داخلية متوافقة مع خط أنابيب العرض. يجب استدعاؤها يدويًا عندما يحدث تغييرات كبيرة في المشهد.

### close() {#close--}
```
public void close()
```


تخلص من [Renderer](../../com.aspose.threed/renderer) وجميع الموارد المرتبطة.

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


ينشئ [Renderer](../../com.aspose.threed/renderer) جديدًا باستخدام الملف التعريفي الافتراضي.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
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
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


نفّذ معالجة لاحقة على هدف العرض المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


الأدلة التي تخزن الأصول الخارجية.

**Returns:**
java.util.ArrayList<java.lang.String> - الأدلة التي تخزن الأصول الخارجية
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableShadows() {#getEnableShadows--}
```
public boolean getEnableShadows()
```


يحصل على ما إذا كان يجب تمكين الظلال.

**Returns:**
boolean - ما إذا كان يجب تمكين الظلال.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


يحصل على عارض الكيان الاحتياطي عندما لا يكون للكيان عارض خاص معرف.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


يحصل على المخروط الذي كان يُستخدم لتوفير مصفوفة العرض.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


يحصل على المادة التي كانت تُستخدم لتوفير معلومات المادة التي يستخدمها المظللون.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


يحصل على مثيل [getNode](../../com.aspose.threed/renderer\#getNode) المستخدم لتوفير مصفوفة تحويل العالم.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


يحصل على معالج لاحق مدمج يدعمه العارض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


سلسلة المعالجة اللاحقة النشطة

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - سلسلة المعالجة اللاحقة النشطة
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


يحصل على مجموعة المظلل المسبقة الإعداد

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


يحصل على المصنع لبناء الكائنات المتعلقة بالعرض.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


يحصل على مرحلة العرض الحالية.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


حدد هدف العرض الذي ستُجرى عليه عمليات العرض التالية.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


يحصل على مثيل المظلل المستخدم لعرض الهندسة.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


يحصل على مجموعة المظلل التي كانت تُستخدم لعرض المشهد

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


الوصول إلى المتغيرات الداخلية المستخدمة للعرض

**Returns:**
[RendererVariableManager](../../com.aspose.threed/renderervariablemanager) - Access to the internal variables used for rendering
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




### registerEntityRenderer(EntityRenderer renderer) {#registerEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void registerEntityRenderer(EntityRenderer renderer)
```


سجّل عارض الكيان للكيان المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


اعرض الهدف المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


يضبط ما إذا كان يجب تمكين الظلال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


يضبط عارض الكيان الاحتياطي عندما لا يكون للكيان عارض خاص معرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | القيمة الجديدة |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


يضبط المخروط الذي كان يُستخدم لتوفير مصفوفة العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | القيمة الجديدة |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


يضبط المادة التي كانت تُستخدم لتوفير معلومات المادة التي يستخدمها المظللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | القيمة الجديدة |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


يضبط مثيل [getNode](../../com.aspose.threed/renderer\#getNode) المستخدم لتوفير مصفوفة تحويل العالم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | القيمة الجديدة |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


يضبط مجموعة المظلل المسبقة الإعداد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | القيمة الجديدة |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


يضبط مثيل المظلل المستخدم لعرض الهندسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | القيمة الجديدة |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


يضبط مجموعة المظلل التي كانت تُستخدم لعرض المشهد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | القيمة الجديدة |

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

