---
title: PointCloud
second_title: Aspose.3D for Java API-referens
description: Punktmolnet innehåller ingen topologiinformation utan endast kontrollpunkterna och vertex-elementen.
type: docs
weight: 132
url: /sv/java/com.aspose.threed/pointcloud/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)
```
public class PointCloud extends Geometry
```

Punktmolnet innehåller ingen topologiinformation utan endast kontrollpunkterna och vertex-elementen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PointCloud(String name)](#PointCloud-java.lang.String-) | Konstruktor för [PointCloud](../../com.aspose.threed/pointcloud) |
| [PointCloud()](#PointCloud--) | Konstruktor för [PointCloud](../../com.aspose.threed/pointcloud) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Hämtar alla deformers med angivna deformer-typer |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Lägger till ett befintligt vertex-element till aktuell geometri |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Skapar ett vertex-element med angiven typ och lägger till det i geometrin. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Skapar ett vertex-element med angiven typ och lägger till det i geometrin. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Skapar en [VertexElementUV](../../com.aspose.threed/vertexelementuv) med given texturkartläggningstyp. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Skapar en [VertexElementUV](../../com.aspose.threed/vertexelementuv) med given texturkartläggningstyp. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [fromGeometry(Geometry g)](#fromGeometry-com.aspose.threed.Geometry-) | Skapa en ny PointCloud-instans från ett geometriskt objekt |
| [fromGeometry(Geometry g, int density)](#fromGeometry-com.aspose.threed.Geometry-int-) | Skapa en ny punktmolnsinstans från ett geometriskt objekt. |
| [getBoundingBox()](#getBoundingBox--) | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| [getCastShadows()](#getCastShadows--) | Hämtar om denna geometri kan kasta skugga |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Hämtar alla kontrollpunkter |
| [getDeformers()](#getDeformers--) | Hämtar alla deformatorer som är associerade med denna geometri. |
| [getDimension()](#getDimension--) | Om ett dimensionsvärde finns för punktmolnet indikerar det ett organiserat punktmoln. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Hämtar ett vertex‑element med angiven typ |
| [getEntityRendererKey()](#getEntityRendererKey--) | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
| [getExcluded()](#getExcluded--) | Hämtar om denna enhet ska exkluderas vid export. |
| [getName()](#getName--) | Hämtar namnet. |
| [getParentNode()](#getParentNode--) | Hämtar den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [getParentNodes()](#getParentNodes--) | Hämtar alla föräldranoder, en enhet kan fästas vid flera föräldranoder för geometrisk instansering |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getReceiveShadows()](#getReceiveShadows--) | Hämtar om denna geometri kan ta emot skugga. |
| [getScene()](#getScene--) | Hämtar scenen som detta objekt tillhör |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Hämtar en [VertexElementUV](../../com.aspose.threed/vertexelementuv)-instans med given texturkartläggningstyp |
| [getVertexElements()](#getVertexElements--) | Hämtar alla vertex‑element |
| [getVisible()](#getVisible--) | Hämtar om geometrin är synlig |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ställer in om denna geometri kan kasta skugga |
| [setDimension(Vector2 value)](#setDimension-com.aspose.threed.Vector2-) | Om ett dimensionsvärde finns för punktmolnet indikerar det ett organiserat punktmoln. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ställer in om denna enhet ska exkluderas vid export. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ställer in den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Ställer in om denna geometri kan ta emot skugga. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ställer in om geometrin är synlig |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointCloud(String name) {#PointCloud-java.lang.String-}
```
public PointCloud(String name)
```


Konstruktor för [PointCloud](../../com.aspose.threed/pointcloud)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namnet på denna entitet |

### PointCloud() {#PointCloud--}
```
public PointCloud()
```


Konstruktor för [PointCloud](../../com.aspose.threed/pointcloud)

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Hämtar alla deformers med angivna deformer-typer

**Returns:**
java.util.Collection<T> - Deformer-samling
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Lägger till ett befintligt vertex-element till aktuell geometri

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Vertex-elementet att lägga till |

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
### fromGeometry(Geometry g) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static PointCloud fromGeometry(Geometry g)
```


Skapa en ny PointCloud-instans från ett geometriskt objekt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Geometry](../../com.aspose.threed/geometry) |  |

**Returns:**
[PointCloud](../../com.aspose.threed/pointcloud)
### fromGeometry(Geometry g, int density) {#fromGeometry-com.aspose.threed.Geometry-int-}
```
public static PointCloud fromGeometry(Geometry g, int density)
```


Skapa en ny punktmolnsinstans från ett geometriskt objekt. Densitet är antalet punkter per enhetstriangel (Enhetstriangel är den triangel med maximal yta från nätet)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g | [Geometry](../../com.aspose.threed/geometry) | Mesh eller annan geometrisk instans |
| densitet | int | Antal punkter per enhetstriangel |

**Returns:**
[PointCloud](../../com.aspose.threed/pointcloud)
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
### getDimension() {#getDimension--}
```
public Vector2 getDimension()
```


Om ett dimensionsvärde finns för punktmolnet indikerar det ett organiserat punktmoln. Utan en specificerad storlek betraktas det som ett oorganiserat punktmoln. Ett organiserat punktmoln betyder att det har en bildliknande struktur.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - If a dimension value is present for the point cloud, it indicates an organized point cloud. Without a specified size, it is considered an unorganized point cloud. Organized point cloud means it has an image-like structure.
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
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
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

### setDimension(Vector2 value) {#setDimension-com.aspose.threed.Vector2-}
```
public void setDimension(Vector2 value)
```


Om ett dimensionsvärde finns för punktmolnet indikerar det ett organiserat punktmoln. Utan en specificerad storlek betraktas det som ett oorganiserat punktmoln. Ett organiserat punktmoln betyder att det har en bildliknande struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

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

