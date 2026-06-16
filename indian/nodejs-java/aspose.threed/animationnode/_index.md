---
title: "AnimationNode"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D एनीमेशन पदानुक्रम का समर्थन करता है, प्रत्येक एनीमेशन कई एनीमेशन्स और एनीमेशन की की-फ़्रेम परिभाषा द्वारा निर्मित हो सकता है। AnimationNode समय के साथ प्रॉपर्टी वैल्यू के परिवर्तन को परिभाषित करता है, उदाहरण के लिए, एनीमेशन नोड का उपयोग नोड के ट्रांसफ़ॉर्मेशन या अन्य A3DObject ऑब्जेक्ट की संख्यात्मक प्रॉपर्टीज़ को नियंत्रित करने के लिए किया जा सकता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(name) | AnimationNode क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload() | AnimationNode क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

 **Result:**



---


### getBindPoints{#getBindPoints}

| नाम | विवरण |
| --- | --- |
| getBindPoints() | वर्तमान प्रॉपर्टी बाइंड पॉइंट्स प्राप्त करता है |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| नाम | विवरण |
| --- | --- |
| getSubAnimations() | वर्तमान एनीमेशन के तहत सब-एनीमेशन नोड्स प्राप्त करता है |

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


### findBindPoint{#findBindPoint}

| नाम | विवरण |
| --- | --- |
| findBindPoint(name) | नाम द्वारा बाइंड पॉइंट खोजता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | खोजने के लिए बाइंड पॉइंट का नाम। |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| नाम | विवरण |
| --- | --- |
| getBindPoint(target, propName, create) | दिए गए प्रॉपर्टी पर एनीमेशन बाइंड पॉइंट प्राप्त करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| target | A3DObject | किस ऑब्जेक्ट पर बाइंड पॉइंट बनाना है। |
| propName | स्ट्रिंग | प्रॉपर्टी का नाम। |
| बनाएँ | boolean | यदि सेट किया गया है |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| नाम | विवरण |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | दिए गए प्रॉपर्टी और चैनल पर कीफ़्रेम सीक्वेंस प्राप्त करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| target | A3DObject | किस इंस्टेंस पर कीफ़्रेम सीक्वेंस बनाना है। |
| propName | स्ट्रिंग | प्रॉपर्टी का नाम। |
| channelName | स्ट्रिंग | चैनल का नाम। |
| बनाएँ | boolean | यदि सेट किया गया है |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| नाम | विवरण |
| --- | --- |
| getKeyframeSequence(target, propName, create) | दिए गए प्रॉपर्टी पर कीफ़्रेम सीक्वेंस प्राप्त करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| target | A3DObject | किस इंस्टेंस पर कीफ़्रेम सीक्वेंस बनाना है। |
| propName | स्ट्रिंग | प्रॉपर्टी का नाम। |
| बनाएँ | boolean | यदि सेट किया गया है |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| नाम | विवरण |
| --- | --- |
| createBindPoint(obj, propName) | प्रॉपर्टी डेटा टाइप के आधार पर एक बाइंड पॉइंट बनाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| obj | A3DObject | ऑब्जेक्ट। |
| propName | स्ट्रिंग | प्रॉपर्टी का नाम। |

 **Result:**
BindPoint


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



