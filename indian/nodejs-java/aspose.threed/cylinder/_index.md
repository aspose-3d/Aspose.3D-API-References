---
title: "Cylinder"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

पैरामीटराइज़्ड सिलिंडर। जब radiusTop या radiusBottom में से कोई एक शून्य हो तो इसे शंकु के रूप में भी उपयोग किया जा सकता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | Cylinder वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(radius, height) | Cylinder वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| radius | Number | ऊपरी और निचले कैप की त्रिज्या। |
| height | Number | ऊँचाई। |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| नाम | विवरण |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Cylinder वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| radiusTop | Number | ऊपरी त्रिज्या। |
| radiusBottom | Number | निचली त्रिज्या। |
| height | Number | ऊँचाई। |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| नाम | विवरण |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Cylinder वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| radiusTop | Number | सिलेंडर के ऊपरी कैप की त्रिज्या। |
| radiusBottom | Number | सिलेंडर के निचले कैप की त्रिज्या। |
| height | Number | सिलेंडर की ऊँचाई। |
| radialSegments | Number | ऊपरी और निचले दोनों वृत्तों के रेडियल सेगमेंट। |
| heightSegments | Number | ऊँचाई खंड। |
| openEnded | boolean | यदि सेट किया गया है |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| नाम | विवरण |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Cylinder वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | इस वस्तु का नाम |
| radiusTop | Number | सिलेंडर के ऊपरी कैप की त्रिज्या। |
| radiusBottom | Number | सिलेंडर के निचले कैप की त्रिज्या। |
| height | Number | सिलेंडर की ऊँचाई। |
| radialSegments | Number | ऊपरी और निचले दोनों वृत्तों के रेडियल सेगमेंट। |
| heightSegments | Number | ऊँचाई खंड। |
| openEnded | boolean | यदि सेट किया गया है |
| thetaStart | Number | Theta प्रारंभ। |
| thetaLength | Number | Theta लंबाई। |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| नाम | विवरण |
| --- | --- |
| getOffsetBottom() | निचले पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| नाम | विवरण |
| --- | --- |
| setOffsetBottom(value) | निचले पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| नाम | विवरण |
| --- | --- |
| getOffsetTop() | ऊपरी पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| नाम | विवरण |
| --- | --- |
| setOffsetTop(value) | ऊपरी पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| नाम | विवरण |
| --- | --- |
| getGenerateFanCylinder() | प्राप्त करता है या सेट करता है कि जब ThetaLength 2PI से कम हो तो फैन-स्टाइल सिलेंडर उत्पन्न किया जाए, अन्यथा मॉडल नहीं काटा जाएगा। |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| नाम | विवरण |
| --- | --- |
| setGenerateFanCylinder(value) | प्राप्त करता है या सेट करता है कि जब ThetaLength 2PI से कम हो तो फैन-स्टाइल सिलेंडर उत्पन्न किया जाए, अन्यथा मॉडल नहीं काटा जाएगा। |

 **Result:**



---


### getShearBottom{#getShearBottom}

| नाम | विवरण |
| --- | --- |
| getShearBottom() | प्राप्त करता है या सेट करता है नीचे की ओर के शियर ट्रांसफ़ॉर्म को, वेक्टर (x-अक्ष, z-अक्ष) शियर मान को रेडियन में मापता है, डिफ़ॉल्ट मान (0, 0) है। |

 **Result:**



---


### setShearBottom{#setShearBottom}

| नाम | विवरण |
| --- | --- |
| setShearBottom(value) | प्राप्त करता है या सेट करता है नीचे की ओर के शियर ट्रांसफ़ॉर्म को, वेक्टर (x-अक्ष, z-अक्ष) शियर मान को रेडियन में मापता है, डिफ़ॉल्ट मान (0, 0) है। |

 **Result:**



---


### getShearTop{#getShearTop}

| नाम | विवरण |
| --- | --- |
| getShearTop() | प्राप्त करता है या सेट करता है ऊपर की ओर के शियर ट्रांसफ़ॉर्म को, वेक्टर (x-अक्ष, z-अक्ष) शियर मान को रेडियन में मापता है, डिफ़ॉल्ट मान (0, 0) है। |

 **Result:**



---


### setShearTop{#setShearTop}

