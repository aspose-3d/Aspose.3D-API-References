---
title: "AnahtarKare"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Anahtar kare, temel olarak bir zaman ve bir değerle tanımlanır; bazı enterpolasyon türleri için son örneklenen değeri hesaplamak amacıyla teğet/gerginlik/yanlılık/süreklilik de kullanılır.  Anahtar kare olmayan bir zaman konumundaki örneklenen değerler, önceki ve sonraki anahtar kareler arasında anahtar kareler tarafından enterpole edilir.  İlk/son anahtar karedan önceki/sonraki değerler Extrapolation sınıfı tarafından hesaplanır.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(curve, time) | Belirtilen eğri üzerinde yeni bir anahtar kare oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| eğri | KeyframeSequence | Anahtar karenin oluşturulacağı eğri |
| zaman | Sayı | Anahtar karenin zaman konumu |

 **Result:**



---


### getTime{#getTime}

| Ad | Açıklama |
| --- | --- |
| getTime() | list.data[index] anahtar karenin zaman konumunu saniye cinsinden alır veya ayarlar. Zaman. |

 **Result:**



---


### setTime{#setTime}

| Ad | Açıklama |
| --- | --- |
| setTime(value) | list.data[index] anahtar karenin zaman konumunu saniye cinsinden alır veya ayarlar. Zaman. |

 **Result:**



---


### getValue{#getValue}

| Ad | Açıklama |
| --- | --- |
| getValue() | Anahtar karenin değerini alır veya ayarlar. Değer. |

 **Result:**



---


### setValue{#setValue}

| Ad | Açıklama |
| --- | --- |
| setValue(value) | Anahtar karenin değerini alır veya ayarlar. Değer. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Ad | Açıklama |
| --- | --- |
| getInterpolation() | Anahtarın ara değerleme (interpolation) tipini alır veya ayarlar, list.data[index] örneklenen değerin nasıl hesaplandığını tanımlayan algoritmayı belirler. Özelliğin değeri Interpolation tam sayı sabitidir. Ara değerleme. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Ad | Açıklama |
| --- | --- |
| setInterpolation(value) | Anahtarın ara değerleme (interpolation) tipini alır veya ayarlar, list.data[index] örneklenen değerin nasıl hesaplandığını tanımlayan algoritmayı belirler. Özelliğin değeri Interpolation tam sayı sabitidir. Ara değerleme. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Ad | Açıklama |
| --- | --- |
| getTangentWeightMode() | Anahtarın teğet ağırlık modunu alır veya ayarlar. Çıkış teğeti veya bir sonraki giriş teğeti, doğru WeightedMode seçilerek özelleştirilebilir. Özelliğin değeri WeightedMode tam sayı sabitidir. Teğet ağırlık modu. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Ad | Açıklama |
| --- | --- |
| setTangentWeightMode(value) | Anahtarın teğet ağırlık modunu alır veya ayarlar. Çıkış teğeti veya bir sonraki giriş teğeti, doğru WeightedMode seçilerek özelleştirilebilir. Özelliğin değeri WeightedMode tam sayı sabitidir. Teğet ağırlık modu. |

 **Result:**



---


### getStepMode{#getStepMode}

| Ad | Açıklama |
| --- | --- |
| getStepMode() | Anahtarın adım (step) modunu alır veya ayarlar. Eğer ara değerleme tipi Interpolation.CONSTANT ise, list.data[index] ara değerleme sırasında hangi anahtar karenin değerinin kullanılacağını belirler. StepMode.PREVIOUS_VALUE, sol anahtar karenin değerinin kullanılacağı anlamına gelir. StepMode.NEXT_VALUE, sağdaki bir sonraki anahtar karenin değerinin kullanılacağı anlamına gelir. Özelliğin değeri StepMode tam sayı sabitidir. Adım modu. |

 **Result:**



---


### setStepMode{#setStepMode}

