---
title: "KeyFrame"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

एक की‑फ़्रेम मुख्यतः समय और मान द्वारा परिभाषित होता है, कुछ इंटरपोलेशन प्रकारों के लिए टैंजेंट/टेंशन/बायस/कंटिन्यूइटी का उपयोग अंतिम सैंपल्ड मान की गणना में किया जाता है। गैर‑की‑फ़्रेम समय स्थिति में सैंपल्ड मानों को पिछले और अगले की‑फ़्रेम के बीच की‑फ़्रेम द्वारा इंटरपोलेट किया जाता है। पहले/अंतिम की‑फ़्रेम से पहले/बाद के मान Extrapolation क्लास द्वारा गणना किए जाते हैं।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(curve, time) | निर्दिष्ट कर्व पर एक नया कीफ़्रेम बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| curve | KeyframeSequence | की फ्रेम जिस वक्र पर बनाया जाएगा वह वक्र |
| time | Number | की फ्रेम की समय स्थिति |

 **Result:**



---


### getTime{#getTime}

| नाम | विवरण |
| --- | --- |
| getTime() | list.data[index] की फ्रेम के समय स्थिति को प्राप्त करता है या सेट करता है, सेकंड में मापा गया। समय। |

 **Result:**



---


### setTime{#setTime}

| नाम | विवरण |
| --- | --- |
| setTime(value) | list.data[index] की फ्रेम के समय स्थिति को प्राप्त करता है या सेट करता है, सेकंड में मापा गया। समय। |

 **Result:**



---


### getValue{#getValue}

| नाम | विवरण |
| --- | --- |
| getValue() | की-फ़्रेम का मान प्राप्त करता है या सेट करता है। मान। |

 **Result:**



---


### setValue{#setValue}

| नाम | विवरण |
| --- | --- |
| setValue(value) | की-फ़्रेम का मान प्राप्त करता है या सेट करता है। मान। |

 **Result:**



---


### getInterpolation{#getInterpolation}

| नाम | विवरण |
| --- | --- |
| getInterpolation() | की की इंटरपोलेशन प्रकार को प्राप्त करता है या सेट करता है, list.data[index] निर्धारित करता है कि सैंपल किया गया मान कैसे गणना किया जाता है। प्रॉपर्टी का मान Interpolation पूर्णांक स्थिरांक है। इंटरपोलेशन। |

 **Result:**



---


### setInterpolation{#setInterpolation}

| नाम | विवरण |
| --- | --- |
| setInterpolation(value) | की की इंटरपोलेशन प्रकार को प्राप्त करता है या सेट करता है, list.data[index] निर्धारित करता है कि सैंपल किया गया मान कैसे गणना किया जाता है। प्रॉपर्टी का मान Interpolation पूर्णांक स्थिरांक है। इंटरपोलेशन। |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| नाम | विवरण |
| --- | --- |
| getTangentWeightMode() | की की टैन्जेंट वेट मोड को प्राप्त करता है या सेट करता है। आउट टैन्जेंट या अगला इन टैन्जेंट सही WeightedMode चुनकर अनुकूलित किया जा सकता है। प्रॉपर्टी का मान WeightedMode पूर्णांक स्थिरांक है। टैन्जेंट वेट मोड। |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| नाम | विवरण |
| --- | --- |
| setTangentWeightMode(value) | की की टैन्जेंट वेट मोड को प्राप्त करता है या सेट करता है। आउट टैन्जेंट या अगला इन टैन्जेंट सही WeightedMode चुनकर अनुकूलित किया जा सकता है। प्रॉपर्टी का मान WeightedMode पूर्णांक स्थिरांक है। टैन्जेंट वेट मोड। |

 **Result:**



---


### getStepMode{#getStepMode}

| नाम | विवरण |
| --- | --- |
| getStepMode() | की की स्टेप मोड को प्राप्त करता है या सेट करता है। यदि इंटरपोलेशन प्रकार Interpolation.CONSTANT है, तो list.data[index] तय करता है कि इंटरपोलेशन के दौरान कौन सा की-फ़्रेम मान उपयोग किया जाएगा। StepMode.PREVIOUS_VALUE का अर्थ है बाएँ की-फ़्रेम का मान उपयोग होगा। StepMode.NEXT_VALUE का अर्थ है अगले दाएँ की-फ़्रेम का मान उपयोग होगा। प्रॉपर्टी का मान StepMode पूर्णांक स्थिरांक है। स्टेप मोड। |

 **Result:**



---


### setStepMode{#setStepMode}