| नाम | विवरण |
| --- | --- |
| setShearTop(value) | प्राप्त करता है या सेट करता है ऊपर की ओर के शियर ट्रांसफ़ॉर्म को, वेक्टर (x-अक्ष, z-अक्ष) शियर मान को रेडियन में मापता है, डिफ़ॉल्ट मान (0, 0) है। |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| नाम | विवरण |
| --- | --- |
| getRadiusTop() | प्राप्त करता है या सेट करता है सिलेंडर के शीर्ष कैप की त्रिज्या। शीर्ष कैप की त्रिज्या। |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| नाम | विवरण |
| --- | --- |
| setRadiusTop(value) | प्राप्त करता है या सेट करता है सिलेंडर के शीर्ष कैप की त्रिज्या। शीर्ष कैप की त्रिज्या। |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| नाम | विवरण |
| --- | --- |
| getRadiusBottom() | प्राप्त करता है या सेट करता है सिलेंडर के निचले कैप की त्रिज्या। निचले कैप की त्रिज्या। |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| नाम | विवरण |
| --- | --- |
| setRadiusBottom(value) | प्राप्त करता है या सेट करता है सिलेंडर के निचले कैप की त्रिज्या। निचले कैप की त्रिज्या। |

 **Result:**



---


### getHeight{#getHeight}

| नाम | विवरण |
| --- | --- |
| getHeight() | प्राप्त करता है या सेट करता है सिलेंडर की ऊँचाई। ऊँचाई। |

 **Result:**



---


### setHeight{#setHeight}

| नाम | विवरण |
| --- | --- |
| setHeight(value) | प्राप्त करता है या सेट करता है सिलेंडर की ऊँचाई। ऊँचाई। |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| नाम | विवरण |
| --- | --- |
| getRadialSegments() | प्राप्त करता है या सेट करता है रेडियल सेगमेंट्स। रेडियल सेगमेंट्स। |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| नाम | विवरण |
| --- | --- |
| setRadialSegments(value) | प्राप्त करता है या सेट करता है रेडियल सेगमेंट्स। रेडियल सेगमेंट्स। |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| नाम | विवरण |
| --- | --- |
| getHeightSegments() | ऊँचाई खंड को प्राप्त या सेट करता है। ऊँचाई खंड। |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| नाम | विवरण |
| --- | --- |
| setHeightSegments(value) | ऊँचाई खंड को प्राप्त या सेट करता है। ऊँचाई खंड। |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| नाम | विवरण |
| --- | --- |
| getOpenEnded() | प्राप्त करता है या सेट करता है एक मान जो दर्शाता है कि यह सिलेंडर खुला है या नहीं। डिफ़ॉल्ट मान false है। यदि खुला है तो true; अन्यथा, शीर्ष/नीचे के कैप मौजूद होते हैं। |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| नाम | विवरण |
| --- | --- |
| setOpenEnded(value) | प्राप्त करता है या सेट करता है एक मान जो दर्शाता है कि यह सिलेंडर खुला है या नहीं। डिफ़ॉल्ट मान false है। यदि खुला है तो true; अन्यथा, शीर्ष/नीचे के कैप मौजूद होते हैं। |

 **Result:**



---


### getThetaStart{#getThetaStart}

| नाम | विवरण |
| --- | --- |
| getThetaStart() | प्राप्त करता है या सेट करता है थीटा की शुरुआत। डिफ़ॉल्ट मान 0 है। थीटा की शुरुआत। |

 **Result:**



---


### setThetaStart{#setThetaStart}

| नाम | विवरण |
| --- | --- |
| setThetaStart(value) | प्राप्त करता है या सेट करता है थीटा की शुरुआत। डिफ़ॉल्ट मान 0 है। थीटा की शुरुआत। |

 **Result:**



---


### getThetaLength{#getThetaLength}

| नाम | विवरण |
| --- | --- |
| getThetaLength() | प्राप्त करता है या सेट करता है थीटा की लंबाई। डिफ़ॉल्ट मान 2π है। थीटा की लंबाई। |

 **Result:**



---


### setThetaLength{#setThetaLength}

| नाम | विवरण |
| --- | --- |
| setThetaLength(value) | प्राप्त करता है या सेट करता है थीटा की लंबाई। डिफ़ॉल्ट मान 2π है। थीटा की लंबाई। |

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
| toMesh() | वर्तमान वस्तु को मेष में परिवर्तित करें |

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



