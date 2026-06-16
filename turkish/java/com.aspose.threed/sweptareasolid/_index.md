---
title: "SweptAreaSolid"
second_title: "Aspose.3D for Java API Referansı"
description: "A  bir profil'i bir directrix boyunca süpürerek bir geometri oluşturur."
type: docs
weight: 181
url: /tr/java/com.aspose.threed/sweptareasolid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class SweptAreaSolid extends Entity implements IMeshConvertible
```

A [SweptAreaSolid](../../com.aspose.threed/sweptareasolid) bir profil'i bir directrix boyunca süpürerek bir geometri oluşturur. **Example:** Aşağıdaki kod, bir C-şeklini bir daire üzerinde süpürerek katı bir varlık modellemenin nasıl yapılacağını gösterir.

```
var directrix = new Circle(20);
         var shape = new CShape();
 
         var swept = new SweptAreaSolid();
         swept.setShape(shape);
         swept.setDirectrix(directrix);
         swept.setStartPoint(EndPoint.fromDegree(0));
         swept.setEndPoint(EndPoint.fromDegree(130));
 
         var scene = new Scene();
         scene.getRootNode().createChildNode(swept);
         scene.save("swept.obj");
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SweptAreaSolid()](#SweptAreaSolid--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getClass()](#getClass--) |  |
| [getDirectrix()](#getDirectrix--) | Süpürülen alanın süpürülerek ilerlediği directrix. |
| [getEndPoint()](#getEndPoint--) | Directrix'in son noktası. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getShape()](#getShape--) | Geometriyi oluşturmak için temel profil. |
| [getStartPoint()](#getStartPoint--) | Directrix'in başlangıç noktası. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setDirectrix(Curve value)](#setDirectrix-com.aspose.threed.Curve-) | Süpürülen alanın süpürülerek ilerlediği directrix. |
| [setEndPoint(EndPoint value)](#setEndPoint-com.aspose.threed.EndPoint-) | Directrix'in son noktası. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | Geometriyi oluşturmak için temel profil. |
| [setStartPoint(EndPoint value)](#setStartPoint-com.aspose.threed.EndPoint-) | Directrix'in başlangıç noktası. |
| [toMesh()](#toMesh--) | Mevcut nesneyi mesh'e dönüştür. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SweptAreaSolid() {#SweptAreaSolid--}
```
public SweptAreaSolid()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirectrix() {#getDirectrix--}
```
public Curve getDirectrix()
```


Süpürülen alanın süpürülerek ilerlediği directrix.

**Returns:**
[Curve](../../com.aspose.threed/curve) - The directrix that the swept area sweeping along with.
### getEndPoint() {#getEndPoint--}
```
public EndPoint getEndPoint()
```


Directrix'in son noktası.

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - The end point of the directrix.
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShape() {#getShape--}
```
public Profile getShape()
```


Geometriyi oluşturmak için temel profil.

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base profile to construct the geometry.
### getStartPoint() {#getStartPoint--}
```
public EndPoint getStartPoint()
```


Directrix'in başlangıç noktası.

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - The start point of the directrix.
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
### setDirectrix(Curve value) {#setDirectrix-com.aspose.threed.Curve-}
```
public void setDirectrix(Curve value)
```


Süpürülen alanın süpürülerek ilerlediği directrix.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Curve](../../com.aspose.threed/curve) | Yeni değer |

### setEndPoint(EndPoint value) {#setEndPoint-com.aspose.threed.EndPoint-}
```
public void setEndPoint(EndPoint value)
```


Directrix'in son noktası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EndPoint](../../com.aspose.threed/endpoint) | Yeni değer |

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


Geometriyi oluşturmak için temel profil.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | Yeni değer |

### setStartPoint(EndPoint value) {#setStartPoint-com.aspose.threed.EndPoint-}
```
public void setStartPoint(EndPoint value)
```


Directrix'in başlangıç noktası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EndPoint](../../com.aspose.threed/endpoint) | Yeni değer |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Mevcut nesneyi mesh'e dönüştür.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

