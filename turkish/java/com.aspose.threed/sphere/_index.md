---
title: "Sphere"
second_title: "Aspose.3D for Java API Referansı"
description: "Parametreli küre."
type: docs
weight: 174
url: /tr/java/com.aspose.threed/sphere/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Sphere extends Primitive
```

Parametreli küre.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Sphere()](#Sphere--) | Varsayılan yarıçap 1 ile yeni bir [Sphere](../../com.aspose.threed/sphere) örneği başlatır. |
| [Sphere(double radius)](#Sphere-double-) | Belirtilen yarıçap ile yeni bir [Sphere](../../com.aspose.threed/sphere) sınıfı örneği başlatır. |
| [Sphere(double radius, int widthSegments, int heightSegments)](#Sphere-double-int-int-) | Belirtilen yarıçap, genişlik segmentleri ve yükseklik segmentleri ile yeni bir [Sphere](../../com.aspose.threed/sphere) sınıfı örneği başlatır. |
| [Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength)](#Sphere-java.lang.String-double-int-int-double-double-double-double-) | Yeni bir [Sphere](../../com.aspose.threed/sphere) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getCastShadows()](#getCastShadows--) | Bu geometrinin gölge oluşturup oluşturamayacağını alır |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getHeightSegments()](#getHeightSegments--) | Yükseklik segmentlerini alır. |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getPhiLength()](#getPhiLength--) | Phi uzunluğunu alır. |
| [getPhiStart()](#getPhiStart--) | Phi başlangıcını alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRadius()](#getRadius--) | Kürenin yarıçapını alır. |
| [getReceiveShadows()](#getReceiveShadows--) | Bu geometrinin gölge alıp almayacağını al. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getThetaLength()](#getThetaLength--) | Theta uzunluğunu alır. |
| [getThetaStart()](#getThetaStart--) | Theta başlangıcını alır. |
| [getWidthSegments()](#getWidthSegments--) | Genişlik segmentlerini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Bu geometrinin gölge oluşturup oluşturamayacağını ayarlar |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Yükseklik segmentlerini ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setPhiLength(double value)](#setPhiLength-double-) | Phi uzunluğunu ayarlar. |
| [setPhiStart(double value)](#setPhiStart-double-) | Phi başlangıcını ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRadius(double value)](#setRadius-double-) | Kürenin yarıçapını ayarlar. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Bu geometrinin gölge alıp almayacağını ayarlar. |
| [setThetaLength(double value)](#setThetaLength-double-) | Theta uzunluğunu ayarlar. |
| [setThetaStart(double value)](#setThetaStart-double-) | Theta başlangıcını ayarlar. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | Genişlik segmentlerini ayarlar. |
| [toMesh()](#toMesh--) | Mevcut nesneyi mesh'e dönüştür. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Sphere() {#Sphere--}
```
public Sphere()
```


Varsayılan yarıçap 1 ile yeni bir [Sphere](../../com.aspose.threed/sphere) örneği başlatır.

### Sphere(double radius) {#Sphere-double-}
```
public Sphere(double radius)
```


Belirtilen yarıçap ile yeni bir [Sphere](../../com.aspose.threed/sphere) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yarıçap | double | Yarıçap. |

### Sphere(double radius, int widthSegments, int heightSegments) {#Sphere-double-int-int-}
```
public Sphere(double radius, int widthSegments, int heightSegments)
```


Belirtilen yarıçap, genişlik segmentleri ve yükseklik segmentleri ile yeni bir [Sphere](../../com.aspose.threed/sphere) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yarıçap | double | Kürenin yarıçapı. |
| widthSegments | int | Genişlik segmentleri. |
| heightSegments | int | Yükseklik segmentleri. |

### Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength) {#Sphere-java.lang.String-double-int-int-double-double-double-double-}
```
public Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength)
```


Yeni bir [Sphere](../../com.aspose.threed/sphere) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |
| yarıçap | double | Kürenin yarıçapı. |
| widthSegments | int | Genişlik segmentleri. |
| heightSegments | int | Yükseklik segmentleri. |
| phiStart | double | Phi başlangıcı. |
| phiLength | double | Phi uzunluğu. |
| thetaStart | double | Theta başlangıcı. |
| thetaLength | double | Theta uzunluğu. |

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
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Yükseklik segmentlerini alır.

**Returns:**
int - yükseklik segmentleri.
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
### getPhiLength() {#getPhiLength--}
```
public double getPhiLength()
```


Phi uzunluğunu alır.

**Returns:**
double - phi uzunluğu.
### getPhiStart() {#getPhiStart--}
```
public double getPhiStart()
```


Phi başlangıcını alır.

**Returns:**
double - phi başlangıcı.
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
### getRadius() {#getRadius--}
```
public double getRadius()
```


Kürenin yarıçapını alır.

**Returns:**
double - kürenin yarıçapı.
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
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Theta uzunluğunu alır.

**Returns:**
double - theta uzunluğu.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Theta başlangıcını alır.

**Returns:**
double - theta başlangıcı.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


Genişlik segmentlerini alır.

**Returns:**
int - genişlik segmentleri.
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

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Yükseklik segmentlerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

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

### setPhiLength(double value) {#setPhiLength-double-}
```
public void setPhiLength(double value)
```


Phi uzunluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setPhiStart(double value) {#setPhiStart-double-}
```
public void setPhiStart(double value)
```


Phi başlangıcını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

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

### setRadius(double value) {#setRadius-double-}
```
public void setRadius(double value)
```


Kürenin yarıçapını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Bu geometrinin gölge alıp almayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Theta uzunluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Theta başlangıcını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


Genişlik segmentlerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

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

