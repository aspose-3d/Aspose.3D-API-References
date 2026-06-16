---
title: "RectangularTorus"
second_title: "Aspose.3D for Java API Referansı"
description: "Parametreli dikdörtgen torus."
type: docs
weight: 146
url: /tr/java/com.aspose.threed/rectangulartorus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class RectangularTorus extends Primitive
```

Parametreli dikdörtgen torus.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RectangularTorus()](#RectangularTorus--) | Yapıcı [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
| [RectangularTorus(String name)](#RectangularTorus-java.lang.String-) | Yapıcı [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getAngleStart()](#getAngleStart--) | Yayının başlangıç açısı, radyan cinsinden ölçülür. |
| [getArc()](#getArc--) | Yayının toplam açısı, radyan cinsinden ölçülür. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getCastShadows()](#getCastShadows--) | Bu geometrinin gölge oluşturup oluşturamayacağını alır |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getHeight()](#getHeight--) | Dikdörtgen torusun yüksekliği. |
| [getInnerRadius()](#getInnerRadius--) | Dikdörtgen torusun iç yarıçapı, varsayılan değer 17'dir. |
| [getName()](#getName--) | Adı alır. |
| [getOuterRadius()](#getOuterRadius--) | Dikdörtgen torusun dış yarıçapı, varsayılan değer 20'dir. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRadialSegments()](#getRadialSegments--) | Radyal segmentler, varsayılan değer 10'dur. |
| [getReceiveShadows()](#getReceiveShadows--) | Bu geometrinin gölge alıp almayacağını al. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setAngleStart(double value)](#setAngleStart-double-) | Yayının başlangıç açısı, radyan cinsinden ölçülür. |
| [setArc(double value)](#setArc-double-) | Yayının toplam açısı, radyan cinsinden ölçülür. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Bu geometrinin gölge oluşturup oluşturamayacağını ayarlar |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setHeight(double value)](#setHeight-double-) | Dikdörtgen torusun yüksekliği. |
| [setInnerRadius(double value)](#setInnerRadius-double-) | Dikdörtgen torusun iç yarıçapı, varsayılan değer 17'dir. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setOuterRadius(double value)](#setOuterRadius-double-) | Dikdörtgen torusun dış yarıçapı, varsayılan değer 20'dir. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Radyal segmentler, varsayılan değer 10'dur. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Bu geometrinin gölge alıp almayacağını ayarlar. |
| [toMesh()](#toMesh--) | Bu ilkel nesneyi [Mesh](../../com.aspose.threed/mesh) formatına dönüştür. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangularTorus() {#RectangularTorus--}
```
public RectangularTorus()
```


Yapıcı [RectangularTorus](../../com.aspose.threed/rectangulartorus)

### RectangularTorus(String name) {#RectangularTorus-java.lang.String-}
```
public RectangularTorus(String name)
```


Yapıcı [RectangularTorus](../../com.aspose.threed/rectangulartorus)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

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
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


Yayının başlangıç açısı, radyan cinsinden ölçülür. Varsayılan değer 0'dır.

**Returns:**
double - Yayın başlangıç açısı, radyan cinsinden ölçülür. Varsayılan değer 0'dır.
### getArc() {#getArc--}
```
public double getArc()
```


Yayın toplam açısı, radyan cinsinden ölçülür. Varsayılan değer PI'dir.

**Returns:**
double - Yayın toplam açısı, radyan cinsinden ölçülür. Varsayılan değer PI'dir.
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Dikdörtgen torusun yüksekliği. Varsayılan değer 20'dir.

**Returns:**
double - Dikdörtgen torusun yüksekliği. Varsayılan değer 20'dir.
### getInnerRadius() {#getInnerRadius--}
```
public double getInnerRadius()
```


Dikdörtgen torusun iç yarıçapı, varsayılan değer 17'dir.

**Returns:**
double - Dikdörtgen torusun iç yarıçapı Varsayılan değer 17'dir.
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getOuterRadius() {#getOuterRadius--}
```
public double getOuterRadius()
```


Dikdörtgen torusun dış yarıçapı, varsayılan değer 20'dir.

**Returns:**
double - Dikdörtgen torusun dış yarıçapı Varsayılan değer 20'dir.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Radyal segmentler, varsayılan değer 10'dur.

**Returns:**
int - Radyal segmentler, varsayılan değer 10'dur.
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
### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


Yayının başlangıç açısı, radyan cinsinden ölçülür. Varsayılan değer 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


Yayın toplam açısı, radyan cinsinden ölçülür. Varsayılan değer PI'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Dikdörtgen torusun yüksekliği. Varsayılan değer 20'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setInnerRadius(double value) {#setInnerRadius-double-}
```
public void setInnerRadius(double value)
```


Dikdörtgen torusun iç yarıçapı, varsayılan değer 17'dir.

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

### setOuterRadius(double value) {#setOuterRadius-double-}
```
public void setOuterRadius(double value)
```


Dikdörtgen torusun dış yarıçapı, varsayılan değer 20'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Radyal segmentler, varsayılan değer 10'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Bu geometrinin gölge alıp almayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Bu ilkel nesneyi [Mesh](../../com.aspose.threed/mesh) formatına dönüştür.

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

