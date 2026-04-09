---
title: Renderer
second_title: Aspose.3D for Java API Reference
description: Το πλαίσιο σχετικά με τον renderer.
type: docs
weight: 152
url: /el/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

Το πλαίσιο σχετικά με τον renderer.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clearCache()](#clearCache--) | Καθαρίστε τη λανθάνουσα μνήμη χειροκίνητα. |
| [close()](#close--) | Αποδεσμεύστε το [Renderer](../../com.aspose.threed/renderer) και όλους τους σχετικούς πόρους |
| [createRenderer()](#createRenderer--) | Δημιουργεί ένα νέο [Renderer](../../com.aspose.threed/renderer) με προεπιλεγμένο προφίλ. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | Εκτελέστε μια μεταεπεξεργασία στον καθορισμένο στόχο απόδοσης |
| [getAssetDirectories()](#getAssetDirectories--) | Καταλόγοι που αποθηκεύουν εξωτερικά περιουσιακά στοιχεία |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Λαμβάνει αν ενεργοποιηθούν οι σκιές. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | Λαμβάνει τον εφεδρικό αποδοχέα οντοτήτων όταν η οντότητα δεν έχει ορισμένο ειδικό αποδοχέα. |
| [getFrustum()](#getFrustum--) | Λαμβάνει το frustum που χρησιμοποιείται για την παροχή του πίνακα προβολής. |
| [getMaterial()](#getMaterial--) | Λαμβάνει το υλικό που χρησιμοποιείται για την παροχή πληροφοριών υλικού που χρησιμοποιούν οι shaders. |
| [getNode()](#getNode--) | Λαμβάνει το παράδειγμα [getNode](../../com.aspose.threed/renderer\#getNode) που χρησιμοποιείται για την παροχή του πίνακα μετασχηματισμού του κόσμου. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | Λαμβάνει έναν ενσωματωμένο μετα-επεξεργαστή που υποστηρίζεται από τον αποδοχέα. |
| [getPostProcessings()](#getPostProcessings--) | Ενεργή αλυσίδα μετα-επεξεργασίας |
| [getPresetShaders()](#getPresetShaders--) | Λαμβάνει το προκαθορισμένο σύνολο shaders |
| [getRenderFactory()](#getRenderFactory--) | Λαμβάνει το εργοστάσιο για τη δημιουργία αντικειμένων σχετικών με την απόδοση. |
| [getRenderStage()](#getRenderStage--) | Λαμβάνει το τρέχον στάδιο απόδοσης. |
| [getRenderTarget()](#getRenderTarget--) | Καθορίστε τον προορισμό απόδοσης στον οποίο θα εκτελεστούν οι παρακάτω λειτουργίες απόδοσης. |
| [getShader()](#getShader--) | Λαμβάνει το παράδειγμα shader που χρησιμοποιείται για την απόδοση της γεωμετρίας. |
| [getShaderSet()](#getShaderSet--) | Λαμβάνει το σύνολο shaders που χρησιμοποιείται για την απόδοση της σκηνής |
| [getVariables()](#getVariables--) | Πρόσβαση στις εσωτερικές μεταβλητές που χρησιμοποιούνται για την απόδοση |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | Καταχωρίστε τον αποδοχέα οντοτήτων για την καθορισμένη οντότητα |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | Αποδώστε τον καθορισμένο προορισμό |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Ορίζει αν θα ενεργοποιηθούν οι σκιές. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | Ορίζει τον εφεδρικό αποδοχέα οντοτήτων όταν η οντότητα δεν έχει ορισμένο ειδικό αποδοχέα. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Ορίζει το frustum που χρησιμοποιείται για την παροχή του πίνακα προβολής. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Ορίζει το υλικό που χρησιμοποιείται για την παροχή πληροφοριών υλικού που χρησιμοποιούν οι shaders. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Ορίζει το παράδειγμα [getNode](../../com.aspose.threed/renderer\#getNode) που χρησιμοποιείται για την παροχή του πίνακα μετασχηματισμού του κόσμου. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | Ορίζει το προκαθορισμένο σύνολο shaders |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | Ορίζει το παράδειγμα shader που χρησιμοποιείται για την απόδοση της γεωμετρίας. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | Ορίζει το σύνολο shaders που χρησιμοποιείται για την απόδοση της σκηνής |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


Καθαρίστε τη λανθάνουσα μνήμη χειροκίνητα. Το Aspose.3D θα αποθηκεύει σε λανθάνουσα μνήμη ορισμένα αντικείμενα όπως υλικά/γεωμετρίες σε εσωτερικούς τύπους που είναι συμβατοί με τη γραμμή παραγωγής. Αυτό πρέπει να κληθεί χειροκίνητα όταν η σκηνή υποστεί σημαντικές αλλαγές.

### close() {#close--}
```
public void close()
```


Αποδεσμεύστε το [Renderer](../../com.aspose.threed/renderer) και όλους τους σχετικούς πόρους

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


Δημιουργεί ένα νέο [Renderer](../../com.aspose.threed/renderer) με προεπιλεγμένο προφίλ.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
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
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


Εκτελέστε μια μεταεπεξεργασία στον καθορισμένο στόχο απόδοσης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Καταλόγοι που αποθηκεύουν εξωτερικά περιουσιακά στοιχεία

**Returns:**
java.util.ArrayList<java.lang.String> - Κατάλογοι που αποθηκεύουν εξωτερικά περιουσιακά στοιχεία
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


Λαμβάνει αν ενεργοποιηθούν οι σκιές.

**Returns:**
boolean - whether to enable shadows.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


Λαμβάνει τον εφεδρικό αποδοχέα οντοτήτων όταν η οντότητα δεν έχει ορισμένο ειδικό αποδοχέα.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Λαμβάνει το frustum που χρησιμοποιείται για την παροχή του πίνακα προβολής.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Λαμβάνει το υλικό που χρησιμοποιείται για την παροχή πληροφοριών υλικού που χρησιμοποιούν οι shaders.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


Λαμβάνει το παράδειγμα [getNode](../../com.aspose.threed/renderer\#getNode) που χρησιμοποιείται για την παροχή του πίνακα μετασχηματισμού του κόσμου.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


Λαμβάνει έναν ενσωματωμένο μετα-επεξεργαστή που υποστηρίζεται από τον αποδοχέα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


Ενεργή αλυσίδα μετα-επεξεργασίας

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - Active post-processing chain
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


Λαμβάνει το προκαθορισμένο σύνολο shaders

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


Λαμβάνει το εργοστάσιο για τη δημιουργία αντικειμένων σχετικών με την απόδοση.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


Λαμβάνει το τρέχον στάδιο απόδοσης.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Καθορίστε τον προορισμό απόδοσης στον οποίο θα εκτελεστούν οι παρακάτω λειτουργίες απόδοσης.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


Λαμβάνει το παράδειγμα shader που χρησιμοποιείται για την απόδοση της γεωμετρίας.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


Λαμβάνει το σύνολο shaders που χρησιμοποιείται για την απόδοση της σκηνής

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


Πρόσβαση στις εσωτερικές μεταβλητές που χρησιμοποιούνται για την απόδοση

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


Καταχωρίστε τον αποδοχέα οντοτήτων για την καθορισμένη οντότητα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


Αποδώστε τον καθορισμένο προορισμό

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Ορίζει αν θα ενεργοποιηθούν οι σκιές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


Ορίζει τον εφεδρικό αποδοχέα οντοτήτων όταν η οντότητα δεν έχει ορισμένο ειδικό αποδοχέα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | Νέα τιμή |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Ορίζει το frustum που χρησιμοποιείται για την παροχή του πίνακα προβολής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Νέα τιμή |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Ορίζει το υλικό που χρησιμοποιείται για την παροχή πληροφοριών υλικού που χρησιμοποιούν οι shaders.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | Νέα τιμή |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Ορίζει το παράδειγμα [getNode](../../com.aspose.threed/renderer\#getNode) που χρησιμοποιείται για την παροχή του πίνακα μετασχηματισμού του κόσμου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Νέα τιμή |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


Ορίζει το προκαθορισμένο σύνολο shaders

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | Νέα τιμή |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


Ορίζει το παράδειγμα shader που χρησιμοποιείται για την απόδοση της γεωμετρίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Νέα τιμή |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


Ορίζει το σύνολο shaders που χρησιμοποιείται για την απόδοση της σκηνής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | Νέα τιμή |

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

