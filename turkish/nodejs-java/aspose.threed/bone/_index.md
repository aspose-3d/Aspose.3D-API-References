---
title: "Bone"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/bone/
---
## Bone class

Bir kemik, geometrinin kontrol noktasının alt kümesini tanımlar ve her kontrol noktası için karışım ağırlığını belirler.  Bone nesnesi doğrudan kullanılamaz, bir SkinDeformer örneği geometrinin deformasyonu için kullanılır ve SkinDeformer bir dizi kemikle birlikte gelir, her kemik bir düğüme bağlanır.  NOT: Bir geometrinin kontrol noktası birden fazla Bone'a bağlanabilir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(name) | Bone sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload() | Bone sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Ad | Açıklama |
| --- | --- |
| getWeightCount() | Ağırlık sayısını alır, bu setWeight(int, double) ile otomatik olarak genişletilir. |

 **Result:**



---


### getTransform{#getTransform}

| Ad | Açıklama |
| --- | --- |
| getTransform() | Kemik içeren düğümün dönüşüm matrisini alır veya ayarlar. |

 **Result:**



---


### setTransform{#setTransform}

| Ad | Açıklama |
| --- | --- |
| setTransform(value) | Kemik içeren düğümün dönüşüm matrisini alır veya ayarlar. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Ad | Açıklama |
| --- | --- |
| getBoneTransform() | Kemiğin dönüşüm matrisini alır veya ayarlar. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Ad | Açıklama |
| --- | --- |
| setBoneTransform(value) | Kemiğin dönüşüm matrisini alır veya ayarlar. |

 **Result:**



---


### getNode{#getNode}

| Ad | Açıklama |
| --- | --- |
| getNode() | Düğümü alır veya ayarlar. Bone node, derinin bağlandığı kemiktir, SkinDeformer bone node'u kontrol noktalarının yer değiştirmesini etkilemek için kullanır. Bone node genellikle bir Skeleton ile ilişkilidir, ancak bu zorunlu değildir. Ekli Skeleton genellikle DCC yazılımı tarafından kullanıcıya iskelet göstermek için kullanılır. |

 **Result:**



---


### setNode{#setNode}

| Ad | Açıklama |
| --- | --- |
| setNode(value) | Düğümü alır veya ayarlar. Bone node, derinin bağlandığı kemiktir, SkinDeformer bone node'u kontrol noktalarının yer değiştirmesini etkilemek için kullanır. Bone node genellikle bir Skeleton ile ilişkilidir, ancak bu zorunlu değildir. Ekli Skeleton genellikle DCC yazılımı tarafından kullanıcıya iskelet göstermek için kullanılır. |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| Ad | Açıklama |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Ad | Açıklama |
| --- | --- |
| getWeight(index) | Belirtilen dizine göre kontrol noktasının ağırlığını alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| indeks | Sayı | Kontrol noktasının dizini |

 **Result:**
Sayı


---


### setWeight{#setWeight}

| Ad | Açıklama |
| --- | --- |
| setWeight(index, weight) | Belirtilen dizine göre kontrol noktasının ağırlığını ayarlar |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| indeks | Sayı | Kontrol noktasının dizini |
| ağırlık | Sayı | Yeni ağırlık |

 **Result:**
Sayı


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



