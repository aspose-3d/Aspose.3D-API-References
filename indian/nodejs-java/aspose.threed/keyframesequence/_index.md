---
title: "KeyframeSequence"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

की‑फ़्रेम की क्रमबद्धता, यह समय के साथ सैंपल्ड मान के परिवर्तन को वर्णित करती है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(name) | KeyframeSequence क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload() | KeyframeSequence क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

 **Result:**



---


### getBindPoint{#getBindPoint}

| नाम | विवरण |
| --- | --- |
| getBindPoint() | इस कर्व को धारण करने वाले प्रॉपर्टी bind point को प्राप्त करता है। |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| नाम | विवरण |
| --- | --- |
| getKeyFrames() | इस कर्व के key frames प्राप्त करता है। कीज़। |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| नाम | विवरण |
| --- | --- |
| getPostBehavior() | post behavior प्राप्त करता है जो दर्शाता है कि अंतिम key frame के बाद सैंपल किया गया मान क्या होना चाहिए। |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| नाम | विवरण |
| --- | --- |
| getPreBehavior() | pre behavior प्राप्त करता है जो दर्शाता है कि पहले key से पहले सैंपल किया गया मान क्या होना चाहिए। |

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


### add{#add}

| नाम | विवरण |
| --- | --- |
| add(time, value) | निर्दिष्ट मान के साथ एक नया कीफ़्रेम बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| time | Number | समय स्थिति(सेकंड में मापी गई) |
| मान | Number | इस समय स्थिति में मान |

 **Result:**



---


### add{#add}

| नाम | विवरण |
| --- | --- |
| add(time, value, interpolation) | निर्दिष्ट मान के साथ एक नया कीफ़्रेम बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| time | Number | समय स्थिति(सेकंड में मापी गई) |
| मान | Number | इस समय स्थिति में मान |
| इंटरपोलेशन | इंटरपोलेशन | इंटरपोलेशन |

 **Result:**



---


### reset{#reset}

| नाम | विवरण |
| --- | --- |
| reset() | सभी कीफ़्रेम हटाता है और पोस्ट/प्रि व्यवहार को रीसेट करता है। |

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


### iterator{#iterator}

| नाम | विवरण |
| --- | --- |
| iterator() | आंतरिक उपयोग के लिए आरक्षित। |

 **Result:**
Property


---



