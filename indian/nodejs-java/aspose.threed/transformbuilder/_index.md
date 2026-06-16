---
title: "TransformBuilder"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

TransformBuilder का उपयोग ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्मेशन की श्रृंखला द्वारा बनाने के लिए किया जाता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(initial, order) | निर्दिष्ट प्रारंभिक ट्रांसफ़ॉर्म मैट्रिक्स और कॉम्पोज़ क्रम के साथ एक TransformBuilder बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| initia | Matrix4 | null |
| क्रम | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(order) | निर्दिष्ट कॉम्पोज़ क्रम और प्रारंभिक आइडेंटिटी ट्रांसफ़ॉर्म मैट्रिक्स के साथ एक TransformBuilder बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| क्रम | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| नाम | विवरण |
| --- | --- |
| getMatrix() | वर्तमान मैट्रिक्स मान को प्राप्त या सेट करता है |

 **Result:**



---


### setMatrix{#setMatrix}

| नाम | विवरण |
| --- | --- |
| setMatrix(value) | वर्तमान मैट्रिक्स मान को प्राप्त या सेट करता है |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| नाम | विवरण |
| --- | --- |
| getComposeOrder() | चेन कॉम्पोज़ क्रम को प्राप्त या सेट करता है। प्रॉपर्टी का मान ComposeOrder पूर्णांक स्थिरांक है। |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| नाम | विवरण |
| --- | --- |
| setComposeOrder(value) | चेन कॉम्पोज़ क्रम को प्राप्त या सेट करता है। प्रॉपर्टी का मान ComposeOrder पूर्णांक स्थिरांक है। |

 **Result:**



---


### compose{#compose}

| नाम | विवरण |
| --- | --- |
| compose(m) | आर्ग्यूमेंट को आंतरिक मैट्रिक्स में जोड़ें या पहले रखें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| नाम | विवरण |
| --- | --- |
| append(m) | नए ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्म चेन में जोड़ें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| नाम | विवरण |
| --- | --- |
| prepend(m) | नए ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्म चेन में prepend करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| नाम | विवरण |
| --- | --- |
| rearrange(newX, newY, newZ) | एक्सिस की लेआउट को पुनः व्यवस्थित करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| newX | अक्ष | अक्ष |
| newY | अक्ष | अक्ष |
| newZ | अक्ष | अक्ष |

 **Result:**



---


### scale{#scale}

| नाम | विवरण |
| --- | --- |
| scale(s) | एक घटक s द्वारा स्केल किए गए स्केलिंग ट्रांसफ़ॉर्म मैट्रिक्स को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| नाम | विवरण |
| --- | --- |
| scale(x, y, z) | एक स्केलिंग ट्रांसफ़ॉर्म मैट्रिक्स को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| नाम | विवरण |
| --- | --- |
| scale(s) | एक स्केल ट्रांसफ़ॉर्म को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| नाम | विवरण |
| --- | --- |
| rotateDegree(angle, axis) | डिग्री में एक रोटेशन ट्रांसफ़ॉर्म को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| कोण | Number | डिग्री में घुमाने का कोण। |
| अक्ष | Vector3 | घुमाने के लिए एक्सिस। |

 **Result:**



---


### rotateRadian{#rotateRadian}

| नाम | विवरण |
| --- | --- |
| rotateRadian(angle, axis) | रेडियन में एक रोटेशन ट्रांसफ़ॉर्म को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| कोण | Number | रेडियन में घुमाने का कोण। |
| अक्ष | Vector3 | घुमाने के लिए एक्सिस। |

 **Result:**



---


### rotate{#rotate}

| नाम | विवरण |
| --- | --- |
| rotate(q) | क्वाटरनियन द्वारा रोटेशन को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | क्वाटरनियन | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| नाम | विवरण |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | डिग्री में यूलेर कोणों द्वारा रोटेशन को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| deg | Number | null |
| deg | Number | null |
| deg | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| नाम | विवरण |
| --- | --- |
| rotateEulerRadian(x, y, z) | रेडियन में यूलेर कोणों द्वारा रोटेशन को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| नाम | विवरण |
| --- | --- |
| rotateEulerRadian(r) | रेडियन में यूलेर कोणों द्वारा रोटेशन को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| नाम | विवरण |
| --- | --- |
| translate(tx, ty, tz) | एक ट्रांसलेशन ट्रांसफ़ॉर्म को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**



---


### translate{#translate}

| नाम | विवरण |
| --- | --- |
| translate(v) | एक ट्रांसलेशन ट्रांसफ़ॉर्म को chain करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| नाम | विवरण |
| --- | --- |
| reset() | ट्रांसफ़ॉर्म को आइडेंटिटी मैट्रिक्स पर रीसेट करें। |

 **Result:**



---


### rotateDegree{#rotateDegree}

| नाम | विवरण |
| --- | --- |
| rotateDegree(rot, order) | निर्दिष्ट क्रम के साथ घुमाव जोड़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| rot | Vector3 | डिग्री में घुमाव |
| क्रम | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| नाम | विवरण |
| --- | --- |
| rotateRadian(rot, order) | निर्दिष्ट क्रम के साथ घुमाव जोड़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| rot | Vector3 | रैडियन में रोटेशन |
| क्रम | RotationOrder | RotationOrder |

 **Result:**



---



