---
title: "Kamera"
second_title: "Aspose.3D for Java API Referansı"
description: "Kamera, sahneyi izleyen izleyicinin göz noktasını tanımlar."
type: docs
weight: 28
url: /tr/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

Kamera, sahneyi izleyen izleyicinin göz noktasını tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Camera()](#Camera--) | Yeni bir [Camera](../../com.aspose.threed/camera) sınıfı örneği başlatır. |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | Yeni bir [Camera](../../com.aspose.threed/camera) sınıfı örneği başlatır. |
| [Camera(String name)](#Camera-java.lang.String-) | Yeni bir [Camera](../../com.aspose.threed/camera) sınıfı örneği başlatır. |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | Yeni bir [Camera](../../com.aspose.threed/camera) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getApertureMode()](#getApertureMode--) | Kameranın diyafram modunu alır |
| [getAspect()](#getAspect--) | Frustum'un en-boy oranını alır |
| [getAspectRatio()](#getAspectRatio--) | Görünüm düzleminin en-boy oranını alır. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Kameranın baktığı yönü alır. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getFarPlane()](#getFarPlane--) | Frustum'un uzak düzlem mesafesini alır. |
| [getFieldOfView()](#getFieldOfView--) | Kameranın görüş alanını derece cinsinden alır, bu özellik yalnızca ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) veya [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) olduğunda kullanılır. |
| [getFieldOfViewX()](#getFieldOfViewX--) | Kameranın yatay görüş alanını derece cinsinden alır, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır. |
| [getFieldOfViewY()](#getFieldOfViewY--) | Kameranın dikey görüş alanını derece cinsinden alır, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır. |
| [getHeight()](#getHeight--) | Görünüm düzleminin yüksekliğini inç cinsinden alır |
| [getLookAt()](#getLookAt--) | Kameranın baktığı ilgili konumu alır. |
| [getMagnification()](#getMagnification--) | Ortografik kamerada kullanılan büyütmeyi alır |
| [getName()](#getName--) | Adı alır. |
| [getNearPlane()](#getNearPlane--) | Frustum'un yakın düzlem mesafesini alır. |
| [getOrthoHeight()](#getOrthoHeight--) | Frustum ortografik projeksiyonda iken yüksekliği alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProjectionType()](#getProjectionType--) | Kameranın projeksiyon tipini alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRotationMode()](#getRotationMode--) | Frustum'un yönelim modunu alır. Bu özellik yalnızca [getTarget](../../com.aspose.threed/frustum\#getTarget) null olduğunda çalışır. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getTarget()](#getTarget--) | Kameranın baktığı hedefi alır. |
| [getUp()](#getUp--) | Kameranın yukarı yönünü alır. |
| [getWidth()](#getWidth--) | Görünüm düzleminin genişliğini inç cinsinden alır |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | Kamerayı yönüne ya da hedefe doğru ileri hareket ettir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | Kameranın diyafram modunu ayarlar |
| [setAspect(double value)](#setAspect-double-) | Frustum'un en-boy oranını ayarlar. |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Görünüm düzleminin en-boy oranını ayarlar. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Kameranın baktığı yönü ayarlar. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setFarPlane(double value)](#setFarPlane-double-) | Frustum'un uzak düzlem mesafesini ayarlar. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Kameranın görüş alanını derece cinsinden ayarlar, bu özellik yalnızca ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) veya [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) olduğunda kullanılır |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | Kameranın yatay görüş alanını derece cinsinden ayarlar, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | Kameranın dikey görüş alanını derece cinsinden ayarlar, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır |
| [setHeight(double value)](#setHeight-double-) | Görünüm düzleminin yüksekliğini inç cinsinden ayarlar |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Kameranın baktığı ilgili konumu ayarlar. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | Ortografik kamerada kullanılan büyütmeyi ayarlar |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setNearPlane(double value)](#setNearPlane-double-) | Frustum'un yakın düzlem mesafesini ayarlar. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Frustum ortografik projeksiyonda olduğunda yüksekliği ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | Kameranın projeksiyon tipini ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Frustum'un yönlendirme modunu ayarlar. Bu özellik yalnızca [getTarget](../../com.aspose.threed/frustum\#getTarget) null olduğunda çalışır. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Kameranın baktığı hedefi ayarlar. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Kameranın yukarı yönünü ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Görünüm düzleminin genişliğini inç cinsinden ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


Yeni bir [Camera](../../com.aspose.threed/camera) sınıfı örneği başlatır.

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


Yeni bir [Camera](../../com.aspose.threed/camera) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Projeksiyon tipi. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


Yeni bir [Camera](../../com.aspose.threed/camera) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


Yeni bir [Camera](../../com.aspose.threed/camera) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Projeksiyon tipi. |

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
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


Kameranın diyafram modunu alır

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Frustum'un en-boy oranını alır

**Returns:**
double - frustum'un en-boy oranı
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


Görünüm düzleminin en-boy oranını alır.

**Returns:**
double - görünüm düzleminin en-boy oranı.
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
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Kameranın baktığı yönü alır. Bu özellikteki değişiklikler ayrıca [getLookAt](../../com.aspose.threed/frustum\#getLookAt) ve [getTarget](../../com.aspose.threed/frustum\#getTarget) öğelerini etkiler.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Frustum'un uzak düzlem mesafesini alır.

**Returns:**
double - frustum'un uzak düzlem mesafesi.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Kameranın görüş alanını derece cinsinden alır, bu özellik yalnızca ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) veya [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) olduğunda kullanılır.

**Returns:**
double - kameranın görüş alanını derece cinsinden, bu özellik yalnızca ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) veya [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) olduğunda kullanılır
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


Kameranın yatay görüş alanını derece cinsinden alır, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır.

**Returns:**
double - kameranın yatay görüş alanını derece cinsinden, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


Kameranın dikey görüş alanını derece cinsinden alır, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır.

**Returns:**
double - kameranın dikey görüş alanını derece cinsinden, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır
### getHeight() {#getHeight--}
```
public double getHeight()
```


Görünüm düzleminin yüksekliğini inç cinsinden alır

**Returns:**
double - görünüm düzleminin yüksekliği inç cinsinden
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Kameranın baktığı ilgili konumu alır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


Ortografik kamerada kullanılan büyütmeyi alır

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Frustum'un yakın düzlem mesafesini alır.

**Returns:**
double - frustum'un yakın düzlem mesafesi.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Frustum ortografik projeksiyonda iken yüksekliği alır.

**Returns:**
double - frustum ortografik projeksiyonda olduğunda yükseklik.
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
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


Kameranın projeksiyon tipini alır. Varsayılan olarak perspektif projeksiyon kullanılır.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
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
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Frustum'un yönlendirme modunu alır. Bu özellik yalnızca [getTarget](../../com.aspose.threed/frustum\#getTarget) null olduğunda çalışır. Değer [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) ise yön her zaman [getLookAt](../../com.aspose.threed/frustum\#getLookAt) özelliğiyle hesaplanır. Aksi takdirde [getLookAt](../../com.aspose.threed/frustum\#getLookAt) her zaman [getDirection](../../com.aspose.threed/frustum\#getDirection) ile hesaplanır.

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Kameranın baktığı hedefi alır. Kullanıcı bu özelliği destekliyorsa, [getLookAt](../../com.aspose.threed/frustum\#getLookAt) özelliğinden önce gelmelidir.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Kameranın yukarı yönünü alır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
### getWidth() {#getWidth--}
```
public double getWidth()
```


Görünüm düzleminin genişliğini inç cinsinden alır

**Returns:**
double - görüntü düzleminin inç cinsinden genişliği
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


Kamerayı yönüne ya da hedefe doğru ileri hareket ettir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesafe | double | İleri ne kadar süre hareket edilsin |

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
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


Kameranın diyafram modunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | Yeni değer |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Frustum'un en-boy oranını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


Görünüm düzleminin en-boy oranını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Kameranın baktığı yönü ayarlar. Bu özellikteki değişiklikler ayrıca [getLookAt](../../com.aspose.threed/frustum\#getLookAt) ve [getTarget](../../com.aspose.threed/frustum\#getTarget) öğelerini etkiler.

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Frustum'un uzak düzlem mesafesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Kameranın görüş alanını derece cinsinden ayarlar, bu özellik yalnızca ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) veya [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) olduğunda kullanılır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


Kameranın yatay görüş alanını derece cinsinden ayarlar, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


Kameranın dikey görüş alanını derece cinsinden ayarlar, bu özellik yalnızca ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) olduğunda kullanılır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Görünüm düzleminin yüksekliğini inç cinsinden ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Kameranın baktığı ilgili konumu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


Ortografik kamerada kullanılan büyütmeyi ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Frustum'un yakın düzlem mesafesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Frustum ortografik projeksiyonda olduğunda yüksekliği ayarlar.

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

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


Kameranın projeksiyon tipini ayarlar. Varsayılan olarak perspektif projeksiyon kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | Yeni değer |

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Frustum'un yönlendirme modunu ayarlar. Bu özellik yalnızca [getTarget](../../com.aspose.threed/frustum\#getTarget) null olduğunda çalışır. Değer [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) ise yön her zaman [getLookAt](../../com.aspose.threed/frustum\#getLookAt) özelliğiyle hesaplanır. Aksi takdirde [getLookAt](../../com.aspose.threed/frustum\#getLookAt) her zaman [getDirection](../../com.aspose.threed/frustum\#getDirection) ile hesaplanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Yeni değer |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Kameranın baktığı hedefi ayarlar. Kullanıcı bu özelliği destekliyorsa, [getLookAt](../../com.aspose.threed/frustum\#getLookAt) özelliğinden önce olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Yeni değer |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Kameranın yukarı yönünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Görünüm düzleminin genişliğini inç cinsinden ayarlar

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

