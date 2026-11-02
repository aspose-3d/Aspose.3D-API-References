---
title: "AxisSystem"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "Axis system कोऑर्डिनेट सिस्टम के अप वेक्टर और फ्रंट वेक्टर का संयोजन है।"
type: docs
weight: 18
url: /hi/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

एक्सिस सिस्टम कोऑर्डिनेट सिस्टम, अप वेक्टर और फ्रंट वेक्टर का संयोजन है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | एक नया axis system बनाता है |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | एक नया axis system बनाता है |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | एक नया axis system बनाता है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | बनाएँ [AxisSystem](../../com.aspose.threed/axissystem) को [AssetInfo](../../com.aspose.threed/assetinfo) से |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | इस axis system का कोऑर्डिनेट सिस्टम प्राप्त करता है। |
| [getFront()](#getFront--) | इस axis system का फ्रंट वेक्टर प्राप्त करता है |
| [getUp()](#getUp--) | इस axis system का अप वेक्टर प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | एक मैट्रिक्स बनाएँ जिसका उपयोग वर्तमान axis system से लक्ष्य axis system में रूपांतरण के लिए किया जाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


एक नया axis system बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | इस axis system में उपयोग किया गया कोऑर्डिनेट सिस्टम |
| up | [Axis](../../com.aspose.threed/axis) | axis system का अप वेक्टर |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


एक नया axis system बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | axis system का अप वेक्टर |
| front | [Axis](../../com.aspose.threed/axis) | axis system का फ्रंट वेक्टर |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


एक नया axis system बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | इस axis system में उपयोग किया गया कोऑर्डिनेट सिस्टम |
| up | [Axis](../../com.aspose.threed/axis) | axis system का अप वेक्टर |
| front | [Axis](../../com.aspose.threed/axis) | axis system का फ्रंट वेक्टर |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


बनाएँ [AxisSystem](../../com.aspose.threed/axissystem) को [AssetInfo](../../com.aspose.threed/assetinfo) से

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | किस एसेट इन्फो से कोऑर्डिनेट सिस्टम, अप और फ्रंट वेक्टर पढ़े जाएँ। |

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - Axis system containg coordinate system, up, front from given asset info
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


इस axis system का कोऑर्डिनेट सिस्टम प्राप्त करता है।

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


इस axis system का फ्रंट वेक्टर प्राप्त करता है

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


इस axis system का अप वेक्टर प्राप्त करता है।

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up vector of this axis system.
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
### transformTo(AxisSystem targetSystem) {#transformTo-com.aspose.threed.AxisSystem-}
```
public Matrix4 transformTo(AxisSystem targetSystem)
```


एक मैट्रिक्स बनाएँ जिसका उपयोग वर्तमान axis system से लक्ष्य axis system में रूपांतरण के लिए किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | लक्ष्य axis system |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - A new transformation matrix to do the axis conversion
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

