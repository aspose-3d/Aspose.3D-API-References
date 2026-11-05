---
title: "CShape"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/cshape/
---
## CShape class

Parametrelerle tanımlanan IFC uyumlu C-şekilli profil. Profilin merkez konumu, sınırlama kutusunun merkezindedir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | CShape yapıcı |

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


### getGirth{#getGirth}

| Ad | Açıklama |
| --- | --- |
| getGirth() | Çevrenin uzunluğunu alır veya ayarlar. |

 **Result:**



---


### setGirth{#setGirth}

| Ad | Açıklama |
| --- | --- |
| setGirth(value) | Çevrenin uzunluğunu alır veya ayarlar. |

 **Result:**



---


### getWallThickness{#getWallThickness}

| Ad | Açıklama |
| --- | --- |
| getWallThickness() | Duvarın kalınlığını alır veya ayarlar. |

 **Result:**



---


### setWallThickness{#setWallThickness}

| Ad | Açıklama |
| --- | --- |
| setWallThickness(value) | Duvarın kalınlığını alır veya ayarlar. |

 **Result:**



---


### getInternalFilletRadius{#getInternalFilletRadius}

| Ad | Açıklama |
| --- | --- |
| getInternalFilletRadius() | İç yuvarlama yarıçapını alır veya ayarlar. |

 **Result:**



---


### setInternalFilletRadius{#setInternalFilletRadius}

| Ad | Açıklama |
| --- | --- |
| setInternalFilletRadius(value) | İç yuvarlama yarıçapını alır veya ayarlar. |

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


### getExtent{#getExtent}

| Ad | Açıklama |
| --- | --- |
| getExtent() | x ve y boyutundaki kapsamı alır. |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Ad | Açıklama |
| --- | --- |
| getEntityRendererKey() | Renderleyicide kayıtlı varlık renderleyicisinin anahtarını alır. |

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



