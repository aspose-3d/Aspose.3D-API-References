---
title: "Property"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/property/
---
## Property class

उपयोगकर्ता-परिभाषित प्रॉपर्टीज़ को रखने के लिए क्लास।  @hideconstructor


## विधियाँ

### getValue{#getValue}

| नाम | विवरण |
| --- | --- |
| getValue() | मान को प्राप्त करता है या सेट करता है। मान। |

 **Result:**



---


### setValue{#setValue}

| नाम | विवरण |
| --- | --- |
| setValue(value) | मान को प्राप्त करता है या सेट करता है। मान। |

 **Result:**



---


### setName{#setName}

| नाम | विवरण |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| नाम | विवरण |
| --- | --- |
| getValueType() | प्रॉपर्टी मान का प्रकार प्राप्त करता है। मान का प्रकार। |

 **Result:**



---


### getProperties{#getProperties}

| नाम | विवरण |
| --- | --- |
| getProperties() | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

 **Result:**



---


### getBindPoint{#getBindPoint}

| नाम | विवरण |
| --- | --- |
| getBindPoint(anim, create) | निर्दिष्ट एनीमेशन इंस्टेंस पर प्रॉपर्टी बाइंड पॉइंट प्राप्त करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| anim | AnimationNode | किस एनीमेशन पर बाइंड पॉइंट बनाना है। |
| बनाएँ | boolean | यदि नहीं मिला तो प्रॉपर्टी बाइंड पॉइंट बनाएँ। |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| नाम | विवरण |
| --- | --- |
| getKeyframeSequence(anim, create) | निर्दिष्ट एनीमेशन इंस्टेंस पर कीफ़्रेम सीक्वेंस प्राप्त करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| anim | AnimationNode | किस एनीमेशन पर कीफ़्रेम सीक्वेंस बनाना है। |
| बनाएँ | boolean | यदि नहीं मिला तो कीफ़्रेम सीक्वेंस बनाएँ। |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | वर्तमान प्रॉपर्टी को दर्शाने वाली स्ट्रिंग लौटाता है। |

 **Result:**
स्ट्रिंग


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



