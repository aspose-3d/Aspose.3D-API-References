---
title: "GlobalTransform"
second_title: "Aspose.3D for Java API Reference"
description: "Η καθολική μετατροπή είναι παρόμοια με  αλλά είναι αμετάβλητη ενώ αντιπροσωπεύει τον τελικό αξιολογημένο μετασχηματισμό."
type: docs
weight: 72
url: /el/java/com.aspose.threed/globaltransform/
---

**Inheritance:**
java.lang.Object
```
public class GlobalTransform
```

Η καθολική μετατροπή είναι παρόμοια με [Transform](../../com.aspose.threed/transform) αλλά είναι αμετάβλητη ενώ αντιπροσωπεύει τον τελικό αξιολογημένο μετασχηματισμό. Το δεξιόχτυπο σύστημα συντεταγμένων χρησιμοποιείται κατά την αξιολόγηση της καθολικής μετατροπής **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να διαβάσετε τη καθολική μετατροπή του κόμβου

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     var global = boxNode.getGlobalTransform();
     System.out.print("The box's position in world coordinate is %s", global.getTranslation());
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Αποκτά την περιστροφή που εκφράζεται σε γωνίες Euler, μετρημένη σε μοίρες |
| [getRotation()](#getRotation--) | Αποκτά την περιστροφή που εκφράζεται σε quaternion. |
| [getScale()](#getScale--) | Αποκτά την κλίμακα |
| [getTransformMatrix()](#getTransformMatrix--) | Λαμβάνει τον πίνακα μετασχηματισμού. |
| [getTranslation()](#getTranslation--) | Αποκτά τη μετατόπιση |
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
| Παράμετρος | Τύπος | Περιγραφή |
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


Αποκτά την περιστροφή που εκφράζεται σε γωνίες Euler, μετρημένη σε μοίρες

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


Αποκτά την περιστροφή που εκφράζεται σε quaternion.

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


Αποκτά την κλίμακα

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


Λαμβάνει τον πίνακα μετασχηματισμού.

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


Αποκτά τη μετατόπιση

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

