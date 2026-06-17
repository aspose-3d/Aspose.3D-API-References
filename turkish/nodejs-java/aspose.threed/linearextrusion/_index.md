---
title: "LinearExtrusion"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

Doğrusal ekstrüzyon, bir 2D şekli girdi olarak alır ve şekli üçüncü boyutta uzatır.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | LinearExtrusion örneğinin yapıcısı. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(shape, height) | LinearExtrusion örneğinin yapıcısı. |

 **Result:**



---


### getShape{#getShape}

| Ad | Açıklama |
| --- | --- |
| getShape() | Ekstrude edilecek temel şekil. |

 **Result:**



---


### setShape{#setShape}

| Ad | Açıklama |
| --- | --- |
| setShape(value) | Ekstrude edilecek temel şekil. |

 **Result:**



---


### getDirection{#getDirection}

| Ad | Açıklama |
| --- | --- |
| getDirection() | Ekstrüzyon yönü, varsayılan değer (0, 0, 1)'dir. |

 **Result:**



---


### setDirection{#setDirection}

| Ad | Açıklama |
| --- | --- |
| setDirection(value) | Ekstrüzyon yönü, varsayılan değer (0, 0, 1)'dir. |

 **Result:**



---


### getHeight{#getHeight}

| Ad | Açıklama |
| --- | --- |
| getHeight() | Ekstrüde edilen geometrinin yüksekliği, varsayılan değer 1.0. |

 **Result:**



---


### setHeight{#setHeight}

| Ad | Açıklama |
| --- | --- |
| setHeight(value) | Ekstrüde edilen geometrinin yüksekliği, varsayılan değer 1.0. |

 **Result:**



---


### getSlices{#getSlices}

| Ad | Açıklama |
| --- | --- |
| getSlices() | Bükülmüş ekstrüde geometrisinin dilimleri, varsayılan değer 1. |

 **Result:**



---


### setSlices{#setSlices}

| Ad | Açıklama |
| --- | --- |
| setSlices(value) | Bükülmüş ekstrüde geometrisinin dilimleri, varsayılan değer 1. |

 **Result:**



---


### getCenter{#getCenter}

| Ad | Açıklama |
| --- | --- |
| getCenter() | Bu değer false ise, lineer ekstrüzyon Z aralığı 0'dan yüksekliğe, aksi takdirde aralık -yükseklik/2'den yükseklik/2'ye olur. |

 **Result:**



---


### setCenter{#setCenter}

| Ad | Açıklama |
| --- | --- |
| setCenter(value) | Bu değer false ise, lineer ekstrüzyon Z aralığı 0'dan yüksekliğe, aksi takdirde aralık -yükseklik/2'den yükseklik/2'ye olur. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Ad | Açıklama |
| --- | --- |
| getTwistOffset() | Bükülmede kullanılan offset, varsayılan değer (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Ad | Açıklama |
| --- | --- |
| setTwistOffset(value) | Bükülmede kullanılan offset, varsayılan değer (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Ad | Açıklama |
| --- | --- |
| getTwist() | Şeklin ekstrüde edildiği derece sayısı. |

 **Result:**



---


### setTwist{#setTwist}

| Ad | Açıklama |
| --- | --- |
| setTwist(value) | Şeklin ekstrüde edildiği derece sayısı. |

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


### toMesh{#toMesh}

| Ad | Açıklama |
| --- | --- |
| toMesh() | Ekstrüzyonu mesh'e dönüştür. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Ad | Açıklama |
| --- | --- |
| getBoundingBox() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |

 **Result:**
Mesh


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



