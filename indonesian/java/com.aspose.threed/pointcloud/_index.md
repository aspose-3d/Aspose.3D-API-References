---
title: PointCloud
second_title: Referensi API Aspose.3D untuk Java
description: Awan titik tidak berisi informasi topologi tetapi hanya titik kontrol dan elemen verteks.
type: docs
weight: 132
url: /id/java/com.aspose.threed/pointcloud/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)
```
public class PointCloud extends Geometry
```

Awan titik tidak berisi informasi topologi tetapi hanya titik kontrol dan elemen verteks.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PointCloud(String name)](#PointCloud-java.lang.String-) | Konstruktor dari [PointCloud](../../com.aspose.threed/pointcloud) |
| [PointCloud()](#PointCloud--) | Konstruktor dari [PointCloud](../../com.aspose.threed/pointcloud) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Mendapatkan semua deformer dengan tipe deformer yang ditentukan |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Menambahkan elemen vertex yang ada ke geometri saat ini |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Membuat sebuah [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Membuat sebuah [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [fromGeometry(Geometry g)](#fromGeometry-com.aspose.threed.Geometry-) | Buat instance PointCloud baru dari objek geometri |
| [fromGeometry(Geometry g, int density)](#fromGeometry-com.aspose.threed.Geometry-int-) | Buat instance point cloud baru dari objek geometri. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getCastShadows()](#getCastShadows--) | Mendapatkan apakah geometri ini dapat memancarkan bayangan |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Mendapatkan semua titik kontrol |
| [getDeformers()](#getDeformers--) | Mendapatkan semua deformer yang terkait dengan geometri ini. |
| [getDimension()](#getDimension--) | Jika nilai dimensi ada untuk point cloud, itu menunjukkan point cloud terorganisir. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Mendapatkan elemen vertex dengan tipe yang ditentukan |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getReceiveShadows()](#getReceiveShadows--) | Mendapatkan apakah geometri ini dapat menerima bayangan. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Mendapatkan sebuah instance [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan |
| [getVertexElements()](#getVertexElements--) | Mendapatkan semua elemen vertex |
| [getVisible()](#getVisible--) | Mendapatkan apakah geometri terlihat |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Mengatur apakah geometri ini dapat memancarkan bayangan |
| [setDimension(Vector2 value)](#setDimension-com.aspose.threed.Vector2-) | Jika nilai dimensi ada untuk point cloud, itu menunjukkan point cloud terorganisir. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Mengatur apakah geometri ini dapat menerima bayangan. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mengatur apakah geometri terlihat |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointCloud(String name) {#PointCloud-java.lang.String-}
```
public PointCloud(String name)
```


Konstruktor dari [PointCloud](../../com.aspose.threed/pointcloud)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama entitas ini |

### PointCloud() {#PointCloud--}
```
public PointCloud()
```


Konstruktor dari [PointCloud](../../com.aspose.threed/pointcloud)

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Mendapatkan semua deformer dengan tipe deformer yang ditentukan

**Returns:**
java.util.Collection<T> - koleksi Deformer
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Menambahkan elemen vertex yang ada ke geometri saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Elemen vertex yang akan ditambahkan |

### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Tipe elemen vertex |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Tipe elemen vertex |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Mode pemetaan default |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Mode referensi default |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Membuat sebuah [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Jenis pemetaan tekstur yang akan dibuat |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Membuat sebuah [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Jenis pemetaan tekstur yang akan dibuat |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Mode pemetaan default |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Mode referensi default |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
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
### fromGeometry(Geometry g) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static PointCloud fromGeometry(Geometry g)
```


Buat instance PointCloud baru dari objek geometri

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g | [Geometry](../../com.aspose.threed/geometry) |  |

**Returns:**
[PointCloud](../../com.aspose.threed/pointcloud)
### fromGeometry(Geometry g, int density) {#fromGeometry-com.aspose.threed.Geometry-int-}
```
public static PointCloud fromGeometry(Geometry g, int density)
```


Buat instance point cloud baru dari objek geometri. Kepadatan adalah jumlah titik per segitiga satuan (Segitiga satuan adalah segitiga dengan luas permukaan maksimum dari mesh)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g | [Geometry](../../com.aspose.threed/geometry) | Instansi Mesh atau geometri lainnya |
| kepadatan | int | Jumlah titik per segitiga satuan |

**Returns:**
[PointCloud](../../com.aspose.threed/pointcloud)
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya.

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


Mendapatkan apakah geometri ini dapat memancarkan bayangan

**Returns:**
boolean - apakah geometri ini dapat menghasilkan bayangan
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Mendapatkan semua titik kontrol

**Returns:**
java.util.List<com.aspose.threed.Vector4> - semua titik kontrol
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Mendapatkan semua deformer yang terkait dengan geometri ini.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - semua deformer yang terkait dengan geometri ini.
### getDimension() {#getDimension--}
```
public Vector2 getDimension()
```


Jika nilai dimensi ada untuk point cloud, itu menunjukkan point cloud terorganisir. Tanpa ukuran yang ditentukan, dianggap sebagai point cloud tidak terorganisir. Point cloud terorganisir berarti memiliki struktur mirip gambar.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - If a dimension value is present for the point cloud, it indicates an organized point cloud. Without a specified size, it is considered an unorganized point cloud. Organized point cloud means it has an image-like structure.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Mendapatkan elemen vertex dengan tipe yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | tipe elemen vertex mana yang akan dicari |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Mendapatkan kunci renderer entitas yang terdaftar di renderer

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor.

**Returns:**
boolean - apakah entitas ini akan dikecualikan saat mengekspor.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - semua node induk, sebuah entitas dapat terhubung ke beberapa node induk untuk instansi geometri
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
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Mendapatkan apakah geometri ini dapat menerima bayangan.

**Returns:**
boolean - apakah geometri ini dapat menerima bayangan.
### getScene() {#getScene--}
```
public Scene getScene()
```


Mendapatkan adegan yang dimiliki objek ini

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Mendapatkan sebuah instance [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Mendapatkan semua elemen vertex

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - semua elemen vertex
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Mendapatkan apakah geometri terlihat

**Returns:**
boolean - jika geometri terlihat
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Mengatur apakah geometri ini dapat memancarkan bayangan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setDimension(Vector2 value) {#setDimension-com.aspose.threed.Vector2-}
```
public void setDimension(Vector2 value)
```


Jika nilai dimensi ada untuk point cloud, itu menunjukkan point cloud terorganisir. Tanpa ukuran yang ditentukan, dianggap sebagai point cloud tidak terorganisir. Point cloud terorganisir berarti memiliki struktur mirip gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Mengatur apakah entitas ini akan dikecualikan saat mengekspor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nilai baru |

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Mengatur apakah geometri ini dapat menerima bayangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Mengatur apakah geometri terlihat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

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

