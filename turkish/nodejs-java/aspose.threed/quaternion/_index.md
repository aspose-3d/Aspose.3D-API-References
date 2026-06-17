---
title: "Kuatör"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion genellikle bilgisayar grafiklerinde dönüşüm gerçekleştirmek için kullanılır.


## Properties

| Ad | Açıklama |
| --- | --- |
| w | w bileşeni. |
| x | x bileşeni. |
| y | y bileşeni. |
| z | z bileşeni. |
| IDENTITY | Birimsal kuaternion. |

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
| constructor_overload(w, x, y, z) | Quaternion sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| w | Number | kuaternionun w bileşeni |
| x | Number | kuaternionun x bileşeni |
| y | Number | kuaternionun y bileşeni |
| z | Number | kuaternionun z bileşeni |

 **Result:**



---


### getLength{#getLength}

| Ad | Açıklama |
| --- | --- |
| getLength() | Kuaternionun uzunluğunu alır |

 **Result:**



---


### equals{#equals}

| Ad | Açıklama |
| --- | --- |
| equals(obj) | İki kuaternionun eşit olup olmadığını kontrol eder |

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
| hashCode() | Quaternion'un hash kodunu alır |

 **Result:**
Number


---


### conjugate{#conjugate}

| Ad | Açıklama |
| --- | --- |
| conjugate() | Mevcut kuaternionun konjugat kuaternionunu döndürür |

 **Result:**
Kuatör


---


### inverse{#inverse}

| Ad | Açıklama |
| --- | --- |
| inverse() | Mevcut kuaternionun ters kuaternionunu döndürür |

 **Result:**
Kuatör


---


### dot{#dot}

| Ad | Açıklama |
| --- | --- |
| dot(q) | Nokta çarpımı |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| q | Kuatör | Kuaternion |

 **Result:**
Number


---


### eulerAngles{#eulerAngles}

| Ad | Açıklama |
| --- | --- |
| eulerAngles() | Kuaternionu Euler açılarıyla temsil edilen dönüşüme dönüştürür. Tüm bileşenler radyan cinsindendir. |

 **Result:**
Vector3


---


### normalize{#normalize}

| Ad | Açıklama |
| --- | --- |
| normalize() | Kuaternionu normalleştir |

 **Result:**
Kuatör


---


### concat{#concat}

| Ad | Açıklama |
| --- | --- |
| concat(rhs) | İki kuaternionu birleştir |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rh | Kuatör | null |

 **Result:**
Kuatör


---


### fromAngleAxis{#fromAngleAxis}

| Ad | Açıklama |
| --- | --- |
| fromAngleAxis(a, axis) | Verilen eksen etrafında bir kuaternion oluşturur ve saat yönünde döndürür |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| a | Number | Saat yönünde dönüş radian cinsinden |
| eksen | Vector3 | Eksen |

 **Result:**
Kuatör


---


### fromRotation{#fromRotation}

| Ad | Açıklama |
| --- | --- |
| fromRotation(orig, dest) | Orijinal yönünden hedef yönüne dönen bir kuaternion oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| orig | Vector3 | Orijinal yön |
| dest | Vector3 | Hedef yön |

 **Result:**
Kuatör


---


### fromEulerAngle{#fromEulerAngle}

| Ad | Açıklama |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Verilen Euler açısından bir kuaternion oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| pitch | Number | Pitch radian cinsinden |
| yaw | Number | Yaw radian cinsinden |
| yuvarlanma | Number | Radyan cinsinden yuvarlanma |

 **Result:**
Kuatör


---


### fromEulerAngle{#fromEulerAngle}

| Ad | Açıklama |
| --- | --- |
| fromEulerAngle(eulerAngle) | Verilen Euler açısından bir kuaternion oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| eulerAngle | Vector3 | Radyan cinsinden Euler açısı |

 **Result:**
Kuatör


---


### toMatrix{#toMatrix}

| Ad | Açıklama |
| --- | --- |
| toMatrix() | Kuatör tarafından sunulan dönüşümü dönüşüm matrisine dönüştür. |

 **Result:**
Matrix4


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Kuatörün temsili dize olarak alınır |

 **Result:**
String


---


### interpolate{#interpolate}

| Ad | Açıklama |
| --- | --- |
| interpolate(t, from, to) | Bu kuatörü, from ve to arasındaki verilen kuatör argümanları için t değeri arasında ara değerle doldurur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| t | Number | Ara değerleme katsayısı. |
| kaynak | Kuatör | Kaynak kuatör. |
| hedef | Kuatör | Hedef kuatör. |

 **Result:**
Kuatör


---



