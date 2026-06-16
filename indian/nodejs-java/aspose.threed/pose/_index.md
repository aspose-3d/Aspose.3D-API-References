---
title: "पोज़"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/pose/
---
## Pose class

जब ज्योमेट्री स्किन्ड होती है तो पोज़ का उपयोग ट्रांसफ़ॉर्मेशन मैट्रिक्स को संग्रहीत करने के लिए किया जाता है। पोज़ BonePose का सेट है, प्रत्येक BonePose हड्डी नोड की ठोस ट्रांसफ़ॉर्मेशन जानकारी सहेजता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(name) | Pose क्लास का नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload() | Pose क्लास का नया उदाहरण प्रारंभ करता है। |

 **Result:**



---


### getPoseType{#getPoseType}

| नाम | विवरण |
| --- | --- |
| getPoseType() | पोज़ के प्रकार को प्राप्त करता है या सेट करता है। प्रॉपर्टी का मान PoseType पूर्णांक स्थिरांक है। पोज़ का प्रकार। |

 **Result:**



---


### setPoseType{#setPoseType}

| नाम | विवरण |
| --- | --- |
| setPoseType(value) | पोज़ के प्रकार को प्राप्त करता है या सेट करता है। प्रॉपर्टी का मान PoseType पूर्णांक स्थिरांक है। पोज़ का प्रकार। |

 **Result:**



---


### getBonePoses{#getBonePoses}

| नाम | विवरण |
| --- | --- |
| getBonePoses() | सभी BonePose प्राप्त करता है। नोड्स। |

 **Result:**



---


### getName{#getName}

| नाम | विवरण |
| --- | --- |
| getName() | नाम को प्राप्त करता है या सेट करता है। नाम। |

 **Result:**



---


### setName{#setName}

| नाम | विवरण |
| --- | --- |
| setName(value) | नाम को प्राप्त करता है या सेट करता है। नाम। |

 **Result:**



---


### getProperties{#getProperties}

| नाम | विवरण |
| --- | --- |
| getProperties() | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

 **Result:**



---


### addBonePose{#addBonePose}

| नाम | विवरण |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | दिए गए बोन नोड के लिए पोज़ ट्रांसफ़ॉर्मेशन मैट्रिक्स सहेजता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| नोड | नोड | बोन नोड। |
| मैट्रिक्स | Matrix4 | ट्रांसफ़ॉर्मेशन मैट्रिक्स। |
| localMatrix | boolean | यदि सेट किया गया है |

 **Result:**



---


### addBonePose{#addBonePose}

| नाम | विवरण |
| --- | --- |
| addBonePose(node, matrix) | दिए गए हड्डी नोड के लिए पोज़ ट्रांसफ़ॉर्मेशन मैट्रिक्स को सहेजता है। ग्लोबल ट्रांसफ़ॉर्मेशन मैट्रिक्स निहित है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| नोड | नोड | बोन नोड। |
| मैट्रिक्स | Matrix4 | ट्रांसफ़ॉर्मेशन मैट्रिक्स। |

 **Result:**



---


### removeProperty{#removeProperty}

| नाम | विवरण |
| --- | --- |
| removeProperty(property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| property | Property | कौन सी प्रॉपर्टी हटानी है |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| नाम | विवरण |
| --- | --- |
| removeProperty(property) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| propert | स्ट्रिंग | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| नाम | विवरण |
| --- | --- |
| getProperty(property) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| property | स्ट्रिंग | प्रॉपर्टी का नाम |

 **Result:**
ऑब्जेक्ट


---


### setProperty{#setProperty}

| नाम | विवरण |
| --- | --- |
| setProperty(property, value) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| property | स्ट्रिंग | प्रॉपर्टी का नाम |
| मान | ऑब्जेक्ट | प्रॉपर्टी का मान |

 **Result:**
ऑब्जेक्ट


---


### findProperty{#findProperty}

| नाम | विवरण |
| --- | --- |
| findProperty(propertyName) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेेटिव प्रॉपर्टी (इसके नाम द्वारा पहचानी गई)। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| propertyName | स्ट्रिंग | प्रॉपर्टी का नाम। |

 **Result:**
Property


---



