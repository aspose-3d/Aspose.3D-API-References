---
title: "Vector3"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Üç bileşenli bir vektör.


## Özellikler

| Ad | Açıklama |
| --- | --- |
| x | x bileşeni. |
| y | y bileşeni. |
| z | z bileşeni. |
| ORIGIN | Köken konumunu alır. Köken. |
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
| x | Sayı | x koordinatı. |
| y | Sayı | y koordinatı. |
| z | Sayı | z koordinatı. |

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
| v | Sayı | V. |

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
| getLength() | Bu vektörün uzunluğunu alır. length. |

 **Result:**



---


### equals{#equals}

| Ad | Açıklama |
| --- | --- |
| equals(obj) | İki vector3 eşit mi kontrol eder |

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
| hashCode() | Vector3'in hash kodunu alır. |

 **Result:**
Sayı


---


### dot{#dot}

| Ad | Açıklama |
| --- | --- |
| dot(rhs) | İki vektörün nokta çarpımını alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rhs | Vector3 | Sağ taraf değeri. |

 **Result:**
Sayı


---


### normalize{#normalize}

| Ad | Açıklama |
| --- | --- |
| normalize() | Bu örneği normalize eder. |

 **Result:**
Vector3


---


### sin{#sin}

| Ad | Açıklama |
| --- | --- |
| sin() | Her bileşende sinüsü hesaplar. |

 **Result:**
Vector3


---


### cos{#cos}

| Ad | Açıklama |
| --- | --- |
| cos() | Her bileşende kosinüsü hesaplar. |

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
| set(newX, newY, newZ) | x/y/z bileşenini tek bir çağrıda ayarlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| newX | Sayı | x bileşeni. |
| newY | Sayı | y bileşeni. |
| newZ | Sayı | z bileşeni. |

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
| angleBetween(dir, up) | İki yön arasındaki iç açıyı hesaplayın. İki yön, normlandırılmamış vektörler olabilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| dir | Vector3 | Karşılaştırılacak yön vektörü |
| up | Vector3 | İki yönün ortak düzlemindeki yukarı vektörü |

 **Result:**
Sayı


---


### angleBetween{#angleBetween}

| Ad | Açıklama |
| --- | --- |
| angleBetween(dir) | İki yön arasındaki iç açıyı hesaplayın. İki yön, normlandırılmamış vektörler olabilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| dir | Vector3 | Karşılaştırılacak yön vektörü |

 **Result:**
Sayı


---


### compareTo{#compareTo}

| Ad | Açıklama |
| --- | --- |
| compareTo(other) | Geçerli vektörü başka bir örnekle karşılaştır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Sayı


---



