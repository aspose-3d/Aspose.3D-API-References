---
title: "HollowRectangleShape"
second_title: "Aspose.3D for Java API Referansı"
description: "IFC uyumlu, iç ve dış yuvarlatılmış köşelere sahip boş dikdörtgen şekil."
type: docs
weight: 79
url: /tr/java/com.aspose.threed/hollowrectangleshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile), [com.aspose.threed.RectangleShape](../../com.aspose.threed/rectangleshape)
```
public class HollowRectangleShape extends RectangleShape
```

IFC uyumlu, iç ve dış yuvarlatılmış köşelere sahip boş dikdörtgen şekil.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HollowRectangleShape()](#HollowRectangleShape--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getExtent()](#getExtent--) | x ve y boyutundaki genişliği alır. |
| [getInnerFilletRadius()](#getInnerFilletRadius--) | İç dikdörtgenin iç yuvarlatma yarıçapı. |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRoundingRadius()](#getRoundingRadius--) | Tüm dört köşenin dairesel yaylarının yarıçapını derece cinsinden alır. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getWallThickness()](#getWallThickness--) | Dikdörtgenin sınırı ile iç delik arasındaki kalınlık |
| [getXDim()](#getXDim--) | Dikdörtgenin x ekseni yönündeki kapsamını alır. Varsayılan değer 2.0 |
| [getYDim()](#getYDim--) | Dikdörtgenin y ekseni yönündeki kapsamını alır. Varsayılan değer 2.0 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setInnerFilletRadius(double value)](#setInnerFilletRadius-double-) | İç dikdörtgenin iç yuvarlatma yarıçapı. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRoundingRadius(double value)](#setRoundingRadius-double-) | Tüm dört köşenin dairesel yaylarının yarıçapını derece cinsinden ayarlar. |
| [setWallThickness(double value)](#setWallThickness-double-) | Dikdörtgenin sınırı ile iç delik arasındaki kalınlık |
| [setXDim(double value)](#setXDim-double-) | Dikdörtgenin x ekseni yönündeki kapsamını ayarlar. Varsayılan değer 2.0 |
| [setYDim(double value)](#setYDim-double-) | Dikdörtgenin y ekseni yönündeki kapsamını ayarlar. Varsayılan değer 2.0 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HollowRectangleShape() {#HollowRectangleShape--}
```
public HollowRectangleShape()
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
### getInnerFilletRadius() {#getInnerFilletRadius--}
```
public double getInnerFilletRadius()
```


İç dikdörtgenin iç yuvarlatma yarıçapı.

**Returns:**
double - İç dikdörtgenin iç yuvarlatma yarıçapı.
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
### getRoundingRadius() {#getRoundingRadius--}
```
public double getRoundingRadius()
```


Tüm dört köşenin dairesel yaylarının yarıçapını derece cinsinden alır. Varsayılan değer 0.0

**Returns:**
double - tüm dört köşenin dairesel yaylarının yarıçapı, derece cinsinden. Varsayılan değer 0.0
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getWallThickness() {#getWallThickness--}
```
public double getWallThickness()
```


Dikdörtgenin sınırı ile iç delik arasındaki kalınlık

**Returns:**
double - Dikdörtgenin sınırı ile iç delik arasındaki kalınlık
### getXDim() {#getXDim--}
```
public double getXDim()
```


Dikdörtgenin x ekseni yönündeki kapsamını alır. Varsayılan değer 2.0

**Returns:**
double - dikdörtgenin x ekseni yönündeki kapsamı. Varsayılan değer 2.0
### getYDim() {#getYDim--}
```
public double getYDim()
```


Dikdörtgenin y ekseni yönündeki kapsamını alır. Varsayılan değer 2.0

**Returns:**
double - dikdörtgenin y ekseni yönündeki kapsamı. Varsayılan değer 2.0
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
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setInnerFilletRadius(double value) {#setInnerFilletRadius-double-}
```
public void setInnerFilletRadius(double value)
```


İç dikdörtgenin iç yuvarlatma yarıçapı.

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

### setRoundingRadius(double value) {#setRoundingRadius-double-}
```
public void setRoundingRadius(double value)
```


Tüm dört köşenin dairesel yaylarının yarıçapını derece cinsinden ayarlar. Varsayılan değer 0.0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setWallThickness(double value) {#setWallThickness-double-}
```
public void setWallThickness(double value)
```


Dikdörtgenin sınırı ile iç delik arasındaki kalınlık

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setXDim(double value) {#setXDim-double-}
```
public void setXDim(double value)
```


Dikdörtgenin x ekseni yönündeki kapsamını ayarlar. Varsayılan değer 2.0

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setYDim(double value) {#setYDim-double-}
```
public void setYDim(double value)
```


Dikdörtgenin y ekseni yönündeki kapsamını ayarlar. Varsayılan değer 2.0

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

