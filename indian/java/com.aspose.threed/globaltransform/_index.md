---
title: "GlobalTransform"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "ग्लोबल ट्रांसफ़ॉर्म समान है  लेकिन यह अपरिवर्तनीय है जबकि यह अंतिम मूल्यांकित ट्रांसफ़ॉर्मेशन का प्रतिनिधित्व करता है।"
type: docs
weight: 72
url: /hi/java/com.aspose.threed/globaltransform/
---

**Inheritance:**
java.lang.Object
```
public class GlobalTransform
```

ग्लोबल ट्रांसफ़ॉर्म समान है [Transform](../../com.aspose.threed/transform) के, लेकिन यह अपरिवर्तनीय है जबकि यह अंतिम मूल्यांकित ट्रांसफ़ॉर्मेशन का प्रतिनिधित्व करता है। ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करते समय दाएँ हाथ का कोऑर्डिनेट सिस्टम उपयोग किया जाता है **Example:** निम्नलिखित कोड दिखाता है कि नोड का ग्लोबल ट्रांसफ़ॉर्म कैसे पढ़ें

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     var global = boxNode.getGlobalTransform();
     System.out.print("The box's position in world coordinate is %s", global.getTranslation());
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | प्राप्त करता है ईयूलर कोणों में दर्शाई गई घूर्णन, डिग्री में मापी गई। |
| [getRotation()](#getRotation--) | प्राप्त करता है क्वाटरनियन में दर्शाई गई घूर्णन। |
| [getScale()](#getScale--) | प्राप्त करता है स्केल |
| [getTransformMatrix()](#getTransformMatrix--) | प्राप्त करता है ट्रांसफ़ॉर्म मैट्रिक्स। |
| [getTranslation()](#getTranslation--) | प्राप्त करता है ट्रांसलेशन |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEulerAngles() {#getEulerAngles--}
```
public Vector3 getEulerAngles()
```


प्राप्त करता है ईयूलर कोणों में दर्शाई गई घूर्णन, डिग्री में मापी गई।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation represented in Euler angles, measured in degree **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("EulerAngles = %s", tr.getEulerAngles());
```
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


प्राप्त करता है क्वाटरनियन में दर्शाई गई घूर्णन।

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("Rotation = %s", tr.getRotation());
```
### getScale() {#getScale--}
```
public Vector3 getScale()
```


प्राप्त करता है स्केल

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scale **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("Scale = %s", tr.getScale());
```
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


प्राप्त करता है ट्रांसफ़ॉर्म मैट्रिक्स।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("Matrix = %s", tr.getTransformMatrix());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


प्राप्त करता है ट्रांसलेशन

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("Translation = %s", tr.getTranslation());
```
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

