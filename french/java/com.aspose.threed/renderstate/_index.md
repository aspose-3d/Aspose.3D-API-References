---
title: "RenderState"
second_title: "Référence d'API Aspose.3D pour Java"
description: "État de rendu pour la construction du pipeline. Les modifications apportées à l'état de rendu n'affecteront pas les instances de pipeline créées."
type: docs
weight: 151
url: /fr/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

État de rendu pour la construction du pipeline Les modifications apportées à l'état de rendu n'affecteront pas les instances de pipeline créées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RenderState()](#RenderState--) | Constructeur de [RenderState](../../com.aspose.threed/renderstate) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) | Libérez le [RenderState](../../com.aspose.threed/renderstate) et libérez toutes les ressources internes. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Comparez l'état de rendu avec une autre instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à un objet spécifié. |
| [getBlend()](#getBlend--) | Activez ou désactivez le mélange de fragments. |
| [getBlendColor()](#getBlendColor--) | Obtient la couleur de mélange où elle est utilisée dans [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Activez ou désactivez la face de culling |
| [getCullFaceMode()](#getCullFaceMode--) | Obtient quelle face sera culled. |
| [getDepthFunction()](#getDepthFunction--) | Obtient la fonction de comparaison utilisée dans le test de profondeur |
| [getDepthMask()](#getDepthMask--) | Activez ou désactivez l'écriture de la profondeur. |
| [getDepthTest()](#getDepthTest--) | Activez ou désactivez le test de profondeur. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Obtient comment la couleur est mélangée. |
| [getFrontFace()](#getFrontFace--) | Obtient quel ordre correspond à la face avant. |
| [getPolygonMode()](#getPolygonMode--) | Obtient le mode de rendu du polygone. |
| [getScissorTest()](#getScissorTest--) | Activez ou désactivez le test de ciseaux |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Obtient comment la couleur est mélangée. |
| [getStencilBackFace()](#getStencilBackFace--) | Obtient l'état du stencil pour la face arrière. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Obtient l'état du stencil pour la face avant. |
| [getStencilMask()](#getStencilMask--) | Obtient le masque qui est ANDé avec la référence et la valeur de stencil stockée lorsque le test est terminé. |
| [getStencilReference()](#getStencilReference--) | Obtient la valeur de référence pour le test de stencil. |
| [getStencilTest()](#getStencilTest--) | Activez ou désactivez le test de stencil. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Activez ou désactivez le mélange de fragments. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Définit la couleur de mélange où elle est utilisée dans [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Activez ou désactivez la face de culling |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Définit quelle face sera culled. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Définit la fonction de comparaison utilisée dans le test de profondeur. |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Activez ou désactivez l'écriture de la profondeur. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Activez ou désactivez le test de profondeur. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Définit comment la couleur est mélangée. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Définit quel ordre correspond à la face avant. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Définit le mode de rendu du polygone. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Activez ou désactivez le test de ciseaux |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Définit comment la couleur est mélangée. |
| [setStencilMask(int value)](#setStencilMask-int-) | Définit le masque qui est combiné en AND avec la valeur de référence et la valeur du pochoir stockée lorsque le test est terminé. |
| [setStencilReference(int value)](#setStencilReference-int-) | Définit la valeur de référence pour le test de pochoir. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Activez ou désactivez le test de stencil. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Constructeur de [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Libérez le [RenderState](../../com.aspose.threed/renderstate) et libérez toutes les ressources internes.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Comparez l'état de rendu avec une autre instance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Un autre état de rendu à comparer |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à un objet spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Activez ou désactivez le mélange de fragments.

**Returns:**
booléen - Activer ou désactiver le mélange des fragments.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Obtient la couleur de mélange où elle est utilisée dans [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


Activez ou désactivez la face de culling

**Returns:**
booléen - Activer ou désactiver la suppression des faces
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Obtient quelle face sera culled.

**Returns:**
int - quelle face sera supprimée.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Obtient la fonction de comparaison utilisée dans le test de profondeur

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Activez ou désactivez l'écriture de la profondeur.

**Returns:**
booléen - Activer ou désactiver l'écriture de la profondeur.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Activez ou désactivez le test de profondeur.

**Returns:**
booléen - Activer ou désactiver le test de profondeur.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Obtient comment la couleur est mélangée.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Obtient quel ordre correspond à la face avant.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Obtient le mode de rendu du polygone.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Activez ou désactivez le test de ciseaux

**Returns:**
booléen - Activer ou désactiver le test de ciseaux
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Obtient comment la couleur est mélangée.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Obtient l'état du stencil pour la face arrière.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Obtient l'état du stencil pour la face avant.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Obtient le masque qui est ANDé avec la référence et la valeur de stencil stockée lorsque le test est terminé.

**Returns:**
int - le masque qui est combiné en AND avec la valeur de référence et la valeur du pochoir stockée lorsque le test est terminé.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Obtient la valeur de référence pour le test de stencil.

**Returns:**
int - la valeur de référence pour le test de pochoir.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Activez ou désactivez le test de stencil.

**Returns:**
booléen - Activer ou désactiver le test de pochoir.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


Activez ou désactivez le mélange de fragments.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Définit la couleur de mélange où elle est utilisée dans [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Nouvelle valeur |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Activez ou désactivez la face de culling

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Définit quelle face sera culled.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Définit la fonction de comparaison utilisée dans le test de profondeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nouvelle valeur |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Activez ou désactivez l'écriture de la profondeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Activez ou désactivez le test de profondeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Définit comment la couleur est mélangée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nouvelle valeur |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Définit quel ordre correspond à la face avant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Nouvelle valeur |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Définit le mode de rendu du polygone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Nouvelle valeur |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Activez ou désactivez le test de ciseaux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Définit comment la couleur est mélangée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nouvelle valeur |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Définit le masque qui est combiné en AND avec la valeur de référence et la valeur du pochoir stockée lorsque le test est terminé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Définit la valeur de référence pour le test de pochoir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Activez ou désactivez le test de stencil.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

