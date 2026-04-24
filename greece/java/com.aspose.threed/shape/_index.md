---
title: Shape
second_title: Aspose.3D for Java API Reference
description: Το σχήμα περιγράφει την παραμόρφωση σε ένα σύνολο σημείων ελέγχου, το οποίο είναι παρόμοιο με τον cluster deformer στο Maya.
type: docs
weight: 171
url: /el/java/com.aspose.threed/shape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)
```
public class Shape extends Geometry
```

Το σχήμα περιγράφει την παραμόρφωση σε ένα σύνολο σημείων ελέγχου, το οποίο είναι παρόμοιο με τον cluster deformer στο Maya. Για παράδειγμα, μπορούμε να προσθέσουμε ένα σχήμα σε μια δημιουργημένη γεωμετρία. Και το σχήμα και η γεωμετρία έχουν τις ίδιες τοπολογικές πληροφορίες αλλά διαφορετική θέση των σημείων ελέγχου. Με διαφορετικά επίπεδα επιρροής, η γεωμετρία εκτελεί ένα εφέ παραμόρφωσης.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Shape()](#Shape--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Shape](../../com.aspose.threed/shape). |
| [Shape(String name)](#Shape-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Shape](../../com.aspose.threed/shape). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Λαμβάνει όλους τους παραμορφωτές με τους καθορισμένους τύπους παραμορφωτών |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Προσθέτει ένα υπάρχον στοιχείο κορυφής στην τρέχουσα γεωμετρία |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Δημιουργεί ένα στοιχείο κορυφής με τον καθορισμένο τύπο και το προσθέτει στη γεωμετρία. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Δημιουργεί ένα στοιχείο κορυφής με τον καθορισμένο τύπο και το προσθέτει στη γεωμετρία. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Δημιουργεί ένα [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Δημιουργεί ένα [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [fromControlPoints(Vector3[] controlPoints)](#fromControlPoints-com.aspose.threed.Vector3...-) | Δημιουργήστε ένα σχήμα με καθορισμένα σημεία ελέγχου και προεπιλεγμένα ευρετήρια. |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getCastShadows()](#getCastShadows--) | Επιστρέφει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Επιστρέφει όλα τα σημεία ελέγχου |
| [getDeformers()](#getDeformers--) | Επιστρέφει όλους τους παραμορφωτές που σχετίζονται με αυτή τη γεωμετρία. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Επιστρέφει ένα στοιχείο κορυφής με καθορισμένο τύπο |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getIndices()](#getIndices--) | Αποκτά τα ευρετήρια. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getReceiveShadows()](#getReceiveShadows--) | Επιστρέφει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Επιστρέφει ένα αντικείμενο [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής |
| [getVertexElements()](#getVertexElements--) | Επιστρέφει όλα τα στοιχεία κορυφής |
| [getVisible()](#getVisible--) | Επιστρέφει αν η γεωμετρία είναι ορατή |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ορίζει αν η γεωμετρία είναι ορατή |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Shape](../../com.aspose.threed/shape).

### Shape(String name) {#Shape-java.lang.String-}
```
public Shape(String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Shape](../../com.aspose.threed/shape).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Λαμβάνει όλους τους παραμορφωτές με τους καθορισμένους τύπους παραμορφωτών

**Returns:**
java.util.Collection<T> - Συλλογή Deformer
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Προσθέτει ένα υπάρχον στοιχείο κορυφής στην τρέχουσα γεωμετρία

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Το στοιχείο κορυφής για προσθήκη |

### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Δημιουργεί ένα στοιχείο κορυφής με τον καθορισμένο τύπο και το προσθέτει στη γεωμετρία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Τύπος στοιχείου κορυφής |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Δημιουργεί ένα στοιχείο κορυφής με τον καθορισμένο τύπο και το προσθέτει στη γεωμετρία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Τύπος στοιχείου κορυφής |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Προεπιλεγμένη λειτουργία αντιστοίχισης |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Προεπιλεγμένη λειτουργία αναφοράς |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Δημιουργεί ένα [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Ποιος τύπος αντιστοίχισης υφής θα δημιουργηθεί |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Δημιουργεί ένα [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Ποιος τύπος αντιστοίχισης υφής θα δημιουργηθεί |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Προεπιλεγμένη λειτουργία αντιστοίχισης |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Προεπιλεγμένη λειτουργία αναφοράς |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
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
### fromControlPoints(Vector3[] controlPoints) {#fromControlPoints-com.aspose.threed.Vector3...-}
```
public static Shape fromControlPoints(Vector3[] controlPoints)
```


Δημιουργήστε ένα σχήμα με καθορισμένα σημεία ελέγχου και προεπιλεγμένα ευρετήρια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controlPoints | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Shape](../../com.aspose.threed/shape)
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
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Επιστρέφει όλα τα σημεία ελέγχου

**Returns:**
java.util.List<com.aspose.threed.Vector4> - όλα τα σημεία ελέγχου
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Επιστρέφει όλους τους παραμορφωτές που σχετίζονται με αυτή τη γεωμετρία.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - όλοι οι παραμορφωτές που σχετίζονται με αυτή τη γεωμετρία.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Επιστρέφει ένα στοιχείο κορυφής με καθορισμένο τύπο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | ποιος τύπος στοιχείου κορυφής να βρεθεί |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
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
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Αποκτά τα ευρετήρια.

**Returns:**
java.util.List<java.lang.Integer> - τα ευρετήρια.
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
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Επιστρέφει ένα αντικείμενο [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Επιστρέφει όλα τα στοιχεία κορυφής

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - όλα τα στοιχεία κορυφής
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Επιστρέφει αν η γεωμετρία είναι ορατή

**Returns:**
boolean - εάν η γεωμετρία είναι ορατή
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

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Ορίζει αν η γεωμετρία είναι ορατή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

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

