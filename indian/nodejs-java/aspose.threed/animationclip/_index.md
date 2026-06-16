---
title: "AnimationClip"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

एनीमेशन क्लिप एनीमेशन्स का संग्रह है। दृश्य में एक या अधिक एनीमेशन क्लिप हो सकते हैं।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | AnimationClip क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(name) | AnimationClip क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम |

 **Result:**



---


### getAnimations{#getAnimations}

| नाम | विवरण |
| --- | --- |
| getAnimations() | क्लिप के भीतर मौजूद एनीमेशन प्राप्त करता है। लेयर्स। |

 **Result:**



---


### getDescription{#getDescription}

| नाम | विवरण |
| --- | --- |
| getDescription() | इस एनीमेशन क्लिप का विवरण प्राप्त करता है या सेट करता है |

 **Result:**



---


### setDescription{#setDescription}

| नाम | विवरण |
| --- | --- |
| setDescription(value) | इस एनीमेशन क्लिप का विवरण प्राप्त करता है या सेट करता है |

 **Result:**



---


### getStart{#getStart}

| नाम | विवरण |
| --- | --- |
| getStart() | क्लिप की शुरुआत का समय सेकंड में प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setStart{#setStart}

| नाम | विवरण |
| --- | --- |
| setStart(value) | क्लिप की शुरुआत का समय सेकंड में प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getStop{#getStop}

| नाम | विवरण |
| --- | --- |
| getStop() | क्लिप के अंत का समय सेकंड में प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setStop{#setStop}

| नाम | विवरण |
| --- | --- |
| setStop(value) | क्लिप के अंत का समय सेकंड में प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getScene{#getScene}

| नाम | विवरण |
| --- | --- |
| getScene() | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है। |

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


### createAnimationNode{#createAnimationNode}

| नाम | विवरण |
| --- | --- |
| createAnimationNode(nodeName) | वर्तमान क्लिप पर एनीमेशन नोड बनाने और रजिस्टर करने के लिए एक शॉर्टहैंड फ़ंक्शन। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | स्ट्रिंग | नए एनीमेशन नोड का नाम |

 **Result:**
AnimationNode


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



