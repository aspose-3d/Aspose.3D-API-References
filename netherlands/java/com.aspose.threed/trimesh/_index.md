---
title: "TriMesh"
second_title: "Aspose.3D voor Java API-referentie"
description: "Een TriMesh bevat ruwe gegevens die direct door de GPU kunnen worden gebruikt."
type: docs
weight: 194
url: /nl/java/com.aspose.threed/trimesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class TriMesh extends Entity implements Iterable<Vertex>
```

Een TriMesh bevat ruwe gegevens die direct door de GPU kunnen worden gebruikt. Deze klasse is een hulpprogramma om een mesh te construeren die alleen per-vertex gegevens bevat. **Voorbeeld:** De volgende code toont hoe je een TriMesh met een aangepaste geheugenindeling maakt en deze naar een bestand exporteert.

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

| Constructor | Beschrijving |
| --- | --- |
| [TriMesh(String name, VertexDeclaration declaration)](#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-) | Initialiseer een instantie van [TriMesh](../../com.aspose.threed/trimesh) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addTriangle(int a, int b, int c)](#addTriangle-int-int-int-) | Voeg een nieuwe driehoek toe |
| [beginVertex()](#beginVertex--) | Begin met het toevoegen van vertex |
| [copyFrom(TriMesh input, VertexDeclaration vd)](#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-) | Kopieer de [TriMesh](../../com.aspose.threed/trimesh) van de invoer met een nieuwe vertex-indeling |
| [endVertex()](#endVertex--) | Beëindig het toevoegen van vertex |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [fromMesh(Mesh mesh)](#fromMesh-com.aspose.threed.Mesh-) | Maak een TriMesh van een gegeven mesh-object, de vertex-declaratie is gebaseerd op de structuur van de invoer-mesh. |
| [fromMesh(Mesh mesh, boolean useFloat)](#fromMesh-com.aspose.threed.Mesh-boolean-) | Maak een TriMesh van een gegeven mesh-object, de vertex-declaratie is gebaseerd op de structuur van de invoer-mesh. |
| [fromMesh(VertexDeclaration declaration, Mesh mesh)](#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-) | Maak een TriMesh van een gegeven mesh-object met een gegeven vertex-indeling. |
| [fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)](#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-) | Maak TriMesh van ruwe gegevens |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omhullende doos van de huidige entiteit op in zijn objectruimte-coördinatensysteem. |
| [getCapacity()](#getCapacity--) | De capaciteit van vooraf toegewezen vertices. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel van de entiteit-renderer op die is geregistreerd in de renderer |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens exporteren. |
| [getIndicesCount()](#getIndicesCount--) | Het aantal indexen in deze [TriMesh](../../com.aspose.threed/trimesh) |
| [getIntIndices()](#getIntIndices--) | Converteer de indexen naar een 32-bit integer-array |
| [getName()](#getName--) | Haalt de naam op. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; indien de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie-instantiering. |
| [getProperties()](#getProperties--) | Haalt de collectie van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde van de opgegeven eigenschap op. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort. |
| [getShortIndices()](#getShortIndices--) | Converteer de indexen naar een 16-bit integer-array |
| [getUnmergedVerticesCount()](#getUnmergedVerticesCount--) | Het aantal niet- samengevoegde vertices dat is doorgegeven door [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) en [endVertex](../../com.aspose.threed/trimesh\#endVertex). |
| [getVertexDeclaration()](#getVertexDeclaration--) | De vertex-indeling van de [TriMesh](../../com.aspose.threed/trimesh). |
| [getVerticesCount()](#getVerticesCount--) | Het aantal vertices in deze [TriMesh](../../com.aspose.threed/trimesh) |
| [getVerticesSizeInBytes()](#getVerticesSizeInBytes--) | De totale grootte van alle vertices in bytes |
| [hashCode()](#hashCode--) |  |
| [indicesToArray(int[][] result)](#indicesToArray-int-----) | Converteer de indexen naar een 32-bit integer-array |
| [indicesToArray(short[][] result)](#indicesToArray-short-----) | Converteer de indexen naar een 16-bit integer-array |
| [iterator()](#iterator--) | Verkrijg de enumerator om [Vertex](../../com.aspose.threed/vertex) te enumereren |
| [loadVerticesFromBytes(byte[] verticesInBytes)](#loadVerticesFromBytes-byte---) | Laad vertices vanuit bytes, de lengte van de bytes moet een geheel veelvoud zijn van de vertex-grootte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(int idx, VertexField field)](#readDouble-int-com.aspose.threed.VertexField-) | Lees het double-veld |
| [readFVector2(int idx, VertexField field)](#readFVector2-int-com.aspose.threed.VertexField-) | Lees het vector2-veld |
| [readFVector3(int idx, VertexField field)](#readFVector3-int-com.aspose.threed.VertexField-) | Lees het vector3-veld |
| [readFVector4(int idx, VertexField field)](#readFVector4-int-com.aspose.threed.VertexField-) | Lees het vector4-veld |
| [readFloat(int idx, VertexField field)](#readFloat-int-com.aspose.threed.VertexField-) | Lees het float-veld |
| [readVector2(int idx, VertexField field)](#readVector2-int-com.aspose.threed.VertexField-) | Lees het vector2-veld |
| [readVector3(int idx, VertexField field)](#readVector3-int-com.aspose.threed.VertexField-) | Lees het vector3-veld |
| [readVector4(int idx, VertexField field)](#readVector4-int-com.aspose.threed.VertexField-) | Lees het vector4-veld |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens exporteren. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; indien de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde van de opgegeven eigenschap in. |
| [toString()](#toString--) | Haalt de stringrepresentatie op van [TriMesh](../../com.aspose.threed/trimesh) |
| [verticesToArray()](#verticesToArray--) | Converteer de vertexgegevens naar een byte-array |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write16bIndicesTo(Stream stream)](#write16bIndicesTo-com.aspose.threed.Stream-) | Schrijf de indexgegevens als 16-bit geheel getal naar de stream **Example:** |
| [write16bIndicesTo(OutputStream stream)](#write16bIndicesTo-java.io.OutputStream-) | Schrijf de indexgegevens als 16-bit geheel getal naar de stream |
| [write32bIndicesTo(Stream stream)](#write32bIndicesTo-com.aspose.threed.Stream-) | Schrijf de indexgegevens als 32-bit geheel getal naar de stream **Example:** |
| [write32bIndicesTo(OutputStream stream)](#write32bIndicesTo-java.io.OutputStream-) | Schrijf de indexgegevens als 32-bit geheel getal naar de stream |
| [writeVerticesTo(Stream stream)](#writeVerticesTo-com.aspose.threed.Stream-) | Schrijf vertexgegevens naar de opgegeven stream |
| [writeVerticesTo(OutputStream stream)](#writeVerticesTo-java.io.OutputStream-) | Schrijf vertexgegevens naar de opgegeven stream |
### TriMesh(String name, VertexDeclaration declaration) {#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-}
```
public TriMesh(String name, VertexDeclaration declaration)
```


Initialiseer een instantie van [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van deze TriMesh |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | De declaratie van de vertex |

### addTriangle(int a, int b, int c) {#addTriangle-int-int-int-}
```
public void addTriangle(int a, int b, int c)
```


Voeg een nieuwe driehoek toe

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | int | De index van de eerste vertex |
| b | int | De index van de tweede vertex |
| c | int | De index van de derde vertex |

### beginVertex() {#beginVertex--}
```
public Vertex beginVertex()
```


Begin met het toevoegen van vertex

**Returns:**
[Vertex](../../com.aspose.threed/vertex) - The reference of internal vertex object in type [Vertex](../../com.aspose.threed/vertex)
### copyFrom(TriMesh input, VertexDeclaration vd) {#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-}
```
public static TriMesh copyFrom(TriMesh input, VertexDeclaration vd)
```


Kopieer de [TriMesh](../../com.aspose.threed/trimesh) van de invoer met een nieuwe vertex-indeling

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [TriMesh](../../com.aspose.threed/trimesh) | De invoer-TriMesh voor het kopiëren |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | De nieuwe vertexdeclaratie van de output-TriMesh |

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


Beëindig het toevoegen van vertex

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap (geïdentificeerd op naam).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyName | java.lang.String | Naam van de eigenschap. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromMesh(Mesh mesh) {#fromMesh-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(Mesh mesh)
```


