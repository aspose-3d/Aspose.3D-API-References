---
title: Plane
second_title: Aspose.3D for Java API Reference
description: Παραμετρικό επίπεδο.
type: docs
weight: 128
url: /el/java/com.aspose.threed/plane/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Plane extends Primitive
```

Παραμετρικό επίπεδο.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Plane()](#Plane--) | Αρχικοποιεί μια νέα παρουσία του [Plane](../../com.aspose.threed/plane) με προεπιλεγμένο μέγεθος 1x1. |
| [Plane(double length, double width)](#Plane-double-double-) | Αρχικοποιεί μια νέα παρουσία του [Plane](../../com.aspose.threed/plane). |
| [Plane(String name, double length, double width, int lengthSegments, int widthSegments)](#Plane-java.lang.String-double-double-int-int-) | Αρχικοποιεί μια νέα παρουσία του [Plane](../../com.aspose.threed/plane). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getCastShadows()](#getCastShadows--) | Επιστρέφει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του επιπέδου. |
| [getLengthSegments()](#getLengthSegments--) | Λαμβάνει τα τμήματα μήκους. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getReceiveShadows()](#getReceiveShadows--) | Επιστρέφει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getUp()](#getUp--) | Λαμβάνει το διάνυσμα άνω του επιπέδου, η προεπιλεγμένη τιμή είναι (0, 1, 0), αυτό επηρεάζει τη δημιουργία του επιπέδου |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του επιπέδου. |
| [getWidthSegments()](#getWidthSegments--) | Λαμβάνει τα τμήματα πλάτους. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setLength(double value)](#setLength-double-) | Ορίζει το μήκος του επιπέδου. |
| [setLengthSegments(int value)](#setLengthSegments-int-) | Ορίζει τα τμήματα μήκους. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Ορίζει το διάνυσμα άνω του επιπέδου, η προεπιλεγμένη τιμή είναι (0, 1, 0), αυτό επηρεάζει τη δημιουργία του επιπέδου |
| [setWidth(double value)](#setWidth-double-) | Ορίζει το πλάτος του επιπέδου. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | Ορίζει τα τμήματα πλάτους. |
| [toMesh()](#toMesh--) | Μετατρέπει το τρέχον αντικείμενο σε πλέγμα |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Plane() {#Plane--}
```
public Plane()
```


Αρχικοποιεί μια νέα παρουσία του [Plane](../../com.aspose.threed/plane) με προεπιλεγμένο μέγεθος 1x1.

### Plane(double length, double width) {#Plane-double-double-}
```
public Plane(double length, double width)
```


Αρχικοποιεί μια νέα παρουσία του [Plane](../../com.aspose.threed/plane).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήκος | double | Μήκος του επιπέδου. |
| width | double | Πλάτος του επιπέδου. |

### Plane(String name, double length, double width, int lengthSegments, int widthSegments) {#Plane-java.lang.String-double-double-int-int-}
```
public Plane(String name, double length, double width, int lengthSegments, int widthSegments)
```


Αρχικοποιεί μια νέα παρουσία του [Plane](../../com.aspose.threed/plane).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |
| μήκος | double | Μήκος του επιπέδου. |
| width | double | Πλάτος του επιπέδου. |
| lengthSegments | int | Τμήματα μήκους. |
| widthSegments | int | Τμήματα πλάτους. |

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
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Επιστρέφει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά

**Returns:**
boolean - εάν αυτή η γεωμετρία μπορεί να ρίξει σκιά
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.

**Returns:**
boolean - αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.
### getLength() {#getLength--}
```
public double getLength()
```


Λαμβάνει το μήκος του επιπέδου.

**Returns:**
double - το μήκος του επιπέδου.
### getLengthSegments() {#getLengthSegments--}
```
public int getLengthSegments()
```


Λαμβάνει τα τμήματα μήκους.

**Returns:**
int - τα τμήματα μήκους.
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - όλοι οι γονικοί κόμβοι, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιτύπων
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
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Επιστρέφει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά.

**Returns:**
boolean - εάν αυτή η γεωμετρία μπορεί να λάβει σκιά.
### getScene() {#getScene--}
```
public Scene getScene()
```


Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Λαμβάνει το διάνυσμα άνω του επιπέδου, η προεπιλεγμένη τιμή είναι (0, 1, 0), αυτό επηρεάζει τη δημιουργία του επιπέδου

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up vector of the plane, default value is (0, 1, 0), this affects the generation of the plane
### getWidth() {#getWidth--}
```
public double getWidth()
```


Λαμβάνει το πλάτος του επιπέδου.

**Returns:**
double - το πλάτος του επιπέδου.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


Λαμβάνει τα τμήματα πλάτους.

**Returns:**
int - τα τμήματα πλάτους.
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setLength(double value) {#setLength-double-}
```
public void setLength(double value)
```


Ορίζει το μήκος του επιπέδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setLengthSegments(int value) {#setLengthSegments-int-}
```
public void setLengthSegments(int value)
```


Ορίζει τα τμήματα μήκους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Νέα τιμή |

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Ορίζει το διάνυσμα άνω του επιπέδου, η προεπιλεγμένη τιμή είναι (0, 1, 0), αυτό επηρεάζει τη δημιουργία του επιπέδου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Ορίζει το πλάτος του επιπέδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


Ορίζει τα τμήματα πλάτους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Μετατρέπει το τρέχον αντικείμενο σε πλέγμα

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

