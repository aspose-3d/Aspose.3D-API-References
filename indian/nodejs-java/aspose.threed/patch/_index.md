---
title: "Patch"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/patch/
---
## Patch class

एक पैच एक पैरामीट्रिक मॉडलिंग सतह है, जो NurbsSurface के समान है, इसे दो PatchDirection, U और V द्वारा भी परिभाषित किया जाता है। लेकिन Patch और NurbsSurface के बीच अंतर यह है कि PatchDirection कर्व PatchDirectionType.BEZIER, PatchDirectionType.QUADRATIC_BEZIER, PatchDirectionType.BASIS_SPLINE, PatchDirectionType.CARDINAL_SPLINE और PatchDirectionType.LINEAR में से कोई एक हो सकता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | Patch क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(name) | Patch क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |

 **Result:**



---


### getU{#getU}

| नाम | विवरण |
| --- | --- |
| getU() | u दिशा प्राप्त करता है। |

 **Result:**



---


### getV{#getV}

| नाम | विवरण |
| --- | --- |
| getV() | v दिशा प्राप्त करता है। वह v. |

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


### getDeformers{#getDeformers}

| नाम | विवरण |
| --- | --- |
| getDeformers() | इस ज्यामिति से जुड़े सभी डिफॉर्मर प्राप्त करता है। डिफॉर्मर। |

 **Result:**



---


### getControlPoints{#getControlPoints}

| नाम | विवरण |
| --- | --- |
| getControlPoints() | सभी नियंत्रण बिंदु प्राप्त करता है |

 **Result:**



---


### getCastShadows{#getCastShadows}

| नाम | विवरण |
| --- | --- |
| getCastShadows() | यह निर्धारित करता है या सेट करता है कि यह ज्यामिति छाया डाल सकती है या नहीं |

 **Result:**



---


### setCastShadows{#setCastShadows}

| नाम | विवरण |
| --- | --- |
| setCastShadows(value) | यह निर्धारित करता है या सेट करता है कि यह ज्यामिति छाया डाल सकती है या नहीं |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| नाम | विवरण |
| --- | --- |
| getReceiveShadows() | यह निर्धारित करता है या सेट करता है कि यह ज्यामिति छाया प्राप्त कर सकती है या नहीं। |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| नाम | विवरण |
| --- | --- |
| setReceiveShadows(value) | यह निर्धारित करता है या सेट करता है कि यह ज्यामिति छाया प्राप्त कर सकती है या नहीं। |

 **Result:**



---


### getVertexElements{#getVertexElements}

| नाम | विवरण |
| --- | --- |
| getVertexElements() | सभी वर्टेक्स तत्व प्राप्त करता है |

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


### getElement{#getElement}

| नाम | विवरण |
| --- | --- |
| getElement(type) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स तत्व प्राप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| नाम | विवरण |
| --- | --- |
| getVertexElementOfUV(textureMapping) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक VertexElementUV इंस्टेंस प्राप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| नाम | विवरण |
| --- | --- |
| createElement(type) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स तत्व बनाता है और इसे ज्यामिति में जोड़ता है। यदि type VertexElementType.UV है, तो TextureMapping.DIFFUSE प्रकार के टेक्सचर मैपिंग के साथ एक VertexElementUV बनाया जाएगा। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| नाम | विवरण |
| --- | --- |
| addElement(element) | एक मौजूदा वर्टेक्स तत्व को वर्तमान ज्यामिति में जोड़ता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| element | VertexElement | जोड़ने के लिए वर्टेक्स तत्व |

 **Result:**
VertexElement


---


### createElement{#createElement}

| नाम | विवरण |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स तत्व बनाता है और इसे ज्यामिति में जोड़ता है। यदि type VertexElementType.UV है, तो TextureMapping.DIFFUSE प्रकार के टेक्सचर मैपिंग के साथ एक VertexElementUV बनाया जाएगा। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| नाम | विवरण |
| --- | --- |
| createElementUV(uvMapping) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक VertexElementUV बनाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| नाम | विवरण |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक VertexElementUV बनाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| नाम | विवरण |
| --- | --- |
| getBoundingBox() | वर्तमान इकाई का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |

 **Result:**
VertexElementUV


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



