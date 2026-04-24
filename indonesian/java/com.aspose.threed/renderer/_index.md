---
title: Renderer
second_title: Referensi API Aspose.3D untuk Java
description: Konteks tentang renderer.
type: docs
weight: 152
url: /id/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

Konteks tentang renderer.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clearCache()](#clearCache--) | Bersihkan cache secara manual. |
| [close()](#close--) | Buang [Renderer](../../com.aspose.threed/renderer) dan semua sumber daya terkait |
| [createRenderer()](#createRenderer--) | Membuat [Renderer](../../com.aspose.threed/renderer) baru dengan profil default. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Jalankan pemrosesan pasca pada target render yang ditentukan |
| [getAssetDirectories()](#getAssetDirectories--) | Direktori yang menyimpan aset eksternal |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Mendapatkan apakah bayangan diaktifkan. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Mendapatkan renderer entitas fallback ketika entitas tidak memiliki renderer khusus yang didefinisikan. |
| [getFrustum()](#getFrustum--) | Mendapatkan frustum yang digunakan untuk menyediakan matriks tampilan. |
| [getMaterial()](#getMaterial--) | Mendapatkan material yang digunakan untuk menyediakan informasi material yang dipakai oleh shader. |
| [getNode()](#getNode--) | Mendapatkan instance [getNode](../../com.aspose.threed/renderer\#getNode) yang digunakan untuk menyediakan matriks transformasi dunia. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Mendapatkan post-processor bawaan yang didukung oleh renderer. |
| [getPostProcessings()](#getPostProcessings--) | Rantai pemrosesan pasca aktif |
| [getPresetShaders()](#getPresetShaders--) | Mendapatkan set shader preset |
| [getRenderFactory()](#getRenderFactory--) | Mendapatkan pabrik untuk membangun objek terkait rendering. |
| [getRenderStage()](#getRenderStage--) | Mendapatkan tahap render saat ini. |
| [getRenderTarget()](#getRenderTarget--) | Tentukan target render dimana operasi render berikut akan dilakukan. |
| [getShader()](#getShader--) | Mendapatkan instance shader yang digunakan untuk merender geometri. |
| [getShaderSet()](#getShaderSet--) | Mendapatkan set shader yang digunakan untuk merender adegan |
| [getVariables()](#getVariables--) | Akses ke variabel internal yang digunakan untuk rendering |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Daftarkan renderer entitas untuk entitas yang ditentukan |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Render target yang ditentukan |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Mengatur apakah bayangan diaktifkan. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Mengatur renderer entitas fallback ketika entitas tidak memiliki renderer khusus yang didefinisikan. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Mengatur frustum yang digunakan untuk menyediakan matriks tampilan. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Mengatur material yang digunakan untuk menyediakan informasi material yang dipakai oleh shader. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Mengatur instance [getNode](../../com.aspose.threed/renderer\#getNode) yang digunakan untuk menyediakan matriks transformasi dunia. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Mengatur set shader preset |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Mengatur instance shader yang digunakan untuk merender geometri. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Mengatur set shader yang digunakan untuk merender adegan |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Bersihkan cache secara manual. Aspose.3D akan menyimpan beberapa objek seperti material/geometri ke dalam tipe internal yang kompatibel dengan pipeline render. Ini harus dipanggil secara manual ketika adegan mengalami perubahan besar.

### close() {#close--}
```
public void close()
```


Buang [Renderer](../../com.aspose.threed/renderer) dan semua sumber daya terkait

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Membuat [Renderer](../../com.aspose.threed/renderer) baru dengan profil default.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Jalankan pemrosesan pasca pada target render yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Direktori yang menyimpan aset eksternal

**Returns:**
java.util.ArrayList<java.lang.String> - Direktori yang menyimpan aset eksternal
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


Mendapatkan apakah bayangan diaktifkan.

**Returns:**
boolean - apakah mengaktifkan bayangan.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Mendapatkan renderer entitas fallback ketika entitas tidak memiliki renderer khusus yang didefinisikan.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Mendapatkan frustum yang digunakan untuk menyediakan matriks tampilan.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Mendapatkan material yang digunakan untuk menyediakan informasi material yang dipakai oleh shader.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Mendapatkan instance [getNode](../../com.aspose.threed/renderer\#getNode) yang digunakan untuk menyediakan matriks transformasi dunia.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Mendapatkan post-processor bawaan yang didukung oleh renderer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Rantai pemrosesan pasca aktif

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Rantai pemrosesan lanjutan aktif
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Mendapatkan set shader preset

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Mendapatkan pabrik untuk membangun objek terkait rendering.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Mendapatkan tahap render saat ini.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Tentukan target render dimana operasi render berikut akan dilakukan.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Mendapatkan instance shader yang digunakan untuk merender geometri.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Mendapatkan set shader yang digunakan untuk merender adegan

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Akses ke variabel internal yang digunakan untuk rendering

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


Daftarkan renderer entitas untuk entitas yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Render target yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Mengatur apakah bayangan diaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Mengatur renderer entitas fallback ketika entitas tidak memiliki renderer khusus yang didefinisikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Nilai baru |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Mengatur frustum yang digunakan untuk menyediakan matriks tampilan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nilai baru |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Mengatur material yang digunakan untuk menyediakan informasi material yang dipakai oleh shader.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Nilai baru |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Mengatur instance [getNode](../../com.aspose.threed/renderer\#getNode) yang digunakan untuk menyediakan matriks transformasi dunia.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nilai baru |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Mengatur set shader preset

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Nilai baru |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Mengatur instance shader yang digunakan untuk merender geometri.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Nilai baru |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Mengatur set shader yang digunakan untuk merender adegan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Nilai baru |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

