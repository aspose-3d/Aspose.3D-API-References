---
title: "PointCloud"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/pointcloud/
---
## PointCloud class

Nokta bulutu topoloji bilgisi içermez, yalnızca kontrol noktaları ve köşe elemanlarını içerir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(name) | PointCloud yapıcı |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Bu varlığın adı |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload() | PointCloud yapıcı |

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
| getDeformers() | Bu geometriye bağlı tüm deformörleri alır. Deformörler. |

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
| getVertexElements() | Tüm köşe öğelerini alır |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Ad | Açıklama |
| --- | --- |
| getParentNodes() | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir. Düğümler. |

 **Result:**



---


### getExcluded{#getExcluded}

| Ad | Açıklama |
| --- | --- |
| getExcluded() | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır veya ayarlar. |

 **Result:**



---


### setExcluded{#setExcluded}

| Ad | Açıklama |
| --- | --- |
| setExcluded(value) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır veya ayarlar. |

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


### getEntityRendererKey{#getEntityRendererKey}

| Ad | Açıklama |
| --- | --- |
| getEntityRendererKey() | Renderleyicide kayıtlı varlık renderleyicisinin anahtarını alır. |

 **Result:**
EntityRendererKey


---


### fromGeometry{#fromGeometry}

| Ad | Açıklama |
| --- | --- |
| fromGeometry(g) | Bir geometri nesnesinden yeni bir PointCloud örneği oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Geometry | null |

 **Result:**
PointCloud


---


### fromGeometry{#fromGeometry}

| Ad | Açıklama |
| --- | --- |
| fromGeometry(g, density) | Bir geometri nesnesinden yeni bir nokta bulutu örneği oluştur. Yoğunluk, birim üçgen başına nokta sayısıdır (Birim üçgen, mesh'ten maksimum yüzey alanına sahip üçgendir). |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| g | Geometry | Mesh veya diğer geometri örneği |
| density | Sayı | Birim üçgen başına nokta sayısı |

 **Result:**
PointCloud


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
| createElement(type) | Belirtilen türde bir vertex öğesi oluşturur ve geometrinin içine ekler. Eğer tür VertexElementType.UV ise, TextureMapping.DIFFUSE doku eşleme türüne sahip bir VertexElementUV oluşturulur. |

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
| addElement(element) | Mevcut geometriye mevcut bir vertex öğesi ekler |

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
| createElement(type, mappingMode, referenceMode) | Belirtilen türde bir vertex öğesi oluşturur ve geometrinin içine ekler. Eğer tür VertexElementType.UV ise, TextureMapping.DIFFUSE doku eşleme türüne sahip bir VertexElementUV oluşturulur. |

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


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Dinamik bir özelliği kaldırır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| özellik | Özellik | Hangi özelliği kaldırmak istiyorsunuz |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Adına göre belirtilen özelliği kaldır |

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
| özellik | String | Özellik adı |

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
| özellik | String | Özellik adı |
| değer | Object | Özelliğin değeri |

 **Result:**
Object


---


### findProperty{#findProperty}

| Ad | Açıklama |
| --- | --- |
| findProperty(propertyName) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| propertyName | String | Özellik adı. |

 **Result:**
Özellik


---



