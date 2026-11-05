---
title: "AnimationNode"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D, animasyon hiyerarşisini destekler, her animasyon birkaç animasyon ve animasyonun anahtar kare tanımıyla oluşturulabilir.  AnimationNode, bir özelliğin değerinin zaman içindeki dönüşümünü tanımlar; örneğin, animasyon düğümü bir düğümün dönüşümünü veya diğer A3DObject nesnesinin sayısal özelliklerini kontrol etmek için kullanılabilir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(name) | AnimationNode sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload() | AnimationNode sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Ad | Açıklama |
| --- | --- |
| getBindPoints() | Mevcut özellik bağlama noktalarını alır |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Ad | Açıklama |
| --- | --- |
| getSubAnimations() | Mevcut animasyonların altındaki alt animasyon düğümlerini alır |

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


### findBindPoint{#findBindPoint}

| Ad | Açıklama |
| --- | --- |
| findBindPoint(name) | Bağlama noktasını ada göre bulur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Bulunacak bağlama noktasının adı. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Ad | Açıklama |
| --- | --- |
| getBindPoint(target, propName, create) | Verilen özellikteki animasyon bağlama noktasını alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| target | A3DObject | Bağlama noktasının oluşturulacağı nesne. |
| propName | String | Özelliğin adı. |
| create | boolean | Eğer ayarlanırsa |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Ad | Açıklama |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Verilen özellik ve kanal için anahtar kare dizisini alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| target | A3DObject | Anahtar kare dizisinin oluşturulacağı örnek. |
| propName | String | Özelliğin adı. |
| channelName | String | Kanalın adı. |
| create | boolean | Eğer ayarlanırsa |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Ad | Açıklama |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Verilen özellik için anahtar kare dizisini alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| target | A3DObject | Anahtar kare dizisinin oluşturulacağı örnek. |
| propName | String | Özelliğin adı. |
| create | boolean | Eğer ayarlanırsa |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Ad | Açıklama |
| --- | --- |
| createBindPoint(obj, propName) | Özellik veri tipine göre bir BindPoint oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| obj | A3DObject | Nesne. |
| propName | String | Özellik adı. |

 **Result:**
BindPoint


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



