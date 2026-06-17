---
title: "Bone"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/bone/
---
## Bone class

Bir kemik, geometrinin kontrol noktasının alt kümesini tanımlar ve her kontrol noktası için karışım ağırlığını belirler.  Bone nesnesi doğrudan kullanılamaz, bir SkinDeformer örneği geometriyi deform etmek için kullanılır ve SkinDeformer bir dizi kemik ile birlikte gelir, her kemik bir düğüme bağlanır.  NOT: Bir geometrinin kontrol noktası birden fazla Bone ile ilişkilendirilebilir.


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
| getWeightCount() | Ağırlık sayısını alır, bu setWeight(int, double) tarafından otomatik olarak genişletilir. |

 **Result:**



---


### getTransform{#getTransform}

| Ad | Açıklama |
| --- | --- |
| getTransform() | Bone'u içeren düğümün dönüşüm matrisini alır veya ayarlar. |

 **Result:**



---


### setTransform{#setTransform}

| Ad | Açıklama |
| --- | --- |
| setTransform(value) | Bone'u içeren düğümün dönüşüm matrisini alır veya ayarlar. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Ad | Açıklama |
| --- | --- |
| getBoneTransform() | Bone'un dönüşüm matrisini alır veya ayarlar. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Ad | Açıklama |
| --- | --- |
| setBoneTransform(value) | Bone'un dönüşüm matrisini alır veya ayarlar. |

 **Result:**



---


### getNode{#getNode}

| Ad | Açıklama |
| --- | --- |
| getNode() | Düğümü alır veya ayarlar. bone node, derinin bağlandığı bone'dur, SkinDeformer bone node'u kontrol noktalarının yer değiştirmesini etkilemek için kullanır. bone node genellikle bir Skeleton'a sahiptir, ancak bu zorunlu değildir. Ekli Skeleton genellikle DCC yazılımı tarafından kullanıcıya iskelet gösterimi için kullanılır. |

 **Result:**



---


### setNode{#setNode}

| Ad | Açıklama |
| --- | --- |
| setNode(value) | Düğümü alır veya ayarlar. bone node, derinin bağlandığı bone'dur, SkinDeformer bone node'u kontrol noktalarının yer değiştirmesini etkilemek için kullanır. bone node genellikle bir Skeleton'a sahiptir, ancak bu zorunlu değildir. Ekli Skeleton genellikle DCC yazılımı tarafından kullanıcıya iskelet gösterimi için kullanılır. |

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
| getWeight(index) | Belirtilen indeksle kontrol noktasının ağırlığını alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| indeks | Number | Kontrol noktasının indeksi |

 **Result:**
Number


---


### setWeight{#setWeight}

| Ad | Açıklama |
| --- | --- |
| setWeight(index, weight) | Belirtilen indeksle kontrol noktasının ağırlığını ayarlar |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| indeks | Number | Kontrol noktasının indeksi |
| ağırlık | Number | Yeni ağırlık |

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



