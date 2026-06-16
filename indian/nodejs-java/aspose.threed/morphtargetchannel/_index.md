---
title: "MorphTargetChannel"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

MorphTargetDeformer द्वारा लक्ष्य ज्यामितियों को व्यवस्थित करने के लिए एक MorphTargetChannel का उपयोग किया जाता है। FBX जैसे कुछ फ़ाइल स्वरूप समानांतर में कई चैनलों का समर्थन करते हैं। वजन 0 से 1.0 के बीच होता है, और लक्ष्य के लिए डिफ़ॉल्ट वजन 0.0 है;


## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| DEFAULT_WEIGHT | मॉर्फ़ टार्गेट के लिए डिफ़ॉल्ट वजन। |

## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(name) | MorphTargetChannel वर्ग का नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload() | MorphTargetChannel वर्ग का नया उदाहरण प्रारंभ करता है। |

 **Result:**



---


### getWeights{#getWeights}

| नाम | विवरण |
| --- | --- |
| getWeights() | लक्ष्य ज्यामितियों के पूर्ण वजन मान प्राप्त करता है। पूर्ण वजन। |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| नाम | विवरण |
| --- | --- |
| getChannelWeight() | इस चैनल के डीफ़ॉर्मर वजन को प्राप्त करता है या सेट करता है। वजन 0.0 और 1.0 के बीच है। |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| नाम | विवरण |
| --- | --- |
| setChannelWeight(value) | इस चैनल के डीफ़ॉर्मर वजन को प्राप्त करता है या सेट करता है। वजन 0.0 और 1.0 के बीच है। |

 **Result:**



---


### getTargets{#getTargets}

| नाम | विवरण |
| --- | --- |
| getTargets() | चैनल से जुड़े सभी लक्ष्य प्राप्त करता है। |

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


### get{#get}

| नाम | विवरण |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| नाम | विवरण |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| नाम | विवरण |
| --- | --- |
| getWeight(target) | निर्दिष्ट लक्ष्य के लिए वजन प्राप्त करता है, यदि लक्ष्य इस चैनल से संबंधित नहीं है, तो डिफ़ॉल्ट मान 0 लौटाया जाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| targe | आकार | null |

 **Result:**
Number


---


### setWeight{#setWeight}

| नाम | विवरण |
| --- | --- |
| setWeight(target, weight) | निर्दिष्ट लक्ष्य के लिए वजन सेट करता है, डिफ़ॉल्ट मान 1 है, सीमा 0~1 के बीच होनी चाहिए। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| targe | आकार | null |
| वज़न | Number | null |

 **Result:**
Number


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



