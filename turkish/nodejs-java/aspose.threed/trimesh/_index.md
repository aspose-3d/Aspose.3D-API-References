---
title: "TriMesh"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

Bir TriMesh, GPU tarafından doğrudan kullanılabilecek ham verileri içerir. Bu sınıf, yalnızca vertex başına veri içeren bir mesh oluşturmayı kolaylaştıran bir yardımcı programdır.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(name, declaration) | TriMesh örneğini başlat |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Bu TriMesh'in adı |
| tanım | VertexDeclaration | Vertex'in tanımı |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Ad | Açıklama |
| --- | --- |
| getVertexDeclaration() | TriMesh'in vertex düzeni. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Ad | Açıklama |
| --- | --- |
| getVerticesCount() | Bu TriMesh'teki vertex sayısı |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Ad | Açıklama |
| --- | --- |
| getIndicesCount() | Bu TriMesh içindeki indislerin sayısı |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Ad | Açıklama |
| --- | --- |
| getUnmergedVerticesCount() | beginVertex() ve endVertex() ile girilen birleştirilmemiş köşe sayısı. |

 **Result:**



---


### getCapacity{#getCapacity}

| Ad | Açıklama |
| --- | --- |
| getCapacity() | Önceden tahsis edilmiş köşelerin kapasitesi. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Ad | Açıklama |
| --- | --- |
| getVerticesSizeInBytes() | Tüm köşelerin bayt cinsinden toplam boyutu |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Ad | Açıklama |
| --- | --- |
| getParentNodes() | Tüm üst düğümleri alır; bir varlık geometri örneklemesi için birden çok üst düğüme bağlanabilir. Düğümler. |

 **Result:**



---


### getExcluded{#getExcluded}

| Ad | Açıklama |
| --- | --- |
| getExcluded() | Bu varlığın dışa aktarım sırasında hariç tutulup tutulmayacağını alır veya ayarlar. |

 **Result:**



---


### setExcluded{#setExcluded}

| Ad | Açıklama |
| --- | --- |
| setExcluded(value) | Bu varlığın dışa aktarım sırasında hariç tutulup tutulmayacağını alır veya ayarlar. |

 **Result:**



---


### getParentNode{#getParentNode}

| Ad | Açıklama |
| --- | --- |
| getParentNode() | İlk üst düğümü alır veya ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. Üst düğüm. |

 **Result:**



---


### setParentNode{#setParentNode}

| Ad | Açıklama |
| --- | --- |
| setParentNode(value) | İlk üst düğümü alır veya ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. Üst düğüm. |

 **Result:**



---


### getScene{#getScene}

| Ad | Açıklama |
| --- | --- |
| getScene() | Bu nesnenin ait olduğu sahneyi alır. |

 **Result:**



---


### getName{#getName}

| Ad | Açıklama |
| --- | --- |
| getName() | Adı alır veya ayarlar. Ad. |

 **Result:**



---


### setName{#setName}

| Ad | Açıklama |
| --- | --- |
| setName(value) | Adı alır veya ayarlar. Ad. |

 **Result:**



---


### getProperties{#getProperties}

| Ad | Açıklama |
| --- | --- |
| getProperties() | Tüm özelliklerin koleksiyonunu alır. |

 **Result:**



---


### fromMesh{#fromMesh}

| Ad | Açıklama |
| --- | --- |
| fromMesh(declaration, mesh) | Verilen mesh nesnesi ve verilen köşe düzeniyle bir TriMesh oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Ad | Açıklama |
| --- | --- |
| copyFrom(input, vd) | TriMesh'i yeni köşe düzeniyle girişten kopyala |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| input | TriMesh | Kopyalama için giriş TriMesh'i |
| vd | VertexDeclaration | Çıktı TriMesh'in yeni köşe bildirimi |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Ad | Açıklama |
| --- | --- |
| fromMesh(mesh, useFloat) | Verilen mesh nesnesinden bir TriMesh oluştur, köşe bildirimi giriş mesh'inin yapısına dayanır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | Her köşe öğesi bileşeni için double yerine float tipi kullan. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Ad | Açıklama |
| --- | --- |
| beginVertex() | Köşe eklemeye başla |

 **Result:**
Köşe


---


### endVertex{#endVertex}

