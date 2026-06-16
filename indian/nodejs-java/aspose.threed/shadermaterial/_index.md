---
title: "ShaderMaterial"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

एक शेडर मैटेरियल बाहरी रेंडरिंग इंजन या शेडर भाषा द्वारा मैटेरियल का वर्णन करने की अनुमति देता है। ShaderMaterial ठोस रेंडरिंग विवरणों का वर्णन करने के लिए ShaderTechnique का उपयोग करता है, और अंतिम रेंडरिंग प्लेटफ़ॉर्म के अनुसार सबसे उपयुक्त का उपयोग किया जाएगा। उदाहरण के लिए, आपके ShaderMaterial इंस्टेंस में दो तकनीकें हो सकती हैं, एक HLSL द्वारा परिभाषित और दूसरी GLSL द्वारा परिभाषित। गैर-विंडो प्लेटफ़ॉर्म पर GLSL का उपयोग HLSL के बजाय किया जाना चाहिए।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | ShaderMaterial क्लास का एक नया इंस्टेंस प्रारंभ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(name) | ShaderMaterial क्लास का एक नया इंस्टेंस प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम |

 **Result:**



---


### getTechniques{#getTechniques}

| नाम | विवरण |
| --- | --- |
| getTechniques() | इस सामग्री में परिभाषित सभी उपलब्ध तकनीकों को प्राप्त करता है। |

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


### getTexture{#getTexture}

| नाम | विवरण |
| --- | --- |
| getTexture(slotName) | निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह सामग्री की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| slotName | स्ट्रिंग | स्लॉट नाम। |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| नाम | विवरण |
| --- | --- |
| setTexture(slotName, texture) | निर्दिष्ट स्लॉट में टेक्सचर सेट करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| slotName | स्ट्रिंग | स्लॉट नाम। |
| texture | TextureBase | टेक्सचर। |

 **Result:**
TextureBase


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है। |

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


### iterator{#iterator}

| नाम | विवरण |
| --- | --- |
| iterator() | आंतरिक उपयोग के लिए आरक्षित। |

 **Result:**
Property


---



