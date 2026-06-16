---
title: "Renderer"
second_title: "Aspose.3D for Java API Referansı"
description: "Renderlayıcıyla ilgili bağlam."
type: docs
weight: 152
url: /tr/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

Renderlayıcıyla ilgili bağlam.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clearCache()](#clearCache--) | Önbelleği manuel olarak temizleyin. |
| [close()](#close--) | [Renderer](../../com.aspose.threed/renderer) 'ı yok edin ve tüm ilgili kaynakları serbest bırakın |
| [createRenderer()](#createRenderer--) | Varsayılan profil ile yeni bir [Renderer](../../com.aspose.threed/renderer) oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Belirtilen render hedefi üzerinde bir post işleme yürütür. |
| [getAssetDirectories()](#getAssetDirectories--) | Harici varlıkları depolayan dizinler. |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Gölgelerin etkinleştirilip etkinleştirilmeyeceğini alır. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Varlığın özel bir renderlayıcı tanımlı olmadığı durumda geri dönüş varlık renderlayıcısını alır. |
| [getFrustum()](#getFrustum--) | Görünüm matrisini sağlamak için kullanılan frustum'u alır. |
| [getMaterial()](#getMaterial--) | Shader'lar tarafından kullanılan malzeme bilgilerini sağlamak için kullanılan malzemeyi alır. |
| [getNode()](#getNode--) | Dünya dönüşüm matrisini sağlamak için kullanılan [getNode](../../com.aspose.threed/renderer\#getNode) örneğini alır. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Renderlayıcı tarafından desteklenen yerleşik bir post-işlemciyi alır. |
| [getPostProcessings()](#getPostProcessings--) | Aktif post-işleme zinciri |
| [getPresetShaders()](#getPresetShaders--) | Önceden ayarlanmış shader setini alır |
| [getRenderFactory()](#getRenderFactory--) | Render ile ilgili nesneleri oluşturmak için fabrikayı alır. |
| [getRenderStage()](#getRenderStage--) | Mevcut render aşamasını alır. |
| [getRenderTarget()](#getRenderTarget--) | Aşağıdaki render işlemlerinin gerçekleştirileceği render hedefini belirtin. |
| [getShader()](#getShader--) | Geometriyi renderlemek için kullanılan shader örneğini alır. |
| [getShaderSet()](#getShaderSet--) | Sahneyi renderlemek için kullanılan shader setini alır |
| [getVariables()](#getVariables--) | Renderleme için kullanılan iç değişkenlere erişim |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Belirtilen varlık için varlık renderlayıcısını kaydet |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Belirtilen hedefi renderla |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Gölge etkinleştirilip etkinleştirilmeyeceğini ayarlar. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Varlığın özel bir renderlayıcı tanımlı olmadığı durumda geri dönüş varlık renderlayıcısını ayarlar. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Görünüm matrisini sağlamak için kullanılan frustum'u ayarlar. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Shader'lar tarafından kullanılan malzeme bilgilerini sağlamak için kullanılan malzemeyi ayarlar. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Dünya dönüşüm matrisini sağlamak için kullanılan [getNode](../../com.aspose.threed/renderer\#getNode) örneğini ayarlar. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Önceden ayarlanmış shader setini ayarlar |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Geometriyi renderlemek için kullanılan shader örneğini ayarlar. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Sahneyi renderlemek için kullanılan shader setini ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Önbelleği manuel olarak temizleyin. Aspose.3D, malzemeler/geometriler gibi bazı nesneleri render boru hattıyla uyumlu iç türlere önbelleğe alır. Sahne büyük değişiklikler geçirdiğinde bu manuel olarak çağrılmalıdır.

### close() {#close--}
```
public void close()
```


[Renderer](../../com.aspose.threed/renderer) 'ı yok edin ve tüm ilgili kaynakları serbest bırakın

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Varsayılan profil ile yeni bir [Renderer](../../com.aspose.threed/renderer) oluşturur.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Belirtilen render hedefi üzerinde bir post işleme yürütür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Harici varlıkları depolayan dizinler.

**Returns:**
java.util.ArrayList<java.lang.String> - Dış varlıkların depolandığı dizinler
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


Gölgelerin etkinleştirilip etkinleştirilmeyeceğini alır.

**Returns:**
boolean - gölgelerin etkinleştirilip etkinleştirilmeyeceği.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Varlığın özel bir renderlayıcı tanımlı olmadığı durumda geri dönüş varlık renderlayıcısını alır.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Görünüm matrisini sağlamak için kullanılan frustum'u alır.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Shader'lar tarafından kullanılan malzeme bilgilerini sağlamak için kullanılan malzemeyi alır.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Dünya dönüşüm matrisini sağlamak için kullanılan [getNode](../../com.aspose.threed/renderer\#getNode) örneğini alır.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Renderlayıcı tarafından desteklenen yerleşik bir post-işlemciyi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Aktif post-işleme zinciri

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Aktif sonrası işleme zinciri
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Önceden ayarlanmış shader setini alır

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Render ile ilgili nesneleri oluşturmak için fabrikayı alır.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Mevcut render aşamasını alır.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Aşağıdaki render işlemlerinin gerçekleştirileceği render hedefini belirtin.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Geometriyi renderlemek için kullanılan shader örneğini alır.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Sahneyi renderlemek için kullanılan shader setini alır

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Renderleme için kullanılan iç değişkenlere erişim

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


Belirtilen varlık için varlık renderlayıcısını kaydet

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Belirtilen hedefi renderla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Gölge etkinleştirilip etkinleştirilmeyeceğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Varlığın özel bir renderlayıcı tanımlı olmadığı durumda geri dönüş varlık renderlayıcısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Yeni değer |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Görünüm matrisini sağlamak için kullanılan frustum'u ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Yeni değer |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Shader'lar tarafından kullanılan malzeme bilgilerini sağlamak için kullanılan malzemeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Yeni değer |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Dünya dönüşüm matrisini sağlamak için kullanılan [getNode](../../com.aspose.threed/renderer\#getNode) örneğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Yeni değer |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Önceden ayarlanmış shader setini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Yeni değer |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Geometriyi renderlemek için kullanılan shader örneğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Yeni değer |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Sahneyi renderlemek için kullanılan shader setini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Yeni değer |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

