---
title: Mesh
second_title: Aspose.3D for Java API-referens
description: Ett nätverk består av många n-sidiga polygoner.
type: docs
weight: 102
url: /sv/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Ett mesh består av många n-sidiga polygoner. **Exempel:** För att lägga till en polygon i mesh:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Gå igenom alla polygoner i mesh:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Mesh()](#Mesh--) | Initierar en ny instans av klassen [Mesh](../../com.aspose.threed/mesh). |
| [Mesh(String name)](#Mesh-java.lang.String-) | Initierar en ny instans av klassen [Mesh](../../com.aspose.threed/mesh). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Hämtar alla deformers med angivna deformer-typer |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Lägg till en ny kontrollpunkt i mesh, detta är mer effektivt. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Lägg till en ny kontrollpunkt i mesh, detta är mer effektivt. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Lägger till ett befintligt vertex-element till aktuell geometri |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Skapar ett vertex-element med angiven typ och lägger till det i geometrin. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Skapar ett vertex-element med angiven typ och lägger till det i geometrin. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Skapar en [VertexElementUV](../../com.aspose.threed/vertexelementuv) med given texturkartläggningstyp. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Skapar en [VertexElementUV](../../com.aspose.threed/vertexelementuv) med given texturkartläggningstyp. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | Skapa en polygon med 3 hörn(triangel) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | Skapa en polygon med 4 hörn(quad) |
| [createPolygon(int[] indices)](#createPolygon-int---) | Skapar en ny polygon med alla hörn definierade i `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | Skapar en ny polygon med alla hörn definierade i `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Beräkna skillnaden mellan två meshar |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | Utför boolesk operation på två meshar |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getBoundingBox()](#getBoundingBox--) | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| [getCastShadows()](#getCastShadows--) | Hämtar om denna geometri kan kasta skugga |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Hämtar alla kontrollpunkter |
| [getDeformers()](#getDeformers--) | Hämtar alla deformatorer som är associerade med denna geometri. |
| [getEdges()](#getEdges--) | Hämtar kanterna på Mesh. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Hämtar ett vertex‑element med angiven typ |
| [getEntityRendererKey()](#getEntityRendererKey--) | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
| [getExcluded()](#getExcluded--) | Hämtar om denna enhet ska exkluderas vid export. |
| [getName()](#getName--) | Hämtar namnet. |
| [getParentNode()](#getParentNode--) | Hämtar den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [getParentNodes()](#getParentNodes--) | Hämtar alla föräldranoder, en enhet kan fästas vid flera föräldranoder för geometrisk instansering |
| [getPolygonCount()](#getPolygonCount--) | Hämtar antalet polygoner |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Hämtar vertex‑antalet för den angivna polygonen. |
| [getPolygons()](#getPolygons--) | Hämtar polygondefinitionen för mesh‑objektet |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getReceiveShadows()](#getReceiveShadows--) | Hämtar om denna geometri kan ta emot skugga. |
| [getScene()](#getScene--) | Hämtar scenen som detta objekt tillhör |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Hämtar en [VertexElementUV](../../com.aspose.threed/vertexelementuv)-instans med given texturkartläggningstyp |
| [getVertexElements()](#getVertexElements--) | Hämtar alla vertex‑element |
| [getVisible()](#getVisible--) | Hämtar om geometrin är synlig |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Beräkna skärningen mellan två meshar |
| [isManifold()](#isManifold--) | Kontrollera om det aktuella mesh‑objektet är ett manifold‑mesh. |
| [iterator()](#iterator--) | Hämtar enumeratorn för varje inre polygon. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ställer in om denna geometri kan kasta skugga |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ställer in om denna enhet ska exkluderas vid export. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ställer in den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Ställer in om denna geometri kan ta emot skugga. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ställer in om geometrin är synlig |
| [toMesh()](#toMesh--) | Hämtar Mesh-instansen från den aktuella enheten. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Returnera triangulerad mesh |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Beräkna unionen av två mesh |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Initierar en ny instans av klassen [Mesh](../../com.aspose.threed/mesh).

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Initierar en ny instans av klassen [Mesh](../../com.aspose.threed/mesh).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Hämtar alla deformers med angivna deformer-typer

**Returns:**
java.util.Collection<T> - Deformer-samling
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Lägg till en ny kontrollpunkt i mesh, detta är mer effektivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | double | x-komponenten för kontrollpunkten |
| y | double | y-komponenten för kontrollpunkten |
| z | double | z-komponenten för kontrollpunkten |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Lägg till en ny kontrollpunkt i mesh, detta är mer effektivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | double | x-komponenten för kontrollpunkten |
| y | double | y-komponenten för kontrollpunkten |
| z | double | z-komponenten för kontrollpunkten |
| w | double | w-komponenten för kontrollpunkten |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Lägger till ett befintligt vertex-element till aktuell geometri

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Vertex-elementet att lägga till |

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


Skapar ett vertex-element med angiven typ och lägger till det i geometrin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Vertex-elementtyp |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Skapar ett vertex-element med angiven typ och lägger till det i geometrin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Vertex-elementtyp |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Standardkartläggningsläge |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Standardreferensläge |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Skapar en [VertexElementUV](../../com.aspose.threed/vertexelementuv) med given texturkartläggningstyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Vilken typ av texturkartläggning som ska skapas |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Skapar en [VertexElementUV](../../com.aspose.threed/vertexelementuv) med given texturkartläggningstyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Vilken typ av texturkartläggning som ska skapas |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Standardkartläggningsläge |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Standardreferensläge |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


Skapa en polygon med 3 hörn(triangel)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v1 | int | Index för den första vertexen |
| v2 | int | Index för den andra vertexen |
|  | v3 | int | Index för den tredje vertexen **Example:** Följande kod visar hur man skapar en ny polygon med kontrollpunkternas index. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


Skapa en polygon med 4 hörn(quad)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v1 | int | Index för den första vertexen |
| v2 | int | Index för den andra vertexen |
| v3 | int | Index för den tredje vertexen |
|  | v4 | int | Index för den fjärde vertexen **Example:** Följande kod visar hur man skapar en ny polygon med kontrollpunkternas index. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Skapar en ny polygon med alla vertexar definierade i `indices`. För att skapa polygon vertex för vertex, använd gärna [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | indices | int[] | Array of the polygon indices, each index points to a control point that forms the polygon. **Example:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Skapar en ny polygon med alla vertexar definierade i `indices`. För att skapa polygon vertex för vertex, använd gärna [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indices | int[] | Array of the polygon indices, each index points to a control point that forms the polygon. |
| offset | int | The offset of the first polygon index |
|  | length | int | The length of the indices **Example:** The following code shows how to create a new polygon with control point's indices. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


Beräkna skillnaden mellan två meshar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | First mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Second mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


Utför boolesk operation på två meshar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | The Boolean operation type. |
| a | [Mesh](../../com.aspose.threed/mesh) | First mesh to operate. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | Transformation matrix of the first mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Second mesh to operate |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | Transformation matrix of the second mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | java.lang.String | Egenskapsnamn. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem.

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


Hämtar om denna geometri kan kasta skugga

**Returns:**
boolean - whether this geometry can cast shadow
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


Hämtar alla kontrollpunkter

**Returns:**
java.util.List<com.aspose.threed.Vector4> - all control points
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Hämtar alla deformatorer som är associerade med denna geometri.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - all deformers associated with this geometry.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Gets edges of the Mesh. Edge is optional in mesh, so it can be empty.

**Returns:**
java.util.List<java.lang.Integer> - edges of the Mesh. Edge is optional in mesh, so it can be empty.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Hämtar ett vertex‑element med angiven typ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | which vertex element type to find |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Hämtar nyckeln för enhetens renderare som är registrerad i renderaren

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Hämtar om denna enhet ska exkluderas vid export.

**Returns:**
boolean - om denna enhet ska exkluderas vid export.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Hämtar den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Hämtar alla föräldranoder, en enhet kan fästas vid flera föräldranoder för geometrisk instansering

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - alla föräldranoder, en entitet kan fästas på flera föräldranoder för geometriinstansering
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Hämtar antalet polygoner

**Returns:**
int - the count of polygons **Example:** The following code shows how to get the number of mesh' polygons.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Hämtar vertex‑antalet för den angivna polygonen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index. |

**Returns:**
int - The polygon size.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Hämtar polygondefinitionen för mesh‑objektet

**Returns:**
java.util.List<int[]> - polygondefinitionen för meshen
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Hämtar samlingen av alla egenskaper.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Hämta värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |

**Returns:**
java.lang.Object - Värdet på den hittade egenskapen
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Hämtar om denna geometri kan ta emot skugga.

**Returns:**
boolean - huruvida denna geometri kan ta emot skugga.
### getScene() {#getScene--}
```
public Scene getScene()
```


Hämtar scenen som detta objekt tillhör

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Hämtar en [VertexElementUV](../../com.aspose.threed/vertexelementuv)-instans med given texturkartläggningstyp

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Hämtar alla vertex‑element

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - alla vertex-element
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Hämtar om geometrin är synlig

**Returns:**
boolean - om geometrin är synlig
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


Beräkna skärningen mellan två meshar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | First mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Second mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Kontrollera om det aktuella meshet är ett manifold-mesh. Denna funktion kommer inte att cachea resultatet av manifold-beräkningen.

**Returns:**
boolean - sant om meshet är ett manifold-mesh.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Hämtar enumeratorn för varje inre polygon.

**Returns:**
java.util.Iterator<int[]> - Enumeratören.
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


Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vertexElements | boolean | Optimera duplicerad vertex-elementdata |

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


Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vertexElements | boolean | Optimera duplicerad vertex-elementdata |
| toleranceControlPoint | float | Toleransen för kontrollpunkt, standardvärdet är 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vertexElements | boolean | Optimera duplicerad vertex-elementdata |
| toleranceControlPoint | float | Toleransen för kontrollpunkt, standardvärdet är 1e-9 |
| toleranceNormal | float | Toleransen för normal/tangent/binormal, standardvärdet är 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vertexElements | boolean | Optimera duplicerad vertex-elementdata |
| toleranceControlPoint | float | Toleransen för kontrollpunkt, standardvärdet är 1e-9 |
| toleranceNormal | float | Toleransen för normal/tangent/binormal, standardvärdet är 1e-9 |
| toleranceUV | float | Toleransen för uv, standardvärdet är 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Optimera mesh‑objektets minnesanvändning genom att eliminera duplicerade kontrollpunkter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vertexElements | boolean | Optimera duplicerad vertex-elementdata |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Tar bort en dynamisk egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Ta bort den angivna egenskapen identifierad med namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Ställer in om denna geometri kan kasta skugga

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ställer in om denna enhet ska exkluderas vid export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Ställer in den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nytt värde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ställer in värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |
| värde | java.lang.Object | Värdet på egenskapen |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Ställer in om denna geometri kan ta emot skugga.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Ställer in om geometrin är synlig

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Hämtar Mesh-instansen från den aktuella enheten.

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


Returnera triangulerad mesh

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


Beräkna unionen av två mesh

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | First mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Second mesh |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

