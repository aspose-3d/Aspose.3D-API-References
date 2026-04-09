---
title: GlobalTransform
second_title: Aspose.3D for Java API Reference
description: ग्लोबल ट्रांसफ़ॉर्म समान है लेकिन यह अपरिवर्तनीय है जबकि यह अंतिम मूल्यांकित ट्रांसफ़ॉर्मेशन को दर्शाता है।
type: docs
weight: 72
url: /hi/java/com.aspose.threed/globaltransform/
---

**Inheritance:**
java.lang.Object
```
public class GlobalTransform
```

ग्लोबल ट्रांसफ़ॉर्म समान है [Transform](../../com.aspose.threed/transform) के साथ लेकिन यह अपरिवर्तनीय है जबकि यह अंतिम मूल्यांकित ट्रांसफ़ॉर्मेशन को दर्शाता है। ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करते समय राइट-हैंड कोऑर्डिनेट सिस्टम का उपयोग किया जाता है **Example:** निम्नलिखित कोड दिखाता है कि नोड का ग्लोबल ट्रांसफ़ॉर्म कैसे पढ़ा जाए

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     var global = boxNode.getGlobalTransform();
     System.out.print("The box's position in world coordinate is %s", global.getTranslation());
```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Euler कोणों में प्रदर्शित रोटेशन प्राप्त करता है, डिग्री में मापा गया |
| [getRotation()](#getRotation--) | क्वाटरनियन में प्रदर्शित रोटेशन प्राप्त करता है। |
| [getScale()](#getScale--) | स्केल प्राप्त करता है |
| [getTransformMatrix()](#getTransformMatrix--) | ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है। |
| [getTranslation()](#getTranslation--) | ट्रांसलेशन प्राप्त करता है |
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
| Parameter | Type | विवरण |
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


Euler कोणों में प्रदर्शित रोटेशन प्राप्त करता है, डिग्री में मापा गया

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


क्वाटरनियन में प्रदर्शित रोटेशन प्राप्त करता है।

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


स्केल प्राप्त करता है

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


ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है।

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


ट्रांसलेशन प्राप्त करता है

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

