---
title: LinearExtrusion
second_title: Aspose.3D for Java API Reference
description: Η γραμμική εξώθηση παίρνει ένα 2D σχήμα ως είσοδο και επεκτείνει το σχήμα στην τρίτη διάσταση.
type: docs
weight: 96
url: /el/java/com.aspose.threed/linearextrusion/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class LinearExtrusion extends Entity implements IMeshConvertible
```

Η γραμμική εξώθηση λαμβάνει ένα 2D σχήμα ως είσοδο και επεκτείνει το σχήμα στην τρίτη διάσταση. **Example:** Ο παρακάτω κώδικας δείχνει πώς να χρησιμοποιήσετε το LinearExtrusion για να εξώθησετε ένα σχήμα σε ένα στερεό μοντέλο.

```
//Create a new 3D scene
 		Scene scene = new Scene();
 
 		// Initialize the base profile to be extruded
 		var profile = new RectangleShape();
 		profile.setRoundingRadius(0.3);
 
 		// Create left node
 		var left = scene.getRootNode().createChildNode();
 		left.createChildNode(new Box(0.01, 3, 3));
 
 		// Create right node
 		var right = scene.getRootNode().createChildNode();
 		right.createChildNode(new Box(0.01, 3, 3));
 		right.getTransform().setTranslation(new Vector3(5, 0, 0));
 
 		//Perform linear extrusion on left node using center and slices property
 		var l = new LinearExtrusion(profile, 10);
 		l.setCenter(false);
 		l.setSlices(3);
 		l.setTwist(20);
 		left.createChildNode(l);
 
 		// Perform linear extrusion on left node using center and slices property
 		var r = new LinearExtrusion(profile, 10);
 		r.setCenter(true);
 		r.setSlices(3);
 		r.setTwist(90);
 		right.createChildNode(r);
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [LinearExtrusion()](#LinearExtrusion--) | Κατασκευαστής του στιγμιότυπου [LinearExtrusion](../../com.aspose.threed/linearextrusion). |
| [LinearExtrusion(Profile shape, double height)](#LinearExtrusion-com.aspose.threed.Profile-double-) | Κατασκευαστής του στιγμιότυπου [LinearExtrusion](../../com.aspose.threed/linearextrusion). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getCenter()](#getCenter--) | Εάν αυτή η τιμή είναι ψευδής, το εύρος Z της γραμμικής εξώθησης είναι από 0 έως το ύψος, διαφορετικά το εύρος είναι από -height/2 έως height/2. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Η κατεύθυνση της εξώθησης, η προεπιλεγμένη τιμή είναι (0, 0, 1) |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getHeight()](#getHeight--) | Το ύψος της εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.0 |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getShape()](#getShape--) | Το βασικό σχήμα που θα εξωθηθεί. |
| [getSlices()](#getSlices--) | Οι φέτες της στριμωγμένης εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1. |
| [getTwist()](#getTwist--) | Ο αριθμός των μοιρών μέσω των οποίων το σχήμα εξωθείται. |
| [getTwistOffset()](#getTwistOffset--) | Η μετατόπιση που χρησιμοποιείται στην στρέψη, η προεπιλεγμένη τιμή είναι (0, 0, 0). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setCenter(boolean value)](#setCenter-boolean-) | Εάν αυτή η τιμή είναι ψευδής, το εύρος Z της γραμμικής εξώθησης είναι από 0 έως το ύψος, διαφορετικά το εύρος είναι από -height/2 έως height/2. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Η κατεύθυνση της εξώθησης, η προεπιλεγμένη τιμή είναι (0, 0, 1) |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setHeight(double value)](#setHeight-double-) | Το ύψος της εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.0 |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | Το βασικό σχήμα που θα εξωθηθεί. |
| [setSlices(int value)](#setSlices-int-) | Οι φέτες της στριμωγμένης εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1. |
| [setTwist(double value)](#setTwist-double-) | Ο αριθμός των μοιρών μέσω των οποίων το σχήμα εξωθείται. |
| [setTwistOffset(Vector3 value)](#setTwistOffset-com.aspose.threed.Vector3-) | Η μετατόπιση που χρησιμοποιείται στην στρέψη, η προεπιλεγμένη τιμή είναι (0, 0, 0). |
| [toMesh()](#toMesh--) | Μετατρέψτε την εξώθηση σε πλέγμα. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearExtrusion() {#LinearExtrusion--}
```
public LinearExtrusion()
```


Κατασκευαστής του στιγμιότυπου [LinearExtrusion](../../com.aspose.threed/linearextrusion).

### LinearExtrusion(Profile shape, double height) {#LinearExtrusion-com.aspose.threed.Profile-double-}
```
public LinearExtrusion(Profile shape, double height)
```


Κατασκευαστής του στιγμιότυπου [LinearExtrusion](../../com.aspose.threed/linearextrusion).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Profile](../../com.aspose.threed/profile) |  |
| height | double |  |

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
### getCenter() {#getCenter--}
```
public boolean getCenter()
```


Εάν αυτή η τιμή είναι ψευδής, το εύρος Z της γραμμικής εξώθησης είναι από 0 έως το ύψος, διαφορετικά το εύρος είναι από -height/2 έως height/2.

**Returns:**
boolean - Εάν αυτή η τιμή είναι ψευδής, το εύρος Z της γραμμικής εξώθησης είναι από 0 έως το ύψος, διαφορετικά το εύρος είναι από -height/2 έως height/2.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Η κατεύθυνση της εξώθησης, η προεπιλεγμένη τιμή είναι (0, 0, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The direction of extrusion, default value is (0, 0, 1)
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Το ύψος της εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.0

**Returns:**
double - Το ύψος της εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.0
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShape() {#getShape--}
```
public Profile getShape()
```


Το βασικό σχήμα που θα εξωθηθεί.

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base shape to be extruded.
### getSlices() {#getSlices--}
```
public int getSlices()
```


Οι φέτες της στριμωγμένης εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.

**Returns:**
int - Οι φέτες της στριμωγμένης εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.
### getTwist() {#getTwist--}
```
public double getTwist()
```


Ο αριθμός των μοιρών μέσω των οποίων το σχήμα εξωθείται.

**Returns:**
double - Ο αριθμός των μοιρών μέσω των οποίων το σχήμα εξωθείται.
### getTwistOffset() {#getTwistOffset--}
```
public Vector3 getTwistOffset()
```


Η μετατόπιση που χρησιμοποιείται στην στρέψη, η προεπιλεγμένη τιμή είναι (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The offset that used in twisting, default value is (0, 0, 0).
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
### setCenter(boolean value) {#setCenter-boolean-}
```
public void setCenter(boolean value)
```


Εάν αυτή η τιμή είναι ψευδής, το εύρος Z της γραμμικής εξώθησης είναι από 0 έως το ύψος, διαφορετικά το εύρος είναι από -height/2 έως height/2.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Η κατεύθυνση της εξώθησης, η προεπιλεγμένη τιμή είναι (0, 0, 1)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Το ύψος της εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


Το βασικό σχήμα που θα εξωθηθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | Νέα τιμή |

### setSlices(int value) {#setSlices-int-}
```
public void setSlices(int value)
```


Οι φέτες της στριμωγμένης εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setTwist(double value) {#setTwist-double-}
```
public void setTwist(double value)
```


Ο αριθμός των μοιρών μέσω των οποίων το σχήμα εξωθείται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setTwistOffset(Vector3 value) {#setTwistOffset-com.aspose.threed.Vector3-}
```
public void setTwistOffset(Vector3 value)
```


Η μετατόπιση που χρησιμοποιείται στην στρέψη, η προεπιλεγμένη τιμή είναι (0, 0, 0).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Μετατρέψτε την εξώθηση σε πλέγμα.

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

