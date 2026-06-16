---
title: "BoundingBox"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

एक्सिस-एलाइन्ड बाउंडिंग बॉक्स


## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| NULL | नल बाउंडिंग बॉक्स। |
| INFINITE | अनंत बाउंडिंग बॉक्स। |

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
| constructor_overload(minimum, maximum) | दिए गए न्यूनतम और अधिकतम कोनों के साथ एक सीमित बाउंडिंग बॉक्स को प्रारंभ करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| minimum | Vector3 | न्यूनतम कोना। |
| maximum | Vector3 | अधिकतम कोना। |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| नाम | विवरण |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | दिए गए न्यूनतम और अधिकतम कोनों के साथ एक सीमित बाउंडिंग बॉक्स को प्रारंभ करें। |

 **Result:**



---


### getExtent{#getExtent}

| नाम | विवरण |
| --- | --- |
| getExtent() | बाउंडिंग बॉक्स का विस्तार प्राप्त करता है। इस प्रॉपर्टी का मान BoundingBoxExtent पूर्णांक स्थिरांक है। |

 **Result:**



---


### getMinimum{#getMinimum}

| नाम | विवरण |
| --- | --- |
| getMinimum() | बाउंडिंग बॉक्स का न्यूनतम कोना। |

 **Result:**



---


### getMaximum{#getMaximum}

| नाम | विवरण |
| --- | --- |
| getMaximum() | बाउंडिंग बॉक्स का अधिकतम कोना। |

 **Result:**



---


### getSize{#getSize}

| नाम | विवरण |
| --- | --- |
| getSize() | बाउंडिंग बॉक्स का आकार |

 **Result:**



---


### getCenter{#getCenter}

| नाम | विवरण |
| --- | --- |
| getCenter() | बाउंडिंग बॉक्स का केंद्र। |

 **Result:**



---


### fromGeometry{#fromGeometry}

| नाम | विवरण |
| --- | --- |
| fromGeometry(geometry) | दिए गए ज्यामिति से बाउंडिंग बॉक्स बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| जियोमेट्र | जियोमेट्री | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | बाउंडिंग बॉक्स का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |

 **Result:**
स्ट्रिंग


---


### hashCode{#hashCode}

| नाम | विवरण |
| --- | --- |
| hashCode() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |

 **Result:**
Number


---


### equals{#equals}

| नाम | विवरण |
| --- | --- |
| equals(obj) | निर्धारित करता है कि दो ऑब्जेक्ट समान हैं या नहीं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| ob | ऑब्जेक्ट | null |

 **Result:**
boolean


---