Maak een TriMesh van een gegeven mesh-object, de vertex-declaratie is gebaseerd op de structuur van de invoer-mesh.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Maak een TriMesh van een gegeven mesh-object, de vertex-declaratie is gebaseerd op de structuur van de invoer-mesh.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| useFloat | boolean | Gebruik het float-type in plaats van het double-type voor elk vertex-elementcomponent. |

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


Maak een TriMesh van een gegeven mesh-object met een gegeven vertex-indeling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Type-definitie van de vertex, of geheugenindeling |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Bron-mesh |

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


Maak TriMesh van ruwe gegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Vertexdeclaratie, moet minstens één veld bevatten. |
| vertices | byte[] | De invoergegevens van de vertices, de minimale lengte van de vertices moet groter of gelijk zijn aan de grootte van de vertexdeclaratie |
| indexen | int[] | De driehoekindices |
| generateVertexMapping | boolean | Genereer [Vertex](../../com.aspose.threed/vertex) voor elke vertex, wat niet nodig is alleen voor serialisatie/deserialisatie. |

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


Haalt de omhullende doos van de huidige entiteit op in zijn objectruimte-coördinatensysteem.

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


De capaciteit van vooraf toegewezen vertices.

**Returns:**
int - De capaciteit van vooraf toegewezen vertices.
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


