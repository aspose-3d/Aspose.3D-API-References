---
title: "LShape"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/lshape/
---
## LShape class

Parametrelerle tanımlanan IFC uyumlu L-şekilli profil.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | LShape yapıcı |

 **Result:**



---


### getDepth{#getDepth}

| Ad | Açıklama |
| --- | --- |
| getDepth() | Profilin derinliğini alır veya ayarlar. |

 **Result:**



---


### setDepth{#setDepth}

| Ad | Açıklama |
| --- | --- |
| setDepth(value) | Profilin derinliğini alır veya ayarlar. |

 **Result:**



---


### getWidth{#getWidth}

| Ad | Açıklama |
| --- | --- |
| getWidth() | Profilin genişliğini alır veya ayarlar. |

 **Result:**



---


### setWidth{#setWidth}

| Ad | Açıklama |
| --- | --- |
| setWidth(value) | Profilin genişliğini alır veya ayarlar. |

 **Result:**



---


### getThickness{#getThickness}

| Ad | Açıklama |
| --- | --- |
| getThickness() | Sabit duvarın kalınlığını alır veya ayarlar. |

 **Result:**



---


### setThickness{#setThickness}

| Ad | Açıklama |
| --- | --- |
| setThickness(value) | Sabit duvarın kalınlığını alır veya ayarlar. |

 **Result:**



---


### getFilletRadius{#getFilletRadius}

| Ad | Açıklama |
| --- | --- |
| getFilletRadius() | Yuvarlamanın yarıçapını alır veya ayarlar. |

 **Result:**



---


### setFilletRadius{#setFilletRadius}

| Ad | Açıklama |
| --- | --- |
| setFilletRadius(value) | Yuvarlamanın yarıçapını alır veya ayarlar. |

 **Result:**



---


### getEdgeRadius{#getEdgeRadius}

| Ad | Açıklama |
| --- | --- |
| getEdgeRadius() | Kenarın yarıçapını alır veya ayarlar. |

 **Result:**



---


### setEdgeRadius{#setEdgeRadius}

| Ad | Açıklama |
| --- | --- |
| setEdgeRadius(value) | Kenarın yarıçapını alır veya ayarlar. |

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


### getExtent{#getExtent}

| Ad | Açıklama |
| --- | --- |
| getExtent() | X ve y boyutundaki kapsamı alır. |

 **Result:**
Vector2


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



