---
title: "Light"
second_title: "Aspose.3D for Java API Referansı"
description: "Işık sahneyi aydınlatır."
type: docs
weight: 94
url: /tr/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

Işık sahneyi aydınlatır.

Işığın toplam zayıflamasını hesaplamak için formül şudur:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Light()](#Light--) | Yeni bir [Light](../../com.aspose.threed/light) sınıfı örneği başlatır. |
| [Light(String name)](#Light-java.lang.String-) | Yeni bir [Light](../../com.aspose.threed/light) sınıfı örneği başlatır. |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | Yeni bir [Light](../../com.aspose.threed/light) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getAspect()](#getAspect--) | Frustum'un en-boy oranını alır |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getCastLight()](#getCastLight--) | Mevcut ışık örneğinin diğer nesneleri aydınlatıp aydınlatamayacağını alır. |
| [getCastShadows()](#getCastShadows--) | Işığın diğer nesnelere gölge atıp atamayacağını alır. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Işığın rengini alır |
| [getConstantAttenuation()](#getConstantAttenuation--) | Işığın toplam zayıflamasını hesaplamak için sabit zayıflamayı alır |
| [getDirection()](#getDirection--) | Kameranın baktığı yönü alır. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getFalloff()](#getFalloff--) | Azalma koni açısını (derece cinsinden) alır. |
| [getFarPlane()](#getFarPlane--) | Frustum'un uzak düzlem mesafesini alır. |
| [getHotSpot()](#getHotSpot--) | Sıcak nokta koni açısını (derece cinsinden) alır. |
| [getIntensity()](#getIntensity--) | Işığın şiddetini alır, varsayılan değer 100'tür. |
| [getLightType()](#getLightType--) | Işığın tipini alır. |
| [getLinearAttenuation()](#getLinearAttenuation--) | Işığın toplam sönümünü hesaplamak için lineer sönüm değerini alır. |
| [getLookAt()](#getLookAt--) | Kameranın baktığı ilgili konumu alır. |
| [getName()](#getName--) | Adı alır. |
| [getNearPlane()](#getNearPlane--) | Frustum'un yakın düzlem mesafesini alır. |
| [getOrthoHeight()](#getOrthoHeight--) | Frustum ortografik projeksiyonda iken yüksekliği alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | Işığın toplam sönümünü hesaplamak için kuadratik sönüm değerini alır. |
| [getRotationMode()](#getRotationMode--) | Frustum'un yönelim modunu alır. Bu özellik yalnızca [getTarget](../../com.aspose.threed/frustum\#getTarget) null olduğunda çalışır. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengini alır. |
| [getTarget()](#getTarget--) | Kameranın baktığı hedefi alır. |
| [getUp()](#getUp--) | Kameranın yukarı yönünü alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setAspect(double value)](#setAspect-double-) | Frustum'un en-boy oranını ayarlar. |
| [setCastLight(boolean value)](#setCastLight-boolean-) | Mevcut ışık örneğinin diğer nesneleri aydınlatıp aydınlatamayacağını ayarlar. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Işığın diğer nesnelere gölge atıp atamayacağını ayarlar. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Işığın rengini ayarlar. |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | Işığın toplam sönümünü hesaplamak için sabit sönüm değerini ayarlar. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Kameranın baktığı yönü ayarlar. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setFalloff(double value)](#setFalloff-double-) | Azalma koni açısını (derece cinsinden) ayarlar. |
| [setFarPlane(double value)](#setFarPlane-double-) | Frustum'un uzak düzlem mesafesini ayarlar. |
| [setHotSpot(double value)](#setHotSpot-double-) | Sıcak nokta koni açısını (derece cinsinden) ayarlar. |
| [setIntensity(double value)](#setIntensity-double-) | Işığın şiddetini ayarlar, varsayılan değer 100'tür. |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | Işığın tipini ayarlar. |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | Işığın toplam sönümünü hesaplamak için lineer sönüm değerini ayarlar. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Kameranın baktığı ilgili konumu ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setNearPlane(double value)](#setNearPlane-double-) | Frustum'un yakın düzlem mesafesini ayarlar. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Frustum ortografik projeksiyonda olduğunda yüksekliği ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | Işığın toplam sönümünü hesaplamak için kuadratik sönümlemeyi ayarlar. |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Frustum'un yönlendirme modunu ayarlar. Bu özellik yalnızca [getTarget](../../com.aspose.threed/frustum\#getTarget) null olduğunda çalışır. |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | Gölgenin rengini ayarlar. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Kameranın baktığı hedefi ayarlar. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Kameranın yukarı yönünü ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


Yeni bir [Light](../../com.aspose.threed/light) sınıfı örneği başlatır.

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


Yeni bir [Light](../../com.aspose.threed/light) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


Yeni bir [Light](../../com.aspose.threed/light) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad |
| type | [LightType](../../com.aspose.threed/lighttype) | Yeni ışık tipi |

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
### getAspect() {#getAspect--}
```
public double getAspect()
```


Frustum'un en-boy oranını alır

**Returns:**
double - frustum'un en-boy oranı
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
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


Mevcut ışık örneğinin diğer nesneleri aydınlatıp aydınlatamayacağını alır.

**Returns:**
boolean - mevcut ışık örneğinin diğer nesneleri aydınlatıp aydınlatamayacağı.
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Işığın diğer nesnelere gölge atıp atamayacağını alır.

**Returns:**
boolean - ışığın diğer nesnelere gölge düşürüp düşürmeyeceği.
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


Işığın rengini alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Işığın toplam zayıflamasını hesaplamak için sabit zayıflamayı alır

**Returns:**
double - ışığın toplam sönümünü hesaplamak için sabit sönümleme.
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
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


Azalma koni açısını (derece cinsinden) alır.

**Returns:**
double - düşüş koni açısı (derece cinsinden).
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Frustum'un uzak düzlem mesafesini alır.

**Returns:**
double - frustum'un uzak düzlem mesafesi.
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


Sıcak nokta koni açısını (derece cinsinden) alır.

**Returns:**
double - sıcak nokta koni açısı (derece cinsinden).
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


Işığın şiddetini alır, varsayılan değer 100'tür.

**Returns:**
double - ışığın yoğunluğu, varsayılan değer 100
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


Işığın tipini alır.

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


Işığın toplam sönümünü hesaplamak için lineer sönüm değerini alır.

**Returns:**
double - ışığın toplam sönümünü hesaplamak için lineer sönümleme.
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Kameranın baktığı ilgili konumu alır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
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
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


Işığın toplam sönümünü hesaplamak için kuadratik sönüm değerini alır.

**Returns:**
double - ışığın toplam sönümünü hesaplamak için kuadratik sönümleme.
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
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


Gölgenin rengini alır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Frustum'un en-boy oranını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


Mevcut ışık örneğinin diğer nesneleri aydınlatıp aydınlatamayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Işığın diğer nesnelere gölge atıp atamayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Işığın rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


Işığın toplam sönümünü hesaplamak için sabit sönüm değerini ayarlar.

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

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


Azalma koni açısını (derece cinsinden) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Frustum'un uzak düzlem mesafesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


Sıcak nokta koni açısını (derece cinsinden) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


Işığın şiddetini ayarlar, varsayılan değer 100'tür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


Işığın tipini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | Yeni değer |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


Işığın toplam sönümünü hesaplamak için lineer sönüm değerini ayarlar.

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

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


Işığın toplam sönümünü hesaplamak için kuadratik sönümlemeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Frustum'un yönlendirme modunu ayarlar. Bu özellik yalnızca [getTarget](../../com.aspose.threed/frustum\#getTarget) null olduğunda çalışır. Değer [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) ise yön her zaman [getLookAt](../../com.aspose.threed/frustum\#getLookAt) özelliğiyle hesaplanır. Aksi takdirde [getLookAt](../../com.aspose.threed/frustum\#getLookAt) her zaman [getDirection](../../com.aspose.threed/frustum\#getDirection) ile hesaplanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Yeni değer |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


Gölgenin rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

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

