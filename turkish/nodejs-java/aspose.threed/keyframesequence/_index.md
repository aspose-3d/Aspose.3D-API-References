---
title: "KeyframeSequence"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

Anahtar karelerin dizisi, örneklenmiş bir değerin zaman içinde dönüşümünü açıklar.


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
| getPostBehavior() | Post davranışı alır; bu, örneklenen değerin son anahtar kareden sonra ne olması gerektiğini gösterir. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Ad | Açıklama |
| --- | --- |
| getPreBehavior() | Pre davranışı alır; bu, örneklenen değerin ilk anahtar kareden önce ne olması gerektiğini gösterir. |

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
| add(time, value) | Belirtilen değerle yeni bir anahtar kare oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| time | Number | Zaman konumu(saniye cinsinden ölçülür) |
| değer | Number | Bu zaman konumundaki değer |

 **Result:**



---


### add{#add}

| Ad | Açıklama |
| --- | --- |
| add(time, value, interpolation) | Belirtilen değerle yeni bir anahtar kare oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| time | Number | Zaman konumu(saniye cinsinden ölçülür) |
| değer | Number | Bu zaman konumundaki değer |
| enterpolasyon | Enterpolasyon | Enterpolasyon |

 **Result:**



---


### reset{#reset}

| Ad | Açıklama |
| --- | --- |
| reset() | Tüm anahtar kareleri kaldırır ve post/ön davranışları sıfırlar. |

 **Result:**



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



