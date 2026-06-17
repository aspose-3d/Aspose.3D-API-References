---
title: "Vector3"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Üç bileşenli bir vektör.


## Properties

| Ad | Açıklama |
| --- | --- |
| x | x bileşeni. |
| y | y bileşeni. |
| z | z bileşeni. |
| ORIGIN | Orijin konumunu alır. Orijin. |
| UNIT_SCALE | Birim ölçek vektörünü alır. |
| X_AXIS | X eksenini alır. X ekseni. |
| Y_AXIS | Y eksenini alır. Y ekseni. |
| Z_AXIS | Z eksenini alır. Z ekseni. |

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
| constructor_overload(x, y, z) | Vector3 yapısının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| x | Number | x koordinatı. |
| y | Number | y koordinatı. |
| z | Number | z koordinatı. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Ad | Açıklama |
| --- | --- |
| constructor_overload2(vec) | Vector3 yapısının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| vec | FVector3 | x koordinatı. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Ad | Açıklama |
| --- | --- |
| constructor_overload3(v) | Vector3 yapısının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| v | Number | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Ad | Açıklama |
| --- | --- |
| constructor_overload4(vec4) | Vector3 yapısının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Ad | Açıklama |
| --- | --- |
| getLength2() | Uzunluğun karesini alır. length2. |

 **Result:**



---


### getLength{#getLength}

| Ad | Açıklama |
| --- | --- |
| getLength() | Bu vektörün uzunluğunu alır. Uzunluk. |

 **Result:**



---


### equals{#equals}

| Ad | Açıklama |
| --- | --- |
| equals(obj) | İki vector3 eşit mi kontrol et |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| obj | Object | Eşitliği kontrol etmek için nesne. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Ad | Açıklama |
| --- | --- |
| hashCode() | Vector3'ün hash kodunu alır. |

 **Result:**
Number


---


### dot{#dot}

| Ad | Açıklama |
| --- | --- |
| dot(rhs) | İki vektörün noktasal çarpımını alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rhs | Vector3 | Sağ taraf değeri. |

 **Result:**
Number


---


### normalize{#normalize}

| Ad | Açıklama |
| --- | --- |
| normalize() | Bu örneği normalleştirir. |

 **Result:**
Vector3


---


### sin{#sin}

| Ad | Açıklama |
| --- | --- |
| sin() | Her bileşende sinüs hesaplar. |

 **Result:**
Vector3


---


### cos{#cos}

| Ad | Açıklama |
| --- | --- |
| cos() | Her bileşende kosinüs hesaplar. |

 **Result:**
Vector3


---


### cross{#cross}

| Ad | Açıklama |
| --- | --- |
| cross(rhs) | İki vektörün çapraz çarpımı. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rhs | Vector3 | Sağ taraf değeri. |

 **Result:**
Vector3


---


### set{#set}

| Ad | Açıklama |
| --- | --- |
| set(newX, newY, newZ) | x/y/z bileşenlerini tek bir çağrıda ayarlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| newX | Number | x bileşeni. |
| newY | Number | y bileşeni. |
| newZ | Number | z bileşeni. |

 **Result:**
Vector3


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Geçerli Vector3'ü temsil eden bir java.lang.String döndürür. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| Ad | Açıklama |
| --- | --- |
| angleBetween(dir, up) | İki yön arasındaki iç açıyı hesaplayın. İki yön, normalize edilmemiş vektörler olabilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| dir | Vector3 | Karşılaştırılacak yön vektörü |
| up | Vector3 | İki yönün ortak düzlemindeki yukarı vektörü |

 **Result:**
Number


---


### angleBetween{#angleBetween}

| Ad | Açıklama |
| --- | --- |
| angleBetween(dir) | İki yön arasındaki iç açıyı hesaplayın. İki yön, normalize edilmemiş vektörler olabilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| dir | Vector3 | Karşılaştırılacak yön vektörü |

 **Result:**
Number


---


### compareTo{#compareTo}

| Ad | Açıklama |
| --- | --- |
| compareTo(other) | Geçerli vektörü başka bir örnek ile karşılaştırın. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Number


---



