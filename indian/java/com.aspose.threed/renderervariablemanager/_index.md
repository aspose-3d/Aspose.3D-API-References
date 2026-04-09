---
title: RendererVariableManager
second_title: Aspose.3D for Java API Reference
description: यह क्लास रेंडरिंग में उपयोग होने वाले वेरिएबल्स को मैनेज करती है।
type: docs
weight: 154
url: /hi/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

यह क्लास रेंडरिंग में उपयोग होने वाले वेरिएबल्स को मैनेज करती है।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | वर्ल्ड कोऑर्डिनेट सिस्टम में कैमरा की स्थिति |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | शैडो मैपिंग के लिए डेप्थ बायस, डिफ़ॉल्ट मान 0.001 है। |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | लाइट स्पेस ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स |
| [getMatrixProjection()](#getMatrixProjection--) | प्रोजेक्शन ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स |
| [getMatrixView()](#getMatrixView--) | व्यू ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | व्यू और प्रोजेक्शन ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स। |
| [getMatrixWorld()](#getMatrixWorld--) | वर्ल्ड ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | ऑब्जेक्ट से वर्ल्ड स्पेस में नॉर्मल को बदलने के लिए मैट्रिक्स। |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | विश्व दृश्य और प्रोजेक्शन ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स |
| [getShadowCaster()](#getShadowCaster--) | विश्व निर्देशांक प्रणाली में शैडो कास्टर की स्थिति |
| [getShadowmap()](#getShadowmap--) | शैडो मैपिंग के लिए उपयोग की गई डेप्थ टेक्सचर |
| [getViewportSize()](#getViewportSize--) | व्यूपोर्ट का आकार, पिक्सेल में मापा गया |
| [getWorldAmbient()](#getWorldAmbient--) | व्यूपोर्ट में परिभाषित एंबिएंट रंग। |
| [getWorldTime()](#getWorldTime--) | सेकंड में समय |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | वर्ल्ड कोऑर्डिनेट सिस्टम में कैमरा की स्थिति |
| [setDepthBias(float value)](#setDepthBias-float-) | शैडो मैपिंग के लिए डेप्थ बायस, डिफ़ॉल्ट मान 0.001 है। |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | लाइट स्पेस ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | प्रोजेक्शन ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | व्यू ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | विश्व निर्देशांक प्रणाली में शैडो कास्टर की स्थिति |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | शैडो मैपिंग के लिए उपयोग की गई डेप्थ टेक्सचर |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | व्यूपोर्ट का आकार, पिक्सेल में मापा गया |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | व्यूपोर्ट में परिभाषित एंबिएंट रंग। |
| [setWorldTime(float value)](#setWorldTime-float-) | सेकंड में समय |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


वर्ल्ड कोऑर्डिनेट सिस्टम में कैमरा की स्थिति

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


शैडो मैपिंग के लिए डेप्थ बायस, डिफ़ॉल्ट मान 0.001 है।

**Returns:**
float - शैडो मैपिंग के लिए डेप्थ बायस, डिफ़ॉल्ट मान 0.001 है
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


लाइट स्पेस ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


प्रोजेक्शन ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


व्यू ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


व्यू और प्रोजेक्शन ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स।

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


वर्ल्ड ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


ऑब्जेक्ट से वर्ल्ड स्पेस में नॉर्मल को बदलने के लिए मैट्रिक्स।

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


विश्व दृश्य और प्रोजेक्शन ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


विश्व निर्देशांक प्रणाली में शैडो कास्टर की स्थिति

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


शैडो मैपिंग के लिए उपयोग की गई डेप्थ टेक्सचर

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


व्यूपोर्ट का आकार, पिक्सेल में मापा गया

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


व्यूपोर्ट में परिभाषित एंबिएंट रंग।

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


सेकंड में समय

**Returns:**
float - सेकंड में समय
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


वर्ल्ड कोऑर्डिनेट सिस्टम में कैमरा की स्थिति

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | नया मान |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


शैडो मैपिंग के लिए डेप्थ बायस, डिफ़ॉल्ट मान 0.001 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


लाइट स्पेस ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | नया मान |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


प्रोजेक्शन ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | नया मान |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


व्यू ट्रांसफ़ॉर्मेशन के लिए मैट्रिक्स

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | नया मान |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


विश्व निर्देशांक प्रणाली में शैडो कास्टर की स्थिति

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | नया मान |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


शैडो मैपिंग के लिए उपयोग की गई डेप्थ टेक्सचर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | नया मान |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


व्यूपोर्ट का आकार, पिक्सेल में मापा गया

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | नया मान |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


व्यूपोर्ट में परिभाषित एंबिएंट रंग।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | नया मान |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


सेकंड में समय

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

