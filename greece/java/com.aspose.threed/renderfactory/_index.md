---
title: RenderFactory
second_title: Aspose.3D for Java API Reference
description: Η RenderFactory δημιουργεί όλους τους πόρους που αντιπροσωπεύονται στο pipeline απόδοσης.
type: docs
weight: 148
url: /el/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

Η RenderFactory δημιουργεί όλους τους πόρους που αντιπροσωπεύονται στο pipeline απόδοσης.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Δημιουργήστε έναν προορισμό απόδοσης που περιέχει 1 υφή κύβου |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | Δημιουργήστε το σύνολο περιγραφέων για το καθορισμένο πρόγραμμα σκίασης. |
| [createIndexBuffer()](#createIndexBuffer--) | Δημιουργήστε μια παρουσία του [IIndexBuffer](../../com.aspose.threed/iindexbuffer) για την αποθήκευση των πληροφοριών προσώπων του πολυγώνου. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | Δημιουργήστε μια προρυθμισμένη γραφική διαδρομή με προρυθμισμένο shader/κατάσταση απόδοσης/δήλωση κορυφής και λειτουργίες σχεδίασης. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Δημιουργήστε έναν προορισμό απόδοσης που περιέχει 1 στόχο ο οποίος αποδίδει στην υφή |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | Δημιουργήστε έναν προορισμό απόδοσης που αποδίδει στην υφή |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | Δημιουργήστε έναν προορισμό απόδοσης που αποδίδει στο εγγενές παράθυρο. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | Δημιουργήστε ένα αντικείμενο [ShaderProgram](../../com.aspose.threed/shaderprogram) |
| [createTextureUnit()](#createTextureUnit--) | Δημιουργήστε μια μονάδα υφής 2D που μπορεί να προσπελαστεί από το shader. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | Δημιουργήστε μια μονάδα υφής που μπορεί να προσπελαστεί από το shader. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | Δημιουργήστε ένα νέο uniform buffer στην πλευρά του GPU με προ-καθορισμένο μέγεθος. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | Δημιουργήστε μια παρουσία του [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) για την αποθήκευση των πληροφοριών κορυφών του πολυγώνου. |
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


Δημιουργήστε έναν προορισμό απόδοσης που περιέχει 1 υφή κύβου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Παράμετροι απόδοσης για τη δημιουργία της υφής απόδοσης |
| width | int | Το πλάτος της υφής απόδοσης |
| height | int | Το ύψος της υφής απόδοσης |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


Δημιουργήστε το σύνολο περιγραφέων για το καθορισμένο πρόγραμμα σκίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Το πρόγραμμα shader |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


Δημιουργήστε μια παρουσία του [IIndexBuffer](../../com.aspose.threed/iindexbuffer) για την αποθήκευση των πληροφοριών προσώπων του πολυγώνου.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


Δημιουργήστε μια προρυθμισμένη γραφική διαδρομή με προρυθμισμένο shader/κατάσταση απόδοσης/δήλωση κορυφής και λειτουργίες σχεδίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Το shader που χρησιμοποιείται στην απόδοση |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | Η κατάσταση απόδοσης που χρησιμοποιείται στην απόδοση |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Η δήλωση κορυφής των εισερχόμενων δεδομένων κορυφής |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Draw operation |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


Δημιουργήστε έναν προορισμό απόδοσης που περιέχει 1 στόχο ο οποίος αποδίδει στην υφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Παράμετροι απόδοσης για τη δημιουργία της υφής απόδοσης |
| width | int | Το πλάτος της υφής απόδοσης |
| height | int | Το ύψος της υφής απόδοσης |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


Δημιουργήστε έναν προορισμό απόδοσης που αποδίδει στην υφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Παράμετροι απόδοσης για τη δημιουργία της υφής απόδοσης |
| στόχοι | int | Πόσοι χρωματικοί προορισμοί εξόδου |
| width | int | Το πλάτος της υφής απόδοσης |
| height | int | Το ύψος της υφής απόδοσης |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


Δημιουργήστε έναν προορισμό απόδοσης που αποδίδει στο εγγενές παράθυρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Παράμετροι απόδοσης για τη δημιουργία του παραθύρου απόδοσης |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | Το handle του παραθύρου για απόδοση |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


Δημιουργήστε ένα αντικείμενο [ShaderProgram](../../com.aspose.threed/shaderprogram)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | Ο κώδικας πηγής του shader |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


Δημιουργήστε μια μονάδα υφής 2D που μπορεί να προσπελαστεί από το shader.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


Δημιουργήστε μια μονάδα υφής που μπορεί να προσπελαστεί από το shader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Type of the texture |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


Δημιουργήστε ένα νέο uniform buffer στην πλευρά του GPU με προ-καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μέγεθος | int | Το μέγεθος του uniform buffer |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


Δημιουργήστε μια παρουσία του [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) για την αποθήκευση των πληροφοριών κορυφών του πολυγώνου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

