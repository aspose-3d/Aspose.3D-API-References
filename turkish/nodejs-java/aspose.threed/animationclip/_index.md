---
title: "AnimationClip"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Animasyon klibi, animasyonların bir koleksiyonudur.  Sahne bir veya daha fazla animasyon klibi içerebilir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | AnimationClip sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(name) | AnimationClip sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad |

 **Result:**



---


### getAnimations{#getAnimations}

| Ad | Açıklama |
| --- | --- |
| getAnimations() | Klip içinde bulunan animasyonları alır. Katmanlar. |

 **Result:**



---


### getDescription{#getDescription}

| Ad | Açıklama |
| --- | --- |
| getDescription() | Bu animasyon klibinin açıklamasını alır veya ayarlar |

 **Result:**



---


### setDescription{#setDescription}

| Ad | Açıklama |
| --- | --- |
| setDescription(value) | Bu animasyon klibinin açıklamasını alır veya ayarlar |

 **Result:**



---


### getStart{#getStart}

| Ad | Açıklama |
| --- | --- |
| getStart() | Klipin başlangıç zamanını saniye cinsinden alır veya ayarlar. |

 **Result:**



---


### setStart{#setStart}

| Ad | Açıklama |
| --- | --- |
| setStart(value) | Klipin başlangıç zamanını saniye cinsinden alır veya ayarlar. |

 **Result:**



---


### getStop{#getStop}

| Ad | Açıklama |
| --- | --- |
| getStop() | Klipin bitiş zamanını saniye cinsinden alır veya ayarlar. |

 **Result:**



---


### setStop{#setStop}

| Ad | Açıklama |
| --- | --- |
| setStop(value) | Klipin bitiş zamanını saniye cinsinden alır veya ayarlar. |

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


### createAnimationNode{#createAnimationNode}

| Ad | Açıklama |
| --- | --- |
| createAnimationNode(nodeName) | Mevcut klip üzerinde animasyon düğümünü oluşturmak ve kaydetmek için bir kısayol işlevi. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nodeName | String | Yeni animasyon düğümünün adı |

 **Result:**
AnimationNode


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



