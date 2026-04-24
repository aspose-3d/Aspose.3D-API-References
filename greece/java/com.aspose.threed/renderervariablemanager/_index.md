---
title: RendererVariableManager
second_title: Aspose.3D for Java API Reference
description: Αυτή η κλάση διαχειρίζεται τις μεταβλητές που χρησιμοποιούνται στην απόδοση.
type: docs
weight: 154
url: /el/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Αυτή η κλάση διαχειρίζεται τις μεταβλητές που χρησιμοποιούνται στην απόδοση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Θέση της κάμερας στο παγκόσμιο σύστημα συντεταγμένων |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Προκατάληψη βάθους για τη σκιερή χαρτογράφηση, η προεπιλεγμένη τιμή είναι 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Μήτρα για μετασχηματισμό χώρου φωτός |
| [getMatrixProjection()](#getMatrixProjection--) | Μήτρα για μετασχηματισμό προβολής |
| [getMatrixView()](#getMatrixView--) | Μήτρα για μετασχηματισμό προβολής |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Μήτρα για μετασχηματισμό θέασης και προβολής. |
| [getMatrixWorld()](#getMatrixWorld--) | Μήτρα για μετασχηματισμό κόσμου |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Μήτρα για μετατροπή του κανονικού από το αντικείμενο στον παγκόσμιο χώρο. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Μήτρα για προβολή του κόσμου και μετασχηματισμό προβολής |
| [getShadowCaster()](#getShadowCaster--) | Θέση του δημιουργού σκιάς στο παγκόσμιο σύστημα συντεταγμένων |
| [getShadowmap()](#getShadowmap--) | Η υφή βάθους που χρησιμοποιείται για τη δημιουργία σκιών |
| [getViewportSize()](#getViewportSize--) | Μέγεθος του παραθύρου προβολής, μετρημένο σε εικονοστοιχεία |
| [getWorldAmbient()](#getWorldAmbient--) | Περιβάλλων χρώμα ορισμένο στο παράθυρο προβολής. |
| [getWorldTime()](#getWorldTime--) | Χρόνος σε δευτερόλεπτα |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Θέση της κάμερας στο παγκόσμιο σύστημα συντεταγμένων |
| [setDepthBias(float value)](#setDepthBias-float-) | Προκατάληψη βάθους για τη σκιερή χαρτογράφηση, η προεπιλεγμένη τιμή είναι 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Μήτρα για μετασχηματισμό χώρου φωτός |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Μήτρα για μετασχηματισμό προβολής |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Μήτρα για μετασχηματισμό προβολής |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Θέση του δημιουργού σκιάς στο παγκόσμιο σύστημα συντεταγμένων |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | Η υφή βάθους που χρησιμοποιείται για τη δημιουργία σκιών |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Μέγεθος του παραθύρου προβολής, μετρημένο σε εικονοστοιχεία |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Περιβάλλων χρώμα ορισμένο στο παράθυρο προβολής. |
| [setWorldTime(float value)](#setWorldTime-float-) | Χρόνος σε δευτερόλεπτα |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Θέση της κάμερας στο παγκόσμιο σύστημα συντεταγμένων

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


Προκατάληψη βάθους για τη σκιερή χαρτογράφηση, η προεπιλεγμένη τιμή είναι 0.001

**Returns:**
float - Μεροληψία βάθους για τη δημιουργία σκιών, η προεπιλεγμένη τιμή είναι 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Μήτρα για μετασχηματισμό χώρου φωτός

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Μήτρα για μετασχηματισμό προβολής

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Μήτρα για μετασχηματισμό προβολής

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Μήτρα για μετασχηματισμό θέασης και προβολής.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Μήτρα για μετασχηματισμό κόσμου

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Μήτρα για μετατροπή του κανονικού από το αντικείμενο στον παγκόσμιο χώρο.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Μήτρα για προβολή του κόσμου και μετασχηματισμό προβολής

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Θέση του δημιουργού σκιάς στο παγκόσμιο σύστημα συντεταγμένων

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


Η υφή βάθους που χρησιμοποιείται για τη δημιουργία σκιών

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Μέγεθος του παραθύρου προβολής, μετρημένο σε εικονοστοιχεία

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Περιβάλλων χρώμα ορισμένο στο παράθυρο προβολής.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Χρόνος σε δευτερόλεπτα

**Returns:**
float - Χρόνος σε δευτερόλεπτα
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


Θέση της κάμερας στο παγκόσμιο σύστημα συντεταγμένων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Νέα τιμή |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Προκατάληψη βάθους για τη σκιερή χαρτογράφηση, η προεπιλεγμένη τιμή είναι 0.001

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Μήτρα για μετασχηματισμό χώρου φωτός

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Νέα τιμή |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Μήτρα για μετασχηματισμό προβολής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Νέα τιμή |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Μήτρα για μετασχηματισμό προβολής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Νέα τιμή |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Θέση του δημιουργού σκιάς στο παγκόσμιο σύστημα συντεταγμένων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Νέα τιμή |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


Η υφή βάθους που χρησιμοποιείται για τη δημιουργία σκιών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Νέα τιμή |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Μέγεθος του παραθύρου προβολής, μετρημένο σε εικονοστοιχεία

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Νέα τιμή |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Περιβάλλων χρώμα ορισμένο στο παράθυρο προβολής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Νέα τιμή |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Χρόνος σε δευτερόλεπτα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

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

