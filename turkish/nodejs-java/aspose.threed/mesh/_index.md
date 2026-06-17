---
title: "Mesh"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/mesh/
---
## Mesh class

Bir ağ, birçok n-köşeli çokgenlerden oluşur.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | Mesh sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(name) | Mesh sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad. |

 **Result:**



---


### getEdges{#getEdges}

| Ad | Açıklama |
| --- | --- |
| getEdges() | Mesh'in kenarlarını alır. Kenar, mesh içinde isteğe bağlıdır, bu yüzden boş olabilir. |

 **Result:**



---


### getPolygonCount{#getPolygonCount}

| Ad | Açıklama |
| --- | --- |
| getPolygonCount() | Poligon sayısını alır. Poligon sayısı. |

 **Result:**



---


### getPolygons{#getPolygons}

| Ad | Açıklama |
| --- | --- |
| getPolygons() | Mesh'in poligon tanımını alır |

 **Result:**



---


### getVisible{#getVisible}

| Ad | Açıklama |
| --- | --- |
| getVisible() | Geometrinin görünür olup olmadığını alır veya ayarlar |

 **Result:**



---


### setVisible{#setVisible}

| Ad | Açıklama |
| --- | --- |
| setVisible(value) | Geometrinin görünür olup olmadığını alır veya ayarlar |

 **Result:**



---


### getDeformers{#getDeformers}

| Ad | Açıklama |
| --- | --- |
| getDeformers() | Bu geometriyle ilişkili tüm deformasyonları alır. Deformasyonlar. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Ad | Açıklama |
| --- | --- |
| getControlPoints() | Tüm kontrol noktalarını alır |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Ad | Açıklama |
| --- | --- |
| getCastShadows() | Bu geometrinin gölge oluşturup oluşturamayacağını alır veya ayarlar |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Ad | Açıklama |
| --- | --- |
| setCastShadows(value) | Bu geometrinin gölge oluşturup oluşturamayacağını alır veya ayarlar |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Ad | Açıklama |
| --- | --- |
| getReceiveShadows() | Bu geometrinin gölge alıp almayacağını alır veya ayarlar. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Ad | Açıklama |
| --- | --- |
| setReceiveShadows(value) | Bu geometrinin gölge alıp almayacağını alır veya ayarlar. |

 **Result:**



---


### getVertexElements{#getVertexElements}

| Ad | Açıklama |
| --- | --- |
| getVertexElements() | Tüm vertex elemanlarını alır |

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


### getPolygonSize{#getPolygonSize}

| Ad | Açıklama |
| --- | --- |
| getPolygonSize(index) | Belirtilen çokgenin köşe sayısını alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| indeks | Number | İndeks. |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Ad | Açıklama |
| --- | --- |
| createPolygon(indices, offset, length) | Tüm köşeleri indekslerde tanımlanan yeni bir çokgen oluşturur. Çokgeni köşe köşe oluşturmak için lütfen PolygonBuilder'ı kullanın. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| indeksler | Number[] | Çokgen indekslerinin dizisi, her indeks çokgeni oluşturan bir kontrol noktasına işaret eder. |
| ofset | Number | İlk çokgen indeksinin ofseti |
| uzunluk | Number | İndekslerin uzunluğu |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Ad | Açıklama |
| --- | --- |
| createPolygon(indices) | Tüm köşeleri indekslerde tanımlanan yeni bir çokgen oluşturur. Çokgeni köşe köşe oluşturmak için lütfen PolygonBuilder'ı kullanın. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| indeksler | Number[] | Çokgen indekslerinin dizisi, her indeks çokgeni oluşturan bir kontrol noktasına işaret eder. |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Ad | Açıklama |
| --- | --- |
| createPolygon(v1, v2, v3, v4) | 4 köşeli bir çokgen oluşturur (quad) |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| v1 | Number | İlk köşenin indeksi |
| v2 | Number | İkinci köşenin indeksi |
| v3 | Number | Üçüncü köşenin indeksi |
| v4 | Number | Dördüncü köşenin indeksi |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Ad | Açıklama |
| --- | --- |
| createPolygon(v1, v2, v3) | 3 köşe ile bir çokgen oluştur (üçgen) |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| v1 | Number | İlk köşenin indeksi |
| v2 | Number | İkinci köşenin indeksi |
| v3 | Number | Üçüncü köşenin indeksi |

 **Result:**
Number


---


### toMesh{#toMesh}

| Ad | Açıklama |
| --- | --- |
| toMesh() | Geçerli varlıktan Mesh örneğini alır. |

 **Result:**
Mesh


---


### getElement{#getElement}

| Ad | Açıklama |
| --- | --- |
| getElement(type) | Belirtilen türde bir vertex öğesi alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Ad | Açıklama |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Verilen doku eşleme türüyle bir VertexElementUV örneği alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Ad | Açıklama |
| --- | --- |
| createElement(type) | Belirtilen türde bir vertex öğesi oluşturur ve geometrinin içine ekler. Eğer tür VertexElementType.UV ise, TextureMapping.DIFFUSE türünde doku eşlemesiyle bir VertexElementUV oluşturulur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Ad | Açıklama |
| --- | --- |
| addElement(element) | Mevcut geometriye var olan bir vertex öğesi ekler |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| element | VertexElement | Eklenecek vertex öğesi |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Ad | Açıklama |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Belirtilen türde bir vertex öğesi oluşturur ve geometrinin içine ekler. Eğer tür VertexElementType.UV ise, TextureMapping.DIFFUSE türünde doku eşlemesiyle bir VertexElementUV oluşturulur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Ad | Açıklama |
| --- | --- |
| createElementUV(uvMapping) | Verilen doku eşleme türüyle bir VertexElementUV oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Ad | Açıklama |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Verilen doku eşleme türüyle bir VertexElementUV oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Ad | Açıklama |
| --- | --- |
| getBoundingBox() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |

 **Result:**
VertexElementUV


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