Haalt de sleutel van de entiteit-renderer op die is geregistreerd in de renderer

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Haalt op of deze entiteit moet worden uitgesloten tijdens exporteren.

**Returns:**
boolean - of deze entiteit moet worden uitgesloten tijdens exporteren.
### getIndicesCount() {#getIndicesCount--}
```
public int getIndicesCount()
```


Het aantal indexen in deze [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
int - Het aantal indices in deze [TriMesh](../../com.aspose.threed/trimesh)
### getIntIndices() {#getIntIndices--}
```
public int[] getIntIndices()
```


Converteer de indexen naar een 32-bit integer-array

**Returns:**
int[]
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Haalt de eerste bovenliggende knoop op; indien de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie-instantiering.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - alle bovenliggende knooppunten, een entiteit kan aan meerdere bovenliggende knooppunten worden gekoppeld voor geometrie‑instantiatie
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Haalt de collectie van alle eigenschappen op.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Haalt de waarde van de opgegeven eigenschap op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van de eigenschap |

**Returns:**
java.lang.Object - De waarde van de gevonden eigenschap
### getScene() {#getScene--}
```
public Scene getScene()
```


Haalt de scène op waartoe dit object behoort.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShortIndices() {#getShortIndices--}
```
public short[] getShortIndices()
```


Converteer de indexen naar een 16-bit integer-array

**Returns:**
short[]
### getUnmergedVerticesCount() {#getUnmergedVerticesCount--}
```
public int getUnmergedVerticesCount()
```


Het aantal niet- samengevoegde vertices dat is doorgegeven door [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) en [endVertex](../../com.aspose.threed/trimesh\#endVertex).

**Returns:**
int - Het aantal niet-gesmolten vertices dat werd doorgegeven door [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) en [endVertex](../../com.aspose.threed/trimesh\#endVertex).
### getVertexDeclaration() {#getVertexDeclaration--}
```
public VertexDeclaration getVertexDeclaration()
```


De vertex-indeling van de [TriMesh](../../com.aspose.threed/trimesh).

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - The vertex layout of the [TriMesh](../../com.aspose.threed/trimesh).
### getVerticesCount() {#getVerticesCount--}
```
public int getVerticesCount()
```


Het aantal vertices in deze [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
int - Het aantal vertices in deze [TriMesh](../../com.aspose.threed/trimesh)
### getVerticesSizeInBytes() {#getVerticesSizeInBytes--}
```
public int getVerticesSizeInBytes()
```


De totale grootte van alle vertices in bytes

**Returns:**
int - De totale grootte van alle vertices in bytes
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


Converteer de indexen naar een 32-bit integer-array

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resultaat | int[][] |  |

### indicesToArray(short[][] result) {#indicesToArray-short-----}
```
public void indicesToArray(short[][] result)
```


Converteer de indexen naar een 16-bit integer-array

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resultaat | short[][] |  |

### iterator() {#iterator--}
```
public Iterator<Vertex> iterator()
```


Verkrijg de enumerator om [Vertex](../../com.aspose.threed/vertex) te enumereren

**Returns:**
java.util.Iterator<com.aspose.threed.Vertex>
### loadVerticesFromBytes(byte[] verticesInBytes) {#loadVerticesFromBytes-byte---}
```
public void loadVerticesFromBytes(byte[] verticesInBytes)
```


Laad vertices vanuit bytes, de lengte van de bytes moet een geheel veelvoud zijn van de vertexgrootte. **Example:** De volgende code toont hoe een lege TriMesh te maken en handmatig vertices te laden vanuit ruwe bytes.

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
| Parameter | Type | Beschrijving |
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


Lees het double-veld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De index van de vertex om te lezen |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Het veld met een float/double compatibel gegevenstype |

**Returns:**
double - Double-waarde van het gespecificeerde vertexveld
### readFVector2(int idx, VertexField field) {#readFVector2-int-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(int idx, VertexField field)
```


Lees het vector2-veld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De index van de vertex om te lezen |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Het veld met een Vector2/FVector2 gegevenstype |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - FVector2 of specified vertex's field
### readFVector3(int idx, VertexField field) {#readFVector3-int-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(int idx, VertexField field)
```


Lees het vector3-veld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De index van de vertex om te lezen |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Het veld met een Vector3/FVector3 gegevenstype |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(int idx, VertexField field) {#readFVector4-int-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(int idx, VertexField field)
```


Lees het vector4-veld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De index van de vertex om te lezen |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Het veld met een Vector4/FVector4 gegevenstype |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(int idx, VertexField field) {#readFloat-int-com.aspose.threed.VertexField-}
```
public float readFloat(int idx, VertexField field)
```


Lees het float-veld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De index van de vertex om te lezen |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Het veld met een float/double compatibel gegevenstype |

**Returns:**
float - Float-waarde van het gespecificeerde vertexveld
### readVector2(int idx, VertexField field) {#readVector2-int-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(int idx, VertexField field)
```


Lees het vector2-veld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De index van de vertex om te lezen |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Het veld met een Vector2/FVector2 gegevenstype |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Vector2 of specified vertex's field
### readVector3(int idx, VertexField field) {#readVector3-int-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(int idx, VertexField field)
```


Lees het vector3-veld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De index van de vertex om te lezen |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Het veld met een Vector3/FVector3 gegevenstype |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(int idx, VertexField field) {#readVector4-int-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(int idx, VertexField field)
```


Lees het vector4-veld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De index van de vertex om te lezen |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Het veld met een Vector4/FVector4 gegevenstype |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Verwijder de opgegeven eigenschap geïdentificeerd op naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Stelt in of deze entiteit moet worden uitgesloten tijdens exporteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Stelt de eerste bovenliggende knoop in; indien de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Stelt de waarde van de opgegeven eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van de eigenschap |
| waarde | java.lang.Object | De waarde van de eigenschap |

### toString() {#toString--}
```
public String toString()
```


Haalt de stringrepresentatie op van [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
java.lang.String - De stringrepresentatie
### verticesToArray() {#verticesToArray--}
```
public byte[] verticesToArray()
```


Converteer de vertexgegevens naar een byte-array

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write16bIndicesTo(Stream stream) {#write16bIndicesTo-com.aspose.threed.Stream-}
```
public void write16bIndicesTo(Stream stream)
```


Schrijf de indexgegevens als 16-bit geheel getal naar de stream **Example:**

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write16bIndicesTo(OutputStream stream) {#write16bIndicesTo-java.io.OutputStream-}
```
public void write16bIndicesTo(OutputStream stream)
```


Schrijf de indexgegevens als 16-bit geheel getal naar de stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stroom | java.io.OutputStream | **Voorbeeld:** |

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


Schrijf de indexgegevens als 32-bit geheel getal naar de stream **Example:**

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write32bIndicesTo(OutputStream stream) {#write32bIndicesTo-java.io.OutputStream-}
```
public void write32bIndicesTo(OutputStream stream)
```


Schrijf de indexgegevens als 32-bit geheel getal naar de stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stroom | java.io.OutputStream | **Voorbeeld:** |

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


Schrijf vertexgegevens naar de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | [Stream](../../com.aspose.threed/stream) | De stream waarin de vertexgegevens worden geschreven **Voorbeeld:** |

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


Schrijf vertexgegevens naar de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stroom | java.io.OutputStream | De stream waarin de vertexgegevens worden geschreven **Voorbeeld:** |

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

