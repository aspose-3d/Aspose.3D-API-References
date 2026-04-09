---
title: Adegan
second_title: Referensi API Aspose.3D untuk Java
description: 
type: docs
weight: 161
url: /id/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Menginisialisasi instance baru dari kelas [Scene](../../com.aspose.threed/scene) dengan entitas yang terlampir pada node baru. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Menginisialisasi instance baru dari kelas [Scene](../../com.aspose.threed/scene) sebagai sub-adegan. |
| [Scene()](#Scene--) | Menginisialisasi instance baru dari kelas [Scene](../../com.aspose.threed/scene). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [VERSION](#VERSION) | Mendapatkan versi rilis saat ini |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clear()](#clear--) | Menghapus konten adegan dan mengembalikan pengaturan default. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | Fungsi singkat untuk membuat dan mendaftarkan [AnimationClip](../../com.aspose.threed/animationclip). [AnimationClip](../../com.aspose.threed/animationclip) pertama akan ditetapkan ke [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Membuka adegan dari jalur yang diberikan |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Membuka adegan dari jalur yang diberikan |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Membuka adegan dari aliran yang diberikan |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Membuka adegan dari aliran yang diberikan |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Mendapatkan [AnimationClip](../../com.aspose.threed/animationclip) yang bernama |
| [getAnimationClips()](#getAnimationClips--) | Mendapatkan semua [AnimationClip](../../com.aspose.threed/animationclip) yang didefinisikan dalam adegan. |
| [getAssetInfo()](#getAssetInfo--) | Mendapatkan informasi aset tingkat atas |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Mendapatkan [AnimationClip](../../com.aspose.threed/animationclip) yang aktif |
| [getLibrary()](#getLibrary--) | Objek yang tidak langsung digunakan dalam hierarki adegan dapat didefinisikan di Perpustakaan. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getPoses()](#getPoses--) | Mendapatkan semua [Pose](../../com.aspose.threed/pose) yang digunakan dalam adegan ini. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRootNode()](#getRootNode--) | Mendapatkan node akar dari adegan. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getSubScenes()](#getSubScenes--) | Mendapatkan semua sub-adegan |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Membuka adegan dari aliran yang diberikan |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Membuka adegan dari aliran yang diberikan |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan. |
| [open(String fileName)](#open-java.lang.String-) | Membuka adegan dari jalur yang diberikan |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Membuka adegan dari jalur yang diberikan |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Render adegan menjadi bitmap dari perspektif kamera yang diberikan. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Render adegan menjadi bitmap dari perspektif kamera yang diberikan. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Render adegan menjadi file eksternal dari perspektif kamera yang diberikan. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Render adegan menjadi file eksternal dari perspektif kamera yang diberikan. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Render adegan menjadi file eksternal dari perspektif kamera yang diberikan. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Menyimpan adegan ke aliran menggunakan format file yang ditentukan. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Menyimpan adegan ke aliran menggunakan format file yang ditentukan. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Menyimpan adegan ke aliran menggunakan format file yang ditentukan. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Menyimpan adegan ke aliran menggunakan format file yang ditentukan. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Menyimpan adegan ke aliran menggunakan format file yang ditentukan. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Menyimpan adegan ke aliran menggunakan format file yang ditentukan. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Menyimpan adegan ke aliran menggunakan format file yang ditentukan. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Menyimpan adegan ke aliran menggunakan format file yang ditentukan. |
| [save(String fileName)](#save-java.lang.String-) | Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Mengatur informasi aset tingkat atas |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Mengatur [AnimationClip](../../com.aspose.threed/animationclip) yang aktif |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Menginisialisasi instance baru dari kelas [Scene](../../com.aspose.threed/scene) dengan entitas yang terlampir pada node baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | Entitas awal yang terlampir ke adegan **Contoh:** Kode berikut menunjukkan cara membuat [getScene](../../com.aspose.threed/scene\#getScene) langsung dari sebuah [Entity](../../com.aspose.threed/entity): |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Menginisialisasi instance baru dari kelas [Scene](../../com.aspose.threed/scene) sebagai sub-adegan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | Adegan induk. |
| nama | java.lang.String | Nama adegan. |

### Scene() {#Scene--}
```
public Scene()
```


Menginisialisasi instance baru dari kelas [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


Mendapatkan versi rilis saat ini

### clear() {#clear--}
```
public void clear()
```


Menghapus konten adegan dan mengembalikan pengaturan default.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


Fungsi singkat untuk membuat dan mendaftarkan [AnimationClip](../../com.aspose.threed/animationclip). [AnimationClip](../../com.aspose.threed/animationclip) pertama akan ditetapkan ke [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama klip animasi |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Menemukan properti. Itu dapat menjadi properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyName | java.lang.String | Nama properti. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Membuka adegan dari jalur yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Membuka adegan dari jalur yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Membuka adegan dari aliran yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Membuka adegan dari aliran yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Membuka adegan dari aliran yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. **Contoh:** Kode berikut menunjukkan cara membuat adegan dari aliran dengan sumber token pembatalan |

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


Membuka adegan dari aliran yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan **Contoh:** Kode berikut menunjukkan cara membuat adegan dari aliran dengan sumber token pembatalan |

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


Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. **Contoh:** Kode berikut menunjukkan cara membuat adegan dari aliran |

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


Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan **Contoh:** Kode berikut menunjukkan cara membuat adegan dari aliran |

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


Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. **Contoh:** Kode berikut menunjukkan cara membuat adegan dari aliran dengan opsi pemuatan |

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


Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan **Contoh:** Kode berikut menunjukkan cara membuat adegan dari aliran dengan opsi pemuatan |

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


Mendapatkan [AnimationClip](../../com.aspose.threed/animationclip) yang bernama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama [AnimationClip](../../com.aspose.threed/animationclip) yang akan dicari |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Mendapatkan semua [AnimationClip](../../com.aspose.threed/animationclip) yang didefinisikan dalam adegan.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - semua [AnimationClip](../../com.aspose.threed/animationclip) yang didefinisikan dalam adegan.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Mendapatkan informasi aset tingkat atas

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


Mendapatkan [AnimationClip](../../com.aspose.threed/animationclip) yang aktif

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Objek yang tidak langsung digunakan dalam hierarki adegan dapat didefinisikan di Perpustakaan. Ini berguna ketika Anda menggunakan sub-adegan dan menempatkan komponen yang dapat digunakan kembali di bawah sub-adegan.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - Objek yang tidak langsung digunakan dalam hierarki adegan dapat didefinisikan di Perpustakaan. Ini berguna ketika Anda menggunakan sub-adegan dan menempatkan komponen yang dapat digunakan kembali di bawah sub-adegan.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Mendapatkan semua [Pose](../../com.aspose.threed/pose) yang digunakan dalam adegan ini.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - semua [Pose](../../com.aspose.threed/pose) yang digunakan dalam adegan ini.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Mendapatkan koleksi semua properti.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Dapatkan nilai properti yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti |

**Returns:**
java.lang.Object - Nilai dari properti yang ditemukan
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Mendapatkan node akar dari adegan.

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


Mendapatkan adegan yang dimiliki objek ini

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Mendapatkan semua sub-adegan

**Returns:**
java.util.List<com.aspose.threed.Scene> - semua sub-adegan
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


Membuka adegan dari aliran yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Membuka adegan dari aliran yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Membuka adegan dari aliran yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. **Contoh:** Kode berikut menunjukkan cara membuka adegan dari aliran |

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


Membuka adegan dari aliran yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan **Contoh:** Kode berikut menunjukkan cara membuka adegan dari aliran dengan token pembatalan |

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


Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. **Contoh:** Kode berikut menunjukkan cara membuka adegan dari aliran |

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


Membuka adegan dari aliran yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan **Contoh:** Kode berikut menunjukkan cara membuka adegan dari aliran |

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


Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. **Contoh:** Kode berikut menunjukkan cara membuka adegan dari aliran dengan opsi pemuatan tambahan |

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


Membuka adegan dari aliran yang diberikan menggunakan konfigurasi IO yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan **Contoh:** Kode berikut menunjukkan cara membuka adegan dari aliran dengan opsi pemuatan tambahan |

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


Membuka adegan dari jalur yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Membuka adegan dari jalur yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Konfigurasi lebih detail untuk membuka aliran. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas pemuatan |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Menghapus properti dinamis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Properti mana yang akan dihapus |

**Returns:**
boolean - true jika properti berhasil dihapus
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Hapus properti yang ditentukan yang diidentifikasi dengan nama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Properti mana yang akan dihapus |

**Returns:**
boolean - true jika properti berhasil dihapus
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Render adegan menjadi bitmap dari perspektif kamera yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Dari perspektif kamera mana untuk merender adegan |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Target hasil render |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Render adegan menjadi bitmap dari perspektif kamera yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Dari perspektif kamera mana untuk merender adegan |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Target hasil render |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | Opsi untuk menyesuaikan beberapa pengaturan internal. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Render adegan ke file eksternal dari perspektif kamera yang diberikan. Ukuran output default adalah 1024x768 dan format output adalah png

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Dari perspektif kamera mana untuk merender adegan |
| fileName | java.lang.String | Nama file dari file output |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Render adegan menjadi file eksternal dari perspektif kamera yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Dari perspektif kamera mana untuk merender adegan |
| fileName | java.lang.String | Nama file dari file output |
| size | [Vector2](../../com.aspose.threed/vector2) | Ukuran gambar render akhir |
| format | java.lang.String | Format gambar dari file output |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Render adegan menjadi file eksternal dari perspektif kamera yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Dari perspektif kamera mana untuk merender adegan |
| fileName | java.lang.String | Nama file dari file output |
| size | [Vector2](../../com.aspose.threed/vector2) | Ukuran gambar render akhir |
| format | java.lang.String | Format gambar dari file output |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | Opsi untuk menyesuaikan beberapa pengaturan internal. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Menyimpan adegan ke aliran menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Menyimpan adegan ke aliran menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas penyimpanan |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Menyimpan adegan ke aliran menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Konfigurasi lebih detail untuk menyimpan aliran. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Menyimpan adegan ke aliran menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Konfigurasi lebih detail untuk menyimpan aliran. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas penyimpanan |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Menyimpan adegan ke aliran menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Format. **Contoh:** Kode berikut menunjukkan cara menyimpan adegan |

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


Menyimpan adegan ke aliran menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas penyimpanan **Contoh:** Kode berikut menunjukkan cara menyimpan adegan |

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


Menyimpan adegan ke aliran menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Konfigurasi lebih detail untuk menyimpan aliran. **Contoh:** Kode berikut menunjukkan cara menyimpan adegan |

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


Menyimpan adegan ke aliran menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | Aliran masukan, pengguna bertanggung jawab menutup aliran. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Konfigurasi lebih detail untuk menyimpan aliran. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas penyimpanan **Contoh:** Kode berikut menunjukkan cara menyimpan adegan |

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


Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas penyimpanan |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Konfigurasi lebih detail untuk menyimpan aliran. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Konfigurasi lebih detail untuk menyimpan aliran. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token pembatalan untuk tugas penyimpanan |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Mengatur informasi aset tingkat atas

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nilai baru **Contoh:** Kode berikut menunjukkan cara membaca informasi aplikasi dari file FBX: |

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


Mengatur [AnimationClip](../../com.aspose.threed/animationclip) yang aktif

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Nilai baru |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Mengatur nilai properti yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti |
| nilai | java.lang.Object | Nilai properti |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

