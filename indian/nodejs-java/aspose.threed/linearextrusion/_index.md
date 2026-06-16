---
title: "LinearExtrusion"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

रैखिक एक्सट्रूज़न 2D आकार को इनपुट के रूप में लेता है और आकार को तीसरी आयाम में विस्तारित करता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | LinearExtrusion का उदाहरण का कंस्ट्रक्टर। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(shape, height) | LinearExtrusion का उदाहरण का कंस्ट्रक्टर। |

 **Result:**



---


### getShape{#getShape}

| नाम | विवरण |
| --- | --- |
| getShape() | एक्सट्रूड किए जाने वाले बेस आकार। |

 **Result:**



---


### setShape{#setShape}

| नाम | विवरण |
| --- | --- |
| setShape(value) | एक्सट्रूड किए जाने वाले बेस आकार। |

 **Result:**



---


### getDirection{#getDirection}

| नाम | विवरण |
| --- | --- |
| getDirection() | एक्सट्रूजन की दिशा, डिफ़ॉल्ट मान (0, 0, 1) है। |

 **Result:**



---


### setDirection{#setDirection}

| नाम | विवरण |
| --- | --- |
| setDirection(value) | एक्सट्रूजन की दिशा, डिफ़ॉल्ट मान (0, 0, 1) है। |

 **Result:**



---


### getHeight{#getHeight}

| नाम | विवरण |
| --- | --- |
| getHeight() | एक्सट्रूडेड ज्योमेट्री की ऊँचाई, डिफ़ॉल्ट मान 1.0 है। |

 **Result:**



---


### setHeight{#setHeight}

| नाम | विवरण |
| --- | --- |
| setHeight(value) | एक्सट्रूडेड ज्योमेट्री की ऊँचाई, डिफ़ॉल्ट मान 1.0 है। |

 **Result:**



---


### getSlices{#getSlices}

| नाम | विवरण |
| --- | --- |
| getSlices() | ट्विस्टेड एक्सट्रूडेड ज्योमेट्री के स्लाइस, डिफ़ॉल्ट मान 1 है। |

 **Result:**



---


### setSlices{#setSlices}

| नाम | विवरण |
| --- | --- |
| setSlices(value) | ट्विस्टेड एक्सट्रूडेड ज्योमेट्री के स्लाइस, डिफ़ॉल्ट मान 1 है। |

 **Result:**



---


### getCenter{#getCenter}

| नाम | विवरण |
| --- | --- |
| getCenter() | यदि यह मान false है, तो लीनियर एक्सट्रूजन Z रेंज 0 से ऊँचाई तक होगी, अन्यथा रेंज -height/2 से height/2 तक होगी। |

 **Result:**



---


### setCenter{#setCenter}

| नाम | विवरण |
| --- | --- |
| setCenter(value) | यदि यह मान false है, तो लीनियर एक्सट्रूजन Z रेंज 0 से ऊँचाई तक होगी, अन्यथा रेंज -height/2 से height/2 तक होगी। |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| नाम | विवरण |
| --- | --- |
| getTwistOffset() | ट्विस्टिंग में उपयोग किया जाने वाला ऑफ़सेट, डिफ़ॉल्ट मान (0, 0, 0) है। |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| नाम | विवरण |
| --- | --- |
| setTwistOffset(value) | ट्विस्टिंग में उपयोग किया जाने वाला ऑफ़सेट, डिफ़ॉल्ट मान (0, 0, 0) है। |

 **Result:**



---


### getTwist{#getTwist}

| नाम | विवरण |
| --- | --- |
| getTwist() | आकार को एक्सट्रूड करने के लिए उपयोग किए जाने वाले डिग्री की संख्या। |

 **Result:**



---


### setTwist{#setTwist}

| नाम | विवरण |
| --- | --- |
| setTwist(value) | आकार को एक्सट्रूड करने के लिए उपयोग किए जाने वाले डिग्री की संख्या। |

 **Result:**



---


### getParentNodes{#getParentNodes}

| नाम | विवरण |
| --- | --- |
| getParentNodes() | सभी पैरेंट नोड्स प्राप्त करता है, एक इकाई को ज्यामिति इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है। नोड्स। |

 **Result:**



---


### getExcluded{#getExcluded}

| नाम | विवरण |
| --- | --- |
| getExcluded() | निर्यात के दौरान इस इकाई को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setExcluded{#setExcluded}

| नाम | विवरण |
| --- | --- |
| setExcluded(value) | निर्यात के दौरान इस इकाई को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getParentNode{#getParentNode}

| नाम | विवरण |
| --- | --- |
| getParentNode() | पहले पैरेंट नोड को प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। पैरेंट नोड। |

 **Result:**



---


### setParentNode{#setParentNode}

| नाम | विवरण |
| --- | --- |
| setParentNode(value) | पहले पैरेंट नोड को प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। पैरेंट नोड। |

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


### toMesh{#toMesh}

| नाम | विवरण |
| --- | --- |
| toMesh() | एक्सट्रूजन को मेष में बदलें। |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| नाम | विवरण |
| --- | --- |
| getBoundingBox() | वर्तमान इकाई का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| नाम | विवरण |
| --- | --- |
| getEntityRendererKey() | रेंडरर में पंजीकृत इकाई रेंडरर की कुंजी प्राप्त करता है। |

 **Result:**
EntityRendererKey


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



