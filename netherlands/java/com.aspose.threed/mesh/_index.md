---
title: Mesh
second_title: Aspose.3D for Java API-referentie
description: Een mesh bestaat uit vele n-zijdige polygonen.
type: docs
weight: 102
url: /nl/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Een mesh bestaat uit veel n‑zijdige polygonen. **Example:** Om een polygoon toe te voegen aan de mesh:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Doorloop alle polygonen in de mesh:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Mesh()](#Mesh--) | Initialiseert een nieuw exemplaar van de [Mesh](../../com.aspose.threed/mesh) klasse. |
| [Mesh(String name)](#Mesh-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Mesh](../../com.aspose.threed/mesh) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Haalt alle deformers op met opgegeven deformer-typen |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Voeg een nieuw controlepunt toe aan de mesh, dit is efficiënter. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Voeg een nieuw controlepunt toe aan de mesh, dit is efficiënter. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Voegt een bestaand vertex‑element toe aan de huidige geometrie |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Creëert een vertex‑element met opgegeven type en voegt het toe aan de geometrie. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Creëert een vertex‑element met opgegeven type en voegt het toe aan de geometrie. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Maakt een [VertexElementUV](../../com.aspose.threed/vertexelementuv) met het opgegeven textuurmappingtype. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Maakt een [VertexElementUV](../../com.aspose.threed/vertexelementuv) met het opgegeven textuurmappingtype. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | Maak een polygoon met 3 hoekpunten (driehoek) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | Maak een polygoon met 4 hoekpunten (vierkant) |
| [createPolygon(int[] indices)](#createPolygon-int---) | Maakt een nieuwe polygoon met alle hoekpunten gedefinieerd in `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | Maakt een nieuwe polygoon met alle hoekpunten gedefinieerd in `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Bereken het verschil van twee meshes |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | Voer een Booleaanse bewerking uit op twee meshes |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |
| [getCastShadows()](#getCastShadows--) | Geeft aan of deze geometrie schaduwen kan werpen |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Geeft alle controlepunten terug |
| [getDeformers()](#getDeformers--) | Geeft alle deformers die aan deze geometrie zijn gekoppeld terug. |
| [getEdges()](#getEdges--) | Geeft de randen van de Mesh terug. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Geeft een vertex-element met het opgegeven type terug |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer. |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [getName()](#getName--) | Haalt de naam op. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getPolygonCount()](#getPolygonCount--) | Geeft het aantal polygonen terug |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Geeft het aantal hoekpunten van de opgegeven polygoon terug. |
| [getPolygons()](#getPolygons--) | Geeft de definitie van de polygonen van de mesh terug |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getReceiveShadows()](#getReceiveShadows--) | Geeft aan of deze geometrie schaduwen kan ontvangen. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Geeft een [VertexElementUV](../../com.aspose.threed/vertexelementuv) instantie met het opgegeven textuurmappingtype terug |
| [getVertexElements()](#getVertexElements--) | Geeft alle vertex-elementen terug |
| [getVisible()](#getVisible--) | Geeft aan of de geometrie zichtbaar is |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Bereken de intersectie van twee meshes |
| [isManifold()](#isManifold--) | Controleer of de huidige mesh een manifold-mesh is. |
| [iterator()](#iterator--) | Geeft de enumerator voor elke interne polygoon terug. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Stelt in of deze geometrie schaduwen kan werpen |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Stelt in of deze geometrie schaduwen kan ontvangen. |
| [setVisible(boolean value)](#setVisible-boolean-) | Stelt in of de geometrie zichtbaar is |
| [toMesh()](#toMesh--) | Haalt de Mesh‑instantie op van de huidige entiteit. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Retourneer getrianguleerde mesh |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Bereken de unie van twee meshes |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Initialiseert een nieuw exemplaar van de [Mesh](../../com.aspose.threed/mesh) klasse.

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Initialiseert een nieuw exemplaar van de [Mesh](../../com.aspose.threed/mesh) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Haalt alle deformers op met opgegeven deformer-typen

**Returns:**
java.util.Collection<T> - Deformer‑collectie
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Voeg een nieuw controlepunt toe aan de mesh, dit is efficiënter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | De x‑component van het controlepunt |
| y | double | De y‑component van het controlepunt |
| z | double | De z‑component van het controlepunt |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Voeg een nieuw controlepunt toe aan de mesh, dit is efficiënter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | De x‑component van het controlepunt |
| y | double | De y‑component van het controlepunt |
| z | double | De z‑component van het controlepunt |
| w | double | De w‑component van het controlepunt |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Voegt een bestaand vertex‑element toe aan de huidige geometrie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Het vertex‑element om toe te voegen |

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


Creëert een vertex‑element met opgegeven type en voegt het toe aan de geometrie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Vertex‑elementtype |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Creëert een vertex‑element met opgegeven type en voegt het toe aan de geometrie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Vertex‑elementtype |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Standaard‑mappingmodus |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Standaard‑referentiemodus |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Maakt een [VertexElementUV](../../com.aspose.threed/vertexelementuv) met het opgegeven textuurmappingtype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Welk textuur‑mappingtype te maken |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Maakt een [VertexElementUV](../../com.aspose.threed/vertexelementuv) met het opgegeven textuurmappingtype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Welk textuur‑mappingtype te maken |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Standaard‑mappingmodus |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Standaard‑referentiemodus |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


Maak een polygoon met 3 hoekpunten (driehoek)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v1 | int | Index van de eerste vertex |
| v2 | int | Index van de tweede vertex |
|  | v3 | int | Index van de derde vertex **Example:** De volgende code laat zien hoe een nieuw polygon met de indices van het controlepunt te maken. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


Maak een polygoon met 4 hoekpunten (vierkant)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v1 | int | Index van de eerste vertex |
| v2 | int | Index van de tweede vertex |
| v3 | int | Index van de derde vertex |
|  | v4 | int | Index van de vierde vertex **Example:** De volgende code laat zien hoe een nieuw polygon met de indices van het controlepunt te maken. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Maakt een nieuw polygon met alle vertices gedefinieerd in `indices`. Om een polygon vertex voor vertex te maken, gebruik alstublieft [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | indices | int[] | Array van de polygoonindices, elke index wijst naar een controlepunt dat de polygoon vormt. **Voorbeeld:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Maakt een nieuw polygon met alle vertices gedefinieerd in `indices`. Om een polygon vertex voor vertex te maken, gebruik alstublieft [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indices | int[] | Array van de polygoonindices, elke index wijst naar een controlepunt dat de polygoon vormt. |
| offset | int | De offset van de eerste polygoonindex |
|  | length | int | De lengte van de indices **Voorbeeld:** De volgende code laat zien hoe je een nieuwe polygoon maakt met de indices van het controlepunt. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


Bereken het verschil van twee meshes

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Eerste mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Tweede mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


Voer een Booleaanse bewerking uit op twee meshes

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Het Boolean-bewerkingstype. |
| a | [Mesh](../../com.aspose.threed/mesh) | Eerste mesh om te bewerken. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | Transformatie matrix van de eerste mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Tweede mesh om te bewerken |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | Transformatie matrix van de tweede mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
| propertyName | java.lang.String | Eigenschapnaam. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem.

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


Geeft aan of deze geometrie schaduwen kan werpen

**Returns:**
boolean - of deze geometrie schaduw kan werpen
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


Geeft alle controlepunten terug

**Returns:**
java.util.List<com.aspose.threed.Vector4> - alle controlepunten
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Geeft alle deformers die aan deze geometrie zijn gekoppeld terug.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - alle deformers die aan deze geometrie zijn gekoppeld.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Haalt de randen van de Mesh op. Een rand is optioneel in een mesh, dus kan deze leeg zijn.

**Returns:**
java.util.List<java.lang.Integer> - randen van de Mesh. Een rand is optioneel in een mesh, dus kan deze leeg zijn.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Geeft een vertex-element met het opgegeven type terug

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | welk vertex-elementtype te vinden |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren.

**Returns:**
boolean - of deze entiteit moet worden uitgesloten tijdens het exporteren.
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


Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - alle bovenliggende knooppunten, een entiteit kan aan meerdere bovenliggende knooppunten worden gekoppeld voor geometrie‑instantiatie
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Geeft het aantal polygonen terug

**Returns:**
int - het aantal polygonen **Voorbeeld:** De volgende code laat zien hoe je het aantal polygonen van de mesh krijgt.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Geeft het aantal hoekpunten van de opgegeven polygoon terug.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index. |

**Returns:**
int - De grootte van de polygoon.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Geeft de definitie van de polygonen van de mesh terug

**Returns:**
java.util.List<int[]> - de definitie van de polygonen van het mesh
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Haalt de verzameling van alle eigenschappen op.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Haalt de waarde op van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |

**Returns:**
java.lang.Object - De waarde van de gevonden eigenschap
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Geeft aan of deze geometrie schaduwen kan ontvangen.

**Returns:**
boolean - of deze geometrie schaduw kan ontvangen.
### getScene() {#getScene--}
```
public Scene getScene()
```


Haalt de scène op waartoe dit object behoort

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Geeft een [VertexElementUV](../../com.aspose.threed/vertexelementuv) instantie met het opgegeven textuurmappingtype terug

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Geeft alle vertex-elementen terug

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - alle vertex-elementen
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Geeft aan of de geometrie zichtbaar is

**Returns:**
boolean - of de geometrie zichtbaar is
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


Bereken de intersectie van twee meshes

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Eerste mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Tweede mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Controleer of de huidige mesh een manifold-mesh is. Deze functie zal het resultaat van de manifold-berekening niet cachen.

**Returns:**
boolean - true als de mesh een manifold-mesh is.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Geeft de enumerator voor elke interne polygoon terug.

**Returns:**
java.util.Iterator<int[]> - De enumerator.
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


Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vertexElements | boolean | Dupliceerde vertex-elementgegevens optimaliseren |

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


Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vertexElements | boolean | Dupliceerde vertex-elementgegevens optimaliseren |
| toleranceControlPoint | float | De tolerantie voor controlepunt, standaardwaarde is 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vertexElements | boolean | Dupliceerde vertex-elementgegevens optimaliseren |
| toleranceControlPoint | float | De tolerantie voor controlepunt, standaardwaarde is 1e-9 |
| toleranceNormal | float | De tolerantie voor normaal/tangent/binormaal, standaardwaarde is 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vertexElements | boolean | Dupliceerde vertex-elementgegevens optimaliseren |
| toleranceControlPoint | float | De tolerantie voor controlepunt, standaardwaarde is 1e-9 |
| toleranceNormal | float | De tolerantie voor normaal/tangent/binormaal, standaardwaarde is 1e-9 |
| toleranceUV | float | De tolerantie voor uv, standaardwaarde is 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Optimaliseer het geheugenverbruik van de mesh door dubbele controlepunten te verwijderen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vertexElements | boolean | Dupliceerde vertex-elementgegevens optimaliseren |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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


Verwijder de opgegeven eigenschap geïdentificeerd op naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Stelt in of deze geometrie schaduwen kan werpen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren.

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


Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Stelt de waarde in van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |
| waarde | java.lang.Object | De waarde van de eigenschap |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Stelt in of deze geometrie schaduwen kan ontvangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Stelt in of de geometrie zichtbaar is

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Haalt de Mesh‑instantie op van de huidige entiteit.

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


Retourneer getrianguleerde mesh

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


Bereken de unie van twee meshes

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Eerste mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Tweede mesh |

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

