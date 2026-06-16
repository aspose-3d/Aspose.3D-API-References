---
title: "सामग्री"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/material/
---
## Material class

सामग्री ज्यामिति की दृश्य उपस्थिति के लिए आवश्यक पैरामीटरों को परिभाषित करती है। Aspose.3D LambertMaterial, PhongMaterial और ShaderMaterial के लिए शेडिंग मॉडल प्रदान करता है  @hideconstructor


## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| MAP_SPECULAR | setTexture(java.lang.String, com.aspose.threed.TextureBase) में उपयोग किया जाता है ताकि एक स्पेक्युलर टेक्सचर मैपिंग सौंपा जा सके। |
| MAP_DIFFUSE | setTexture(java.lang.String, com.aspose.threed.TextureBase) में उपयोग किया जाता है ताकि एक डिफ्यूज़ टेक्सचर मैपिंग सौंपा जा सके। |
| MAP_EMISSIVE | setTexture(java.lang.String, com.aspose.threed.TextureBase) में उपयोग किया जाता है ताकि एक इमिसिव टेक्सचर मैपिंग सौंपा जा सके। |
| MAP_AMBIENT | setTexture(java.lang.String, com.aspose.threed.TextureBase) में उपयोग किया जाता है ताकि एक एंबिएंट टेक्सचर मैपिंग सौंपा जा सके। |
| MAP_NORMAL | setTexture(java.lang.String, com.aspose.threed.TextureBase) में उपयोग किया जाता है ताकि एक नॉर्मल टेक्सचर मैपिंग सौंपा जा सके। |

## विधियाँ

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



