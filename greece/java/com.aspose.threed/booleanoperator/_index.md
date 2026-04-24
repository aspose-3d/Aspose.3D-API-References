---
title: BooleanOperator
second_title: Aspose.3D for Java API Reference
description: Ο τελεστής Boolean σας επιτρέπει να εφαρμόσετε λογική λειτουργία σε δύο αντικείμενα.
type: docs
weight: 23
url: /el/java/com.aspose.threed/booleanoperator/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class BooleanOperator extends Entity implements IMeshConvertible
```

Ο τελεστής Boolean επιτρέπει την εφαρμογή λογικής λειτουργίας σε δύο παραδείγματα του [IMeshConvertible](../../com.aspose.threed/imeshconvertible).
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [BooleanOperator()](#BooleanOperator--) | Κατασκευαστής του [BooleanOperator](../../com.aspose.threed/booleanoperator) |
| [BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second)](#BooleanOperator-com.aspose.threed.BooleanOperation-com.aspose.threed.A3DObject-com.aspose.threed.A3DObject-) | Δημιουργεί ένα νέο αντικείμενο του [BooleanOperator](../../com.aspose.threed/booleanoperator) με δύο τελεστές |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getFirst()](#getFirst--) | Ο πρώτος τελεστής του τελεστή Boolean |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getOperator()](#getOperator--) | Ο τελεστής Boolean που χρησιμοποιείται στη λειτουργία για τη δημιουργία του τελικού πλέγματος. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getSecond()](#getSecond--) | Ο δεύτερος τελεστής του τελεστή Boolean |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setFirst(BooleanOperand value)](#setFirst-com.aspose.threed.BooleanOperand-) | Ο πρώτος τελεστής του τελεστή Boolean |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setOperator(BooleanOperation value)](#setOperator-com.aspose.threed.BooleanOperation-) | Ο τελεστής Boolean που χρησιμοποιείται στη λειτουργία για τη δημιουργία του τελικού πλέγματος. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setSecond(BooleanOperand value)](#setSecond-com.aspose.threed.BooleanOperand-) | Ο δεύτερος τελεστής του τελεστή Boolean |
| [toMesh()](#toMesh--) | Εκτελέστε τη λογική λειτουργία σε δύο τελεστές |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BooleanOperator() {#BooleanOperator--}
```
public BooleanOperator()
```


Κατασκευαστής του [BooleanOperator](../../com.aspose.threed/booleanoperator)

### BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second) {#BooleanOperator-com.aspose.threed.BooleanOperation-com.aspose.threed.A3DObject-com.aspose.threed.A3DObject-}
```
public BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second)
```


Δημιουργεί ένα νέο αντικείμενο του [BooleanOperator](../../com.aspose.threed/booleanoperator) με δύο τελεστές

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operation | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Τύπος λογικής λειτουργίας |
| first | [A3DObject](../../com.aspose.threed/a3dobject) | Παράδειγμα του [IMeshConvertible](../../com.aspose.threed/imeshconvertible), του [HalfSpace](../../com.aspose.threed/halfspace) ή του [Node](../../com.aspose.threed/node) |
| second | [A3DObject](../../com.aspose.threed/a3dobject) | Παράδειγμα του [IMeshConvertible](../../com.aspose.threed/imeshconvertible), του [HalfSpace](../../com.aspose.threed/halfspace) ή του [Node](../../com.aspose.threed/node) |

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
### getFirst() {#getFirst--}
```
public BooleanOperand getFirst()
```


Ο πρώτος τελεστής του τελεστή Boolean

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - The first operand of the Boolean operator
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getOperator() {#getOperator--}
```
public BooleanOperation getOperator()
```


Ο τελεστής Boolean που χρησιμοποιείται στη λειτουργία για τη δημιουργία του τελικού πλέγματος.

**Returns:**
[BooleanOperation](../../com.aspose.threed/booleanoperation) - The Boolean operator used in the operation to create the result mesh.
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSecond() {#getSecond--}
```
public BooleanOperand getSecond()
```


Ο δεύτερος τελεστής του τελεστή Boolean

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - The second operand of the Boolean operator
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
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setFirst(BooleanOperand value) {#setFirst-com.aspose.threed.BooleanOperand-}
```
public void setFirst(BooleanOperand value)
```


Ο πρώτος τελεστής του τελεστή Boolean

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BooleanOperand](../../com.aspose.threed/booleanoperand) | Νέα τιμή |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setOperator(BooleanOperation value) {#setOperator-com.aspose.threed.BooleanOperation-}
```
public void setOperator(BooleanOperation value)
```


Ο τελεστής Boolean που χρησιμοποιείται στη λειτουργία για τη δημιουργία του τελικού πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Νέα τιμή |

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

### setSecond(BooleanOperand value) {#setSecond-com.aspose.threed.BooleanOperand-}
```
public void setSecond(BooleanOperand value)
```


Ο δεύτερος τελεστής του τελεστή Boolean

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BooleanOperand](../../com.aspose.threed/booleanoperand) | Νέα τιμή |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Εκτελέστε τη λογική λειτουργία σε δύο τελεστές

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

