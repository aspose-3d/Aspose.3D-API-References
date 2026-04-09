---
title: Transform
second_title: Aspose.3D for Java API Reference
description: Ένα μετασχηματισμό περιέχει πληροφορίες που επιτρέπουν πρόσβαση στη μετάφραση/κλιμάκωση/περιστροφή αντικειμένων ή στο μητρώο μετασχηματισμού με ελάχιστο κόστος. Αυτό χρησιμοποιείται από τον τοπικό μετασχηματισμό.
type: docs
weight: 190
url: /el/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

Ένα μετασχηματισμό περιέχει πληροφορίες που επιτρέπουν πρόσβαση στη μετάφραση/κλιμάκωση/περιστροφή αντικειμένων ή στο μητρώο μετασχηματισμού με ελάχιστο κόστος. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μετασχηματισμό του κόμβου:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Αποκτά την περιστροφή που εκφράζεται σε γωνίες Euler, μετρημένη σε μοίρες |
| [getGeometricRotation()](#getGeometricRotation--) | Λαμβάνει την γεωμετρική περιστροφή Euler (μετράται σε μοίρες). |
| [getGeometricScaling()](#getGeometricScaling--) | Λαμβάνει την γεωμετρική κλιμάκωση. |
| [getGeometricTranslation()](#getGeometricTranslation--) | Λαμβάνει τη γεωμετρική μετάφραση. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getPostRotation()](#getPostRotation--) | Λαμβάνει την μετα-περιστροφή που εκφράζεται σε μοίρες |
| [getPreRotation()](#getPreRotation--) | Λαμβάνει την προ-περιστροφή που εκφράζεται σε μοίρες |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getRotation()](#getRotation--) | Αποκτά την περιστροφή που εκφράζεται σε quaternion. |
| [getRotationOffset()](#getRotationOffset--) | Λαμβάνει τη μετατόπιση περιστροφής |
| [getRotationPivot()](#getRotationPivot--) | Gets the rotation pivot |
| [getScaling()](#getScaling--) | Gets the scaling |
| [getScalingOffset()](#getScalingOffset--) | Gets the scaling offset |
| [getScalingPivot()](#getScalingPivot--) | Gets the scaling pivot |
| [getTransformMatrix()](#getTransformMatrix--) | Gets the transform matrix. |
| [getTranslation()](#getTranslation--) | Αποκτά τη μετατόπιση |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | Sets the rotation represented in Euler angles, measured in degree |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | Ορίζει τις γωνίες Euler σε μοίρες του τρέχοντος μετασχηματισμού. |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | Sets the geometric Euler rotation(measured in degree). |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | Sets the geometric Euler rotation(measured in degree). |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | Sets the geometric scaling. |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | Sets the geometric scaling. |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | Sets the geometric translation. |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | Sets the geometric translation. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | Ορίζει την μετά-περιστροφή που αναπαρίσταται σε μοίρες |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | Sets the post-rotation represented in degree **Example:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | Ορίζει την προ-περιστροφή που αναπαρίσταται σε μοίρες |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | Sets the pre-rotation represented in degree **Example:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | Sets the rotation represented in quaternion. |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | Ορίζει την περιστροφή (ως συνιστώσες quaternion) του τρέχοντος μετασχηματισμού. |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | Sets the rotation offset |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | Sets the rotation pivot |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | Ορίζει την κλίμακα του τρέχοντος μετασχηματισμού. |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | Sets the scaling |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | Sets the scaling offset |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | Sets the scaling pivot |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | Sets the transform matrix. |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | Sets the translation |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | Ορίζει τη μετάφραση του τρέχοντος μετασχηματισμού. |
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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Βρίσκει την ιδιότητα. Μπορεί να είναι μια δυναμική ιδιότητα (Δημιουργήθηκε με CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Προσδιορίζεται με το όνομά της)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyName | java.lang.String | Όνομα ιδιότητας. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
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
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
```
### getGeometricRotation() {#getGeometricRotation--}
```
public Vector3 getGeometricRotation()
```


Gets the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


Λαμβάνει τη γεωμετρική κλιμάκωση. Ο γεωμετρικός μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους κόμβους-παιδιά αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τον γεωμετρικό μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric scaling. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
```
### getGeometricTranslation() {#getGeometricTranslation--}
```
public Vector3 getGeometricTranslation()
```


Λαμβάνει τη γεωμετρική μετάθεση. Ο γεωμετρικός μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους κόμβους-παιδιά αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τον γεωμετρικό μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric translation. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
```
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


Λαμβάνει την μετα-περιστροφή που εκφράζεται σε μοίρες

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the post-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
```
### getPreRotation() {#getPreRotation--}
```
public Vector3 getPreRotation()
```


Λαμβάνει την προ-περιστροφή που εκφράζεται σε μοίρες

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the pre-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
```
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Λαμβάνει τη συλλογή όλων των ιδιοτήτων.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Λάβετε την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |

**Returns:**
java.lang.Object - Η τιμή της ευρεθείσας ιδιότητας
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


Αποκτά την περιστροφή που εκφράζεται σε quaternion.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
```
### getRotationOffset() {#getRotationOffset--}
```
public Vector3 getRotationOffset()
```


Λαμβάνει τη μετατόπιση περιστροφής

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


Gets the rotation pivot

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


Gets the scaling

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling **Example:**

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
```
### getScalingOffset() {#getScalingOffset--}
```
public Vector3 getScalingOffset()
```


Gets the scaling offset

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


Gets the scaling pivot

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


Gets the transform matrix.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Remarks:** Assign on this will reset the [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) and [getRotation](../../com.aspose.threed/transform\#getRotation), the [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) and [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) will not be affected. **Example:**

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


Αποκτά τη μετατόπιση

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Αφαιρεί μια δυναμική ιδιότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


Sets the rotation represented in Euler angles, measured in degree

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή **Example:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


Ορίζει τις γωνίες Euler σε μοίρες του τρέχοντος μετασχηματισμού. **Παράδειγμα:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricRotation(Vector3 value) {#setGeometricRotation-com.aspose.threed.Vector3-}
```
public void setGeometricRotation(Vector3 value)
```


Ορίζει την γεωμετρική περιστροφή Euler (μετρημένη σε μοίρες). Ο γεωμετρικός μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους κόμβους-παιδιά αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τον γεωμετρικό μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


Ορίζει την γεωμετρική περιστροφή Euler (μετρημένη σε μοίρες). Ο γεωμετρικός μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους κόμβους-παιδιά αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τον γεωμετρικό μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν. **Παράδειγμα:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricScaling(Vector3 value) {#setGeometricScaling-com.aspose.threed.Vector3-}
```
public void setGeometricScaling(Vector3 value)
```


Ορίζει τη γεωμετρική κλιμάκωση. Ο γεωμετρικός μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους κόμβους-παιδιά αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τον γεωμετρικό μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή **Example:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


Ορίζει τη γεωμετρική κλιμάκωση. Ο γεωμετρικός μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους κόμβους-παιδιά αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τον γεωμετρικό μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν. **Παράδειγμα:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricTranslation(Vector3 value) {#setGeometricTranslation-com.aspose.threed.Vector3-}
```
public void setGeometricTranslation(Vector3 value)
```


Ορίζει τη γεωμετρική μετάθεση. Ο γεωμετρικός μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους κόμβους-παιδιά αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τον γεωμετρικό μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή **Example:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


Ορίζει τη γεωμετρική μετάθεση. Ο γεωμετρικός μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους κόμβους-παιδιά αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τον γεωμετρικό μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν. **Παράδειγμα:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


Ορίζει την μετά-περιστροφή που αναπαρίσταται σε μοίρες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή **Example:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


Sets the post-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setPreRotation(Vector3 value) {#setPreRotation-com.aspose.threed.Vector3-}
```
public void setPreRotation(Vector3 value)
```


Ορίζει την προ-περιστροφή που αναπαρίσταται σε μοίρες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή **Example:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


Sets the pre-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ορίζει την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |
| τιμή | java.lang.Object | Η τιμή της ιδιότητας |

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


Sets the rotation represented in quaternion.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | Νέα τιμή **Example:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


Ορίζει την περιστροφή (ως συνιστώσες τετραδίου) του τρέχοντος μετασχηματισμού. **Παράδειγμα:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rw | double |  |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setRotationOffset(Vector3 value) {#setRotationOffset-com.aspose.threed.Vector3-}
```
public void setRotationOffset(Vector3 value)
```


Sets the rotation offset

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


Sets the rotation pivot

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


Ορίζει την κλίμακα του τρέχοντος μετασχηματισμού. **Παράδειγμα:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setScaling(Vector3 value) {#setScaling-com.aspose.threed.Vector3-}
```
public void setScaling(Vector3 value)
```


Sets the scaling

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή **Example:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


Sets the scaling offset

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


Sets the scaling pivot

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


Sets the transform matrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | Νέα τιμή **Σχόλια:** Η ανάθεση σε αυτό θα επαναφέρει το [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) και [getRotation](../../com.aspose.threed/transform\#getRotation), ενώ τα [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) και [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) δεν θα επηρεαστούν. **Παράδειγμα:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


Sets the translation

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή **Example:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


Ορίζει τη μετάθεση του τρέχοντος μετασχηματισμού. **Παράδειγμα:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

