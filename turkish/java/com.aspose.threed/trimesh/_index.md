---
title: "TriMesh"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir TriMesh, GPU tarafından doğrudan kullanılabilecek ham verileri içerir."
type: docs
weight: 194
url: /tr/java/com.aspose.threed/trimesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class TriMesh extends Entity implements Iterable<Vertex>
```

Bir TriMesh, GPU tarafından doğrudan kullanılabilecek ham verileri içerir. Bu sınıf, yalnızca köşe başına veri içeren bir ağ oluşturmayı kolaylaştıran bir yardımcı programdır. **Örnek:** Aşağıdaki kod, özel bellek düzeniyle bir TriMesh'in nasıl oluşturulacağını ve dosyaya nasıl dışa aktarılacağını gösterir.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TriMesh(String name, VertexDeclaration declaration)](#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-) | Bir [TriMesh](../../com.aspose.threed/trimesh) örneği başlatın |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addTriangle(int a, int b, int c)](#addTriangle-int-int-int-) | Yeni bir üçgen ekle |
| [beginVertex()](#beginVertex--) | Köşe eklemeye başla |
| [copyFrom(TriMesh input, VertexDeclaration vd)](#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-) | Girdiden yeni köşe düzeniyle [TriMesh](../../com.aspose.threed/trimesh) kopyala |
| [endVertex()](#endVertex--) | Köşe eklemeyi bitir |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [fromMesh(Mesh mesh)](#fromMesh-com.aspose.threed.Mesh-) | Verilen ağ nesnesinden bir TriMesh oluştur, köşe bildirimi giriş ağının yapısına dayanır. |
| [fromMesh(Mesh mesh, boolean useFloat)](#fromMesh-com.aspose.threed.Mesh-boolean-) | Verilen ağ nesnesinden bir TriMesh oluştur, köşe bildirimi giriş ağının yapısına dayanır. |
| [fromMesh(VertexDeclaration declaration, Mesh mesh)](#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-) | Verilen köşe düzeniyle verilen ağ nesnesinden bir TriMesh oluştur. |
| [fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)](#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-) | Ham veriden TriMesh oluştur |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getCapacity()](#getCapacity--) | Önceden ayrılmış köşelerin kapasitesi. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getIndicesCount()](#getIndicesCount--) | Bu [TriMesh](../../com.aspose.threed/trimesh) içindeki indeks sayısı. |
| [getIntIndices()](#getIntIndices--) | İndeksleri 32 bit tamsayı dizisine dönüştür |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getShortIndices()](#getShortIndices--) | İndeksleri 16 bit tamsayı dizisine dönüştür |
| [getUnmergedVerticesCount()](#getUnmergedVerticesCount--) | Bu [beginVertex](../../com.aspose.threed/trimesh\\#beginVertex) ve [endVertex](../../com.aspose.threed/trimesh\\#endVertex) tarafından sağlanan birleştirilmemiş köşe sayısı. |
| [getVertexDeclaration()](#getVertexDeclaration--) | [TriMesh](../../com.aspose.threed/trimesh) köşe düzeni. |
| [getVerticesCount()](#getVerticesCount--) | Bu [TriMesh](../../com.aspose.threed/trimesh) içindeki köşe sayısı. |
| [getVerticesSizeInBytes()](#getVerticesSizeInBytes--) | Tüm köşelerin bayt cinsinden toplam boyutu |
| [hashCode()](#hashCode--) |  |
| [indicesToArray(int[][] result)](#indicesToArray-int-----) | İndeksleri 32 bit tamsayı dizisine dönüştür |
| [indicesToArray(short[][] result)](#indicesToArray-short-----) | İndeksleri 16 bit tamsayı dizisine dönüştür |
| [iterator()](#iterator--) | [Vertex](../../com.aspose.threed/vertex) öğelerini yinelemek için enumeratörü al |
| [loadVerticesFromBytes(byte[] verticesInBytes)](#loadVerticesFromBytes-byte---) | Köşeleri baytlardan yükle, bayt uzunluğu köşe boyutunun tam katı olmalıdır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(int idx, VertexField field)](#readDouble-int-com.aspose.threed.VertexField-) | Double alanını oku |
| [readFVector2(int idx, VertexField field)](#readFVector2-int-com.aspose.threed.VertexField-) | Vector2 alanını oku |
| [readFVector3(int idx, VertexField field)](#readFVector3-int-com.aspose.threed.VertexField-) | Vector3 alanını oku |
| [readFVector4(int idx, VertexField field)](#readFVector4-int-com.aspose.threed.VertexField-) | vector4 alanını oku |
| [readFloat(int idx, VertexField field)](#readFloat-int-com.aspose.threed.VertexField-) | float alanını oku |
| [readVector2(int idx, VertexField field)](#readVector2-int-com.aspose.threed.VertexField-) | Vector2 alanını oku |
| [readVector3(int idx, VertexField field)](#readVector3-int-com.aspose.threed.VertexField-) | Vector3 alanını oku |
| [readVector4(int idx, VertexField field)](#readVector4-int-com.aspose.threed.VertexField-) | vector4 alanını oku |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [toString()](#toString--) | [TriMesh](../../com.aspose.threed/trimesh) öğesinin dize temsili alınır |
| [verticesToArray()](#verticesToArray--) | Köşe verilerini bayt dizisine dönüştür |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write16bIndicesTo(Stream stream)](#write16bIndicesTo-com.aspose.threed.Stream-) | İndeks verilerini 16bit tamsayı olarak akışa yaz **Example:** |
| [write16bIndicesTo(OutputStream stream)](#write16bIndicesTo-java.io.OutputStream-) | İndeks verilerini 16bit tamsayı olarak akışa yaz |
| [write32bIndicesTo(Stream stream)](#write32bIndicesTo-com.aspose.threed.Stream-) | İndeks verilerini 32bit tamsayı olarak akışa yaz **Example:** |
| [write32bIndicesTo(OutputStream stream)](#write32bIndicesTo-java.io.OutputStream-) | İndeks verilerini 32bit tamsayı olarak akışa yaz |
| [writeVerticesTo(Stream stream)](#writeVerticesTo-com.aspose.threed.Stream-) | Köşe verilerini belirtilen akışa yaz |
| [writeVerticesTo(OutputStream stream)](#writeVerticesTo-java.io.OutputStream-) | Köşe verilerini belirtilen akışa yaz |
### TriMesh(String name, VertexDeclaration declaration) {#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-}
```
public TriMesh(String name, VertexDeclaration declaration)
```


Bir [TriMesh](../../com.aspose.threed/trimesh) örneği başlatın

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Bu TriMesh'in adı |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Köşenin bildirimi |

### addTriangle(int a, int b, int c) {#addTriangle-int-int-int-}
```
public void addTriangle(int a, int b, int c)
```


Yeni bir üçgen ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | int | İlk köşenin indeksi |
| b | int | İkinci köşenin indeksi |
| c | int | Üçüncü köşenin indeksi |

### beginVertex() {#beginVertex--}
```
public Vertex beginVertex()
```


Köşe eklemeye başla

**Returns:**
[Vertex](../../com.aspose.threed/vertex) - The reference of internal vertex object in type [Vertex](../../com.aspose.threed/vertex)
### copyFrom(TriMesh input, VertexDeclaration vd) {#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-}
```
public static TriMesh copyFrom(TriMesh input, VertexDeclaration vd)
```


Girdiden yeni köşe düzeniyle [TriMesh](../../com.aspose.threed/trimesh) kopyala

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | [TriMesh](../../com.aspose.threed/trimesh) | Kopyalama için giriş TriMesh'i |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Çıktı TriMesh'inin yeni köşe bildirimi |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - A new TriMesh instance with new vertex declaration. **Example:**

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
  vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
  //convert a mesh to TriMesh, the layout is automatically inferred from input mesh
  var oldTriMesh = TriMesh.fromMesh((new Sphere()).toMesh());
  //now create a new TriMesh from old TriMesh, using explicit memory layout defined by vd
  var newTriMesh = TriMesh.copyFrom(oldTriMesh, vd);
```
### endVertex() {#endVertex--}
```
public int endVertex()
```


