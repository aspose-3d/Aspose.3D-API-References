---
title: "BoundingBox2D"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Vector2 için eksen hizalı sınırlayıcı kutu


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
| minimum | Vector2 | Minimum köşe |
| maximum | Vector2 | Maksimum köşe |

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


### merge{#merge}

| Ad | Açıklama |
| --- | --- |
| merge(pt) | Yeni kutuyu mevcut sınırlama kutusuna birleştirir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Ad | Açıklama |
| --- | --- |
| merge(bb) | Yeni kutuyu mevcut sınırlama kutusuna birleştirir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Sınırlayıcı kutunun dize temsilini alır. |

 **Result:**
String


---



