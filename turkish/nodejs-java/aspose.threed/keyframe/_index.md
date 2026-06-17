---
title: "KeyFrame"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Bir anahtar kare, temel olarak bir zaman ve bir değerle tanımlanır, bazı enterpolasyon tipleri için son örneklenmiş değeri hesaplamak amacıyla teğet/gerginlik/yanlılık/süreklilik de kullanılır.  Anahtar kare olmayan bir zaman konumundaki örneklenmiş değerler, önceki ve sonraki anahtar kareler arasındaki anahtar kareler tarafından enterpole edilir.  İlk/son anahtar kareden önceki/sonraki değerler Extrapolation sınıfı tarafından hesaplanır.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(curve, time) | Belirtilen eğri üzerinde yeni bir ana kare oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| curve | KeyframeSequence | Anahtar çerçevenin oluşturulacağı eğri |
| time | Number | Anahtar çerçevenin zaman konumu |

 **Result:**



---


### getTime{#getTime}

| Ad | Açıklama |
| --- | --- |
| getTime() | list.data[index] anahtar çerçevenin zaman konumunu alır veya ayarlar, saniye cinsinden ölçülür. Zaman. |

 **Result:**



---


### setTime{#setTime}

| Ad | Açıklama |
| --- | --- |
| setTime(value) | list.data[index] anahtar çerçevenin zaman konumunu alır veya ayarlar, saniye cinsinden ölçülür. Zaman. |

 **Result:**



---


### getValue{#getValue}

| Ad | Açıklama |
| --- | --- |
| getValue() | anahtar çerçevenin değerini alır veya ayarlar. Değer. |

 **Result:**



---


### setValue{#setValue}

| Ad | Açıklama |
| --- | --- |
| setValue(value) | anahtar çerçevenin değerini alır veya ayarlar. Değer. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Ad | Açıklama |
| --- | --- |
| getInterpolation() | anahtarın ara değerleme tipini alır veya ayarlar, list.data[index] örneklenen değerin nasıl hesaplandığını belirleyen algoritmayı tanımlar. Özelliğin değeri Interpolation tam sayı sabitidir. Ara değerleme. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Ad | Açıklama |
| --- | --- |
| setInterpolation(value) | anahtarın ara değerleme tipini alır veya ayarlar, list.data[index] örneklenen değerin nasıl hesaplandığını belirleyen algoritmayı tanımlar. Özelliğin değeri Interpolation tam sayı sabitidir. Ara değerleme. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Ad | Açıklama |
| --- | --- |
| getTangentWeightMode() | anahtarın teğet ağırlık modunu alır veya ayarlar. Çıkış teğeti veya sonraki giriş teğeti, doğru WeightedMode seçilerek özelleştirilebilir. Özelliğin değeri WeightedMode tam sayı sabitidir. Teğet ağırlık modu. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Ad | Açıklama |
| --- | --- |
| setTangentWeightMode(value) | anahtarın teğet ağırlık modunu alır veya ayarlar. Çıkış teğeti veya sonraki giriş teğeti, doğru WeightedMode seçilerek özelleştirilebilir. Özelliğin değeri WeightedMode tam sayı sabitidir. Teğet ağırlık modu. |

 **Result:**



---


### getStepMode{#getStepMode}

| Ad | Açıklama |
| --- | --- |
| getStepMode() | anahtarın adım modunu alır veya ayarlar. Eğer ara değerleme tipi Interpolation.CONSTANT ise, list.data[index] ara değerleme sırasında hangi anahtar çerçevenin değerinin kullanılacağını belirler. StepMode.PREVIOUS_VALUE sol anahtar çerçevenin değerinin kullanılacağı anlamına gelir. StepMode.NEXT_VALUE ise sağdaki bir sonraki anahtar çerçevenin değerinin kullanılacağı anlamına gelir. Özelliğin değeri StepMode tam sayı sabitidir. Adım modu. |

 **Result:**



---


### setStepMode{#setStepMode}

