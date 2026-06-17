---
title: "Dönüştürme"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/transform/
---
## Transform class

Bir transform, nesnenin çeviri/ölçekleme/döndürme veya transform matrisine minimum maliyetle erişim sağlayan bilgileri içerir. Bu, yerel transform tarafından kullanılır.  @hideconstructor


## Yöntemler

### getGeometricTranslation{#getGeometricTranslation}

| Ad | Açıklama |
| --- | --- |
| getGeometricTranslation() | Geometrik çeviriyi alır veya ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Desteklemeyen dosya türlerine geometrik dönüşümü dışa aktarırken, yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Ad | Açıklama |
| --- | --- |
| setGeometricTranslation(value) | Geometrik çeviriyi alır veya ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Desteklemeyen dosya türlerine geometrik dönüşümü dışa aktarırken, yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| Ad | Açıklama |
| --- | --- |
| getGeometricScaling() | Geometrik ölçeklemeyi alır veya ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Desteklemeyen dosya türlerine geometrik dönüşümü dışa aktarırken, yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Ad | Açıklama |
| --- | --- |
| setGeometricScaling(value) | Geometrik ölçeklemeyi alır veya ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Desteklemeyen dosya türlerine geometrik dönüşümü dışa aktarırken, yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| Ad | Açıklama |
| --- | --- |
| getGeometricRotation() | Geometrik Euler dönüşümünü (derece cinsinden ölçülür) alır veya ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Desteklemeyen dosya türlerine geometrik dönüşümü dışa aktarırken, yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Ad | Açıklama |
| --- | --- |
| setGeometricRotation(value) | Geometrik Euler dönüşümünü (derece cinsinden ölçülür) alır veya ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Desteklemeyen dosya türlerine geometrik dönüşümü dışa aktarırken, yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### getTranslation{#getTranslation}

| Ad | Açıklama |
| --- | --- |
| getTranslation() | Öteleme alır veya ayarlar |

 **Result:**



---


### setTranslation{#setTranslation}

| Ad | Açıklama |
| --- | --- |
| setTranslation(value) | Öteleme alır veya ayarlar |

 **Result:**



---


### getScale{#getScale}

| Ad | Açıklama |
| --- | --- |
| getScale() | Ölçeği alır veya ayarlar |

 **Result:**



---


### setScale{#setScale}

| Ad | Açıklama |
| --- | --- |
| setScale(value) | Ölçeği alır veya ayarlar |

 **Result:**



---


### getPreRotation{#getPreRotation}

| Ad | Açıklama |
| --- | --- |
| getPreRotation() | Derece cinsinden temsil edilen ön-rotasyonu alır veya ayarlar |

 **Result:**



---


### setPreRotation{#setPreRotation}

| Ad | Açıklama |
| --- | --- |
| setPreRotation(value) | Derece cinsinden temsil edilen ön-rotasyonu alır veya ayarlar |

 **Result:**



---


### getPostRotation{#getPostRotation}

| Ad | Açıklama |
| --- | --- |
| getPostRotation() | Derece cinsinden temsil edilen son-rotasyonu alır veya ayarlar |

 **Result:**



---


### setPostRotation{#setPostRotation}

| Ad | Açıklama |
| --- | --- |
| setPostRotation(value) | Derece cinsinden temsil edilen son-rotasyonu alır veya ayarlar |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| Ad | Açıklama |
| --- | --- |
| getEulerAngles() | Derece cinsinden ölçülen Euler açılarıyla temsil edilen rotasyonu alır veya ayarlar |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| Ad | Açıklama |
| --- | --- |
| setEulerAngles(value) | Derece cinsinden ölçülen Euler açılarıyla temsil edilen rotasyonu alır veya ayarlar |

 **Result:**



---


### getRotation{#getRotation}

| Ad | Açıklama |
| --- | --- |
| getRotation() | Kuatör içinde temsil edilen rotasyonu alır veya ayarlar. |

 **Result:**



---


### setRotation{#setRotation}

| Ad | Açıklama |
| --- | --- |
| setRotation(value) | Kuatör içinde temsil edilen rotasyonu alır veya ayarlar. |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Ad | Açıklama |
| --- | --- |
| getTransformMatrix() | Dönüşüm matrisini alır veya ayarlar. Buna atama yapmak, Translation, Scale ve Rotation'ı sıfırlar, GeometricRotation, GeometricScaling ve GeometricTranslation etkilenmez. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Ad | Açıklama |
| --- | --- |
| setTransformMatrix(value) | Dönüşüm matrisini alır veya ayarlar. Buna atama yapmak, Translation, Scale ve Rotation'ı sıfırlar, GeometricRotation, GeometricScaling ve GeometricTranslation etkilenmez. |

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


### setGeometricTranslation{#setGeometricTranslation}

| Ad | Açıklama |
| --- | --- |
| setGeometricTranslation(x, y, z) | Geometric translation ayarlar. Geometric transformation yalnızca ekli varlıkları etkiler ve child nodes'ı etkilemez. Geometric transformation'ı desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Ad | Açıklama |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | Geometric scaling ayarlar. Geometric transformation yalnızca ekli varlıkları etkiler ve child nodes'ı etkilemez. Geometric transformation'ı desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Ad | Açıklama |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | Geometric Euler rotation'ı (derece cinsinden ölçülen) ayarlar. Geometric transformation yalnızca ekli varlıkları etkiler ve child nodes'ı etkilemez. Geometric transformation'ı desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir. |

 **Result:**



---


### setTranslation{#setTranslation}

| Ad | Açıklama |
| --- | --- |
| setTranslation(tx, ty, tz) | Mevcut dönüşümün ötelemesini ayarlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**
Dönüştürme


---


### setScale{#setScale}

| Ad | Açıklama |
| --- | --- |
| setScale(sx, sy, sz) | Mevcut dönüşümün ölçeğini ayarlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| s | Number | null |
| s | Number | null |
| s | Number | null |

 **Result:**
Dönüştürme


---


### setEulerAngles{#setEulerAngles}

| Ad | Açıklama |
| --- | --- |
| setEulerAngles(rx, ry, rz) | Geçerli dönüşümün Euler açılarını derece cinsinden ayarlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| r | Number | null |
| r | Number | null |
| r | Number | null |

 **Result:**
Dönüştürme


---


### setRotation{#setRotation}

| Ad | Açıklama |
| --- | --- |
| setRotation(rw, rx, ry, rz) | Geçerli dönüşümün dönüşünü (kuaternion bileşenleri olarak) ayarlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| r | Number | null |
| r | Number | null |
| r | Number | null |
| r | Number | null |

 **Result:**
Dönüştürme


---


### setPreRotation{#setPreRotation}

| Ad | Açıklama |
| --- | --- |
| setPreRotation(rx, ry, rz) | Derece cinsinden temsil edilen ön dönüşümü ayarlar. |

 **Result:**
Dönüştürme


---


### setPostRotation{#setPostRotation}

| Ad | Açıklama |
| --- | --- |
| setPostRotation(rx, ry, rz) | Derece cinsinden temsil edilen son dönüşümü ayarlar. |

 **Result:**
Dönüştürme


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



