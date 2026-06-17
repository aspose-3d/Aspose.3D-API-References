---
title: "BoundingBox"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

Eksen hizalı sınırlayıcı kutu


## Properties

| Ad | Açıklama |
| --- | --- |
| NULL | Null sınırlama kutusu |
| INFINITE | Sonsuz sınırlama kutusu |

## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(minimum, maximum) | Verilen minimum ve maksimum köşe ile sonlu bir sınırlama kutusu başlatır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| minimum | Vector3 | Minimum köşe |
| maximum | Vector3 | Maksimum köşe |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Ad | Açıklama |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Verilen minimum ve maksimum köşe ile sonlu bir sınırlama kutusu başlatır |

 **Result:**



---


### getExtent{#getExtent}

| Ad | Açıklama |
| --- | --- |
| getExtent() | Sınırlama kutusunun kapsamını alır. Özelliğin değeri BoundingBoxExtent tam sayı sabitidir. |

 **Result:**



---


### getMinimum{#getMinimum}

| Ad | Açıklama |
| --- | --- |
| getMinimum() | Sınırlama kutusunun minimum köşesi |

 **Result:**



---


### getMaximum{#getMaximum}

| Ad | Açıklama |
| --- | --- |
| getMaximum() | Sınırlama kutusunun maksimum köşesi |

 **Result:**



---


### getSize{#getSize}

| Ad | Açıklama |
| --- | --- |
| getSize() | Sınırlayıcı kutunun boyutu |

 **Result:**



---


### getCenter{#getCenter}

| Ad | Açıklama |
| --- | --- |
| getCenter() | Sınırlayıcı kutunun merkezi. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Ad | Açıklama |
| --- | --- |
| fromGeometry(geometry) | Verilen geometriden bir sınırlayıcı kutu oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| geometr | Geometri | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Sınırlayıcı kutunun dize temsilini alır. |

 **Result:**
String


---


### hashCode{#hashCode}

| Ad | Açıklama |
| --- | --- |
| hashCode() | Bu örnek için hash kodunu döndürür |

 **Result:**
Number


---


### equals{#equals}

| Ad | Açıklama |
| --- | --- |
| equals(obj) | İki nesnenin eşit olup olmadığını belirler |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



