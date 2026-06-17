---
title: "TransformedCurve"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/transformedcurve/
---
## TransformedCurve class

Bir TransformedCurve, bir dönüşüm matrisi kullanarak bir eğriye konum verir. Bu, bir TrimmedCurve veya CompositeCurve içinde dönüşüm yapmaya olanak tanır.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | TransformedCurve'in yapıcı metodu |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(basisCurve, transformation) | TransformedCurve'in yapıcı metodu |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Ad | Açıklama |
| --- | --- |
| getTransformMatrix() | Dönüşüm matrisi. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Ad | Açıklama |
| --- | --- |
| setTransformMatrix(value) | Dönüşüm matrisi. |

 **Result:**



---


### getBasisCurve{#getBasisCurve}

| Ad | Açıklama |
| --- | --- |
| getBasisCurve() | Temel eğri. |

 **Result:**



---


### setBasisCurve{#setBasisCurve}

| Ad | Açıklama |
| --- | --- |
| setBasisCurve(value) | Temel eğri. |

 **Result:**



---


### getColor{#getColor}

| Ad | Açıklama |
| --- | --- |
| getColor() | Çizginin rengini alır veya ayarlar, varsayılan değer beyazdır (1, 1, 1). |

 **Result:**



---


### setColor{#setColor}

| Ad | Açıklama |
| --- | --- |
| setColor(value) | Çizginin rengini alır veya ayarlar, varsayılan değer beyazdır (1, 1, 1). |

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


### getEntityRendererKey{#getEntityRendererKey}

| Ad | Açıklama |
| --- | --- |
| getEntityRendererKey() | Renderörde kaydedilen varlık renderlayıcısının anahtarını alır. |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Ad | Açıklama |
| --- | --- |
| getBoundingBox() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |

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



