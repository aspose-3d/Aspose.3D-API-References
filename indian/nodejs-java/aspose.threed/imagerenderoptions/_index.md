---
title: "ImageRenderOptions"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/imagerenderoptions/
---
## ImageRenderOptions class

Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) और Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions) के विकल्प


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | ImageRenderOptions का एक इंस्टेंस प्रारंभ करें |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| नाम | विवरण |
| --- | --- |
| getBackgroundColor() | रेंडर परिणाम का बैकग्राउंड रंग। |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| नाम | विवरण |
| --- | --- |
| setBackgroundColor(value) | रेंडर परिणाम का बैकग्राउंड रंग। |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| नाम | विवरण |
| --- | --- |
| getAssetDirectories() | बाहरी एसेट्स (जैसे टेक्सचर) संग्रहीत करने वाले डायरेक्टरीज़ |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| नाम | विवरण |
| --- | --- |
| getEnableShadows() | छायाओं को रेंडर करने के लिए प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| नाम | विवरण |
| --- | --- |
| setEnableShadows(value) | छायाओं को रेंडर करने के लिए प्राप्त करता है या सेट करता है। |

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



