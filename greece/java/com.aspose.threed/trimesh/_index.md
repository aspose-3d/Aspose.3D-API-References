---
title: TriMesh
second_title: Aspose.3D for Java API Reference
description: Ένα TriMesh περιέχει ακατέργαστα δεδομένα που μπορούν να χρησιμοποιηθούν άμεσα από την GPU.
type: docs
weight: 194
url: /el/java/com.aspose.threed/trimesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class TriMesh extends Entity implements Iterable<Vertex>
```

Ένα TriMesh περιέχει ακατέργαστα δεδομένα που μπορούν να χρησιμοποιηθούν απευθείας από το GPU. Αυτή η κλάση είναι ένα βοηθητικό εργαλείο για τη δημιουργία ενός πλέγματος που περιέχει μόνο δεδομένα ανά κορυφή. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα TriMesh με προσαρμοσμένη διάταξη μνήμης και να το εξάγετε σε αρχείο.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [TriMesh(String name, VertexDeclaration declaration)](#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-) | Αρχικοποιήστε ένα στιγμιότυπο του [TriMesh](../../com.aspose.threed/trimesh) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addTriangle(int a, int b, int c)](#addTriangle-int-int-int-) | Προσθέστε ένα νέο τρίγωνο |
| [beginVertex()](#beginVertex--) | Ξεκινήστε την προσθήκη κορυφής |
| [copyFrom(TriMesh input, VertexDeclaration vd)](#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-) | Αντιγράψτε το [TriMesh](../../com.aspose.threed/trimesh) από την είσοδο με νέα διάταξη κορυφών |
| [endVertex()](#endVertex--) | Τελειώστε την προσθήκη κορυφής |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [fromMesh(Mesh mesh)](#fromMesh-com.aspose.threed.Mesh-) | Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος, η δήλωση κορυφών βασίζεται στη δομή του εισαγόμενου πλέγματος. |
| [fromMesh(Mesh mesh, boolean useFloat)](#fromMesh-com.aspose.threed.Mesh-boolean-) | Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος, η δήλωση κορυφών βασίζεται στη δομή του εισαγόμενου πλέγματος. |
| [fromMesh(VertexDeclaration declaration, Mesh mesh)](#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-) | Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος με τη δοσμένη διάταξη κορυφών. |
| [fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)](#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-) | Δημιουργήστε TriMesh από ακατέργαστα δεδομένα |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getCapacity()](#getCapacity--) | Η χωρητικότητα των προ-καθορισμένων κορυφών. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getIndicesCount()](#getIndicesCount--) | Ο αριθμός των δεικτών σε αυτό το [TriMesh](../../com.aspose.threed/trimesh) |
| [getIntIndices()](#getIntIndices--) | Μετατρέψτε τους δείκτες σε πίνακα ακεραίων 32bit |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getShortIndices()](#getShortIndices--) | Μετατρέψτε τους δείκτες σε πίνακα ακεραίων 16bit |
| [getUnmergedVerticesCount()](#getUnmergedVerticesCount--) | Ο αριθμός των μη συγχωνευμένων κορυφών που περάστηκαν από το [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) και το [endVertex](../../com.aspose.threed/trimesh\#endVertex). |
| [getVertexDeclaration()](#getVertexDeclaration--) | Η διάταξη κορυφών του [TriMesh](../../com.aspose.threed/trimesh). |
| [getVerticesCount()](#getVerticesCount--) | Ο αριθμός των κορυφών σε αυτό το [TriMesh](../../com.aspose.threed/trimesh) |
| [getVerticesSizeInBytes()](#getVerticesSizeInBytes--) | Το συνολικό μέγεθος όλων των κορυφών σε bytes |
| [hashCode()](#hashCode--) |  |
| [indicesToArray(int[][] result)](#indicesToArray-int-----) | Μετατρέψτε τους δείκτες σε πίνακα ακεραίων 32bit |
| [indicesToArray(short[][] result)](#indicesToArray-short-----) | Μετατρέψτε τους δείκτες σε πίνακα ακεραίων 16bit |
| [iterator()](#iterator--) | Get the enumerator to enumerate [Vertex](../../com.aspose.threed/vertex) |
| [loadVerticesFromBytes(byte[] verticesInBytes)](#loadVerticesFromBytes-byte---) | Φορτώστε τις κορυφές από byte, το μήκος των byte πρέπει να είναι ακέραιο πολλαπλάσιο του μεγέθους της κορυφής. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(int idx, VertexField field)](#readDouble-int-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο double |
| [readFVector2(int idx, VertexField field)](#readFVector2-int-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector2 |
| [readFVector3(int idx, VertexField field)](#readFVector3-int-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector3 |
| [readFVector4(int idx, VertexField field)](#readFVector4-int-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector4 |
| [readFloat(int idx, VertexField field)](#readFloat-int-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο float |
| [readVector2(int idx, VertexField field)](#readVector2-int-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector2 |
| [readVector3(int idx, VertexField field)](#readVector3-int-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector3 |
| [readVector4(int idx, VertexField field)](#readVector4-int-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector4 |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [toString()](#toString--) | Gets the string representation of [TriMesh](../../com.aspose.threed/trimesh) |
| [verticesToArray()](#verticesToArray--) | Μετατρέψτε τα δεδομένα των κορυφών σε πίνακα byte |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write16bIndicesTo(Stream stream)](#write16bIndicesTo-com.aspose.threed.Stream-) | Write the indices data as 16bit integer to the stream **Example:** |
| [write16bIndicesTo(OutputStream stream)](#write16bIndicesTo-java.io.OutputStream-) | Write the indices data as 16bit integer to the stream |
| [write32bIndicesTo(Stream stream)](#write32bIndicesTo-com.aspose.threed.Stream-) | Write the indices data as 32bit integer to the stream **Example:** |
| [write32bIndicesTo(OutputStream stream)](#write32bIndicesTo-java.io.OutputStream-) | Write the indices data as 32bit integer to the stream |
| [writeVerticesTo(Stream stream)](#writeVerticesTo-com.aspose.threed.Stream-) | Write vertices data to the specified stream |
| [writeVerticesTo(OutputStream stream)](#writeVerticesTo-java.io.OutputStream-) | Write vertices data to the specified stream |
### TriMesh(String name, VertexDeclaration declaration) {#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-}
```
public TriMesh(String name, VertexDeclaration declaration)
```


Αρχικοποιήστε ένα στιγμιότυπο του [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | The name of this TriMesh |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | The vertex's declaration |

### addTriangle(int a, int b, int c) {#addTriangle-int-int-int-}
```
public void addTriangle(int a, int b, int c)
```


Προσθέστε ένα νέο τρίγωνο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | int | The index of first vertex |
| b | int | The index of second vertex |
| c | int | The index of third vertex |

### beginVertex() {#beginVertex--}
```
public Vertex beginVertex()
```


Ξεκινήστε την προσθήκη κορυφής

**Returns:**
[Vertex](../../com.aspose.threed/vertex) - The reference of internal vertex object in type [Vertex](../../com.aspose.threed/vertex)
### copyFrom(TriMesh input, VertexDeclaration vd) {#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-}
```
public static TriMesh copyFrom(TriMesh input, VertexDeclaration vd)
```


Αντιγράψτε το [TriMesh](../../com.aspose.threed/trimesh) από την είσοδο με νέα διάταξη κορυφών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [TriMesh](../../com.aspose.threed/trimesh) | The input TriMesh for copying |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | The new vertex declaration of the output TriMesh |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - A new TriMesh instance with new vertex declaration. **Example:**

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
  vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
  //convert a mesh to TriMesh, the layout is automatically inferred from input mesh
  var oldTriMesh = TriMesh.fromMesh((new Sphere()).toMesh());
  //now create a new TriMesh from old TriMesh, using explicit memory layout defined by vd
  var newTriMesh = TriMesh.copyFrom(oldTriMesh, vd);
```
### endVertex() {#endVertex--}
```
public int endVertex()
```


