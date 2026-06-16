---
title: "AssetInfo"
second_title: "Aspose.3D for Java API Referansı"
description: "Varlık bilgisi."
type: docs
weight: 17
url: /tr/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Varlık bilgisi. Varlık bilgisi bir [Scene](../../com.aspose.threed/scene) öğesine eklenebilir. Çocuk [Scene](../../com.aspose.threed/scene) kendi [AssetInfo](../../com.aspose.threed/assetinfo) öğesine sahip olabilir ve ebeveynin tanımını geçersiz kılabilir. **Örnek:** Aşağıdaki kod, bir fbx dosyasından varlık bilgisinin nasıl okunacağını gösterir:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | [AssetInfo](../../com.aspose.threed/assetinfo) sınıfının yeni bir örneğini başlatır. |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | [AssetInfo](../../com.aspose.threed/assetinfo) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getAmbient()](#getAmbient--) | Bu varlığın varsayılan ortam rengini alır veya ayarlar |
| [getApplicationName()](#getApplicationName--) | Bu varlığı oluşturan uygulamayı alır |
| [getApplicationVendor()](#getApplicationVendor--) | Uygulama satıcısının adını alır |
| [getApplicationVersion()](#getApplicationVersion--) | Bu varlığı oluşturan uygulamanın sürümünü alır. |
| [getAuthor()](#getAuthor--) | Bu varlığın yazarını alır |
| [getAxisSystem()](#getAxisSystem--) | Varlık bilgisinin koordinat sistemini/yukarı vektörünü/ön vektörünü alır. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Bu varlığın yorumunu alır. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Bu varlıkta kullanılan koordinat sistemini alır. |
| [getCopyright()](#getCopyright--) | Belgenin telif hakkını alır |
| [getCreationTime()](#getCreationTime--) | Bu varlığın oluşturulma zamanını alır veya ayarlar |
| [getFrontVector()](#getFrontVector--) | Bu varlıkta kullanılan ön vektörü alır. |
| [getKeywords()](#getKeywords--) | Bu varlığın anahtar kelimelerini alır |
| [getModificationTime()](#getModificationTime--) | Bu varlığın değiştirilme zamanını alır veya ayarlar |
| [getName()](#getName--) | Adı alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRevision()](#getRevision--) | Bu varlığın revizyon numarasını alır, genellikle sürüm kontrol sisteminde kullanılır. |
| [getSubject()](#getSubject--) | Bu varlığın konusunu alır |
| [getTitle()](#getTitle--) | Bu varlığın başlığını alır |
| [getUnitName()](#getUnitName--) | Bu varlıkta kullanılan uzunluk birimini alır. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Gerçek dünya metreye ölçek faktörünü alır. |
| [getUpVector()](#getUpVector--) | Bu varlıkta kullanılan yukarı vektörünü alır. |
| [getUrl()](#getUrl--) | Bu varlığın URL'sini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Bu varlığın varsayılan ortam rengini alır veya ayarlar |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Bu varlığı oluşturan uygulamayı ayarlar |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Uygulama satıcısının adını ayarlar |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Bu varlığı oluşturan uygulamanın sürümünü ayarlar. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Bu varlığın yazarını ayarlar |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Varlık bilgilerinin koordinat sistemini/yukarı vektörünü/ön vektörünü ayarlar. |
| [setComment(String value)](#setComment-java.lang.String-) | Bu varlığın yorumunu ayarlar. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Bu varlıkta kullanılan koordinat sistemini ayarlar. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Belgenin telif hakkını ayarlar |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Bu varlığın oluşturulma zamanını alır veya ayarlar |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Bu varlıkta kullanılan ön vektörü ayarlar. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Bu varlığın anahtar kelimelerini ayarlar |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Bu varlığın değiştirilme zamanını alır veya ayarlar |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRevision(String value)](#setRevision-java.lang.String-) | Bu varlığın revizyon numarasını ayarlar, genellikle sürüm kontrol sisteminde kullanılır. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Bu varlığın konusunu ayarlar |
| [setTitle(String value)](#setTitle-java.lang.String-) | Bu varlığın başlığını ayarlar |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Bu varlıkta kullanılan uzunluk birimini ayarlar. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Gerçek dünya metre birimine ölçek faktörünü ayarlar. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Bu varlıkta kullanılan up-vektörünü ayarlar. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Bu varlığın URL'sini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


[AssetInfo](../../com.aspose.threed/assetinfo) sınıfının yeni bir örneğini başlatır.

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


[AssetInfo](../../com.aspose.threed/assetinfo) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad |

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Bu varlığın varsayılan ortam rengini alır veya ayarlar

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Bu varlığı oluşturan uygulamayı alır

**Returns:**
java.lang.String - bu varlığı oluşturan uygulama
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Uygulama satıcısının adını alır

**Returns:**
java.lang.String - uygulama satıcısının adı
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Bu varlığı oluşturan uygulamanın sürümünü alır.

**Returns:**
java.lang.String - bu varlığı oluşturan uygulamanın sürümü.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Bu varlığın yazarını alır

**Returns:**
java.lang.String - bu varlığın yazarı
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Varlık bilgisinin koordinat sistemini/yukarı vektörünü/ön vektörünü alır.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


Bu varlığın yorumunu alır.

**Returns:**
java.lang.String - bu varlığın yorumu.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Bu varlıkta kullanılan koordinat sistemini alır.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Belgenin telif hakkını alır

**Returns:**
java.lang.String - belgenin telif hakkı
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Bu varlığın oluşturulma zamanını alır veya ayarlar

**Returns:**
java.util.Calendar - veya bu varlığın oluşturulma zamanını ayarlar
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Bu varlıkta kullanılan ön vektörü alır.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Bu varlığın anahtar kelimelerini alır

**Returns:**
java.lang.String - bu varlığın anahtar kelimeleri
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Bu varlığın değiştirilme zamanını alır veya ayarlar

**Returns:**
java.util.Calendar - veya bu varlığın değiştirilme zamanını ayarlar
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


Bu varlığın revizyon numarasını alır, genellikle sürüm kontrol sisteminde kullanılır.

**Returns:**
java.lang.String - bu varlığın revizyon numarası, genellikle sürüm kontrol sisteminde kullanılır.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Bu varlığın konusunu alır

**Returns:**
java.lang.String - bu varlığın konusu
### getTitle() {#getTitle--}
```
public String getTitle()
```


Bu varlığın başlığını alır

**Returns:**
java.lang.String - bu varlığın başlığı
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Bu varlıkta kullanılan uzunluk birimini alır. örnek: cm/m/km/inch/feet

**Returns:**
java.lang.String - bu varlıkta kullanılan uzunluk birimi. örnek: cm/m/km/inch/feet
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Gerçek dünya metreye ölçek faktörünü alır.

**Returns:**
double - gerçek dünya metre birimine ölçek faktörü. **Remarks:** Birim adı null ise serileştirme sırasında yok sayılır.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Bu varlıkta kullanılan yukarı vektörünü alır.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Bu varlığın URL'sini alır veya ayarlar.

**Returns:**
java.lang.String - veya bu varlığın URL'sini ayarlar.
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Bu varlığın varsayılan ortam rengini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Yeni değer |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Bu varlığı oluşturan uygulamayı ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Uygulama satıcısının adını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Bu varlığı oluşturan uygulamanın sürümünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Bu varlığın yazarını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Varlık bilgilerinin koordinat sistemini/yukarı vektörünü/ön vektörünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Yeni değer |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Bu varlığın yorumunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Bu varlıkta kullanılan koordinat sistemini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Yeni değer |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Belgenin telif hakkını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Bu varlığın oluşturulma zamanını alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Calendar | Yeni değer |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Bu varlıkta kullanılan ön vektörü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Yeni değer |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Bu varlığın anahtar kelimelerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Bu varlığın değiştirilme zamanını alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Calendar | Yeni değer |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Bu varlığın revizyon numarasını ayarlar, genellikle sürüm kontrol sisteminde kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Bu varlığın konusunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Bu varlığın başlığını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Bu varlıkta kullanılan uzunluk birimini ayarlar. örnek: cm/m/km/inch/feet

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Gerçek dünya metre birimine ölçek faktörünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer **Remarks:** Birim adı null ise serileştirme sırasında yok sayılır. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Bu varlıkta kullanılan up-vektörünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Yeni değer |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Bu varlığın URL'sini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

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

