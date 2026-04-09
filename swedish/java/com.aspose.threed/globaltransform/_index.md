---
title: GlobalTransform
second_title: Aspose.3D for Java API-referens
description: Global transform är liknande  men den är oföränderlig medan den representerar den slutgiltiga utvärderade transformationen
type: docs
weight: 72
url: /sv/java/com.aspose.threed/globaltransform/
---

**Inheritance:**
java.lang.Object
```
public class GlobalTransform
```

Global transform är liknande [Transform](../../com.aspose.threed/transform) men den är oföränderlig medan den representerar den slutgiltiga utvärderade transformationen. Högerhandskoordinatsystem används vid utvärdering av global transform **Example:** Följande kod visar hur man läser nodens globala transform

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     var global = boxNode.getGlobalTransform();
     System.out.print("The box's position in world coordinate is %s", global.getTranslation());
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Hämtar rotationen representerad i Euler-vinklar, mätt i grader |
| [getRotation()](#getRotation--) | Hämtar rotationen representerad i en kvaternion. |
| [getScale()](#getScale--) | Hämtar skalan |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar transformmatrisen. |
| [getTranslation()](#getTranslation--) | Hämtar translationen |
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
| Parameter | Typ | Beskrivning |
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


Hämtar rotationen representerad i Euler-vinklar, mätt i grader

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


Hämtar rotationen representerad i en kvaternion.

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


Hämtar skalan

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


Hämtar transformmatrisen.

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


Hämtar translationen

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

