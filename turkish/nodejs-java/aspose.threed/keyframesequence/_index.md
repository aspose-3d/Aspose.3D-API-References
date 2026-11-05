---
title: "KeyframeSequence"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

Anahtar karelerin dizisi, örneklenen bir değerin zaman içindeki dönüşümünü açıklar.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(name) | KeyframeSequence sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload() | KeyframeSequence sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Ad | Açıklama |
| --- | --- |
| getBindPoint() | Bu eğriyi sahip olan özellik bağlama noktasını alır |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Ad | Açıklama |
| --- | --- |
| getKeyFrames() | Bu eğrinin anahtar karelerini alır. Anahtarlar. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Ad | Açıklama |
| --- | --- |
| getPostBehavior() | Post davranışı alır, bu son anahtar kareden sonra örneklenen değerin ne olması gerektiğini gösterir. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Ad | Açıklama |
| --- | --- |
| getPreBehavior() | Pre davranışı alır, bu ilk anahtardan önce örneklenen değerin ne olması gerektiğini gösterir. |

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


### add{#add}

| Ad | Açıklama |
| --- | --- |
| add(time, value) | Belirtilen değerle yeni bir anahtar kare oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| zaman | Sayı | Zaman konumu (saniye cinsinden ölçülür) |
| değer | Sayı | Bu zaman konumundaki değer |

 **Result:**



---


### add{#add}

| Ad | Açıklama |
| --- | --- |
| add(time, value, interpolation) | Belirtilen değerle yeni bir anahtar kare oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| zaman | Sayı | Zaman konumu (saniye cinsinden ölçülür) |
| değer | Sayı | Bu zaman konumundaki değer |
| interpolasyon | Interpolasyon | Interpolasyon |

 **Result:**



---


### reset{#reset}

| Ad | Açıklama |
| --- | --- |
| reset() | Tüm anahtar kareleri kaldırır ve post/pre davranışlarını sıfırlar. |

 **Result:**



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


### iterator{#iterator}

| Ad | Açıklama |
| --- | --- |
| iterator() | Dahili kullanım için ayrılmıştır. |

 **Result:**
Özellik


---