| Ad | Açıklama |
| --- | --- |
| setStepMode(value) | anahtarın adım modunu alır veya ayarlar. Eğer ara değerleme tipi Interpolation.CONSTANT ise, list.data[index] ara değerleme sırasında hangi anahtar çerçevenin değerinin kullanılacağını belirler. StepMode.PREVIOUS_VALUE sol anahtar çerçevenin değerinin kullanılacağı anlamına gelir. StepMode.NEXT_VALUE ise sağdaki bir sonraki anahtar çerçevenin değerinin kullanılacağı anlamına gelir. Özelliğin değeri StepMode tam sayı sabitidir. Adım modu. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Ad | Açıklama |
| --- | --- |
| getNextInTangent() | Bu anahtar çerçevedeki bir sonraki giriş (sol) teğeti alır veya ayarlar. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Ad | Açıklama |
| --- | --- |
| setNextInTangent(value) | Bu anahtar çerçevedeki bir sonraki giriş (sol) teğeti alır veya ayarlar. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Ad | Açıklama |
| --- | --- |
| getOutTangent() | Bu anahtar çerçevedeki çıkış (sağ) teğeti alır veya ayarlar. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Ad | Açıklama |
| --- | --- |
| setOutTangent(value) | Bu anahtar çerçevedeki çıkış (sağ) teğeti alır veya ayarlar. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Ad | Açıklama |
| --- | --- |
| getOutWeight() | Bu anahtar çerçevedeki çıkış (sağ) ağırlığı alır veya ayarlar. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Ad | Açıklama |
| --- | --- |
| setOutWeight(value) | Bu anahtar çerçevedeki çıkış (sağ) ağırlığı alır veya ayarlar. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Ad | Açıklama |
| --- | --- |
| getNextInWeight() | Bu anahtar karede sonraki iç (sol) ağırlığı alır veya ayarlar. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Ad | Açıklama |
| --- | --- |
| setNextInWeight(value) | Bu anahtar karede sonraki iç (sol) ağırlığı alır veya ayarlar. |

 **Result:**



---


### getTension{#getTension}

| Ad | Açıklama |
| --- | --- |
| getTension() | TCB spline'ında kullanılan gerilimi alır veya ayarlar |

 **Result:**



---


### setTension{#setTension}

| Ad | Açıklama |
| --- | --- |
| setTension(value) | TCB spline'ında kullanılan gerilimi alır veya ayarlar |

 **Result:**



---


### getContinuity{#getContinuity}

| Ad | Açıklama |
| --- | --- |
| getContinuity() | TCB spline'ında kullanılan sürekliliği alır veya ayarlar |

 **Result:**



---


### setContinuity{#setContinuity}

| Ad | Açıklama |
| --- | --- |
| setContinuity(value) | TCB spline'ında kullanılan sürekliliği alır veya ayarlar |

 **Result:**



---


### getBias{#getBias}

| Ad | Açıklama |
| --- | --- |
| getBias() | TCB spline'ında kullanılan yanlılığı alır veya ayarlar |

 **Result:**



---


### setBias{#setBias}

| Ad | Açıklama |
| --- | --- |
| setBias(value) | TCB spline'ında kullanılan yanlılığı alır veya ayarlar |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Ad | Açıklama |
| --- | --- |
| getIndependentTangent() | Çıkış ve sonraki iç teğetlerin bağımsız olduğunu alır veya ayarlar. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Ad | Açıklama |
| --- | --- |
| setIndependentTangent(value) | Çıkış ve sonraki iç teğetlerin bağımsız olduğunu alır veya ayarlar. |

 **Result:**



---


### getFlat{#getFlat}

| Ad | Açıklama |
| --- | --- |
| getFlat() | Anahtar karenin düz olup olmadığını alır veya ayarlar. Anahtar kare, sonraki veya önceki anahtar kare aynı değere sahipse düz olmalıdır. Düz anahtar kare düz teğetlere ve sabit ara değerlemeye sahiptir. |

 **Result:**



---


### setFlat{#setFlat}

| Ad | Açıklama |
| --- | --- |
| setFlat(value) | Anahtar karenin düz olup olmadığını alır veya ayarlar. Anahtar kare, sonraki veya önceki anahtar kare aynı değere sahipse düz olmalıdır. Düz anahtar kare düz teğetlere ve sabit ara değerlemeye sahiptir. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Ad | Açıklama |
| --- | --- |
| getTimeIndependentTangent() | Teğetin zaman bağımsız olduğunu alır veya ayarlar |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Ad | Açıklama |
| --- | --- |
| setTimeIndependentTangent(value) | Teğetin zaman bağımsız olduğunu alır veya ayarlar |

 **Result:**



---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Anahtar karenin dize temsili alır |

 **Result:**
String


---



