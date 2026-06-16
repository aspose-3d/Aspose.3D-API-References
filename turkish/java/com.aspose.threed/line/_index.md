---
title: "Çizgi"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir çoklu çizgi, bir dizi nokta ile tanımlanır ve   ile bağlanır, bu da aynı zamanda bağlı çizgi segmentlerinden oluşan bir set olabileceği anlamına gelir."
type: docs
weight: 95
url: /tr/java/com.aspose.threed/line/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class Line extends Curve
```

Bir çoklu çizgi, bir dizi nokta ile [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) kullanılarak tanımlanan ve [getSegments](../../com.aspose.threed/line\#getSegments) ile bağlanan bir yoldur, bu da aynı zamanda bağlı çizgi segmentlerinden oluşan bir set olabileceği anlamına gelir. Çizgi genellikle doğrusal bir nesnedir, bu da bir eğriyi temsil etmek için kullanılamayacağı anlamına gelir; bir eğriyi temsil etmek için [NurbsCurve](../../com.aspose.threed/nurbscurve) kullanılır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Line()](#Line--) | Yeni bir [Line](../../com.aspose.threed/line) sınıfı örneği başlatır. |
| [Line(String name)](#Line-java.lang.String-) | Yeni bir [Line](../../com.aspose.threed/line) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [fromPoints(Vector3[] points)](#fromPoints-com.aspose.threed.Vector3...-) | Bir dizi noktadan bir [Line](../../com.aspose.threed/line) örneği oluştur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Çizginin rengini alır, varsayılan değer beyaz(1, 1, 1)'dir |
| [getControlPoints()](#getControlPoints--) | Tüm kontrol noktalarını al |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getSegments()](#getSegments--) | Çizginin segmentlerini alır |
| [getVisible()](#getVisible--) | Geometrinin görünür olup olmadığını al |
| [hashCode()](#hashCode--) |  |
| [makeDefaultIndices()](#makeDefaultIndices--) | ControlPoints'in tek bir çizgi olarak kullanılabilmesi için 0,1,2,3....[Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints).Length-1 dizisini [getSegments](../../com.aspose.threed/line\#getSegments) ile oluştur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Çizginin rengini ayarlar, varsayılan değer beyaz(1, 1, 1)'dir |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setVisible(boolean value)](#setVisible-boolean-) | Geometrinin görünür olup olmadığını ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Line() {#Line--}
```
public Line()
```


Yeni bir [Line](../../com.aspose.threed/line) sınıfı örneği başlatır.

### Line(String name) {#Line-java.lang.String-}
```
public Line(String name)
```


Yeni bir [Line](../../com.aspose.threed/line) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

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
### fromPoints(Vector3[] points) {#fromPoints-com.aspose.threed.Vector3...-}
```
public static Line fromPoints(Vector3[] points)
```


Bir dizi noktadan bir [Line](../../com.aspose.threed/line) örneği oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Line](../../com.aspose.threed/line)
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


Çizginin rengini alır, varsayılan değer beyaz(1, 1, 1)'dir

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Tüm kontrol noktalarını al

**Returns:**
java.util.List<com.aspose.threed.Vector4> - tüm kontrol noktaları
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSegments() {#getSegments--}
```
public List<int[]> getSegments()
```


Çizginin segmentlerini alır

**Returns:**
java.util.List<int[]> - çizginin segmentleri
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
### makeDefaultIndices() {#makeDefaultIndices--}
```
public void makeDefaultIndices()
```


ControlPoints'in tek bir çizgi olarak kullanılabilmesi için 0,1,2,3....[Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints).Length-1 dizisini [getSegments](../../com.aspose.threed/line\#getSegments) ile oluştur.

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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Çizginin rengini ayarlar, varsayılan değer beyaz(1, 1, 1)'dir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

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

