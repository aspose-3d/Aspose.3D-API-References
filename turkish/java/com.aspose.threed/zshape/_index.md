---
title: "ZShape"
second_title: "Aspose.3D for Java API Referansı"
description: "Parametrelerle tanımlanan, IFC uyumlu Z-şekilli profil."
type: docs
weight: 234
url: /tr/java/com.aspose.threed/zshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class ZShape extends ParameterizedProfile
```

Parametrelerle tanımlanan, IFC uyumlu Z-şekilli profil.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ZShape()](#ZShape--) | Yapıcı [ZShape](../../com.aspose.threed/zshape) |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getClass()](#getClass--) |  |
| [getDepth()](#getDepth--) | Web'in uzunluğunu alır. |
| [getEdgeRadius()](#getEdgeRadius--) | Flanş kenarının yarıçapını alır. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getExtent()](#getExtent--) | x ve y boyutundaki genişliği alır. |
| [getFilletRadius()](#getFilletRadius--) | Flanş ve web arasındaki yuvarlama yarıçapını alır. |
| [getFlangeThickness()](#getFlangeThickness--) | Flanş kalınlığını alır. |
| [getFlangeWidth()](#getFlangeWidth--) | Flanş uzunluğunu alır. |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getWebThickness()](#getWebThickness--) | Duvar kalınlığını alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setDepth(double value)](#setDepth-double-) | Web'in uzunluğunu ayarlar. |
| [setEdgeRadius(double value)](#setEdgeRadius-double-) | Flanş kenarının yarıçapını ayarlar. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setFilletRadius(double value)](#setFilletRadius-double-) | Flanş ve web arasındaki yuvarlama yarıçapını ayarlar. |
| [setFlangeThickness(double value)](#setFlangeThickness-double-) | Flanş kalınlığını ayarlar. |
| [setFlangeWidth(double value)](#setFlangeWidth-double-) | Flanş uzunluğunu ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setWebThickness(double value)](#setWebThickness-double-) | Duvar kalınlığını ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZShape() {#ZShape--}
```
public ZShape()
```


Yapıcı [ZShape](../../com.aspose.threed/zshape)

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
### getDepth() {#getDepth--}
```
public double getDepth()
```


Web'in uzunluğunu alır.

**Returns:**
double - web'in uzunluğu.
### getEdgeRadius() {#getEdgeRadius--}
```
public double getEdgeRadius()
```


Flanş kenarının yarıçapını alır.

**Returns:**
double - flanş kenarının yarıçapı.
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
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


x ve y boyutundaki genişliği alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### getFilletRadius() {#getFilletRadius--}
```
public double getFilletRadius()
```


Flanş ve web arasındaki yuvarlama yarıçapını alır.

**Returns:**
double - flanş ve web arasındaki yuvarlama yarıçapı.
### getFlangeThickness() {#getFlangeThickness--}
```
public double getFlangeThickness()
```


Flanş kalınlığını alır.

**Returns:**
double - flanş kalınlığı.
### getFlangeWidth() {#getFlangeWidth--}
```
public double getFlangeWidth()
```


Flanş uzunluğunu alır.

**Returns:**
double - flanş uzunluğu.
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
### getWebThickness() {#getWebThickness--}
```
public double getWebThickness()
```


Duvar kalınlığını alır.

**Returns:**
double - duvar kalınlığı.
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
### setDepth(double value) {#setDepth-double-}
```
public void setDepth(double value)
```


Web'in uzunluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setEdgeRadius(double value) {#setEdgeRadius-double-}
```
public void setEdgeRadius(double value)
```


Flanş kenarının yarıçapını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setFilletRadius(double value) {#setFilletRadius-double-}
```
public void setFilletRadius(double value)
```


Flanş ve web arasındaki yuvarlama yarıçapını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setFlangeThickness(double value) {#setFlangeThickness-double-}
```
public void setFlangeThickness(double value)
```


Flanş kalınlığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setFlangeWidth(double value) {#setFlangeWidth-double-}
```
public void setFlangeWidth(double value)
```


Flanş uzunluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

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

### setWebThickness(double value) {#setWebThickness-double-}
```
public void setWebThickness(double value)
```


Duvar kalınlığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

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

