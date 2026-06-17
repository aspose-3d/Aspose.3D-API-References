---
title: "MorphTargetChannel"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

Bir MorphTargetChannel, hedef geometrileri düzenlemek için MorphTargetDeformer tarafından kullanılır. FBX gibi bazı dosya formatları paralel olarak birden fazla kanal destekler. Ağırlık 0 ile 1.0 arasındadır ve hedef için varsayılan ağırlık 0.0'dır;


## Properties

| Ad | Açıklama |
| --- | --- |
| DEFAULT_WEIGHT | Morph hedefi için varsayılan ağırlık. |

## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(name) | MorphTargetChannel sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload() | MorphTargetChannel sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### getWeights{#getWeights}

| Ad | Açıklama |
| --- | --- |
| getWeights() | Hedef geometrilerin tam ağırlık değerlerini alır. Tam ağırlıklar. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Ad | Açıklama |
| --- | --- |
| getChannelWeight() | Bu kanalın deformasyon ağırlığını alır veya ayarlar. Ağırlık 0.0 ile 1.0 arasındadır. |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Ad | Açıklama |
| --- | --- |
| setChannelWeight(value) | Bu kanalın deformasyon ağırlığını alır veya ayarlar. Ağırlık 0.0 ile 1.0 arasındadır. |

 **Result:**



---


### getTargets{#getTargets}

| Ad | Açıklama |
| --- | --- |
| getTargets() | Kanal ile ilişkili tüm hedefleri alır. |

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


### get{#get}

| Ad | Açıklama |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| Ad | Açıklama |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Ad | Açıklama |
| --- | --- |
| getWeight(target) | Belirtilen target için ağırlığı alır, target bu kanala ait değilse, varsayılan değer 0 döndürülür. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| targe | Şekil | null |

 **Result:**
Number


---


### setWeight{#setWeight}

| Ad | Açıklama |
| --- | --- |
| setWeight(target, weight) | Belirtilen target için ağırlığı ayarlar, varsayılan değer 1'dir, aralık 0~1 arasında olmalıdır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| targe | Şekil | null |
| ağırlık | Number | null |

 **Result:**
Number


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