Τελειώστε την προσθήκη κορυφής

**Returns:**
int
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
### fromMesh(Mesh mesh) {#fromMesh-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(Mesh mesh)
```


Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος, η δήλωση κορυφών βασίζεται στη δομή του εισαγόμενου πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(Mesh mesh, boolean useFloat) {#fromMesh-com.aspose.threed.Mesh-boolean-}
```
public static TriMesh fromMesh(Mesh mesh, boolean useFloat)
```


Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος, η δήλωση κορυφών βασίζεται στη δομή του εισαγόμενου πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| useFloat | boolean | Χρησιμοποιήστε τύπο float αντί για τύπο double για κάθε συνιστώσα στοιχείου κορυφής. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(VertexDeclaration declaration, Mesh mesh) {#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(VertexDeclaration declaration, Mesh mesh)
```


Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος με τη δοσμένη διάταξη κορυφών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Vertex's type definition, or memory layout |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Source mesh |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - Instance of TriMesh converted from input mesh with specified vertex's memory layout **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping) {#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-}
```
public static TriMesh fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)
```


Δημιουργήστε TriMesh από ακατέργαστα δεδομένα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Η δήλωση κορυφών πρέπει να περιέχει τουλάχιστον ένα πεδίο. |
| vertices | byte[] | Τα δεδομένα εισόδου των κορυφών, το ελάχιστο μήκος των κορυφών πρέπει να είναι μεγαλύτερο ή ίσο με το μέγεθος της δήλωσης κορυφών. |
| δείκτες | int[] | Οι δείκτες τριγώνων |
| generateVertexMapping | boolean | Generate [Vertex](../../com.aspose.threed/vertex) for each vertex, which is not necessary for just serialization/deserialization. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) instance that encapsulated the input byte array. **Remarks:** The returned TriMesh will not copy the input byte array for performance, external changes on the array will be reflected to this instance. **Example:** The following code shows how to construct a TriMesh from raw bytes, this is useful when build your own 3D format

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0The string representation,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```
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
### getCapacity() {#getCapacity--}
```
public int getCapacity()
```


Η χωρητικότητα των προ-καθορισμένων κορυφών.

**Returns:**
int - The capacity of pre-allocated vertices.
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
### getIndicesCount() {#getIndicesCount--}
```
public int getIndicesCount()
```


Ο αριθμός των δεικτών σε αυτό το [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
int - The count of indices in this [TriMesh](../../com.aspose.threed/trimesh)
### getIntIndices() {#getIntIndices--}
```
public int[] getIntIndices()
```


Μετατρέψτε τους δείκτες σε πίνακα ακεραίων 32bit

**Returns:**
int[]
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
### getShortIndices() {#getShortIndices--}
```
public short[] getShortIndices()
```


Μετατρέψτε τους δείκτες σε πίνακα ακεραίων 16bit

**Returns:**
short[]
### getUnmergedVerticesCount() {#getUnmergedVerticesCount--}
```
public int getUnmergedVerticesCount()
```


Ο αριθμός των μη συγχωνευμένων κορυφών που περάστηκαν από το [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) και το [endVertex](../../com.aspose.threed/trimesh\#endVertex).

**Returns:**
int - The count of unmerged vertices that passed in by [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) and [endVertex](../../com.aspose.threed/trimesh\#endVertex).
### getVertexDeclaration() {#getVertexDeclaration--}
```
public VertexDeclaration getVertexDeclaration()
```


Η διάταξη κορυφών του [TriMesh](../../com.aspose.threed/trimesh).

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - The vertex layout of the [TriMesh](../../com.aspose.threed/trimesh).
### getVerticesCount() {#getVerticesCount--}
```
public int getVerticesCount()
```


Ο αριθμός των κορυφών σε αυτό το [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
int - The count of vertices in this [TriMesh](../../com.aspose.threed/trimesh)
### getVerticesSizeInBytes() {#getVerticesSizeInBytes--}
```
public int getVerticesSizeInBytes()
```


Το συνολικό μέγεθος όλων των κορυφών σε bytes

**Returns:**
int - The total size of all vertices in bytes
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicesToArray(int[][] result) {#indicesToArray-int-----}
```
public void indicesToArray(int[][] result)
```


Μετατρέψτε τους δείκτες σε πίνακα ακεραίων 32bit

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| result | int[][] |  |

### indicesToArray(short[][] result) {#indicesToArray-short-----}
```
public void indicesToArray(short[][] result)
```


Μετατρέψτε τους δείκτες σε πίνακα ακεραίων 16bit

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| result | short[][] |  |

### iterator() {#iterator--}
```
public Iterator<Vertex> iterator()
```


Get the enumerator to enumerate [Vertex](../../com.aspose.threed/vertex)

**Returns:**
java.util.Iterator<com.aspose.threed.Vertex>
### loadVerticesFromBytes(byte[] verticesInBytes) {#loadVerticesFromBytes-byte---}
```
public void loadVerticesFromBytes(byte[] verticesInBytes)
```


Load vertices from bytes, the length of bytes must be an integer multiple of vertex size. **Example:** The following code shows how to create an empty TriMesh and manually load vertices from raw bytes.

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.LoadVerticesFromBytes(vertices);
  triMesh.AddTriangle(0, 1, 2);
```

