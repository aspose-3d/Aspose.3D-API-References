---
title: "Cylinder"
second_title: "Aspose.3D for Java API Referansı"
description: "Parametreli Silindir."
type: docs
weight: 40
url: /tr/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Parametreli Silindir. radiusTop/radiusBottom'dan biri sıfır olduğunda koniyi temsil etmek için de kullanılabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Cylinder()](#Cylinder--) | Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır. |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır. |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır. |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır. |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır. |
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
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | ThetaLength 2\*PI'dan küçük olduğunda fan tarzı silindir oluşturulup oluşturulmayacağını alır, aksi takdirde model kesilmez. |
| [getHeight()](#getHeight--) | Silindirin yüksekliğini alır. |
| [getHeightSegments()](#getHeightSegments--) | Yükseklik segmentlerini alır. |
| [getName()](#getName--) | Adı alır. |
| [getOffsetBottom()](#getOffsetBottom--) | Alt tarafın köşe dönüşüm ofsetini alır. |
| [getOffsetTop()](#getOffsetTop--) | Üst tarafın köşe dönüşüm ofsetini alır. |
| [getOpenEnded()](#getOpenEnded--) | Bu [Cylinder](../../com.aspose.threed/cylinder) açık uçlu olup olmadığını gösteren bir değer alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRadialSegments()](#getRadialSegments--) | Radyal segmentleri alır. |
| [getRadiusBottom()](#getRadiusBottom--) | Silindirin alt kapağının yarıçapını alır. |
| [getRadiusTop()](#getRadiusTop--) | Silindirin üst kapağının yarıçapını alır. |
| [getReceiveShadows()](#getReceiveShadows--) | Bu geometrinin gölge alıp almayacağını al. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getShearBottom()](#getShearBottom--) | Alt tarafın kayma dönüşümünü alır, vektör (x ekseni, z ekseni) kayma değerini radian cinsinden saklar, varsayılan değer (0, 0)'dır. |
| [getShearTop()](#getShearTop--) | Üst tarafın kayma dönüşümünü alır, vektör (x ekseni, z ekseni) kayma değerini radian cinsinden saklar, varsayılan değer (0, 0)'dır. |
| [getThetaLength()](#getThetaLength--) | Theta uzunluğunu alır. |
| [getThetaStart()](#getThetaStart--) | Theta başlangıcını alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Bu geometrinin gölge oluşturup oluşturamayacağını ayarlar |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | ThetaLength 2\*PI'den küçük olduğunda fan tarzı silindir oluşturulup oluşturulmayacağını ayarlar, aksi takdirde model kesilmez. |
| [setHeight(double value)](#setHeight-double-) | Silindirin yüksekliğini ayarlar. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Yükseklik segmentlerini ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | Alt tarafın köşe dönüşüm ofsetini ayarlar. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | Üst tarafın köşe dönüşüm ofsetini ayarlar. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | Bu [Cylinder](../../com.aspose.threed/cylinder) açık uçlu olup olmadığını gösteren bir değeri ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Radyal segmentleri ayarlar. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | Silindirin alt kapağının yarıçapını ayarlar. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | Silindirin üst kapağının yarıçapını ayarlar. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Bu geometrinin gölge alıp almayacağını ayarlar. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | Alt tarafın kayma dönüşümünü ayarlar, vektör (x ekseni, z ekseni) kayma değerini radian cinsinden saklar, varsayılan değer (0, 0)'dır. |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | Üst tarafın kayma dönüşümünü ayarlar, vektör (x ekseni, z ekseni) kayma değerini radian cinsinden saklar, varsayılan değer (0, 0)'dır. |
| [setThetaLength(double value)](#setThetaLength-double-) | Theta uzunluğunu ayarlar. |
| [setThetaStart(double value)](#setThetaStart-double-) | Theta başlangıcını ayarlar. |
| [toMesh()](#toMesh--) | Mevcut nesneyi mesh'e dönüştür. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır.

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yarıçap | double | Üst ve alt kapağın yarıçapı. |
| yükseklik | double | Yükseklik. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radiusTop | double | Üst yarıçap. |
| radiusBottom | double | Alt yarıçap. |
| yükseklik | double | Yükseklik. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radiusTop | double | Silindirin üst kapağının yarıçapı. |
| radiusBottom | double | Silindirin alt kapağının yarıçapı. |
| yükseklik | double | Silindirin yüksekliği. |
| radialSegments | int | Üst ve alt dairelerin radyal segmentleri.. |
| heightSegments | int | Yükseklik segmentleri. |
| openEnded | boolean | Eğer  true  olarak ayarlanırsa silindirin alt/üst kapakları olmaz.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Yeni bir [Cylinder](../../com.aspose.threed/cylinder) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Bu nesnenin adı |
| radiusTop | double | Silindirin üst kapağının yarıçapı. |
| radiusBottom | double | Silindirin alt kapağının yarıçapı. |
| yükseklik | double | Silindirin yüksekliği. |
| radialSegments | int | Üst ve alt dairelerin radyal segmentleri.. |
| heightSegments | int | Yükseklik segmentleri. |
| openEnded | boolean | Eğer  true  olarak ayarlanırsa silindirin alt/üst kapakları olmaz.. |
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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


ThetaLength 2\*PI'dan küçük olduğunda fan tarzı silindir oluşturulup oluşturulmayacağını alır, aksi takdirde model kesilmez.

**Returns:**
boolean - ThetaLength 2\*PI'den küçük olduğunda fan tarzı silindir oluşturulup oluşturulmayacağını, aksi takdirde model kesilmeyecek.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Silindirin yüksekliğini alır.

**Returns:**
double - silindirin yüksekliği.
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
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Alt tarafın köşe dönüşüm ofsetini alır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Üst tarafın köşe dönüşüm ofsetini alır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


Bu [Cylinder](../../com.aspose.threed/cylinder) açık uçlu olup olmadığını gösteren bir değer alır. Varsayılan değer false.

**Returns:**
boolean - bu [Cylinder](../../com.aspose.threed/cylinder) açık uçlu olup olmadığını gösteren bir değer. Varsayılan değer false.
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


Radyal segmentleri alır.

**Returns:**
int - radyal segmentler.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Silindirin alt kapağının yarıçapını alır.

**Returns:**
double - silindirin alt kapağının yarıçapı.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


Silindirin üst kapağının yarıçapını alır.

**Returns:**
double - silindirin üst kapağının yarıçapı.
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
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


Alt tarafın kayma dönüşümünü alır, vektör (x ekseni, z ekseni) kayma değerini radian cinsinden saklar, varsayılan değer (0, 0)'dır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


Üst tarafın kayma dönüşümünü alır, vektör (x ekseni, z ekseni) kayma değerini radian cinsinden saklar, varsayılan değer (0, 0)'dır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Theta uzunluğunu alır. Varsayılan değer 2\\u03c0.

**Returns:**
double - theta uzunluğu. Varsayılan değer 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Theta başlangıcını alır. Varsayılan değer 0.

**Returns:**
double - theta başlangıcı. Varsayılan değer 0.
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

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


ThetaLength 2\*PI'den küçük olduğunda fan tarzı silindir oluşturulup oluşturulmayacağını ayarlar, aksi takdirde model kesilmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Silindirin yüksekliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

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

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


Alt tarafın köşe dönüşüm ofsetini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


Üst tarafın köşe dönüşüm ofsetini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


Bu [Cylinder](../../com.aspose.threed/cylinder) açık uçlu olup olmadığını gösteren bir değer ayarlar. Varsayılan değer false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

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


Radyal segmentleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


Silindirin alt kapağının yarıçapını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


Silindirin üst kapağının yarıçapını ayarlar.

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

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


Alt tarafın kayma dönüşümünü ayarlar, vektör (x ekseni, z ekseni) kayma değerini radian cinsinden saklar, varsayılan değer (0, 0)'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


Üst tarafın kayma dönüşümünü ayarlar, vektör (x ekseni, z ekseni) kayma değerini radian cinsinden saklar, varsayılan değer (0, 0)'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Theta uzunluğunu ayarlar. Varsayılan değer 2\\u03c0.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Theta başlangıcını ayarlar. Varsayılan değer 0.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

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

