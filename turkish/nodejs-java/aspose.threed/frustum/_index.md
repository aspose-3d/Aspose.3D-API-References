---
title: "Frustum"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/frustum/
---
## Frustum class

Kamera ve Işık sınıflarının temel sınıfı  @hideconstructor


## Yöntemler

### getRotationMode{#getRotationMode}

| Ad | Açıklama |
| --- | --- |
| getRotationMode() | Frustumun yönelim modunu alır veya ayarlar. Bu özellik yalnızca Target null olduğunda çalışır. Değer RotationMode.FIXED_TARGET ise, yön her zaman LookAt özelliği tarafından hesaplanır. Aksi takdirde LookAt her zaman Direction tarafından hesaplanır. Özelliğin değeri RotationMode tamsayı sabitidir. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Ad | Açıklama |
| --- | --- |
| setRotationMode(value) | Frustumun yönelim modunu alır veya ayarlar. Bu özellik yalnızca Target null olduğunda çalışır. Değer RotationMode.FIXED_TARGET ise, yön her zaman LookAt özelliği tarafından hesaplanır. Aksi takdirde LookAt her zaman Direction tarafından hesaplanır. Özelliğin değeri RotationMode tamsayı sabitidir. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Ad | Açıklama |
| --- | --- |
| getNearPlane() | Frustumun yakın düzlem mesafesini alır veya ayarlar. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Ad | Açıklama |
| --- | --- |
| setNearPlane(value) | Frustumun yakın düzlem mesafesini alır veya ayarlar. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Ad | Açıklama |
| --- | --- |
| getFarPlane() | Frustum'un uzak düzlem mesafesini alır veya ayarlar. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Ad | Açıklama |
| --- | --- |
| setFarPlane(value) | Frustum'un uzak düzlem mesafesini alır veya ayarlar. |

 **Result:**



---


### getAspect{#getAspect}

| Ad | Açıklama |
| --- | --- |
| getAspect() | Frustumun en‑boy oranını alır veya ayarlar. |

 **Result:**



---


### setAspect{#setAspect}

| Ad | Açıklama |
| --- | --- |
| setAspect(value) | Frustumun en‑boy oranını alır veya ayarlar. |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Ad | Açıklama |
| --- | --- |
| getOrthoHeight() | Frustum ortografik projeksiyonda iken yüksekliği alır veya ayarlar. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Ad | Açıklama |
| --- | --- |
| setOrthoHeight(value) | Frustum ortografik projeksiyonda iken yüksekliği alır veya ayarlar. |

 **Result:**



---


### getUp{#getUp}

| Ad | Açıklama |
| --- | --- |
| getUp() | Kameranın yukarı yönünü alır veya ayarlar. |

 **Result:**



---


### setUp{#setUp}

| Ad | Açıklama |
| --- | --- |
| setUp(value) | Kameranın yukarı yönünü alır veya ayarlar. |

 **Result:**



---


### getLookAt{#getLookAt}

| Ad | Açıklama |
| --- | --- |
| getLookAt() | Kameranın baktığı ilgili konumu alır veya ayarlar. |

 **Result:**



---


### setLookAt{#setLookAt}

| Ad | Açıklama |
| --- | --- |
| setLookAt(value) | Kameranın baktığı ilgili konumu alır veya ayarlar. |

 **Result:**



---


### getDirection{#getDirection}

| Ad | Açıklama |
| --- | --- |
| getDirection() | Kameranın baktığı yönü alır veya ayarlar. Bu özelliğin değişiklikleri LookAt ve Target'ı da etkiler. |

 **Result:**



---


### setDirection{#setDirection}

| Ad | Açıklama |
| --- | --- |
| setDirection(value) | Kameranın baktığı yönü alır veya ayarlar. Bu özelliğin değişiklikleri LookAt ve Target'ı da etkiler. |

 **Result:**



---


### getTarget{#getTarget}

| Ad | Açıklama |
| --- | --- |
| getTarget() | Kameranın baktığı hedefi alır veya ayarlar. Kullanıcı bu özelliği destekliyorsa, LookAt özelliğinden önce gelmelidir. |

 **Result:**



---


### setTarget{#setTarget}

| Ad | Açıklama |
| --- | --- |
| setTarget(value) | Kameranın baktığı hedefi alır veya ayarlar. Kullanıcı bu özelliği destekliyorsa, LookAt özelliğinden önce gelmelidir. |

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


### getBoundingBox{#getBoundingBox}

| Ad | Açıklama |
| --- | --- |
| getBoundingBox() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |

 **Result:**



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