```
int[] indices = new int[] { 0,  1,  2 };
  byte[] vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.loadVerticesFromBytes(vertices);
  triMesh.addTriangle(0, 1, 2);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| verticesInBytes | byte[] |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readDouble(int idx, VertexField field) {#readDouble-int-com.aspose.threed.VertexField-}
```
public double readDouble(int idx, VertexField field)
```


Διαβάστε το πεδίο double

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Ο δείκτης της κορυφής για ανάγνωση |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με συμβατό τύπο δεδομένων float/double |

**Returns:**
double - Double value of specified vertex's field
### readFVector2(int idx, VertexField field) {#readFVector2-int-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(int idx, VertexField field)
```


Διαβάστε το πεδίο vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Ο δείκτης της κορυφής για ανάγνωση |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector2/FVector2 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - FVector2 of specified vertex's field
### readFVector3(int idx, VertexField field) {#readFVector3-int-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(int idx, VertexField field)
```


Διαβάστε το πεδίο vector3

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Ο δείκτης της κορυφής για ανάγνωση |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector3/FVector3 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(int idx, VertexField field) {#readFVector4-int-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(int idx, VertexField field)
```


Διαβάστε το πεδίο vector4

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Ο δείκτης της κορυφής για ανάγνωση |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector4/FVector4 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(int idx, VertexField field) {#readFloat-int-com.aspose.threed.VertexField-}
```
public float readFloat(int idx, VertexField field)
```


Διαβάστε το πεδίο float

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Ο δείκτης της κορυφής για ανάγνωση |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με συμβατό τύπο δεδομένων float/double |

**Returns:**
float - Float value of specified vertex's field
### readVector2(int idx, VertexField field) {#readVector2-int-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(int idx, VertexField field)
```


Διαβάστε το πεδίο vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Ο δείκτης της κορυφής για ανάγνωση |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector2/FVector2 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Vector2 of specified vertex's field
### readVector3(int idx, VertexField field) {#readVector3-int-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(int idx, VertexField field)
```


Διαβάστε το πεδίο vector3

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Ο δείκτης της κορυφής για ανάγνωση |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector3/FVector3 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(int idx, VertexField field) {#readVector4-int-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(int idx, VertexField field)
```


Διαβάστε το πεδίο vector4

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Ο δείκτης της κορυφής για ανάγνωση |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector4/FVector4 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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

### toString() {#toString--}
```
public String toString()
```


Gets the string representation of [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
java.lang.String - The string representation
### verticesToArray() {#verticesToArray--}
```
public byte[] verticesToArray()
```


Μετατρέψτε τα δεδομένα των κορυφών σε πίνακα byte

**Returns:**
byte[]
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

### write16bIndicesTo(Stream stream) {#write16bIndicesTo-com.aspose.threed.Stream-}
```
public void write16bIndicesTo(Stream stream)
```


Write the indices data as 16bit integer to the stream **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write16bIndicesTo(OutputStream stream) {#write16bIndicesTo-java.io.OutputStream-}
```
public void write16bIndicesTo(OutputStream stream)
```


Write the indices data as 16bit integer to the stream

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.OutputStream | **Example:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
     var mesh = (new Sphere()).toMesh();    
     var triMesh = TriMesh.fromMesh(mesh);    
     //save it to a stream, 115 vertices * 32bytes per vertex    
     var stream = new ByteArrayOutputStream();    
     triMesh.writeVerticesTo(stream);    
     //save indices as ushort to stream, 504 indices * 2 bytes per index    
     triMesh.write16bIndicesTo(stream);
``` |

### write32bIndicesTo(Stream stream) {#write32bIndicesTo-com.aspose.threed.Stream-}
```
public void write32bIndicesTo(Stream stream)
```


Write the indices data as 32bit integer to the stream **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write32bIndicesTo(s);
      }
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write32bIndicesTo(OutputStream stream) {#write32bIndicesTo-java.io.OutputStream-}
```
public void write32bIndicesTo(OutputStream stream)
```


Write the indices data as 32bit integer to the stream

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.OutputStream | **Example:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write32bIndicesTo(stream);
``` |

### writeVerticesTo(Stream stream) {#writeVerticesTo-com.aspose.threed.Stream-}
```
public void writeVerticesTo(Stream stream)
```


Write vertices data to the specified stream

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | [Stream](../../com.aspose.threed/stream) | The stream that the vertices data will be written to **Example:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
``` |

### writeVerticesTo(OutputStream stream) {#writeVerticesTo-java.io.OutputStream-}
```
public void writeVerticesTo(OutputStream stream)
```


Write vertices data to the specified stream

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.OutputStream | The stream that the vertices data will be written to **Example:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write16bIndicesTo(stream);
``` |

