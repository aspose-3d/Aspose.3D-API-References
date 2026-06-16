---
title: "क्वाटरनियन"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

क्वाटरनियन का आमतौर पर कंप्यूटर ग्राफिक्स में रोटेशन करने के लिए उपयोग किया जाता है।


## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| w | w घटक। |
| x | x घटक। |
| y | y घटक। |
| z | z घटक। |
| IDENTITY | पहचान क्वाटरनियन। |

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
| constructor_overload(w, x, y, z) | क्वाटरनियन क्लास का एक नया उदाहरण आरंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| w | Number | क्वाटरनियन का w घटक |
| x | Number | क्वाटरनियन का x घटक |
| y | Number | क्वाटरनियन का y घटक |
| z | Number | क्वाटरनियन का z घटक |

 **Result:**



---


### getLength{#getLength}

| नाम | विवरण |
| --- | --- |
| getLength() | क्वाटरनियन की लंबाई प्राप्त करता है |

 **Result:**



---


### equals{#equals}

| नाम | विवरण |
| --- | --- |
| equals(obj) | जाँचें कि दो क्वाटरनियन समान हैं |

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
| hashCode() | क्वाटरनियन का हैश कोड प्राप्त करता है |

 **Result:**
Number


---


### conjugate{#conjugate}

| नाम | विवरण |
| --- | --- |
| conjugate() | वर्तमान क्वाटरनियन का संयुग्म क्वाटरनियन लौटाता है |

 **Result:**
क्वाटरनियन


---


### inverse{#inverse}

| नाम | विवरण |
| --- | --- |
| inverse() | वर्तमान क्वाटरनियन का प्रतिलोम क्वाटरनियन लौटाता है |

 **Result:**
क्वाटरनियन


---


### dot{#dot}

| नाम | विवरण |
| --- | --- |
| dot(q) | डॉट्स का गुणनफल |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| q | क्वाटरनियन | यह क्वाटरनियन |

 **Result:**
Number


---


### eulerAngles{#eulerAngles}

| नाम | विवरण |
| --- | --- |
| eulerAngles() | क्वाटरनियन को यूलेर कोणों द्वारा दर्शाए गए घूर्णन में बदलता है सभी घटक रैडियन में हैं |

 **Result:**
Vector3


---


### normalize{#normalize}

| नाम | विवरण |
| --- | --- |
| normalize() | क्वाटरनियन को सामान्यीकृत करें |

 **Result:**
क्वाटरनियन


---


### concat{#concat}

| नाम | विवरण |
| --- | --- |
| concat(rhs) | दो क्वाटरनियनों को जोड़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| rh | क्वाटरनियन | null |

 **Result:**
क्वाटरनियन


---


### fromAngleAxis{#fromAngleAxis}

| नाम | विवरण |
| --- | --- |
| fromAngleAxis(a, axis) | दिए गए अक्ष के चारों ओर एक क्वाटरनियन बनाता है और घड़ी की दिशा में घुमाता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| एक | Number | घड़ी की दिशा में घूर्णन रैडियन में |
| अक्ष | Vector3 | अक्ष |

 **Result:**
क्वाटरनियन


---


### fromRotation{#fromRotation}

| नाम | विवरण |
| --- | --- |
| fromRotation(orig, dest) | एक क्वाटरनियन बनाता है जो मूल दिशा से गंतव्य दिशा की ओर घूमता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| orig | Vector3 | मूल दिशा |
| dest | Vector3 | गंतव्य दिशा |

 **Result:**
क्वाटरनियन


---


### fromEulerAngle{#fromEulerAngle}

| नाम | विवरण |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | दिए गए यूलेर कोण से क्वाटरनियन बनाता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| पिच | Number | पिच रैडियन में |
| यॉ | Number | यॉ रैडियन में |
| रोल | Number | रैडियन में रोल |

 **Result:**
क्वाटरनियन


---


### fromEulerAngle{#fromEulerAngle}

| नाम | विवरण |
| --- | --- |
| fromEulerAngle(eulerAngle) | दिए गए यूलेर कोण से क्वाटरनियन बनाता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| eulerAngle | Vector3 | रैडियन में यूलेर कोण |

 **Result:**
क्वाटरनियन


---


### toMatrix{#toMatrix}

| नाम | विवरण |
| --- | --- |
| toMatrix() | क्वाटरनियन द्वारा प्रस्तुत घूर्णन को ट्रांसफ़ॉर्म मैट्रिक्स में बदलें। |

 **Result:**
Matrix4


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | क्वाटरनियन का प्रतिनिधित्व स्ट्रिंग में प्राप्त करता है। |

 **Result:**
स्ट्रिंग


---


### interpolate{#interpolate}

| नाम | विवरण |
| --- | --- |
| interpolate(t, from, to) | इस क्वाटरनियन को दिए गए क्वाटरनियन तर्कों के बीच t के मान के लिए इंटरपोलेटेड मान से भरता है, जहाँ t from और to के बीच होता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| t | Number | इंटरपोलेशन के लिए गुणांक। |
| from | क्वाटरनियन | स्रोत क्वाटरनियन। |
| to | क्वाटरनियन | लक्ष्य क्वाटरनियन। |

 **Result:**
क्वाटरनियन


---



