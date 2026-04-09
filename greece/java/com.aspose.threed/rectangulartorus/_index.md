---
title: RectangularTorus
second_title: Aspose.3D for Java API Reference
description: Παραμετροποιημένος ορθογώνιος τόρος.
type: docs
weight: 146
url: /el/java/com.aspose.threed/rectangulartorus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class RectangularTorus extends Primitive
```

Παραμετροποιημένος ορθογώνιος τόρος.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [RectangularTorus()](#RectangularTorus--) | Κατασκευαστής του [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
| [RectangularTorus(String name)](#RectangularTorus-java.lang.String-) | Κατασκευαστής του [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getAngleStart()](#getAngleStart--) | Η αρχική γωνία του τόξου, μετρημένη σε ακτίνια. |
| [getArc()](#getArc--) | Η συνολική γωνία του τόξου, μετρημένη σε ακτίνια. |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getCastShadows()](#getCastShadows--) | Επιστρέφει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getHeight()](#getHeight--) | Το ύψος του ορθογώνιου δακτυλίου. |
| [getInnerRadius()](#getInnerRadius--) | Η εσωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 17 |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getOuterRadius()](#getOuterRadius--) | Η εξωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20 |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getRadialSegments()](#getRadialSegments--) | Τα ακτινικά τμήματα, η προεπιλεγμένη τιμή είναι 10 |
| [getReceiveShadows()](#getReceiveShadows--) | Επιστρέφει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setAngleStart(double value)](#setAngleStart-double-) | Η αρχική γωνία του τόξου, μετρημένη σε ακτίνια. |
| [setArc(double value)](#setArc-double-) | Η συνολική γωνία του τόξου, μετρημένη σε ακτίνια. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setHeight(double value)](#setHeight-double-) | Το ύψος του ορθογώνιου δακτυλίου. |
| [setInnerRadius(double value)](#setInnerRadius-double-) | Η εσωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 17 |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setOuterRadius(double value)](#setOuterRadius-double-) | Η εξωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Τα ακτινικά τμήματα, η προεπιλεγμένη τιμή είναι 10 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [toMesh()](#toMesh--) | Μετατρέψτε αυτό το πρωτότυπο σε [Mesh](../../com.aspose.threed/mesh) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangularTorus() {#RectangularTorus--}
```
public RectangularTorus()
```


Κατασκευαστής του [RectangularTorus](../../com.aspose.threed/rectangulartorus)

### RectangularTorus(String name) {#RectangularTorus-java.lang.String-}
```
public RectangularTorus(String name)
```


Κατασκευαστής του [RectangularTorus](../../com.aspose.threed/rectangulartorus)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

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
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


Η αρχική γωνία του τόξου, μετρημένη σε ακτίνια. Η προεπιλεγμένη τιμή είναι 0

**Returns:**
double - Η αρχική γωνία του τόξου, μετρημένη σε ακτίνια. Η προεπιλεγμένη τιμή είναι 0
### getArc() {#getArc--}
```
public double getArc()
```


Η συνολική γωνία του τόξου, μετρημένη σε ακτίνια. Η προεπιλεγμένη τιμή είναι PI

**Returns:**
double - Η συνολική γωνία του τόξου, μετρημένη σε ακτίνια. Η προεπιλεγμένη τιμή είναι PI
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Το ύψος του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20

**Returns:**
double - Το ύψος του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20
### getInnerRadius() {#getInnerRadius--}
```
public double getInnerRadius()
```


Η εσωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 17

**Returns:**
double - Η εσωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 17
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getOuterRadius() {#getOuterRadius--}
```
public double getOuterRadius()
```


Η εξωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20

**Returns:**
double - Η εξωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Τα ακτινικά τμήματα, η προεπιλεγμένη τιμή είναι 10

**Returns:**
int - Τα ακτινικά τμήματα, η προεπιλεγμένη τιμή είναι 10
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
### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


Η αρχική γωνία του τόξου, μετρημένη σε ακτίνια. Η προεπιλεγμένη τιμή είναι 0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


Η συνολική γωνία του τόξου, μετρημένη σε ακτίνια. Η προεπιλεγμένη τιμή είναι PI

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Το ύψος του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setInnerRadius(double value) {#setInnerRadius-double-}
```
public void setInnerRadius(double value)
```


Η εσωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 17

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

### setOuterRadius(double value) {#setOuterRadius-double-}
```
public void setOuterRadius(double value)
```


Η εξωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Τα ακτινικά τμήματα, η προεπιλεγμένη τιμή είναι 10

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Μετατρέψτε αυτό το πρωτότυπο σε [Mesh](../../com.aspose.threed/mesh)

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

