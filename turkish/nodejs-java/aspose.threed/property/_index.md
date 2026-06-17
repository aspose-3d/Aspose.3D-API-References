---
title: "Property"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/property/
---
## Property class

Kullanıcı tanımlı özellikleri tutmak için sınıf.  @hideconstructor


## Yöntemler

### getValue{#getValue}

| Ad | Açıklama |
| --- | --- |
| getValue() | Değeri alır veya ayarlar. Değer. |

 **Result:**



---


### setValue{#setValue}

| Ad | Açıklama |
| --- | --- |
| setValue(value) | Değeri alır veya ayarlar. Değer. |

 **Result:**



---


### setName{#setName}

| Ad | Açıklama |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Ad | Açıklama |
| --- | --- |
| getValueType() | Özellik değerinin tipini alır. Değerin tipi. |

 **Result:**



---


### getProperties{#getProperties}

| Ad | Açıklama |
| --- | --- |
| getProperties() | Tüm özelliklerin koleksiyonunu alır. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Ad | Açıklama |
| --- | --- |
| getBindPoint(anim, create) | Belirtilen animasyon örneğinde özelliğin bağlama noktasını alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| anim | AnimationNode | Bağlama noktasını oluşturmak için hangi animasyon? |
| oluştur | boolean | Özellik bağlama noktasını bulunamazsa oluştur. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Ad | Açıklama |
| --- | --- |
| getKeyframeSequence(anim, create) | Belirtilen animasyon örneğinde anahtar kare dizisini alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| anim | AnimationNode | Anahtar kare dizisini oluşturmak için hangi animasyon? |
| oluştur | boolean | Anahtar kare dizisi bulunamazsa oluştur. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Geçerli Özelliği temsil eden bir dize döndürür. |

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



