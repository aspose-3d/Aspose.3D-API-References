---
title: Mesh
second_title: Aspose.3D for Java API Reference
description: Ένα mesh αποτελείται από πολλά n-πλευρά πολυγωνικά.
type: docs
weight: 102
url: /el/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Ένα πλέγμα αποτελείται από πολλά n‑πλευρά πολυγωνικά. **Example:** Για να προσθέσετε ένα πολύγωνο στο πλέγμα:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Περιηγηθείτε σε όλα τα πολύγωνα στο πλέγμα:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Mesh()](#Mesh--) | Αρχικοποιεί ένα νέο αντίγραφο της κλάσης [Mesh](../../com.aspose.threed/mesh). |
| [Mesh(String name)](#Mesh-java.lang.String-) | Αρχικοποιεί ένα νέο αντίγραφο της κλάσης [Mesh](../../com.aspose.threed/mesh). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Λαμβάνει όλους τους παραμορφωτές με τους καθορισμένους τύπους παραμορφωτών |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Προσθέστε ένα νέο σημείο ελέγχου στο πλέγμα, αυτό είναι πιο αποδοτικό. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Προσθέστε ένα νέο σημείο ελέγχου στο πλέγμα, αυτό είναι πιο αποδοτικό. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Προσθέτει ένα υπάρχον στοιχείο κορυφής στην τρέχουσα γεωμετρία |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Δημιουργεί ένα στοιχείο κορυφής με τον καθορισμένο τύπο και το προσθέτει στη γεωμετρία. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Δημιουργεί ένα στοιχείο κορυφής με τον καθορισμένο τύπο και το προσθέτει στη γεωμετρία. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Δημιουργεί ένα [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Δημιουργεί ένα [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | Δημιουργήστε ένα πολύγωνο με 3 κορυφές(τρίγωνο) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | Δημιουργήστε ένα πολύγωνο με 4 κορυφές(τετράπλευρο) |
| [createPolygon(int[] indices)](#createPolygon-int---) | Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές που ορίζονται στο `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές που ορίζονται στο `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Υπολογίστε τη διαφορά δύο πλεγμάτων |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | Εκτελέστε λογική Boolean λειτουργία σε δύο πλέγματα |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getCastShadows()](#getCastShadows--) | Επιστρέφει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Επιστρέφει όλα τα σημεία ελέγχου |
| [getDeformers()](#getDeformers--) | Επιστρέφει όλους τους παραμορφωτές που σχετίζονται με αυτή τη γεωμετρία. |
| [getEdges()](#getEdges--) | Επιστρέφει τις άκρες του πλέγματος. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Επιστρέφει ένα στοιχείο κορυφής με καθορισμένο τύπο |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getPolygonCount()](#getPolygonCount--) | Επιστρέφει τον αριθμό των πολυγώνων |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Επιστρέφει τον αριθμό κορυφών του καθορισμένου πολυγώνου. |
| [getPolygons()](#getPolygons--) | Επιστρέφει τον ορισμό των πολυγώνων του πλέγματος |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getReceiveShadows()](#getReceiveShadows--) | Επιστρέφει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Επιστρέφει ένα αντικείμενο [VertexElementUV](../../com.aspose.threed/vertexelementuv) με τον δεδομένο τύπο χαρτογράφησης υφής |
| [getVertexElements()](#getVertexElements--) | Επιστρέφει όλα τα στοιχεία κορυφής |
| [getVisible()](#getVisible--) | Επιστρέφει αν η γεωμετρία είναι ορατή |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Υπολογίστε τη διασταύρωση δύο πλεγμάτων |
| [isManifold()](#isManifold--) | Ελέγξτε αν το τρέχον πλέγμα είναι ένα manifold πλέγμα. |
| [iterator()](#iterator--) | Επιστρέφει τον απαριθμητή για κάθε εσωτερικό πολύγωνο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ορίζει αν η γεωμετρία είναι ορατή |
| [toMesh()](#toMesh--) | Gets the Mesh instance from current entity. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Return triangulated mesh |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calculate the union of two meshes |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Αρχικοποιεί ένα νέο αντίγραφο της κλάσης [Mesh](../../com.aspose.threed/mesh).

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Αρχικοποιεί ένα νέο αντίγραφο της κλάσης [Mesh](../../com.aspose.threed/mesh).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Λαμβάνει όλους τους παραμορφωτές με τους καθορισμένους τύπους παραμορφωτών

**Returns:**
java.util.Collection<T> - Συλλογή Deformer
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Προσθέστε ένα νέο σημείο ελέγχου στο πλέγμα, αυτό είναι πιο αποδοτικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double | Το στοιχείο x του σημείου ελέγχου |
| y | double | Το στοιχείο y του σημείου ελέγχου |
| z | double | Το στοιχείο z του σημείου ελέγχου |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Προσθέστε ένα νέο σημείο ελέγχου στο πλέγμα, αυτό είναι πιο αποδοτικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | double | Το στοιχείο x του σημείου ελέγχου |
| y | double | Το στοιχείο y του σημείου ελέγχου |
| z | double | Το στοιχείο z του σημείου ελέγχου |
| w | double | Το στοιχείο w του σημείου ελέγχου |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Προσθέτει ένα υπάρχον στοιχείο κορυφής στην τρέχουσα γεωμετρία

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Το στοιχείο κορυφής για προσθήκη |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


Δημιουργήστε ένα πολύγωνο με 3 κορυφές(τρίγωνο)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v1 | int | Δείκτης της πρώτης κορυφής |
| v2 | int | Δείκτης της δεύτερης κορυφής |
|  | v3 | int | Δείκτης της τρίτης κορυφής **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα νέο πολύγωνο με δείκτες του σημείου ελέγχου. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


Δημιουργήστε ένα πολύγωνο με 4 κορυφές(τετράπλευρο)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v1 | int | Δείκτης της πρώτης κορυφής |
| v2 | int | Δείκτης της δεύτερης κορυφής |
| v3 | int | Δείκτης της τρίτης κορυφής |
|  | v4 | int | Δείκτης της τέταρτης κορυφής **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα νέο πολύγωνο με δείκτες του σημείου ελέγχου. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές ορισμένες στο `indices`. Για δημιουργία πολύγωνου κορυφή προς κορυφή, παρακαλούμε χρησιμοποιήστε [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | δείκτες | int[] | Πίνακας των δεικτών του πολύγωνου, κάθε δείκτης δείχνει σε ένα σημείο ελέγχου που σχηματίζει το πολύγωνο. **Παράδειγμα:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Δημιουργεί ένα νέο πολύγωνο με όλες τις κορυφές ορισμένες στο `indices`. Για δημιουργία πολύγωνου κορυφή προς κορυφή, παρακαλούμε χρησιμοποιήστε [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτες | int[] | Πίνακας των δεικτών του πολύγωνου, κάθε δείκτης δείχνει σε ένα σημείο ελέγχου που σχηματίζει το πολύγωνο. |
| μετατόπιση | int | Η μετατόπιση του πρώτου δείκτη του πολύγωνου |
|  | μήκος | int | Το μήκος των δεικτών **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα νέο πολύγωνο με δείκτες σημείων ελέγχου. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


Υπολογίστε τη διαφορά δύο πλεγμάτων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Πρώτο πλέγμα |
| b | [Mesh](../../com.aspose.threed/mesh) | Δεύτερο πλέγμα |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


Εκτελέστε λογική Boolean λειτουργία σε δύο πλέγματα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Ο τύπος λειτουργίας Boolean. |
| a | [Mesh](../../com.aspose.threed/mesh) | Το πρώτο πλέγμα για λειτουργία. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | Μήτρα μετασχηματισμού του πρώτου πλέγματος |
| b | [Mesh](../../com.aspose.threed/mesh) | Το δεύτερο πλέγμα για λειτουργία |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | Μήτρα μετασχηματισμού του δεύτερου πλέγματος |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Λαμβάνει τις ακμές του πλέγματος. Η ακμή είναι προαιρετική στο πλέγμα, οπότε μπορεί να είναι κενή.

**Returns:**
java.util.List<java.lang.Integer> - ακμές του πλέγματος. Η ακμή είναι προαιρετική στο πλέγμα, οπότε μπορεί να είναι κενή.
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Επιστρέφει τον αριθμό των πολυγώνων

**Returns:**
int - ο αριθμός των πολύγωνων **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να λάβετε τον αριθμό των πολύγωνων του πλέγματος.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Επιστρέφει τον αριθμό κορυφών του καθορισμένου πολυγώνου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης. |

**Returns:**
int - Το μέγεθος του πολύγωνου.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Επιστρέφει τον ορισμό των πολυγώνων του πλέγματος

**Returns:**
java.util.List<int[]> - ο ορισμός των πολυγώνων του πλέγματος
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
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


Υπολογίστε τη διασταύρωση δύο πλεγμάτων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Πρώτο πλέγμα |
| b | [Mesh](../../com.aspose.threed/mesh) | Δεύτερο πλέγμα |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Ελέγξτε εάν το τρέχον πλέγμα είναι ένα manifold πλέγμα. Αυτή η λειτουργία δεν θα αποθηκεύσει στην κρυφή μνήμη το αποτέλεσμα του υπολογισμού manifold.

**Returns:**
boolean - true εάν το πλέγμα είναι ένα manifold πλέγμα.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Επιστρέφει τον απαριθμητή για κάθε εσωτερικό πολύγωνο.

**Returns:**
java.util.Iterator<int[]> - Ο απαριθμητής.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vertexElements | boolean | Βελτιστοποιήστε τα διπλότυπα δεδομένα στοιχείων κορυφής |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vertexElements | boolean | Βελτιστοποιήστε τα διπλότυπα δεδομένα στοιχείων κορυφής |
| toleranceControlPoint | float | Η ανοχή για το σημείο ελέγχου, η προεπιλεγμένη τιμή είναι 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vertexElements | boolean | Βελτιστοποιήστε τα διπλότυπα δεδομένα στοιχείων κορυφής |
| toleranceControlPoint | float | Η ανοχή για το σημείο ελέγχου, η προεπιλεγμένη τιμή είναι 1e-9 |
| toleranceNormal | float | Η ανοχή για normal/tangent/binormal, η προεπιλεγμένη τιμή είναι 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vertexElements | boolean | Βελτιστοποιήστε τα διπλότυπα δεδομένα στοιχείων κορυφής |
| toleranceControlPoint | float | Η ανοχή για το σημείο ελέγχου, η προεπιλεγμένη τιμή είναι 1e-9 |
| toleranceNormal | float | Η ανοχή για normal/tangent/binormal, η προεπιλεγμένη τιμή είναι 1e-9 |
| toleranceUV | float | Η ανοχή για uv, η προεπιλεγμένη τιμή είναι 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Βελτιστοποιήστε τη χρήση μνήμης του πλέγματος αφαιρώντας διπλότυπα σημεία ελέγχου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vertexElements | boolean | Βελτιστοποιήστε τα διπλότυπα δεδομένα στοιχείων κορυφής |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Gets the Mesh instance from current entity.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


Return triangulated mesh

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


Calculate the union of two meshes

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Πρώτο πλέγμα |
| b | [Mesh](../../com.aspose.threed/mesh) | Δεύτερο πλέγμα |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
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

