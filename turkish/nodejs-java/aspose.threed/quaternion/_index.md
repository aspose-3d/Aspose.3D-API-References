---
title: "Quaternion"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion genellikle bilgisayar grafiklerinde döndürme yapmak için kullanılır.


## Özellikler

| Ad | Açıklama |
| --- | --- |
| w | w bileşeni. |
| x | x bileşeni. |
| y | y bileşeni. |
| z | z bileşeni. |
| IDENTITY | Kimlik kuaterni. |

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
| w | Sayı | kuaterni'nin w bileşeni |
| x | Sayı | kuaterni'nin x bileşeni |
| y | Sayı | kuaterni'nin y bileşeni |
| z | Sayı | kuaterni'nin z bileşeni |

 **Result:**



---


### getLength{#getLength}

| Ad | Açıklama |
| --- | --- |
| getLength() | Kuaterni'nin uzunluğunu alır |

 **Result:**



---


### equals{#equals}

| Ad | Açıklama |
| --- | --- |
| equals(obj) | İki kuaterniyonun eşit olup olmadığını kontrol et |

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
| hashCode() | Quaternion'ın karma kodunu alır |

 **Result:**
Sayı


---


### conjugate{#conjugate}

| Ad | Açıklama |
| --- | --- |
| conjugate() | Mevcut kuaterniyonun eşleni kuaterniyonunu döndürür |

 **Result:**
Quaternion


---


### inverse{#inverse}

| Ad | Açıklama |
| --- | --- |
| inverse() | Mevcut kuaterniyonun ters kuaterniyonunu döndürür |

 **Result:**
Quaternion


---


### dot{#dot}

| Ad | Açıklama |
| --- | --- |
| dot(q) | Nokta çarpımı |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| q | Quaternion | Kuaterniyon |

 **Result:**
Sayı


---


### eulerAngles{#eulerAngles}

| Ad | Açıklama |
| --- | --- |
| eulerAngles() | Kuaterniyonu Euler açılarıyla temsil edilen dönüşüme çevirir. Tüm bileşenler radyan cinsindedir |

 **Result:**
Vector3


---


### normalize{#normalize}

| Ad | Açıklama |
| --- | --- |
| normalize() | Kuaterniyonu normalleştir |

 **Result:**
Quaternion


---


### concat{#concat}

| Ad | Açıklama |
| --- | --- |
| concat(rhs) | İki kuaterniyonu birleştir |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rh | Quaternion | null |

 **Result:**
Quaternion


---


### fromAngleAxis{#fromAngleAxis}

| Ad | Açıklama |
| --- | --- |
| fromAngleAxis(a, axis) | Verilen eksen etrafında bir kuaterniyon oluşturur ve saat yönünde döndürür |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| a | Sayı | Saat yönünde dönüş radyan cinsinden |
| axis | Vector3 | Eksen |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| Ad | Açıklama |
| --- | --- |
| fromRotation(orig, dest) | Orijinal yönünden hedef yönüne dönen bir kuaterniyon oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| orig | Vector3 | Orijinal yön |
| dest | Vector3 | Hedef yön |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Ad | Açıklama |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Verilen Euler açısından quaternion oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| eğim | Sayı | Radyan cinsinden eğim |
| sapma | Sayı | Radyan cinsinden sapma |
| yuvarlanma | Sayı | Radyan cinsinden yuvarlanma |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Ad | Açıklama |
| --- | --- |
| fromEulerAngle(eulerAngle) | Verilen Euler açısından quaternion oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| eulerAngle | Vector3 | Radyan cinsinden Euler açısı |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| Ad | Açıklama |
| --- | --- |
| toMatrix() | Quaternion tarafından temsil edilen dönüşümü dönüşüm matrisine dönüştürür. |

 **Result:**
Matrix4


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Quaternion'ın dize temsilini alır. |

 **Result:**
String


---


### interpolate{#interpolate}

| Ad | Açıklama |
| --- | --- |
| interpolate(t, from, to) | Bu quaternion'ı, verilen quaternion argümanları arasında, from ve to arasında bir t değeri için ara değerle doldurur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| t | Sayı | Ara değerleme katsayısı. |
| kaynak | Quaternion | Kaynak quaternion. |
| hedef | Quaternion | Hedef quaternion. |

 **Result:**
Quaternion


---



