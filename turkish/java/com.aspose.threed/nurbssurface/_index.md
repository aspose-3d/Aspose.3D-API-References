---
title: "NurbsSurface"
second_title: "Aspose.3D for Java API Referansı"
description: "NURBS (Non-uniform rational basis spline) tarafından temsil edilen bir yüzeydir  A  iki  ve  tarafından tanımlanır."
type: docs
weight: 114
url: /tr/java/com.aspose.threed/nurbssurface/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class NurbsSurface extends Geometry implements IMeshConvertible
```

[NurbsSurface](../../com.aspose.threed/nurbssurface) is a surface represented by [NURBS(Non-uniform rational basis spline)][NURBS_Non-uniform rational basis spline], A [NurbsSurface](../../com.aspose.threed/nurbssurface) is defined by two [NurbsDirection](../../com.aspose.threed/nurbsdirection)[getU](../../com.aspose.threed/nurbssurface\#getU) and [getV](../../com.aspose.threed/nurbssurface\#getV). The w component in control point is used as control point's weight whatever the direction's type is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS_Non-uniform rational basis spline]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NurbsSurface()](#NurbsSurface--) | [NurbsSurface](../../com.aspose.threed/nurbssurface) sınıfının yeni bir örneğini başlatır. |
| [NurbsSurface(String name)](#NurbsSurface-java.lang.String-) | [NurbsSurface](../../com.aspose.threed/nurbssurface) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Belirtilen deformer türleriyle tüm deformörleri alır. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Mevcut geometriye mevcut bir vertex öğesi ekler |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Belirtilen tipte bir vertex öğesi oluşturur ve geometriye ekler |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Belirtilen tipte bir vertex öğesi oluşturur ve geometriye ekler |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) oluşturur. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getCastShadows()](#getCastShadows--) | Bu geometrinin gölge oluşturup oluşturamayacağını alır |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Tüm kontrol noktalarını al |
| [getDeformers()](#getDeformers--) | Bu geometriyle ilişkili tüm deformasyonları al. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Belirtilen türde bir köşe öğesini al |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getReceiveShadows()](#getReceiveShadows--) | Bu geometrinin gölge alıp almayacağını al. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getU()](#getU--) | NURBS yüzeyinin U yönünü alır |
| [getV()](#getV--) | NURBS yüzeyinin V yönünü alır |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) örneği al |
| [getVertexElements()](#getVertexElements--) | Tüm köşe öğelerini al |
| [getVisible()](#getVisible--) | Geometrinin görünür olup olmadığını al |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Bu geometrinin gölge oluşturup oluşturamayacağını ayarlar |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Bu geometrinin gölge alıp almayacağını ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Geometrinin görünür olup olmadığını ayarlar |
| [toMesh()](#toMesh--) | NURBS yüzeyini örgüye dönüştür |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsSurface() {#NurbsSurface--}
```
public NurbsSurface()
```


[NurbsSurface](../../com.aspose.threed/nurbssurface) sınıfının yeni bir örneğini başlatır.

### NurbsSurface(String name) {#NurbsSurface-java.lang.String-}
```
public NurbsSurface(String name)
```


[NurbsSurface](../../com.aspose.threed/nurbssurface) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Belirtilen deformer türleriyle tüm deformörleri alır.

**Returns:**
java.util.Collection<T> - Deformer koleksiyonu
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Mevcut geometriye mevcut bir vertex öğesi ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Eklenecek köşe öğesi |

### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Belirtilen tipte bir vertex öğesi oluşturur ve geometriye ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Köşe öğesi türü |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Belirtilen tipte bir vertex öğesi oluşturur ve geometriye ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Köşe öğesi türü |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Varsayılan eşleme modu |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Varsayılan referans modu |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Oluşturulacak doku eşleme türü |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Oluşturulacak doku eşleme türü |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Varsayılan eşleme modu |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Varsayılan referans modu |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty) veya native property(Identified by its name) olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyName | java.lang.String | Özellik adı. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır.

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


Bu geometrinin gölge oluşturup oluşturamayacağını alır

**Returns:**
boolean - bu geometrinin gölge oluşturup oluşturamayacağı
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


Tüm kontrol noktalarını al

**Returns:**
java.util.List<com.aspose.threed.Vector4> - tüm kontrol noktaları
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Bu geometriyle ilişkili tüm deformasyonları al.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - bu geometriyle ilişkili tüm deformasyonlar.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Belirtilen türde bir köşe öğesini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | hangi köşe öğesi türünün bulunacağı |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır

**Returns:**
boolean - bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağı.
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - tüm üst düğümler, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Tüm özelliklerin koleksiyonunu alır.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Belirtilen özelliğin değerini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |

**Returns:**
java.lang.Object - Bulunan özelliğin değeri
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Bu geometrinin gölge alıp almayacağını al.

**Returns:**
boolean - bu geometrinin gölge alıp almayacağını.
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getU() {#getU--}
```
public NurbsDirection getU()
```


NURBS yüzeyinin U yönünü alır

**Returns:**
[NurbsDirection](../../com.aspose.threed/nurbsdirection) - the NURBS surface's U direction
### getV() {#getV--}
```
public NurbsDirection getV()
```


NURBS yüzeyinin V yönünü alır

**Returns:**
[NurbsDirection](../../com.aspose.threed/nurbsdirection) - the NURBS surface's V direction
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) örneği al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Tüm köşe öğelerini al

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - tüm köşe öğeleri
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Geometrinin görünür olup olmadığını al

**Returns:**
boolean - geometrinin görünür olup olmadığı
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


Dinamik bir özelliği kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


İsimle tanımlanan belirtilen özelliği kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Bu geometrinin gölge oluşturup oluşturamayacağını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Yeni değer |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Belirtilen özelliğin değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |
| değer | java.lang.Object | Özelliğin değeri |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Bu geometrinin gölge alıp almayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Geometrinin görünür olup olmadığını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


NURBS yüzeyini örgüye dönüştür

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

