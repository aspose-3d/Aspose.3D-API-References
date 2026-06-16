---
title: "PointCloud"
second_title: "Aspose.3D for Java API Referansı"
description: "Nokta bulutu topoloji bilgisi içermez, yalnızca kontrol noktalarını ve köşe öğelerini içerir."
type: docs
weight: 132
url: /tr/java/com.aspose.threed/pointcloud/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)
```
public class PointCloud extends Geometry
```

Nokta bulutu topoloji bilgisi içermez, yalnızca kontrol noktalarını ve köşe öğelerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PointCloud(String name)](#PointCloud-java.lang.String-) | Yapıcı [PointCloud](../../com.aspose.threed/pointcloud) |
| [PointCloud()](#PointCloud--) | Yapıcı [PointCloud](../../com.aspose.threed/pointcloud) |
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
| [fromGeometry(Geometry g)](#fromGeometry-com.aspose.threed.Geometry-) | Yeni bir PointCloud örneğini bir geometri nesnesinden oluştur |
| [fromGeometry(Geometry g, int density)](#fromGeometry-com.aspose.threed.Geometry-int-) | Yeni bir point cloud örneğini bir geometri nesnesinden oluştur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getCastShadows()](#getCastShadows--) | Bu geometrinin gölge oluşturup oluşturamayacağını alır |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Tüm kontrol noktalarını al |
| [getDeformers()](#getDeformers--) | Bu geometriyle ilişkili tüm deformasyonları al. |
| [getDimension()](#getDimension--) | Eğer point cloud için bir boyut değeri mevcutsa, bu düzenli bir point cloud olduğunu gösterir. |
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
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) örneği al |
| [getVertexElements()](#getVertexElements--) | Tüm köşe öğelerini al |
| [getVisible()](#getVisible--) | Geometrinin görünür olup olmadığını al |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Bu geometrinin gölge oluşturup oluşturamayacağını ayarlar |
| [setDimension(Vector2 value)](#setDimension-com.aspose.threed.Vector2-) | Eğer point cloud için bir boyut değeri mevcutsa, bu düzenli bir point cloud olduğunu gösterir. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Bu geometrinin gölge alıp almayacağını ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Geometrinin görünür olup olmadığını ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointCloud(String name) {#PointCloud-java.lang.String-}
```
public PointCloud(String name)
```


Yapıcı [PointCloud](../../com.aspose.threed/pointcloud)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Bu varlığın adı |

### PointCloud() {#PointCloud--}
```
public PointCloud()
```


Yapıcı [PointCloud](../../com.aspose.threed/pointcloud)

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
### fromGeometry(Geometry g) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static PointCloud fromGeometry(Geometry g)
```


Yeni bir PointCloud örneğini bir geometri nesnesinden oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g | [Geometry](../../com.aspose.threed/geometry) |  |

**Returns:**
[PointCloud](../../com.aspose.threed/pointcloud)
### fromGeometry(Geometry g, int density) {#fromGeometry-com.aspose.threed.Geometry-int-}
```
public static PointCloud fromGeometry(Geometry g, int density)
```


Yeni bir point cloud örneğini bir geometri nesnesinden oluştur. Yoğunluk, bir birim üçgen başına düşen nokta sayısıdır (Birim üçgen, ağın en büyük yüzey alanına sahip üçgendir).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g | [Geometry](../../com.aspose.threed/geometry) | Mesh veya diğer geometri örneği |
| yoğunluk | int | Bir birim üçgen başına düşen nokta sayısı |

**Returns:**
[PointCloud](../../com.aspose.threed/pointcloud)
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
### getDimension() {#getDimension--}
```
public Vector2 getDimension()
```


Eğer point cloud için bir boyut değeri mevcutsa, bu düzenli bir point cloud olduğunu gösterir. Belirtilen bir boyut olmadan, bu düzenlenmemiş bir point cloud olarak kabul edilir. Düzenli point cloud, görüntü benzeri bir yapıya sahip olduğu anlamına gelir.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - If a dimension value is present for the point cloud, it indicates an organized point cloud. Without a specified size, it is considered an unorganized point cloud. Organized point cloud means it has an image-like structure.
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
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
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

### setDimension(Vector2 value) {#setDimension-com.aspose.threed.Vector2-}
```
public void setDimension(Vector2 value)
```


Eğer point cloud için bir boyut değeri mevcutsa, bu düzenli bir point cloud olduğunu gösterir. Belirtilen bir boyut olmadan, bu düzenlenmemiş bir point cloud olarak kabul edilir. Düzenli point cloud, görüntü benzeri bir yapıya sahip olduğu anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

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

