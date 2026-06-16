---
title: "Viewport"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un  contient au moins un viewport pour le rendu de la scène."
type: docs
weight: 229
url: /fr/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

Un [IRenderTarget](../../com.aspose.threed/irendertarget) contient au moins un viewport pour le rendu de la scène.
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Obtient la zone du viewport dans la cible de rendu. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur d'arrière-plan du viewport. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Obtient la valeur de profondeur utilisée lors du nettoyage du viewport avec le bit de tampon de profondeur activé. |
| [getEnabled()](#getEnabled--) | Active ou désactive ce viewport. |
| [getFrustum()](#getFrustum--) | Obtient la caméra de ce [Viewport](../../com.aspose.threed/viewport) |
| [getRenderTarget()](#getRenderTarget--) | Obtient la cible de rendu qui a créé ce viewport. |
| [getZOrder()](#getZOrder--) | Obtient l'ordre Z du viewport. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Définit la zone du viewport dans la cible de rendu. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Définit la couleur d'arrière-plan du viewport. |
| [setDepthClear(float value)](#setDepthClear-float-) | Définit la valeur de profondeur utilisée lors du nettoyage du viewport avec le bit du tampon de profondeur activé. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Active ou désactive ce viewport. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Définit la caméra de ce [Viewport](../../com.aspose.threed/viewport) |
| [setZOrder(int value)](#setZOrder-int-) | Définit l'ordre Z du viewport. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clone() {#clone--}
```
public Viewport clone()
```




**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Obtient la zone du viewport dans la cible de rendu.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Obtient la couleur d'arrière-plan du viewport.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the background color of the viewport.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthClear() {#getDepthClear--}
```
public float getDepthClear()
```


Obtient la valeur de profondeur utilisée lors du nettoyage du viewport avec le bit de tampon de profondeur activé.

**Returns:**
float - la valeur de profondeur utilisée lors du nettoyage du viewport avec le bit du tampon de profondeur activé.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Active ou désactive ce viewport.

**Returns:**
boolean - Activer ou désactiver ce viewport.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Obtient la caméra de ce [Viewport](../../com.aspose.threed/viewport)

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Obtient la cible de rendu qui a créé ce viewport.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Obtient l'ordre Z du viewport.

**Returns:**
int - l'ordre Z du viewport.
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




### setArea(RelativeRectangle value) {#setArea-com.aspose.threed.RelativeRectangle-}
```
public void setArea(RelativeRectangle value)
```


Définit la zone du viewport dans la cible de rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Nouvelle valeur |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Définit la couleur d'arrière-plan du viewport.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Définit la valeur de profondeur utilisée lors du nettoyage du viewport avec le bit du tampon de profondeur activé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Active ou désactive ce viewport.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Définit la caméra de ce [Viewport](../../com.aspose.threed/viewport)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nouvelle valeur |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Définit l'ordre Z du viewport.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

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

