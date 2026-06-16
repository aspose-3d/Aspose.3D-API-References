---
title: "BoundingBox2D"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Vector2 के लिए एक्सिस-एलाइन्ड बाउंडिंग बॉक्स


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
| minimum | Vector2 | न्यूनतम कोना। |
| maximum | Vector2 | अधिकतम कोना। |

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


### merge{#merge}

| नाम | विवरण |
| --- | --- |
| merge(pt) | नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| नाम | विवरण |
| --- | --- |
| merge(bb) | नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | बाउंडिंग बॉक्स का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |

 **Result:**
स्ट्रिंग


---



