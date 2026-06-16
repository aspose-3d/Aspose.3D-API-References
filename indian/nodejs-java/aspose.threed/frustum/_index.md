---
title: "फ्रस्टम"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/frustum/
---
## Frustum class

कैमरा और लाइट की बेस क्लास  @hideconstructor


## विधियाँ

### getRotationMode{#getRotationMode}

| नाम | विवरण |
| --- | --- |
| getRotationMode() | फ़्रस्टम की अभिविन्यास मोड को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब काम करती है जब Target null हो। यदि मान RotationMode.FIXED_TARGET है, तो दिशा हमेशा LookAt प्रॉपर्टी द्वारा गणना की जाती है। अन्यथा LookAt हमेशा Direction द्वारा गणना की जाती है। इस प्रॉपर्टी का मान RotationMode पूर्णांक स्थिरांक है। |

 **Result:**



---


### setRotationMode{#setRotationMode}

| नाम | विवरण |
| --- | --- |
| setRotationMode(value) | फ़्रस्टम की अभिविन्यास मोड को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब काम करती है जब Target null हो। यदि मान RotationMode.FIXED_TARGET है, तो दिशा हमेशा LookAt प्रॉपर्टी द्वारा गणना की जाती है। अन्यथा LookAt हमेशा Direction द्वारा गणना की जाती है। इस प्रॉपर्टी का मान RotationMode पूर्णांक स्थिरांक है। |

 **Result:**



---


### getNearPlane{#getNearPlane}

| नाम | विवरण |
| --- | --- |
| getNearPlane() | फ़्रस्टम की निकट प्लेन दूरी को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setNearPlane{#setNearPlane}

| नाम | विवरण |
| --- | --- |
| setNearPlane(value) | फ़्रस्टम की निकट प्लेन दूरी को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getFarPlane{#getFarPlane}

| नाम | विवरण |
| --- | --- |
| getFarPlane() | फ़्रस्टम की दूरस्थ प्लेन दूरी को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setFarPlane{#setFarPlane}

| नाम | विवरण |
| --- | --- |
| setFarPlane(value) | फ़्रस्टम की दूरस्थ प्लेन दूरी को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getAspect{#getAspect}

| नाम | विवरण |
| --- | --- |
| getAspect() | फ़्रस्टम के आस्पेक्ट अनुपात को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setAspect{#setAspect}

| नाम | विवरण |
| --- | --- |
| setAspect(value) | फ़्रस्टम के आस्पेक्ट अनुपात को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| नाम | विवरण |
| --- | --- |
| getOrthoHeight() | ऑर्थोग्राफिक प्रोजेक्शन में फ़्रस्टम के लिए ऊँचाई को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| नाम | विवरण |
| --- | --- |
| setOrthoHeight(value) | ऑर्थोग्राफिक प्रोजेक्शन में फ़्रस्टम के लिए ऊँचाई को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getUp{#getUp}

| नाम | विवरण |
| --- | --- |
| getUp() | कैमरा की ऊपर की दिशा को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setUp{#setUp}

| नाम | विवरण |
| --- | --- |
| setUp(value) | कैमरा की ऊपर की दिशा को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getLookAt{#getLookAt}

| नाम | विवरण |
| --- | --- |
| getLookAt() | कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setLookAt{#setLookAt}

| नाम | विवरण |
| --- | --- |
| setLookAt(value) | कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getDirection{#getDirection}

| नाम | विवरण |
| --- | --- |
| getDirection() | कैमरा जिस दिशा की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। इस प्रॉपर्टी में परिवर्तन LookAt और Target को भी प्रभावित करेंगे। |

 **Result:**



---


### setDirection{#setDirection}

| नाम | विवरण |
| --- | --- |
| setDirection(value) | कैमरा जिस दिशा की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। इस प्रॉपर्टी में परिवर्तन LookAt और Target को भी प्रभावित करेंगे। |

 **Result:**



---


### getTarget{#getTarget}

| नाम | विवरण |
| --- | --- |
| getTarget() | कैमरा जिस लक्ष्य की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। यदि उपयोगकर्ता इस प्रॉपर्टी का समर्थन करता है, तो यह LookAt प्रॉपर्टी से पहले होना चाहिए। |

 **Result:**



---


### setTarget{#setTarget}

| नाम | विवरण |
| --- | --- |
| setTarget(value) | कैमरा जिस लक्ष्य की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। यदि उपयोगकर्ता इस प्रॉपर्टी का समर्थन करता है, तो यह LookAt प्रॉपर्टी से पहले होना चाहिए। |

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


### getBoundingBox{#getBoundingBox}

| नाम | विवरण |
| --- | --- |
| getBoundingBox() | वर्तमान इकाई का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |

 **Result:**



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