Köşe eklemeyi bitir

**Returns:**
int
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
### fromMesh(Mesh mesh) {#fromMesh-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(Mesh mesh)
```


Verilen ağ nesnesinden bir TriMesh oluştur, köşe bildirimi giriş ağının yapısına dayanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(Mesh mesh, boolean useFloat) {#fromMesh-com.aspose.threed.Mesh-boolean-}
```
public static TriMesh fromMesh(Mesh mesh, boolean useFloat)
```


Verilen ağ nesnesinden bir TriMesh oluştur, köşe bildirimi giriş ağının yapısına dayanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| useFloat | boolean | Her köşe öğesi bileşeni için double tipi yerine float tipi kullanın. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(VertexDeclaration declaration, Mesh mesh) {#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(VertexDeclaration declaration, Mesh mesh)
```


Verilen köşe düzeniyle verilen ağ nesnesinden bir TriMesh oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Köşe tip tanımı veya bellek düzeni |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Kaynak ağ |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - Instance of TriMesh converted from input mesh with specified vertex's memory layout **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping) {#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-}
```
public static TriMesh fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)
```


Ham veriden TriMesh oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Köşe bildirimi, en az bir alan içermelidir. |
| köşeler | byte[] | Giriş köşe verileri, köşelerin minimum uzunluğu köşe bildiriminin boyutuna eşit ya da daha büyük olmalıdır |
| indeksler | int[] | Üçgen indeksleri |
| generateVertexMapping | boolean | Her köşe için [Vertex](../../com.aspose.threed/vertex) oluşturun, bu yalnızca serileştirme/seriden çıkarma için gerekli değildir. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) instance that encapsulated the input byte array. **Remarks:** The returned TriMesh will not copy the input byte array for performance, external changes on the array will be reflected to this instance. **Example:** The following code shows how to construct a TriMesh from raw bytes, this is useful when build your own 3D format

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0The string representation,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```
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
### getCapacity() {#getCapacity--}
```
public int getCapacity()
```


Önceden ayrılmış köşelerin kapasitesi.

**Returns:**
int - Önceden tahsis edilmiş köşelerin kapasitesi.
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
### getIndicesCount() {#getIndicesCount--}
```
public int getIndicesCount()
```


Bu [TriMesh](../../com.aspose.threed/trimesh) içindeki indeks sayısı.

**Returns:**
int - Bu [TriMesh](../../com.aspose.threed/trimesh) içindeki indeks sayısı
### getIntIndices() {#getIntIndices--}
```
public int[] getIntIndices()
```


İndeksleri 32 bit tamsayı dizisine dönüştür

**Returns:**
int[]
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShortIndices() {#getShortIndices--}
```
public short[] getShortIndices()
```


İndeksleri 16 bit tamsayı dizisine dönüştür

**Returns:**
short[]
### getUnmergedVerticesCount() {#getUnmergedVerticesCount--}
```
public int getUnmergedVerticesCount()
```


Bu [beginVertex](../../com.aspose.threed/trimesh\\#beginVertex) ve [endVertex](../../com.aspose.threed/trimesh\\#endVertex) tarafından sağlanan birleştirilmemiş köşe sayısı.

**Returns:**
int - [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) ve [endVertex](../../com.aspose.threed/trimesh\#endVertex) tarafından geçirilen birleştirilmemiş köşe sayısı.
### getVertexDeclaration() {#getVertexDeclaration--}
```
public VertexDeclaration getVertexDeclaration()
```


[TriMesh](../../com.aspose.threed/trimesh) köşe düzeni.

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - The vertex layout of the [TriMesh](../../com.aspose.threed/trimesh).
### getVerticesCount() {#getVerticesCount--}
```
public int getVerticesCount()
```


Bu [TriMesh](../../com.aspose.threed/trimesh) içindeki köşe sayısı.

**Returns:**
int - Bu [TriMesh](../../com.aspose.threed/trimesh) içindeki köşe sayısı
### getVerticesSizeInBytes() {#getVerticesSizeInBytes--}
```
public int getVerticesSizeInBytes()
```


Tüm köşelerin bayt cinsinden toplam boyutu

**Returns:**
int - Tüm köşelerin bayt cinsinden toplam boyutu
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicesToArray(int[][] result) {#indicesToArray-int-----}
```
public void indicesToArray(int[][] result)
```


İndeksleri 32 bit tamsayı dizisine dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sonuç | int[][] |  |

### indicesToArray(short[][] result) {#indicesToArray-short-----}
```
public void indicesToArray(short[][] result)
```


İndeksleri 16 bit tamsayı dizisine dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sonuç | short[][] |  |

### iterator() {#iterator--}
```
public Iterator<Vertex> iterator()
```


[Vertex](../../com.aspose.threed/vertex) öğelerini yinelemek için enumeratörü al

**Returns:**
java.util.Iterator<com.aspose.threed.Vertex>
### loadVerticesFromBytes(byte[] verticesInBytes) {#loadVerticesFromBytes-byte---}
```
public void loadVerticesFromBytes(byte[] verticesInBytes)
```


Köşeleri baytlardan yükleyin, bayt uzunluğu köşe boyutunun tam katı olmalıdır. **Örnek:** Aşağıdaki kod, boş bir TriMesh oluşturmanın ve ham baytlardan köşeleri manuel olarak yüklemenin nasıl yapılacağını gösterir.

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.LoadVerticesFromBytes(vertices);
  triMesh.AddTriangle(0, 1, 2);
```

