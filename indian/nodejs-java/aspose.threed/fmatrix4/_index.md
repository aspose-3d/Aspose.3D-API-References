---
title: "FMatrix4"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

फ़्लोट प्रकार के सभी घटकों के साथ 4x4 मैट्रिक्स


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
| IDENTITY | यह पहचान मैट्रिक्स |

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
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | FMatrix4 का उदाहरण प्रारंभ करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| m0 | Number | null |
| m0 | Number | null |
| m0 | Number | null |
| m0 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m3 | Number | null |
| m3 | Number | null |
| m3 | Number | null |
| m3 | Number | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| नाम | विवरण |
| --- | --- |
| constructor_overload2(mat) | FMatrix4 की instance को एक Matrix4 instance से प्रारंभ करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| नाम | विवरण |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | 4 पंक्तियों से मैट्रिक्स बनाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| नाम | विवरण |
| --- | --- |
| concatenate(m2) | दोनों मैट्रिक्स को जोड़ता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


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
FMatrix4


---


### transpose{#transpose}

| नाम | विवरण |
| --- | --- |
| transpose() | इस instance को ट्रांसपोज़ करता है। |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| नाम | विवरण |
| --- | --- |
| inverse() | वर्तमान instance का इनवर्स मैट्रिक्स गणना करें। |

 **Result:**
FMatrix4


---



