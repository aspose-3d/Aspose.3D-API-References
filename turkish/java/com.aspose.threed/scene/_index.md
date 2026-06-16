---
title: "Sahne"
second_title: "Aspose.3D for Java API Referansı"
description: 
type: docs
weight: 161
url: /tr/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Yeni bir [Scene](../../com.aspose.threed/scene) sınıfının örneğini, yeni bir düğüme eklenmiş bir varlık ile başlatır. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Yeni bir [Scene](../../com.aspose.threed/scene) sınıfının örneğini alt sahne olarak başlatır. |
| [Scene()](#Scene--) | Yeni bir [Scene](../../com.aspose.threed/scene) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [VERSION](#VERSION) | Mevcut sürüm numarasını alır |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clear()](#clear--) | Sahne içeriğini temizler ve varsayılan ayarları geri yükler. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | Kısa bir işlev, [AnimationClip](../../com.aspose.threed/animationclip) oluşturur ve kaydeder. İlk [AnimationClip](../../com.aspose.threed/animationclip) [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) öğesine atanacaktır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Verilen yoldan sahneyi açar |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Verilen yoldan sahneyi açar |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Verilen akıştan sahneyi açar |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Verilen akıştan sahneyi açar |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Verilen akıştan sahneyi açar |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Verilen akıştan sahneyi açar |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Adlandırılmış bir [AnimationClip](../../com.aspose.threed/animationclip) alır |
| [getAnimationClips()](#getAnimationClips--) | Sahnede tanımlı tüm [AnimationClip](../../com.aspose.threed/animationclip) öğelerini alır. |
| [getAssetInfo()](#getAssetInfo--) | Üst düzey varlık bilgilerini alır |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Etkin [AnimationClip](../../com.aspose.threed/animationclip) öğesini alır |
| [getLibrary()](#getLibrary--) | Sahne hiyerarşisinde doğrudan kullanılmayan nesneler Kütüphane içinde tanımlanabilir. |
| [getName()](#getName--) | Adı alır. |
| [getPoses()](#getPoses--) | Bu sahnede kullanılan tüm [Pose](../../com.aspose.threed/pose) öğelerini alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRootNode()](#getRootNode--) | Sahnenin kök düğümünü alır. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getSubScenes()](#getSubScenes--) | Tüm alt sahneleri alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Verilen akıştan sahneyi açar |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Verilen akıştan sahneyi açar |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Verilen akıştan sahneyi açar |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Verilen akıştan sahneyi açar |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar. |
| [open(String fileName)](#open-java.lang.String-) | Verilen yoldan sahneyi açar |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Verilen yoldan sahneyi açar |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Verilen kameranın perspektifinden sahneyi bitmap olarak render eder. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Verilen kameranın perspektifinden sahneyi bitmap olarak render eder. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Verilen kameranın perspektifinden sahneyi dış dosya olarak render eder. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Verilen kameranın perspektifinden sahneyi dış dosya olarak render eder. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Verilen kameranın perspektifinden sahneyi dış dosya olarak render eder. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder. |
| [save(String fileName)](#save-java.lang.String-) | Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Üst düzey varlık bilgilerini ayarlar |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Aktif [AnimationClip](../../com.aspose.threed/animationclip) ayarlar |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Yeni bir [Scene](../../com.aspose.threed/scene) sınıfının örneğini, yeni bir düğüme eklenmiş bir varlık ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | Sahneye eklenen ilk varlık **Example:** Aşağıdaki kod, bir [getScene](../../com.aspose.threed/scene\#getScene) doğrudan bir [Entity](../../com.aspose.threed/entity) üzerinden nasıl oluşturulacağını gösterir: |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Yeni bir [Scene](../../com.aspose.threed/scene) sınıfının örneğini alt sahne olarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | Üst sahne. |
| ad | java.lang.String | Sahnenin adı. |

### Scene() {#Scene--}
```
public Scene()
```


Yeni bir [Scene](../../com.aspose.threed/scene) sınıfının örneğini başlatır.

### VERSION {#VERSION}
```
public static final String VERSION
```


Mevcut sürüm numarasını alır

### clear() {#clear--}
```
public void clear()
```


Sahne içeriğini temizler ve varsayılan ayarları geri yükler.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


Kısa bir işlev, [AnimationClip](../../com.aspose.threed/animationclip) oluşturur ve kaydeder. İlk [AnimationClip](../../com.aspose.threed/animationclip) [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) öğesine atanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Animasyon klibinin adı |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Verilen yoldan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Verilen yoldan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Verilen akıştan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Verilen akıştan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Verilen akıştan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. **Example:** Aşağıdaki kod, bir iptal belirteci kaynağı ile akıştan sahne oluşturmanın nasıl yapılacağını gösterir |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


Verilen akıştan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci **Example:** Aşağıdaki kod, bir iptal belirteci kaynağı ile akıştan sahne oluşturmanın nasıl yapılacağını gösterir |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. **Example:** Aşağıdaki kod, bir akıştan sahne oluşturmanın nasıl yapılacağını gösterir |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci **Example:** Aşağıdaki kod, bir akıştan sahne oluşturmanın nasıl yapılacağını gösterir |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. **Example:** Aşağıdaki kod, yükleme seçenekleriyle bir akıştan sahne oluşturmanın nasıl yapılacağını gösterir |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci **Example:** Aşağıdaki kod, yükleme seçenekleriyle bir akıştan sahne oluşturmanın nasıl yapılacağını gösterir |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


Adlandırılmış bir [AnimationClip](../../com.aspose.threed/animationclip) alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | [AnimationClip](../../com.aspose.threed/animationclip) adını aramak için |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Sahnede tanımlı tüm [AnimationClip](../../com.aspose.threed/animationclip) öğelerini alır.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - sahnede tanımlı tüm [AnimationClip](../../com.aspose.threed/animationclip).
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Üst düzey varlık bilgilerini alır

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


Etkin [AnimationClip](../../com.aspose.threed/animationclip) öğesini alır

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Sahne hiyerarşisinde doğrudan kullanılmayan nesneler Kütüphane içinde tanımlanabilir. Bu, alt sahneler kullandığınızda ve yeniden kullanılabilir bileşenleri alt sahnelerin altına koyduğunuzda faydalıdır.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - sahne hiyerarşisinde doğrudan kullanılmayan nesneler Kütüphane içinde tanımlanabilir. Bu, alt sahneler kullandığınızda ve yeniden kullanılabilir bileşenleri alt sahnelerin altına koyduğunuzda faydalıdır.
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Bu sahnede kullanılan tüm [Pose](../../com.aspose.threed/pose) öğelerini alır.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - bu sahnede kullanılan tüm [Pose](../../com.aspose.threed/pose).
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
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Sahnenin kök düğümünü alır.

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Tüm alt sahneleri alır

**Returns:**
java.util.List<com.aspose.threed.Scene> - tüm alt sahneler
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




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


Verilen akıştan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Verilen akıştan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Verilen akıştan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. **Example:** Aşağıdaki kod, bir akıştan sahne açmanın nasıl yapılacağını gösterir |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


Verilen akıştan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine Cancellation token **Örnek:** Aşağıdaki kod, bir akıştan sahneyi Cancellation token ile nasıl açacağını gösterir. |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. **Örnek:** Aşağıdaki kod, bir akıştan sahneyi nasıl açacağını gösterir. |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine Cancellation token **Örnek:** Aşağıdaki kod, bir akıştan sahneyi nasıl açacağını gösterir. |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. **Örnek:** Aşağıdaki kod, ek yük seçenekleriyle bir akıştan sahneyi nasıl açacağını gösterir. |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Belirtilen IO yapılandırmasını kullanarak verilen akıştan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine Cancellation token **Örnek:** Aşağıdaki kod, ek yük seçenekleriyle bir akıştan sahneyi nasıl açacağını gösterir. |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


Verilen yoldan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Verilen yoldan sahneyi açar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Dosya formatı. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak verilen yoldan sahneyi açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Akışı açmak için daha ayrıntılı yapılandırma. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Yükleme görevine iptal belirteci |

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
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Verilen kameranın perspektifinden sahneyi bitmap olarak render eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Sahneyi hangi kamera perspektifinden render edeceksiniz |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Render edilen sonucun hedefi |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Verilen kameranın perspektifinden sahneyi bitmap olarak render eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Sahneyi hangi kamera perspektifinden render edeceksiniz |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Render edilen sonucun hedefi |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | İç ayarların bir kısmını özelleştirmek için seçenek. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Verilen kamera perspektifinden sahneyi dış dosyaya render edin. Varsayılan çıktı boyutu 1024x768 ve çıktı formatı png'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Sahneyi hangi kamera perspektifinden render edeceksiniz |
| fileName | java.lang.String | Çıktı dosyasının dosya adı |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Verilen kameranın perspektifinden sahneyi dış dosya olarak render eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Sahneyi hangi kamera perspektifinden render edeceksiniz |
| fileName | java.lang.String | Çıktı dosyasının dosya adı |
| size | [Vector2](../../com.aspose.threed/vector2) | Son render edilen görüntünün boyutu |
| biçim | java.lang.String | Çıktı dosyasının görüntü formatı |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Verilen kameranın perspektifinden sahneyi dış dosya olarak render eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Sahneyi hangi kamera perspektifinden render edeceksiniz |
| fileName | java.lang.String | Çıktı dosyasının dosya adı |
| size | [Vector2](../../com.aspose.threed/vector2) | Son render edilen görüntünün boyutu |
| biçim | java.lang.String | Çıktı dosyasının görüntü formatı |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | İç ayarların bir kısmını özelleştirmek için seçenek. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Kaydetme görevine Cancellation token |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Akışı kaydetmek için daha ayrıntılı yapılandırma. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Akışı kaydetmek için daha ayrıntılı yapılandırma. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Kaydetme görevine Cancellation token |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Format. **Örnek:** Aşağıdaki kod, sahneyi nasıl kaydedeceğinizi gösterir. |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Kaydetme görevine Cancellation token **Örnek:** Aşağıdaki kod, sahneyi nasıl kaydedeceğinizi gösterir. |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Akışı kaydetmek için daha ayrıntılı yapılandırma. **Örnek:** Aşağıdaki kod, sahneyi nasıl kaydedeceğinizi gösterir. |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


Belirtilen dosya biçimini kullanarak sahneyi akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Giriş akışı, akışı kapatmak kullanıcı sorumluluğundadır. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Akışı kaydetmek için daha ayrıntılı yapılandırma. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Kaydetme görevine Cancellation token **Örnek:** Aşağıdaki kod, sahneyi nasıl kaydedeceğinizi gösterir. |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Kaydetme görevine Cancellation token |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Akışı kaydetmek için daha ayrıntılı yapılandırma. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Akışı kaydetmek için daha ayrıntılı yapılandırma. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Kaydetme görevine Cancellation token |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Üst düzey varlık bilgilerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Yeni değer **Örnek:** Aşağıdaki kod, bir FBX dosyasından uygulama bilgilerini nasıl okuyacağınızı gösterir: |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


Aktif [AnimationClip](../../com.aspose.threed/animationclip) ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Yeni değer |

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