```
int[] indices = new int[] { 0,  1,  2 };
  byte[] vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.loadVerticesFromBytes(vertices);
  triMesh.addTriangle(0, 1, 2);
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| verticesInBytes | byte[] |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readDouble(int idx, VertexField field) {#readDouble-int-com.aspose.threed.VertexField-}
```
public double readDouble(int idx, VertexField field)
```


Double alanını oku

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Okunacak köşenin indeksi |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Float/double uyumlu veri tipine sahip alan |

**Returns:**
double - Belirtilen köşenin alanının Double değeri
### readFVector2(int idx, VertexField field) {#readFVector2-int-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(int idx, VertexField field)
```


Vector2 alanını oku

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Okunacak köşenin indeksi |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 veri tipine sahip alan |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - FVector2 of specified vertex's field
### readFVector3(int idx, VertexField field) {#readFVector3-int-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(int idx, VertexField field)
```


Vector3 alanını oku

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Okunacak köşenin indeksi |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 veri tipine sahip alan |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(int idx, VertexField field) {#readFVector4-int-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(int idx, VertexField field)
```


vector4 alanını oku

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Okunacak köşenin indeksi |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 veri tipine sahip alan |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(int idx, VertexField field) {#readFloat-int-com.aspose.threed.VertexField-}
```
public float readFloat(int idx, VertexField field)
```


float alanını oku

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Okunacak köşenin indeksi |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Float/double uyumlu veri tipine sahip alan |

**Returns:**
float - Belirtilen köşenin alanının Float değeri
### readVector2(int idx, VertexField field) {#readVector2-int-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(int idx, VertexField field)
```


Vector2 alanını oku

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Okunacak köşenin indeksi |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 veri tipine sahip alan |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Vector2 of specified vertex's field
### readVector3(int idx, VertexField field) {#readVector3-int-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(int idx, VertexField field)
```


Vector3 alanını oku

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Okunacak köşenin indeksi |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 veri tipine sahip alan |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(int idx, VertexField field) {#readVector4-int-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(int idx, VertexField field)
```


vector4 alanını oku

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int | Okunacak köşenin indeksi |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 veri tipine sahip alan |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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

### toString() {#toString--}
```
public String toString()
```


[TriMesh](../../com.aspose.threed/trimesh) öğesinin dize temsili alınır

**Returns:**
java.lang.String - Dize temsili
### verticesToArray() {#verticesToArray--}
```
public byte[] verticesToArray()
```


Köşe verilerini bayt dizisine dönüştür

**Returns:**
byte[]
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

### write16bIndicesTo(Stream stream) {#write16bIndicesTo-com.aspose.threed.Stream-}
```
public void write16bIndicesTo(Stream stream)
```


İndeks verilerini 16bit tamsayı olarak akışa yaz **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write16bIndicesTo(OutputStream stream) {#write16bIndicesTo-java.io.OutputStream-}
```
public void write16bIndicesTo(OutputStream stream)
```


İndeks verilerini 16bit tamsayı olarak akışa yaz

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.OutputStream | **Örnek:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
     var mesh = (new Sphere()).toMesh();    
     var triMesh = TriMesh.fromMesh(mesh);    
     //save it to a stream, 115 vertices * 32bytes per vertex    
     var stream = new ByteArrayOutputStream();    
     triMesh.writeVerticesTo(stream);    
     //save indices as ushort to stream, 504 indices * 2 bytes per index    
     triMesh.write16bIndicesTo(stream);
``` |

### write32bIndicesTo(Stream stream) {#write32bIndicesTo-com.aspose.threed.Stream-}
```
public void write32bIndicesTo(Stream stream)
```


İndeks verilerini 32bit tamsayı olarak akışa yaz **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write32bIndicesTo(s);
      }
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write32bIndicesTo(OutputStream stream) {#write32bIndicesTo-java.io.OutputStream-}
```
public void write32bIndicesTo(OutputStream stream)
```


İndeks verilerini 32bit tamsayı olarak akışa yaz

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.OutputStream | **Örnek:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write32bIndicesTo(stream);
``` |

### writeVerticesTo(Stream stream) {#writeVerticesTo-com.aspose.threed.Stream-}
```
public void writeVerticesTo(Stream stream)
```


Köşe verilerini belirtilen akışa yaz

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | [Stream](../../com.aspose.threed/stream) | Veri noktalarının yazılacağı akış **Örnek:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
``` |

### writeVerticesTo(OutputStream stream) {#writeVerticesTo-java.io.OutputStream-}
```
public void writeVerticesTo(OutputStream stream)
```


Köşe verilerini belirtilen akışa yaz

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.OutputStream | Veri noktalarının yazılacağı akış **Örnek:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write16bIndicesTo(stream);
``` |

