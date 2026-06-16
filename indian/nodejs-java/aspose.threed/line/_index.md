---
title: "Line"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/line/
---
## Line class

एक पॉलीलाइन वह पथ है जो Geometry.ControlPoints के सेट द्वारा परिभाषित होती है और Segments द्वारा जुड़ी होती है, जिसका अर्थ है कि यह जुड़ी हुई रेखा खंडों का सेट भी हो सकता है। रेखा आमतौर पर एक रैखिक वस्तु होती है, इसलिए इसे वक्र को दर्शाने के लिए उपयोग नहीं किया जा सकता; वक्र को दर्शाने के लिए NurbsCurve का उपयोग किया जाता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | Line क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(name) | Line क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |

 **Result:**



---


### getControlPoints{#getControlPoints}

| नाम | विवरण |
| --- | --- |
| getControlPoints() | सभी नियंत्रण बिंदु प्राप्त करता है |

 **Result:**



---


### getVisible{#getVisible}

| नाम | विवरण |
| --- | --- |
| getVisible() | ज्यामिति दृश्यमान है या नहीं, प्राप्त करता है या सेट करता है |

 **Result:**



---


### setVisible{#setVisible}

| नाम | विवरण |
| --- | --- |
| setVisible(value) | ज्यामिति दृश्यमान है या नहीं, प्राप्त करता है या सेट करता है |

 **Result:**



---


### getSegments{#getSegments}

| नाम | विवरण |
| --- | --- |
| getSegments() | लाइन के खंडों को प्राप्त करता है |

 **Result:**



---


### getColor{#getColor}

| नाम | विवरण |
| --- | --- |
| getColor() | रेखा का रंग प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान सफेद (1, 1, 1) है। |

 **Result:**



---


### setColor{#setColor}

| नाम | विवरण |
| --- | --- |
| setColor(value) | रेखा का रंग प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान सफेद (1, 1, 1) है। |

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


### fromPoints{#fromPoints}

| नाम | विवरण |
| --- | --- |
| fromPoints(points) | बिंदुओं के सेट से एक Line इंस्टेंस बनाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| बिंदु | Vector3[] | null |

 **Result:**
Line


---


### makeDefaultIndices{#makeDefaultIndices}

| नाम | विवरण |
| --- | --- |
| makeDefaultIndices() | 0,1,2,3....Geometry.ControlPoints.Length-1 अनुक्रम को Segments में उत्पन्न करें ताकि ControlPoints को एकल रेखा के रूप में उपयोग किया जा सके। |

 **Result:**
Line


---


### getEntityRendererKey{#getEntityRendererKey}

| नाम | विवरण |
| --- | --- |
| getEntityRendererKey() | रेंडरर में पंजीकृत इकाई रेंडरर की कुंजी प्राप्त करता है। |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| नाम | विवरण |
| --- | --- |
| getBoundingBox() | वर्तमान इकाई का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |

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



