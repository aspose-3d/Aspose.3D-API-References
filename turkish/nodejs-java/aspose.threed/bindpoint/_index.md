---
title: "BindPoint"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

Bir BindPoint genellikle bir nesnenin özelliği üzerinde oluşturulur, bazı özellik tipleri birden fazla bileşen alanı içerir (örneğin bir Vector3 alanı), BindPoint her bileşen alanı için bir kanal oluşturur ve alanı bir veya daha fazla anahtar kare sekans örneğiyle kanallar aracılığıyla bağlar.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(scene, prop) | BindPoint sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| scene | Scene | Animasyonu içeren sahne. |
| prop | Property | Özellik. |

 **Result:**



---


### getProperty{#getProperty}

| Ad | Açıklama |
| --- | --- |
| getProperty() | CurveMapping ile ilişkili özelliği alır. |

 **Result:**



---


### setProperty{#setProperty}

| Ad | Açıklama |
| --- | --- |
| setProperty(value) | CurveMapping ile ilişkili özelliği alır. |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Ad | Açıklama |
| --- | --- |
| getChannelsCount() | Bu animasyon eğri eşlemesinde tanımlanan toplam özellik kanalı sayısını alır. |

 **Result:**
Number


---


### getName{#getName}

| Ad | Açıklama |
| --- | --- |
| getName() | Adı alır veya ayarlar. Ad. |

 **Result:**
Number


---


### setName{#setName}

| Ad | Açıklama |
| --- | --- |
| setName(value) | Adı alır veya ayarlar. Ad. |

 **Result:**
Number


---


### getProperties{#getProperties}

| Ad | Açıklama |
| --- | --- |
| getProperties() | Tüm özelliklerin koleksiyonunu alır. |

 **Result:**
Number


---


### get{#get}

| Ad | Açıklama |
| --- | --- |
| get(channelName) |  |

 **Result:**
Number


---


### getKeyframeSequence{#getKeyframeSequence}

| Ad | Açıklama |
| --- | --- |
| getKeyframeSequence(channelName) | Belirtilen kanaldaki ilk anahtar kare dizisini alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| channelName | String | Bulunacak kanal adı |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Ad | Açıklama |
| --- | --- |
| getKeyframeSequences(channelName) | Belirtilen kanaldaki tüm anahtar kare dizilerini alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| channelName | String | Bulunacak kanal adı |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Ad | Açıklama |
| --- | --- |
| createKeyframeSequence(name) | Yeni bir eğri oluşturur ve eğri eşlemesinin ilk kanalına bağlar |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Yeni dizinin adı. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Ad | Açıklama |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Anahtar kare dizisini belirtilen kanala bağla |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| channelName | String | Anahtar kare dizisinin bağlanacağı kanal |
| dizi | KeyframeSequence | Bağlanacak anahtar kare dizisi |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Ad | Açıklama |
| --- | --- |
| getChannel(channelName) | Verilen adla kanalı alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| channelName | String | Bulunacak kanal adı |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Ad | Açıklama |
| --- | --- |
| addChannel(name, value) | Belirtilen kanal özelliğini ekler. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad. |
| değer | Object | Değer. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Ad | Açıklama |
| --- | --- |
| addChannel(name, type, value) | Belirtilen kanal özelliğini ekler. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad. |
| type | Sınıf | Tür. |
| değer | Object | Değer. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Ad | Açıklama |
| --- | --- |
| resetChannels() | Bu animasyon eğri eşlemesinin özellik kanallarını boşaltır. |

 **Result:**
boolean


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Nesneyi dizeye biçimlendir |

 **Result:**
String


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



