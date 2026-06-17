---
title: "TransformBuilder"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

TransformBuilder, bir dizi dönüşümle transform matrisini oluşturmak için kullanılır.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(initial, order) | Belirtilen başlangıç dönüşüm matrisine ve belirli bir birleştirme sırasına sahip bir TransformBuilder oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| initia | Matrix4 | null |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(order) | Başlangıç kimlik dönüşüm matrisine ve belirtilen birleştirme sırasına sahip bir TransformBuilder oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Ad | Açıklama |
| --- | --- |
| getMatrix() | Geçerli matris değerini alır veya ayarlar. |

 **Result:**



---


### setMatrix{#setMatrix}

| Ad | Açıklama |
| --- | --- |
| setMatrix(value) | Geçerli matris değerini alır veya ayarlar. |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Ad | Açıklama |
| --- | --- |
| getComposeOrder() | Zincir birleştirme sırasını alır veya ayarlar. Özelliğin değeri ComposeOrder tamsayı sabitidir. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Ad | Açıklama |
| --- | --- |
| setComposeOrder(value) | Zincir birleştirme sırasını alır veya ayarlar. Özelliğin değeri ComposeOrder tamsayı sabitidir. |

 **Result:**



---


### compose{#compose}

| Ad | Açıklama |
| --- | --- |
| compose(m) | Argümanı iç matrisine ekle veya ön ekle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Ad | Açıklama |
| --- | --- |
| append(m) | Yeni dönüşüm matrisini dönüşüm zincirine ekle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Ad | Açıklama |
| --- | --- |
| prepend(m) | Yeni dönüşüm matrisini dönüşüm zincirine ekle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Ad | Açıklama |
| --- | --- |
| rearrange(newX, newY, newZ) | Eksenin düzenini yeniden düzenle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| newX | Eksen | Eksen |
| newY | Eksen | Eksen |
| newZ | Eksen | Eksen |

 **Result:**



---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(s) | Bir bileşeni s ile ölçeklendirilmiş bir ölçekleme dönüşüm matrisini zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(x, y, z) | Bir ölçekleme dönüşüm matrisini zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(s) | Bir ölçek dönüşümünü zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Ad | Açıklama |
| --- | --- |
| rotateDegree(angle, axis) | Derece cinsinden bir döndürme dönüşümünü zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| açı | Number | Derece cinsinden döndürme açısı. |
| eksen | Vector3 | Döndürülecek eksen. |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Ad | Açıklama |
| --- | --- |
| rotateRadian(angle, axis) | Radyan cinsinden bir döndürme dönüşümünü zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| açı | Number | Radyan cinsinden döndürme açısı. |
| eksen | Vector3 | Döndürülecek eksen. |

 **Result:**



---


### rotate{#rotate}

| Ad | Açıklama |
| --- | --- |
| rotate(q) | Bir kuaternion ile döndürmeyi zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Kuatör | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Ad | Açıklama |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Derece cinsinden Euler açılarıyla bir döndürmeyi zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| deg | Number | null |
| deg | Number | null |
| deg | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Ad | Açıklama |
| --- | --- |
| rotateEulerRadian(x, y, z) | Radyan cinsinden Euler açılarıyla bir döndürmeyi zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Ad | Açıklama |
| --- | --- |
| rotateEulerRadian(r) | Radyan cinsinden Euler açılarıyla bir döndürmeyi zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Ad | Açıklama |
| --- | --- |
| translate(tx, ty, tz) | Bir çeviri dönüşümünü zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**



---


### translate{#translate}

| Ad | Açıklama |
| --- | --- |
| translate(v) | Bir çeviri dönüşümünü zincirle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Ad | Açıklama |
| --- | --- |
| reset() | Dönüşümü birim matrisine sıfırla. |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Ad | Açıklama |
| --- | --- |
| rotateDegree(rot, order) | Belirtilen sırayla döndürmeyi ekle |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rot | Vector3 | Derece cinsinden dönüş |
| order | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Ad | Açıklama |
| --- | --- |
| rotateRadian(rot, order) | Belirtilen sırayla döndürmeyi ekle |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rot | Vector3 | Radyan cinsinden dönüş |
| order | RotationOrder | RotationOrder |

 **Result:**



---



