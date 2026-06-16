---
title: "कंकाल"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/skeleton/
---
## Skeleton class

Skeleton मुख्य रूप से CAD सॉफ़्टवेयर द्वारा डिज़ाइनर को कंकाल संरचना के परिवर्तन को नियंत्रित करने में मदद करने के लिए उपयोग किया जाता है, यह आमतौर पर CAD सॉफ़्टवेयर के बाहर बेकार होता है। Skeleton पदानुक्रम को CAD सॉफ़्टवेयर में एक वस्तु की तरह कार्य करने के लिए, शीर्ष Skeleton नोड को Type को SkeletonType.SKELETON सेट करके रूट नोड के रूप में चिन्हित करना आवश्यक है, और सभी बच्चों को SkeletonType.BONE पर सेट करना चाहिए।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | Skeleton वर्ग का नया उदाहरण प्रारंभ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(name) | Skeleton वर्ग का नया उदाहरण प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |

 **Result:**



---


### getSize{#getSize}

| नाम | विवरण |
| --- | --- |
| getSize() | CAD सॉफ़्टवेयर में हड्डी के आकार को दर्शाने के लिए उपयोग किए जाने वाले लिम्ब नोड आकार को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setSize{#setSize}

| नाम | विवरण |
| --- | --- |
| setSize(value) | CAD सॉफ़्टवेयर में हड्डी के आकार को दर्शाने के लिए उपयोग किए जाने वाले लिम्ब नोड आकार को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getType{#getType}

| नाम | विवरण |
| --- | --- |
| getType() | कंकाल का प्रकार प्राप्त करता है या सेट करता है। इस गुण का मान SkeletonType पूर्णांक स्थिरांक है। कंकाल का प्रकार। |

 **Result:**



---


### setType{#setType}

| नाम | विवरण |
| --- | --- |
| setType(value) | कंकाल का प्रकार प्राप्त करता है या सेट करता है। इस गुण का मान SkeletonType पूर्णांक स्थिरांक है। कंकाल का प्रकार। |

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



