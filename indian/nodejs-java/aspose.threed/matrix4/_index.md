---
title: "Matrix4"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4 मैट्रिक्स कार्यान्वयन।


## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| m00 | यह m00। |
| m01 | यह m01। |
| m02 | यह m02। |
| m03 | यह m03। |
| m10 | यह m10। |
| m11 | यह m11। |
| m12 | यह m12. |
| m13 | यह m13. |
| m20 | यह m20. |
| m21 | यह m21. |
| m22 | यह m22. |
| m23 | यह m23. |
| m30 | यह m30. |
| m31 | यह m31. |
| m32 | यह m32. |
| m33 | यह m33. |

## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(r0, r1, r2, r3) | 4 पंक्तियों से मैट्रिक्स बनाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| नाम | विवरण |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Matrix4 स्ट्रक्ट का एक नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| m00 | Number | M00. |
| m01 | Number | M01. |
| m02 | Number | M02. |
| m03 | Number | M03. |
| m10 | Number | M10. |
| m11 | Number | M11. |
| m12 | Number | M12. |
| m13 | Number | M13. |
| m20 | Number | M20. |
| m21 | Number | M21. |
| m22 | Number | M22. |
| m23 | Number | M23. |
| m30 | Number | M30. |
| m31 | Number | M31. |
| m32 | Number | M32. |
| m33 | Number | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| नाम | विवरण |
| --- | --- |
| constructor_overload3(m) | एक FMatrix4 उदाहरण से Matrix4 बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| नाम | विवरण |
| --- | --- |
| constructor_overload4(m) | Matrix4 स्ट्रक्ट का एक नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| नाम | विवरण |
| --- | --- |
| getIdentity() | पहचान मैट्रिक्स प्राप्त करता है। पहचान। |

 **Result:**



---


### getDeterminant{#getDeterminant}

| नाम | विवरण |
| --- | --- |
| getDeterminant() | मैट्रिक्स का निर्धारक प्राप्त करता है। निर्धारक। |

 **Result:**



---


### concatenate{#concatenate}

| नाम | विवरण |
| --- | --- |
| concatenate(m2) | दोनों मैट्रिक्स को जोड़ता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| नाम | विवरण |
| --- | --- |
| transpose() | इस instance को ट्रांसपोज़ करता है। |

 **Result:**
Matrix4


---


### normalize{#normalize}

| नाम | विवरण |
| --- | --- |
| normalize() | इस उदाहरण को सामान्यीकृत करता है। |

 **Result:**
Matrix4


---


### inverse{#inverse}

| नाम | विवरण |
| --- | --- |
| inverse() | इस उदाहरण का उलटा बनाता है। |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| नाम | विवरण |
| --- | --- |
| setTRS(translation, rotation, scale) | मैट्रिक्स को अनुवाद/घूर्णन/स्केल के साथ आरंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| अनुवाद | Vector3 | अनुवाद। |
| घूर्णन | Vector3 | घूर्णन के लिए यूलेर कोण, फ़ील्ड डिग्री में हैं। |
| स्केल | Vector3 | स्केल। |

 **Result:**
Matrix4


---


### toArray{#toArray}

| नाम | विवरण |
| --- | --- |
| toArray() | मैट्रिक्स को एरे में बदलता है। |

 **Result:**
Number[]


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | वर्तमान Matrix4 को दर्शाने वाला java.lang.String लौटाता है। |

 **Result:**
स्ट्रिंग


---


### translate{#translate}

| नाम | विवरण |
| --- | --- |
| translate(t) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ अनुवाद करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| t | Vector3 | अनुवाद ऑफ़सेट |

 **Result:**
Matrix4


---


### translate{#translate}

| नाम | विवरण |
| --- | --- |
| translate(tx, ty, tz) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ अनुवाद करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| tx | Number | X-निर्देशांक ऑफ़सेट |
| ty | Number | Y-निर्देशांक ऑफ़सेट |
| tz | Number | Z-निर्देशांक ऑफ़सेट |

 **Result:**
Matrix4


---


### scale{#scale}

| नाम | विवरण |
| --- | --- |
| scale(s) | एक मैट्रिक्स बनाता है जो x-axis, y-axis और z-axis के साथ स्केल करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| s | Vector3 | स्केलिंग फैक्ट्रीज़ x-axis, y-axis और z-axis पर लागू होती हैं। |

 **Result:**
Matrix4


---


### scale{#scale}

| नाम | विवरण |
| --- | --- |
| scale(s) | एक मैट्रिक्स बनाता है जो x-axis, y-axis और z-axis के साथ स्केल करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| s | Number | स्केलिंग फैक्ट्रीज़ सभी अक्षों पर लागू होती हैं। |

 **Result:**
Matrix4


---


### scale{#scale}

| नाम | विवरण |
| --- | --- |
| scale(sx, sy, sz) | एक मैट्रिक्स बनाता है जो x-axis, y-axis और z-axis के साथ स्केल करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| sx | Number | स्केलिंग फैक्ट्रीज़ x-axis पर लागू होती हैं। |
| sy | Number | स्केलिंग फैक्ट्रीज़ y-axis पर लागू होती हैं। |
| sz | Number | स्केलिंग फैक्ट्रीज़ z-axis पर लागू होती हैं। |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| नाम | विवरण |
| --- | --- |
| rotateFromEuler(eul) | Euler कोण से एक रोटेशन मैट्रिक्स बनाएं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| eul | Vector3 | रैडियन में रोटेशन |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| नाम | विवरण |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Euler कोण से एक रोटेशन मैट्रिक्स बनाएं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| rx | Number | x-axis में रैडियन में रोटेशन |
| ry | Number | y-axis में रैडियन में रोटेशन |
| rz | Number | z अक्ष में रेडियन में घूर्णन |

 **Result:**
Matrix4


---


### rotate{#rotate}

| नाम | विवरण |
| --- | --- |
| rotate(angle, axis) | घूर्णन कोण और अक्ष द्वारा एक घूर्णन मैट्रिक्स बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| कोण | Number | रेडियन में घूर्णन कोण |
| अक्ष | Vector3 | घूर्णन अक्ष |

 **Result:**
Matrix4


---


### rotate{#rotate}

| नाम | विवरण |
| --- | --- |
| rotate(q) | क्वाटरनियन से एक घूर्णन मैट्रिक्स बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| q | क्वाटरनियन | घूर्णन क्वाटरनियन |

 **Result:**
Matrix4


---



