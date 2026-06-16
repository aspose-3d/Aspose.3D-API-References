---
title: "Mesh"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir ağ, birçok n-köşeli çokgenlerden oluşur."
type: docs
weight: 102
url: /tr/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Bir mesh birçok n‑kenarlı çokgenlerden oluşur. **Örnek:** Mesh içinde bir çokgen eklemek için:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Mesh içindeki tüm çokgenlerde gezin:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Mesh()](#Mesh--) | Yeni bir [Mesh](../../com.aspose.threed/mesh) sınıfı örneği oluşturur. |
| [Mesh(String name)](#Mesh-java.lang.String-) | Yeni bir [Mesh](../../com.aspose.threed/mesh) sınıfı örneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Belirtilen deformer türleriyle tüm deformörleri alır. |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Mesh'e yeni bir kontrol noktası ekleyin, bu daha verimlidir. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Mesh'e yeni bir kontrol noktası ekleyin, bu daha verimlidir. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Mevcut geometriye mevcut bir vertex öğesi ekler |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Belirtilen tipte bir vertex öğesi oluşturur ve geometriye ekler |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Belirtilen tipte bir vertex öğesi oluşturur ve geometriye ekler |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) oluşturur. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) oluşturur. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | 3 köşe (üçgen) ile bir çokgen oluştur |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | 4 köşe (dörtlü) ile bir çokgen oluştur |
| [createPolygon(int[] indices)](#createPolygon-int---) | `indices` içinde tanımlanan tüm köşelerle yeni bir çokgen oluşturur. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | `indices` içinde tanımlanan tüm köşelerle yeni bir çokgen oluşturur. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | İki ağın farkını hesapla |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | İki ağ üzerinde Boolean işlemi gerçekleştir |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getCastShadows()](#getCastShadows--) | Bu geometrinin gölge oluşturup oluşturamayacağını alır |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Tüm kontrol noktalarını al |
| [getDeformers()](#getDeformers--) | Bu geometriyle ilişkili tüm deformasyonları al. |
| [getEdges()](#getEdges--) | Ağın kenarlarını al. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Belirtilen türde bir köşe öğesini al |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getPolygonCount()](#getPolygonCount--) | Çokgen sayısını al |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Belirtilen çokgenin köşe sayısını al. |
| [getPolygons()](#getPolygons--) | Ağın çokgen tanımını al |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getReceiveShadows()](#getReceiveShadows--) | Bu geometrinin gölge alıp almayacağını al. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) örneği al |
| [getVertexElements()](#getVertexElements--) | Tüm köşe öğelerini al |
| [getVisible()](#getVisible--) | Geometrinin görünür olup olmadığını al |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | İki ağın kesişimini hesapla |
| [isManifold()](#isManifold--) | Mevcut ağın manifold bir ağ olup olmadığını kontrol et. |
| [iterator()](#iterator--) | Her iç çokgen için yineleyiciyi al. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Bu geometrinin gölge oluşturup oluşturamayacağını ayarlar |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Bu geometrinin gölge alıp almayacağını ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) | Geometrinin görünür olup olmadığını ayarlar |
| [toMesh()](#toMesh--) | Geçerli varlıktan Mesh örneğini alır. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Üçgenleştirilmiş ağı döndür. |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | İki ağın birleşimini hesapla. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Yeni bir [Mesh](../../com.aspose.threed/mesh) sınıfı örneği oluşturur.

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Yeni bir [Mesh](../../com.aspose.threed/mesh) sınıfı örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Belirtilen deformer türleriyle tüm deformörleri alır.

**Returns:**
java.util.Collection<T> - Deformer koleksiyonu
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Mesh'e yeni bir kontrol noktası ekleyin, bu daha verimlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | Kontrol noktasının x bileşeni |
| y | double | Kontrol noktasının y bileşeni |
| z | double | Kontrol noktasının z bileşeni |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Mesh'e yeni bir kontrol noktası ekleyin, bu daha verimlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | Kontrol noktasının x bileşeni |
| y | double | Kontrol noktasının y bileşeni |
| z | double | Kontrol noktasının z bileşeni |
| w | double | Kontrol noktasının w bileşeni |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Mevcut geometriye mevcut bir vertex öğesi ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Eklenecek köşe öğesi |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Belirtilen tipte bir vertex öğesi oluşturur ve geometriye ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Köşe öğesi türü |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Belirtilen tipte bir vertex öğesi oluşturur ve geometriye ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Köşe öğesi türü |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Varsayılan eşleme modu |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Varsayılan referans modu |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Oluşturulacak doku eşleme türü |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Oluşturulacak doku eşleme türü |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Varsayılan eşleme modu |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Varsayılan referans modu |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


3 köşe (üçgen) ile bir çokgen oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v1 | int | İlk köşenin indeksi |
| v2 | int | İkinci köşenin indeksi |
|  | v3 | int | Üçüncü köşenin indeksi **Örnek:** Aşağıdaki kod, kontrol noktasının indeksleriyle yeni bir çokgenin nasıl oluşturulacağını gösterir. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


4 köşe (dörtlü) ile bir çokgen oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v1 | int | İlk köşenin indeksi |
| v2 | int | İkinci köşenin indeksi |
| v3 | int | Üçüncü köşenin indeksi |
|  | v4 | int | Dördüncü köşenin indeksi **Örnek:** Aşağıdaki kod, kontrol noktasının indeksleriyle yeni bir çokgenin nasıl oluşturulacağını gösterir. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Tüm köşeleri `indices` içinde tanımlanmış yeni bir çokgen oluşturur. Çokgeni köşe köşe oluşturmak için lütfen [PolygonBuilder](../../com.aspose.threed/polygonbuilder) kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | indeksler | int[] | Poligon indekslerinin dizisi, her indeks poligonu oluşturan bir kontrol noktasına işaret eder. **Example:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Tüm köşeleri `indices` içinde tanımlanmış yeni bir çokgen oluşturur. Çokgeni köşe köşe oluşturmak için lütfen [PolygonBuilder](../../com.aspose.threed/polygonbuilder) kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeksler | int[] | Poligon indekslerinin dizisi, her indeks poligonu oluşturan bir kontrol noktasına işaret eder. |
| ofset | int | İlk poligon indeksinin ofseti |
|  | uzunluk | int | İndekslerin uzunluğu **Example:** Aşağıdaki kod, kontrol noktası indeksleriyle yeni bir poligon oluşturmanın nasıl yapılacağını gösterir. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


İki ağın farkını hesapla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | İlk ağ |
| b | [Mesh](../../com.aspose.threed/mesh) | İkinci ağ |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


İki ağ üzerinde Boolean işlemi gerçekleştir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Boolean işlem türü. |
| a | [Mesh](../../com.aspose.threed/mesh) | İşlem yapılacak ilk ağ. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | İlk ağın dönüşüm matrisi |
| b | [Mesh](../../com.aspose.threed/mesh) | İşlem yapılacak ikinci ağ |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | İkinci ağın dönüşüm matrisi |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Tüm kontrol noktalarını al

**Returns:**
java.util.List<com.aspose.threed.Vector4> - tüm kontrol noktaları
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Bu geometriyle ilişkili tüm deformasyonları al.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - bu geometriyle ilişkili tüm deformasyonlar.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Ağın kenarlarını alır. Kenar, ağda isteğe bağlıdır, bu yüzden boş olabilir.

**Returns:**
java.util.List<java.lang.Integer> - Ağın kenarları. Kenar, ağda isteğe bağlıdır, bu yüzden boş olabilir.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Belirtilen türde bir köşe öğesini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | hangi köşe öğesi türünün bulunacağı |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Çokgen sayısını al

**Returns:**
int - poligon sayısı **Example:** Aşağıdaki kod, ağın poligon sayısını nasıl alacağınızı gösterir.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Belirtilen çokgenin köşe sayısını al.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | İndeks. |

**Returns:**
int - Poligon boyutu.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Ağın çokgen tanımını al

**Returns:**
java.util.List<int[]> - ağın çokgen tanımı
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
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Verilen doku eşleme türüyle bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) örneği al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Tüm köşe öğelerini al

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - tüm köşe öğeleri
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Geometrinin görünür olup olmadığını al

**Returns:**
boolean - geometrinin görünür olup olmadığı
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


İki ağın kesişimini hesapla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | İlk ağ |
| b | [Mesh](../../com.aspose.threed/mesh) | İkinci ağ |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Mevcut ağın manifold bir ağ olup olmadığını kontrol edin. Bu işlev, manifold hesaplama sonucunu önbelleğe almayacaktır.

**Returns:**
boolean - ağ bir manifold ağ ise doğru.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Her iç çokgen için yineleyiciyi al.

**Returns:**
java.util.Iterator<int[]> - İteratör.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vertexElements | boolean | Kopyalanmış köşe öğesi verilerini optimize edin |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vertexElements | boolean | Kopyalanmış köşe öğesi verilerini optimize edin |
| toleranceControlPoint | float | Kontrol noktası için tolerans, varsayılan değer 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vertexElements | boolean | Kopyalanmış köşe öğesi verilerini optimize edin |
| toleranceControlPoint | float | Kontrol noktası için tolerans, varsayılan değer 1e-9 |
| toleranceNormal | float | Normal/tanjant/binormal için tolerans, varsayılan değer 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vertexElements | boolean | Kopyalanmış köşe öğesi verilerini optimize edin |
| toleranceControlPoint | float | Kontrol noktası için tolerans, varsayılan değer 1e-9 |
| toleranceNormal | float | Normal/tanjant/binormal için tolerans, varsayılan değer 1e-9 |
| toleranceUV | float | UV için tolerans, varsayılan değer 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Yinelenen kontrol noktalarını ortadan kaldırarak ağın bellek kullanımını optimize et

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vertexElements | boolean | Kopyalanmış köşe öğesi verilerini optimize edin |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Bu geometrinin gölge alıp almayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Geometrinin görünür olup olmadığını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Geçerli varlıktan Mesh örneğini alır.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


Üçgenleştirilmiş ağı döndür.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


İki ağın birleşimini hesapla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | İlk ağ |
| b | [Mesh](../../com.aspose.threed/mesh) | İkinci ağ |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
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

