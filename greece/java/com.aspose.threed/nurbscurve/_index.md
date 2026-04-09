---
title: NurbsCurve
second_title: Aspose.3D for Java API Reference
description: NURBS curve is a curve represented by NURBSNon-uniform rational basis spline  A NURBS curve is defined by its  a set of weighted  and a  The w component in control point is used as control points weight whatever it is a  or
type: docs
weight: 112
url: /el/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [NurbsCurve](../../com.aspose.threed/nurbscurve). |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [NurbsCurve](../../com.aspose.threed/nurbscurve). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | Αξιολογήστε την καμπύλη NURBS |
| [evaluate(int steps)](#evaluate-int-) | Αξιολογήστε την καμπύλη NURBS |
| [evaluateAt(double u)](#evaluateAt-double-) | Αξιολογήστε το σημείο της καμπύλης στη συγκεκριμένη θέση |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Λαμβάνει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό (1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Επιστρέφει όλα τα σημεία ελέγχου |
| [getCurveType()](#getCurveType--) | Λαμβάνει τον τύπο της καμπύλης. |
| [getDegree()](#getDegree--) | Λαμβάνει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1 |
| [getDimension()](#getDimension--) | Λαμβάνει τη διάσταση της καμπύλης. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getKnotVectors()](#getKnotVectors--) | Λαμβάνει το διάνυσμα κόμβων, είναι μια ακολουθία τιμών παραμέτρων που καθορίζει πού και πώς τα σημεία ελέγχου επηρεάζουν την καμπύλη NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Λαμβάνει την πολλαπλότητα. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getOrder()](#getOrder--) | Λαμβάνει την τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getRational()](#getRational--) | Λαμβάνει αν είναι ρητή, αυτή η τιμή υποδεικνύει αν αυτή η [NurbsCurve](../../com.aspose.threed/nurbscurve) είναι ρητή spline ή μη ρητή spline. |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Ορίζει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό (1, 1, 1). |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Ορίζει τον τύπο της καμπύλης. |
| [setDegree(int value)](#setDegree-int-) | Ορίζει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1. |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Ορίζει τη διάσταση της καμπύλης. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setOrder(int value)](#setOrder-int-) | Ορίζει την τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setRational(boolean value)](#setRational-boolean-) | Ορίζει αν είναι ρητή, αυτή η τιμή υποδεικνύει αν αυτή η [NurbsCurve](../../com.aspose.threed/nurbscurve) είναι ρητή spline ή μη ρητή spline. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [NurbsCurve](../../com.aspose.threed/nurbscurve).

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [NurbsCurve](../../com.aspose.threed/nurbscurve).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


Αξιολογήστε την καμπύλη NURBS

**Returns:**
com.aspose.threed.Vector4[] - Σημεία στην καμπύλη
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


Αξιολογήστε την καμπύλη NURBS

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| βήματα | int | Η συχνότητα αξιολόγησης μεταξύ δύο γειτονικών κόμβων, η προεπιλεγμένη τιμή είναι 20 |

**Returns:**
com.aspose.threed.Vector4[] - Σημεία στην καμπύλη
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Αξιολογήστε το σημείο της καμπύλης στη συγκεκριμένη θέση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| u | double | Η θέση στην καμπύλη, μεταξύ 0 και 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Λαμβάνει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Επιστρέφει όλα τα σημεία ελέγχου

**Returns:**
java.util.List<com.aspose.threed.Vector4> - όλα τα σημεία ελέγχου
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Λαμβάνει τον τύπο της καμπύλης.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Λαμβάνει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1

**Returns:**
int - ο βαθμός μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Λαμβάνει τη διάσταση της καμπύλης.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.

**Returns:**
boolean - αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Λαμβάνει το διάνυσμα κόμβων, είναι μια ακολουθία τιμών παραμέτρων που καθορίζει πού και πώς τα σημεία ελέγχου επηρεάζουν την καμπύλη NURBS.

**Returns:**
java.util.List<java.lang.Double> - το διάνυσμα κόμβων, είναι μια ακολουθία τιμών παραμέτρων που καθορίζει πού και πώς τα σημεία ελέγχου επηρεάζουν την καμπύλη NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Λαμβάνει την πολλαπλότητα.

**Returns:**
java.util.List<java.lang.Integer> - η πολλαπλότητα.
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Λαμβάνει την τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης.

**Returns:**
int - η τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης.
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
### getRational() {#getRational--}
```
public boolean getRational()
```


Λαμβάνει αν είναι ρητός, αυτή η τιμή υποδεικνύει αν αυτή η [NurbsCurve](../../com.aspose.threed/nurbscurve) είναι ρητή spline ή μη ρητή spline. Η μη ρητή B-spline είναι μια ειδική περίπτωση των ρητών B-splines.

**Returns:**
boolean - αν είναι ρητός, αυτή η τιμή υποδεικνύει αν αυτή η [NurbsCurve](../../com.aspose.threed/nurbscurve) είναι ρητή spline ή μη ρητή spline. Η μη ρητή B-spline είναι μια ειδική περίπτωση των ρητών B-splines.
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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Ορίζει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό (1, 1, 1).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Ορίζει τον τύπο της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Νέα τιμή |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Ορίζει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Ορίζει τη διάσταση της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Νέα τιμή **Σχόλια:** Για μια καμπύλη [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL), το συστατικό z στο σημείο ελέγχου δεν χρησιμοποιείται. |

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

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Ορίζει την τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

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

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Ορίζει αν είναι ρητός, αυτή η τιμή υποδεικνύει αν αυτή η [NurbsCurve](../../com.aspose.threed/nurbscurve) είναι ρητή spline ή μη ρητή spline. Η μη ρητή B-spline είναι μια ειδική περίπτωση των ρητών B-splines.

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