| Ad | Açıklama |
| --- | --- |
| endVertex() | Düğüm eklemeyi sonlandır |

 **Result:**
Köşe


---


### verticesToArray{#verticesToArray}

| Ad | Açıklama |
| --- | --- |
| verticesToArray() | Düğümlerin verisini bayt dizisine dönüştür |

 **Result:**
byte[]


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| Ad | Açıklama |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Ham veriden TriMesh oluştur. Döndürülen TriMesh, performans için giriş bayt dizisini kopyalamaz; dizideki dış değişiklikler bu örneğe yansıtılır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| vd | VertexDeclaration | Düğüm bildirimi, en az bir alan içermelidir. |
| vertices | byte[] | Giriş düğüm verisi, düğümlerin minimum uzunluğu düğüm bildirim boyutuna eşit veya daha büyük olmalıdır. |
| indeksler | Number[] | Üçgen indeksleri |
| generateVertexMapping | boolean | Oluştur |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Ad | Açıklama |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Düğümleri baytlardan yükle, bayt uzunluğu düğüm boyutunun tam katı olmalıdır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Ad | Açıklama |
| --- | --- |
| readVector4(idx, field) | vector4 alanını oku |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| idx | Number | Okunacak düğümün indeksi |
| field | VertexField | Vector4/FVector4 veri tipine sahip alan |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Ad | Açıklama |
| --- | --- |
| readFVector4(idx, field) | vector4 alanını oku |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| idx | Number | Okunacak düğümün indeksi |
| field | VertexField | Vector4/FVector4 veri tipine sahip alan |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Ad | Açıklama |
| --- | --- |
| readVector3(idx, field) | vector3 alanını oku |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| idx | Number | Okunacak düğümün indeksi |
| field | VertexField | Vector3/FVector3 veri tipine sahip alan |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Ad | Açıklama |
| --- | --- |
| readFVector3(idx, field) | vector3 alanını oku |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| idx | Number | Okunacak düğümün indeksi |
| field | VertexField | Vector3/FVector3 veri tipine sahip alan |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Ad | Açıklama |
| --- | --- |
| readVector2(idx, field) | vector2 alanını oku |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| idx | Number | Okunacak düğümün indeksi |
| field | VertexField | Vector2/FVector2 veri tipine sahip alan |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Ad | Açıklama |
| --- | --- |
| readFVector2(idx, field) | vector2 alanını oku |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| idx | Number | Okunacak düğümün indeksi |
| field | VertexField | Vector2/FVector2 veri tipine sahip alan |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Ad | Açıklama |
| --- | --- |
| readDouble(idx, field) | double alanını oku |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| idx | Number | Okunacak düğümün indeksi |
| field | VertexField | float/double uyumlu veri tipine sahip alan |

 **Result:**
Number


---


### readFloat{#readFloat}

| Ad | Açıklama |
| --- | --- |
| readFloat(idx, field) | float alanını oku |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| idx | Number | Okunacak düğümün indeksi |
| field | VertexField | float/double uyumlu veri tipine sahip alan |

 **Result:**
Number


---


### getBoundingBox{#getBoundingBox}

| Ad | Açıklama |
| --- | --- |
| getBoundingBox() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |

 **Result:**
Number


---


### getEntityRendererKey{#getEntityRendererKey}

| Ad | Açıklama |
| --- | --- |
| getEntityRendererKey() | Renderörde kaydedilen varlık renderlayıcısının anahtarını alır. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Dinamik bir özelliği kaldırır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | Property | Hangi özellik kaldırılacak |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Adı belirtilen özelliği kaldır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Ad | Açıklama |
| --- | --- |
| getProperty(property) | Belirtilen özelliğin değerini al |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | String | Özellik adı |

 **Result:**
Object


---


### setProperty{#setProperty}

| Ad | Açıklama |
| --- | --- |
| setProperty(property, value) | Belirtilen özelliğin değerini ayarlar |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | String | Özellik adı |
| değer | Object | Özelliğin değeri |

 **Result:**
Object


---


### findProperty{#findProperty}

| Ad | Açıklama |
| --- | --- |
| findProperty(propertyName) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| propertyName | String | Özellik adı. |

 **Result:**
Property


---


### iterator{#iterator}

| Ad | Açıklama |
| --- | --- |
| iterator() | Dahili kullanım için ayrılmıştır. |

 **Result:**
Property


---