| नाम | विवरण |
| --- | --- |
| setStepMode(value) | की की स्टेप मोड को प्राप्त करता है या सेट करता है। यदि इंटरपोलेशन प्रकार Interpolation.CONSTANT है, तो list.data[index] तय करता है कि इंटरपोलेशन के दौरान कौन सा की-फ़्रेम मान उपयोग किया जाएगा। StepMode.PREVIOUS_VALUE का अर्थ है बाएँ की-फ़्रेम का मान उपयोग होगा। StepMode.NEXT_VALUE का अर्थ है अगले दाएँ की-फ़्रेम का मान उपयोग होगा। प्रॉपर्टी का मान StepMode पूर्णांक स्थिरांक है। स्टेप मोड। |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| नाम | विवरण |
| --- | --- |
| getNextInTangent() | इस की फ्रेम पर अगला इन (बायाँ) टैन्जेंट प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| नाम | विवरण |
| --- | --- |
| setNextInTangent(value) | इस की फ्रेम पर अगला इन (बायाँ) टैन्जेंट प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getOutTangent{#getOutTangent}

| नाम | विवरण |
| --- | --- |
| getOutTangent() | इस की फ्रेम पर आउट (दायाँ) टैन्जेंट प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setOutTangent{#setOutTangent}

| नाम | विवरण |
| --- | --- |
| setOutTangent(value) | इस की फ्रेम पर आउट (दायाँ) टैन्जेंट प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getOutWeight{#getOutWeight}

| नाम | विवरण |
| --- | --- |
| getOutWeight() | इस की फ्रेम पर आउट (दायाँ) वेट प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setOutWeight{#setOutWeight}

| नाम | विवरण |
| --- | --- |
| setOutWeight(value) | इस की फ्रेम पर आउट (दायाँ) वेट प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| नाम | विवरण |
| --- | --- |
| getNextInWeight() | इस कुंजी फ्रेम पर अगला इन(left) वजन प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| नाम | विवरण |
| --- | --- |
| setNextInWeight(value) | इस कुंजी फ्रेम पर अगला इन(left) वजन प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getTension{#getTension}

| नाम | विवरण |
| --- | --- |
| getTension() | TCB स्प्लाइन में उपयोग किए जाने वाले तनाव को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setTension{#setTension}

| नाम | विवरण |
| --- | --- |
| setTension(value) | TCB स्प्लाइन में उपयोग किए जाने वाले तनाव को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getContinuity{#getContinuity}

| नाम | विवरण |
| --- | --- |
| getContinuity() | TCB स्प्लाइन में उपयोग की जाने वाली निरंतरता को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setContinuity{#setContinuity}

| नाम | विवरण |
| --- | --- |
| setContinuity(value) | TCB स्प्लाइन में उपयोग की जाने वाली निरंतरता को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getBias{#getBias}

| नाम | विवरण |
| --- | --- |
| getBias() | TCB स्प्लाइन में उपयोग किए जाने वाले बायस को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setBias{#setBias}

| नाम | विवरण |
| --- | --- |
| setBias(value) | TCB स्प्लाइन में उपयोग किए जाने वाले बायस को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| नाम | विवरण |
| --- | --- |
| getIndependentTangent() | बाहर और अगले इन टैन्जेंट स्वतंत्र हैं, इसे प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| नाम | विवरण |
| --- | --- |
| setIndependentTangent(value) | बाहर और अगले इन टैन्जेंट स्वतंत्र हैं, इसे प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getFlat{#getFlat}

| नाम | विवरण |
| --- | --- |
| getFlat() | यदि कुंजी फ्रेम सपाट है तो इसे प्राप्त या सेट करें। कुंजी फ्रेम तब सपाट होना चाहिए जब अगला या पिछला कुंजी फ्रेम समान मान रखता हो। सपाट कुंजी फ्रेम में सपाट टैन्जेंट और स्थिर इंटरपोलेशन होते हैं। |

 **Result:**



---


### setFlat{#setFlat}

| नाम | विवरण |
| --- | --- |
| setFlat(value) | यदि कुंजी फ्रेम सपाट है तो इसे प्राप्त या सेट करें। कुंजी फ्रेम तब सपाट होना चाहिए जब अगला या पिछला कुंजी फ्रेम समान मान रखता हो। सपाट कुंजी फ्रेम में सपाट टैन्जेंट और स्थिर इंटरपोलेशन होते हैं। |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| नाम | विवरण |
| --- | --- |
| getTimeIndependentTangent() | टैन्जेंट को समय-स्वतंत्र प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| नाम | विवरण |
| --- | --- |
| setTimeIndependentTangent(value) | टैन्जेंट को समय-स्वतंत्र प्राप्त करता है या सेट करता है। |

 **Result:**



---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | कुंजी फ्रेम का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |

 **Result:**
स्ट्रिंग


---



