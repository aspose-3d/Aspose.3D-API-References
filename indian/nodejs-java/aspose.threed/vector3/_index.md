---
title: "Vector3"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

तीन घटकों वाला वेक्टर।


## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| x | x घटक। |
| y | y घटक। |
| z | z घटक। |
| ORIGIN | मूल स्थिति प्राप्त करता है। मूल। |
| UNIT_SCALE | यूनिट स्केल वेक्टर प्राप्त करता है। |
| X_AXIS | X अक्ष प्राप्त करता है। X अक्ष। |
| Y_AXIS | Y अक्ष प्राप्त करता है। Y अक्ष। |
| Z_AXIS | Z अक्ष प्राप्त करता है। Z अक्ष। |

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
| constructor_overload(x, y, z) | Vector3 संरचना का नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| x | Number | x निर्देशांक। |
| y | Number | y निर्देशांक। |
| z | Number | z निर्देशांक। |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| नाम | विवरण |
| --- | --- |
| constructor_overload2(vec) | Vector3 संरचना का नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| vec | FVector3 | x निर्देशांक। |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| नाम | विवरण |
| --- | --- |
| constructor_overload3(v) | Vector3 संरचना का नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| v | Number | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| नाम | विवरण |
| --- | --- |
| constructor_overload4(vec4) | Vector3 संरचना का नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| नाम | विवरण |
| --- | --- |
| getLength2() | लंबाई का वर्ग प्राप्त करता है। length2। |

 **Result:**



---


### getLength{#getLength}

| नाम | विवरण |
| --- | --- |
| getLength() | इस वेक्टर की लंबाई प्राप्त करता है। लंबाई। |

 **Result:**



---


### equals{#equals}

| नाम | विवरण |
| --- | --- |
| equals(obj) | जाँचें कि दो vector3 बराबर हैं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| obj | ऑब्जेक्ट | समानता जाँचने के लिए वस्तु। |

 **Result:**
boolean


---


### hashCode{#hashCode}

| नाम | विवरण |
| --- | --- |
| hashCode() | Vector3 का हैश कोड प्राप्त करता है |

 **Result:**
Number


---


### dot{#dot}

| नाम | विवरण |
| --- | --- |
| dot(rhs) | दो वेक्टरों का डॉट प्रोडक्ट प्राप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| rhs | Vector3 | दाएँ हाथ की मान। |

 **Result:**
Number


---


### normalize{#normalize}

| नाम | विवरण |
| --- | --- |
| normalize() | इस उदाहरण को सामान्यीकृत करता है। |

 **Result:**
Vector3


---


### sin{#sin}

| नाम | विवरण |
| --- | --- |
| sin() | प्रत्येक घटक पर साइन की गणना करता है |

 **Result:**
Vector3


---


### cos{#cos}

| नाम | विवरण |
| --- | --- |
| cos() | प्रत्येक घटक पर कोसाइन की गणना करता है |

 **Result:**
Vector3


---


### cross{#cross}

| नाम | विवरण |
| --- | --- |
| cross(rhs) | दो वेक्टरों का क्रॉस प्रोडक्ट |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| rhs | Vector3 | दाएँ हाथ की मान। |

 **Result:**
Vector3


---


### set{#set}

| नाम | विवरण |
| --- | --- |
| set(newX, newY, newZ) | एक कॉल में x/y/z घटक सेट करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| newX | Number | x घटक। |
| newY | Number | y घटक। |
| newZ | Number | z घटक। |

 **Result:**
Vector3


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | वर्तमान Vector3 को दर्शाने वाला java.lang.String लौटाता है। |

 **Result:**
स्ट्रिंग


---


### angleBetween{#angleBetween}

| नाम | विवरण |
| --- | --- |
| angleBetween(dir, up) | दो दिशा के बीच का आंतरिक कोण गणना करें दो दिशा गैर-नॉर्मलाइज़्ड वेक्टर हो सकते हैं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| dir | Vector3 | तुलना करने के लिए दिशा वेक्टर |
| up | Vector3 | दो दिशा के साझा तल का up वेक्टर |

 **Result:**
Number


---


### angleBetween{#angleBetween}

| नाम | विवरण |
| --- | --- |
| angleBetween(dir) | दो दिशा के बीच का आंतरिक कोण गणना करें दो दिशा गैर-नॉर्मलाइज़्ड वेक्टर हो सकते हैं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| dir | Vector3 | तुलना करने के लिए दिशा वेक्टर |

 **Result:**
Number


---


### compareTo{#compareTo}

| नाम | विवरण |
| --- | --- |
| compareTo(other) | वर्तमान वेक्टर की तुलना किसी अन्य इंस्टेंस से करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Number


---



