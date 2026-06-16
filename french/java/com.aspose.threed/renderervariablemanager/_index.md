---
title: "RendererVariableManager"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Cette classe gère les variables utilisées dans le rendu"
type: docs
weight: 154
url: /fr/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Cette classe gère les variables utilisées dans le rendu
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Position de la caméra dans le système de coordonnées du monde |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Biais de profondeur pour le rendu d'ombres, la valeur par défaut est 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Matrice pour la transformation de l'espace lumière |
| [getMatrixProjection()](#getMatrixProjection--) | Matrice pour la transformation de projection |
| [getMatrixView()](#getMatrixView--) | Matrice pour la transformation de vue |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Matrice pour la transformation de vue et de projection. |
| [getMatrixWorld()](#getMatrixWorld--) | Matrice pour la transformation du monde |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Matrice pour convertir la normale de l'objet à l'espace monde. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Matrice pour la vue du monde et la transformation de projection |
| [getShadowCaster()](#getShadowCaster--) | Position du lanceur d'ombre dans le système de coordonnées du monde |
| [getShadowmap()](#getShadowmap--) | La texture de profondeur utilisée pour le rendu d'ombres |
| [getViewportSize()](#getViewportSize--) | Taille du viewport, mesurée en pixels |
| [getWorldAmbient()](#getWorldAmbient--) | Couleur ambiante définie dans le viewport. |
| [getWorldTime()](#getWorldTime--) | Temps en secondes |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Position de la caméra dans le système de coordonnées du monde |
| [setDepthBias(float value)](#setDepthBias-float-) | Biais de profondeur pour le rendu d'ombres, la valeur par défaut est 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Matrice pour la transformation de l'espace lumière |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Matrice pour la transformation de projection |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Matrice pour la transformation de vue |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Position du lanceur d'ombre dans le système de coordonnées du monde |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | La texture de profondeur utilisée pour le rendu d'ombres |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Taille du viewport, mesurée en pixels |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Couleur ambiante définie dans le viewport. |
| [setWorldTime(float value)](#setWorldTime-float-) | Temps en secondes |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Position de la caméra dans le système de coordonnées du monde

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Camera's position in world coordinate system
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthBias() {#getDepthBias--}
```
public float getDepthBias()
```


Biais de profondeur pour le rendu d'ombres, la valeur par défaut est 0.001

**Returns:**
float - Biais de profondeur pour le rendu d'ombres, la valeur par défaut est 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Matrice pour la transformation de l'espace lumière

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Matrice pour la transformation de projection

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Matrice pour la transformation de vue

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Matrice pour la transformation de vue et de projection.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Matrice pour la transformation du monde

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Matrice pour convertir la normale de l'objet à l'espace monde.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Matrice pour la vue du monde et la transformation de projection

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Position du lanceur d'ombre dans le système de coordonnées du monde

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


La texture de profondeur utilisée pour le rendu d'ombres

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Taille du viewport, mesurée en pixels

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Couleur ambiante définie dans le viewport.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Temps en secondes

**Returns:**
float - Temps en secondes
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




### setCameraPosition(FVector3 value) {#setCameraPosition-com.aspose.threed.FVector3-}
```
public void setCameraPosition(FVector3 value)
```


Position de la caméra dans le système de coordonnées du monde

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nouvelle valeur |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Biais de profondeur pour le rendu d'ombres, la valeur par défaut est 0.001

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Matrice pour la transformation de l'espace lumière

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nouvelle valeur |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Matrice pour la transformation de projection

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nouvelle valeur |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Matrice pour la transformation de vue

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nouvelle valeur |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Position du lanceur d'ombre dans le système de coordonnées du monde

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nouvelle valeur |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


La texture de profondeur utilisée pour le rendu d'ombres

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Nouvelle valeur |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Taille du viewport, mesurée en pixels

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Nouvelle valeur |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Couleur ambiante définie dans le viewport.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nouvelle valeur |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Temps en secondes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

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