| Ad | Açıklama |
| --- | --- |
| setStepMode(value) | Anahtarın adım (step) modunu alır veya ayarlar. Eğer ara değerleme tipi Interpolation.CONSTANT ise, list.data[index] ara değerleme sırasında hangi anahtar karenin değerinin kullanılacağını belirler. StepMode.PREVIOUS_VALUE, sol anahtar karenin değerinin kullanılacağı anlamına gelir. StepMode.NEXT_VALUE, sağdaki bir sonraki anahtar karenin değerinin kullanılacağı anlamına gelir. Özelliğin değeri StepMode tam sayı sabitidir. Adım modu. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Ad | Açıklama |
| --- | --- |
| getNextInTangent() | Bu anahtar karede bir sonraki giriş (sol) teğeti alır veya ayarlar. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Ad | Açıklama |
| --- | --- |
| setNextInTangent(value) | Bu anahtar karede bir sonraki giriş (sol) teğeti alır veya ayarlar. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Ad | Açıklama |
| --- | --- |
| getOutTangent() | Bu anahtar karede çıkış (sağ) teğeti alır veya ayarlar. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Ad | Açıklama |
| --- | --- |
| setOutTangent(value) | Bu anahtar karede çıkış (sağ) teğeti alır veya ayarlar. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Ad | Açıklama |
| --- | --- |
| getOutWeight() | Bu anahtar çerçevede dış (sağ) ağırlığı alır veya ayarlar. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Ad | Açıklama |
| --- | --- |
| setOutWeight(value) | Bu anahtar çerçevede dış (sağ) ağırlığı alır veya ayarlar. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Ad | Açıklama |
| --- | --- |
| getNextInWeight() | Bu anahtar çerçevede sonraki iç (sol) ağırlığı alır veya ayarlar. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Ad | Açıklama |
| --- | --- |
| setNextInWeight(value) | Bu anahtar çerçevede sonraki iç (sol) ağırlığı alır veya ayarlar. |

 **Result:**



---


### getTension{#getTension}

| Ad | Açıklama |
| --- | --- |
| getTension() | TCB spline'ında kullanılan gerilimi alır veya ayarlar. |

 **Result:**



---


### setTension{#setTension}

| Ad | Açıklama |
| --- | --- |
| setTension(value) | TCB spline'ında kullanılan gerilimi alır veya ayarlar. |

 **Result:**



---


### getContinuity{#getContinuity}

| Ad | Açıklama |
| --- | --- |
| getContinuity() | TCB spline'ında kullanılan sürekliliği alır veya ayarlar. |

 **Result:**



---


### setContinuity{#setContinuity}

| Ad | Açıklama |
| --- | --- |
| setContinuity(value) | TCB spline'ında kullanılan sürekliliği alır veya ayarlar. |

 **Result:**



---


### getBias{#getBias}

| Ad | Açıklama |
| --- | --- |
| getBias() | TCB spline'ında kullanılan önyargıyı alır veya ayarlar. |

 **Result:**



---


### setBias{#setBias}

| Ad | Açıklama |
| --- | --- |
| setBias(value) | TCB spline'ında kullanılan önyargıyı alır veya ayarlar. |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Ad | Açıklama |
| --- | --- |
| getIndependentTangent() | Dış ve sonraki iç teğetlerin bağımsız olup olduğunu alır veya ayarlar. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Ad | Açıklama |
| --- | --- |
| setIndependentTangent(value) | Dış ve sonraki iç teğetlerin bağımsız olup olduğunu alır veya ayarlar. |

 **Result:**



---


### getFlat{#getFlat}

| Ad | Açıklama |
| --- | --- |
| getFlat() | Anahtar çerçevenin düz olup olmadığını alır veya ayarlar. Anahtar çerçeve, sonraki veya önceki anahtar çerçeve aynı değere sahipse düz olmalıdır. Düz anahtar çerçeve düz teğetlere ve sabit ara değerlemeye sahiptir. |

 **Result:**



---


### setFlat{#setFlat}

| Ad | Açıklama |
| --- | --- |
| setFlat(value) | Anahtar çerçevenin düz olup olmadığını alır veya ayarlar. Anahtar çerçeve, sonraki veya önceki anahtar çerçeve aynı değere sahipse düz olmalıdır. Düz anahtar çerçeve düz teğetlere ve sabit ara değerlemeye sahiptir. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Ad | Açıklama |
| --- | --- |
| getTimeIndependentTangent() | Teğetin zaman bağımsız olduğunu alır veya ayarlar. |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Ad | Açıklama |
| --- | --- |
| setTimeIndependentTangent(value) | Teğetin zaman bağımsız olduğunu alır veya ayarlar. |

 **Result:**



---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Ana kare'nin dize temsilini alır |

 **Result:**
String


---



