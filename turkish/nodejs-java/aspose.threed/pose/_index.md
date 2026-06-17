---
title: "Pose"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/pose/
---
## Pose class

Poz, geometri skinlendiğinde dönüşüm matrisini depolamak için kullanılır. Poz, bir dizi BonePose'dan oluşur; her BonePose, kemik düğümünün somut dönüşüm bilgilerini kaydeder.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(name) | Pose sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload() | Pose sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### getPoseType{#getPoseType}

| Ad | Açıklama |
| --- | --- |
| getPoseType() | Pozun tipini alır veya ayarlar. Özelliğin değeri PoseType tamsayı sabitidir. Pozun tipi. |

 **Result:**



---


### setPoseType{#setPoseType}

| Ad | Açıklama |
| --- | --- |
| setPoseType(value) | Pozun tipini alır veya ayarlar. Özelliğin değeri PoseType tamsayı sabitidir. Pozun tipi. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Ad | Açıklama |
| --- | --- |
| getBonePoses() | Tüm BonePose'ları alır. Düğümler. |

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


### addBonePose{#addBonePose}

| Ad | Açıklama |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Verilen kemik düğümü için poz dönüşüm matrisini kaydeder. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| düğüm | Düğüm | Kemik Düğümü. |
| matrix | Matrix4 | Dönüşüm matrisi. |
| localMatrix | boolean | Eğer ayarlanırsa |

 **Result:**



---


### addBonePose{#addBonePose}

| Ad | Açıklama |
| --- | --- |
| addBonePose(node, matrix) | Verilen kemik düğümü için poz dönüşüm matrisini kaydeder. Küresel dönüşüm matrisi ima edilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| düğüm | Düğüm | Kemik Düğümü. |
| matrix | Matrix4 | Dönüşüm matrisi. |

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



