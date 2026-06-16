---
title: "नोड"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/node/
---
## Node class

दृश्य ग्राफ़ में एक तत्व का प्रतिनिधित्व करता है। दृश्य ग्राफ़ Node वस्तुओं का एक वृक्ष है। वृक्ष प्रबंधन सेवाएँ इस क्लास में स्वयं-contained हैं। ध्यान दें कि Aspose.3D SDK निर्मित दृश्य ग्राफ़ की वैधता की जाँच नहीं करता। यह कॉलर की जिम्मेदारी है कि वह सुनिश्चित करे कि नोड पदानुक्रम में चक्रीय ग्राफ़ न बनें। वृक्ष प्रबंधन के अलावा, यह क्लास वस्तु की स्थिति का वर्णन करने के लिए आवश्यक सभी गुणों को परिभाषित करती है। इस जानकारी में मूल Translation, Rotation और Scaling गुण तथा पिवट, सीमाएँ, और IK जॉइंट्स जैसे उन्नत विकल्प शामिल हैं, जैसे stiffness और damping। जब पहली बार बनाया जाता है, तो Node वस्तु "empty" (अर्थात् यह एक ऐसी वस्तु है जिसमें कोई ग्राफिकल प्रतिनिधित्व नहीं है और केवल स्थिति जानकारी होती है) होती है। इस स्थिति में, इसे नोड ट्री संरचना में पैरेंट्स को दर्शाने के लिए उपयोग किया जा सकता है लेकिन अधिक नहीं। इस प्रकार की वस्तुओं का सामान्य उपयोग उन्हें एक Entity जोड़ना है जो नोड को विशेष बनाता है (देखें "Entity")। Entity स्वयं में एक वस्तु है और Node से जुड़ी होती है। इसका अर्थ यह भी है कि वही Entity कई नोड्स के बीच साझा किया जा सकता है। Camera, Light, Mesh आदि सभी Entity से व्युत्पन्न हैं और सभी Entity बेस क्लास से विरासत में प्राप्त हैं।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | Node वर्ग की नई उदाहरण को प्रारंभ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(name, entity) | Node वर्ग की नई उदाहरण को प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |
| एंटिटी | एंटिटी | डिफ़ॉल्ट इकाई। |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| नाम | विवरण |
| --- | --- |
| constructor_overload2(name) | Node वर्ग की नई उदाहरण को प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| नाम | विवरण |
| --- | --- |
| getAssetInfo() | प्रति-नोड संपत्ति जानकारी |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| नाम | विवरण |
| --- | --- |
| setAssetInfo(value) | प्रति-नोड संपत्ति जानकारी |

 **Result:**



---


### getVisible{#getVisible}

| नाम | विवरण |
| --- | --- |
| getVisible() | नोड को दिखाने के लिए प्राप्त करता है या सेट करता है |

 **Result:**



---


### setVisible{#setVisible}

| नाम | विवरण |
| --- | --- |
| setVisible(value) | नोड को दिखाने के लिए प्राप्त करता है या सेट करता है |

 **Result:**



---


### getChildNodes{#getChildNodes}

| नाम | विवरण |
| --- | --- |
| getChildNodes() | बच्चे नोड्स को प्राप्त करता है। नोड्स। |

 **Result:**



---


### getEntity{#getEntity}

| नाम | विवरण |
| --- | --- |
| getEntity() | इस नोड से जुड़ी पहली इकाई को प्राप्त करता है या सेट करता है, यदि सेट किया जाता है तो अन्य इकाइयों को साफ़ कर देगा। नोड इकाई। |

 **Result:**



---


### setEntity{#setEntity}

| नाम | विवरण |
| --- | --- |
| setEntity(value) | इस नोड से जुड़ी पहली इकाई को प्राप्त करता है या सेट करता है, यदि सेट किया जाता है तो अन्य इकाइयों को साफ़ कर देगा। नोड इकाई। |

 **Result:**



---


### getExcluded{#getExcluded}

| नाम | विवरण |
| --- | --- |
| getExcluded() | निर्यात के दौरान इस नोड और सभी चाइल्ड नोड्स/इकाइयों को बाहर रखने के बारे में प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setExcluded{#setExcluded}

| नाम | विवरण |
| --- | --- |
| setExcluded(value) | निर्यात के दौरान इस नोड और सभी चाइल्ड नोड्स/इकाइयों को बाहर रखने के बारे में प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getEntities{#getEntities}

| नाम | विवरण |
| --- | --- |
| getEntities() | सभी नोड इकाइयों को प्राप्त करता है। नोड इकाइयाँ। |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| नाम | विवरण |
| --- | --- |
| getMetaDatas() | इस नोड में परिभाषित मेटा डेटा को प्राप्त करता है। मेटा डेटा। |

 **Result:**



---


### getMaterials{#getMaterials}

| नाम | विवरण |
| --- | --- |
| getMaterials() | इस नोड से जुड़े सामग्री को प्राप्त करता है। सामग्री। |

 **Result:**



---


### getMaterial{#getMaterial}

| नाम | विवरण |
| --- | --- |
| getMaterial() | इस नोड से जुड़ी पहली सामग्री को प्राप्त करता है या सेट करता है, यदि सेट किया जाता है तो अन्य सामग्रियों को साफ़ कर देगा। सामग्री। |

 **Result:**



---


### setMaterial{#setMaterial}

| नाम | विवरण |
| --- | --- |
| setMaterial(value) | इस नोड से जुड़ी पहली सामग्री को प्राप्त करता है या सेट करता है, यदि सेट किया जाता है तो अन्य सामग्रियों को साफ़ कर देगा। सामग्री। |

 **Result:**



---


### getParentNode{#getParentNode}

| नाम | विवरण |
| --- | --- |
| getParentNode() | पैरेंट नोड को प्राप्त करता है या सेट करता है। पैरेंट नोड। |

 **Result:**



---


### setParentNode{#setParentNode}

| नाम | विवरण |
| --- | --- |
| setParentNode(value) | पैरेंट नोड को प्राप्त करता है या सेट करता है। पैरेंट नोड। |

 **Result:**



---


### getTransform{#getTransform}

| नाम | विवरण |
| --- | --- |
| getTransform() | स्थानीय ट्रांसफ़ॉर्म प्राप्त करता है। ट्रांसफ़ॉर्म। |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| नाम | विवरण |
| --- | --- |
| getGlobalTransform() | वैश्विक ट्रांसफ़ॉर्म प्राप्त करता है। वैश्विक ट्रांसफ़ॉर्म। |

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


### createChildNode{#createChildNode}

| नाम | विवरण |
| --- | --- |
| createChildNode() | एक चाइल्ड नोड बनाता है |

 **Result:**
नोड


---


### merge{#merge}

| नाम | विवरण |
| --- | --- |
| merge(node) | नोड के तहत सभी चीज़ों को अलग करें और उन्हें वर्तमान नोड से संलग्न करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| नोड | नोड | null |

 **Result:**
नोड


---


### createChildNode{#createChildNode}

| नाम | विवरण |
| --- | --- |
| createChildNode(nodeName) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | स्ट्रिंग | नए चाइल्ड नोड का नाम |

 **Result:**
नोड


---


### createChildNode{#createChildNode}

| नाम | विवरण |
| --- | --- |
| createChildNode(entity) | दिए गए एंटिटी संलग्न के साथ एक नया चाइल्ड नोड बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | डिफ़ॉल्ट एंटिटी नोड से संलग्न है |

 **Result:**
नोड


---


### createChildNode{#createChildNode}

| नाम | विवरण |
| --- | --- |
| createChildNode(nodeName, entity) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | स्ट्रिंग | नए चाइल्ड नोड का नाम |
| एंटिटी | एंटिटी | डिफ़ॉल्ट एंटिटी नोड से संलग्न है |

 **Result:**
नोड


---


### createChildNode{#createChildNode}

| नाम | विवरण |
| --- | --- |
| createChildNode(nodeName, entity, material) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं, और निर्दिष्ट एंटिटी और एक सामग्री संलग्न करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | स्ट्रिंग | नए चाइल्ड नोड का नाम |
| एंटिटी | एंटिटी | डिफ़ॉल्ट एंटिटी नोड से संलग्न है |
| material | सामग्री | नोड से संलग्न सामग्री |

 **Result:**
नोड


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| नाम | विवरण |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | वैश्विक ट्रांसफ़ॉर्म का मूल्यांकन करें, ज्यामितीय ट्रांसफ़ॉर्म को शामिल करें या नहीं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| withGeometricTransform | boolean | क्या ज्यामितीय ट्रांसफ़ॉर्म आवश्यक है। |

 **Result:**
Matrix4


---


### getChild{#getChild}

| नाम | विवरण |
| --- | --- |
| getChild(index) | निर्दिष्ट अनुक्रमांक पर चाइल्ड नोड प्राप्त करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| index | Number | Index. |

 **Result:**
नोड


---


### getChild{#getChild}

| नाम | विवरण |
| --- | --- |
| getChild(nodeName) | निर्दिष्ट नाम वाले चाइल्ड नोड को प्राप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | स्ट्रिंग | खोजने के लिए चाइल्ड का नाम। |

 **Result:**
नोड


---


### accept{#accept}

| नाम | विवरण |
| --- | --- |
| accept(visitor) | सभी वंशज नोड्स (वर्तमान नोड सहित) के माध्यम से चलता है और नोड के साथ विज़िटर को कॉल करता है। विज़िटर false लौटाकर वॉक-थ्रू को रोक सकता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| visitor | NodeVisitor | नोड को विज़िट करने के लिए विज़िटर कॉलबैक |

 **Result:**
boolean


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | इस नोड का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |

 **Result:**
स्ट्रिंग


---


### getBoundingBox{#getBoundingBox}

| नाम | विवरण |
| --- | --- |
| getBoundingBox() | नोड का बाउंडिंग बॉक्स गणना करता है |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| नाम | विवरण |
| --- | --- |
| addEntity(entity) | नोड में एक एंटिटी जोड़ें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | नोड से जुड़ने वाली एंटिटी |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| नाम | विवरण |
| --- | --- |
| addChildNode(node) | इस नोड में एक चाइल्ड नोड जोड़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| नोड | नोड | जुड़ने वाला चाइल्ड नोड |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| नाम | विवरण |
| --- | --- |
| selectSingleObject(path) | XPath जैसी क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के तहत एकल ऑब्जेक्ट चुनें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| pat | स्ट्रिंग | null |

 **Result:**
ऑब्जेक्ट


---


### selectObjects{#selectObjects}

| नाम | विवरण |
| --- | --- |
| selectObjects(path) | XPath जैसी क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के तहत कई ऑब्जेक्ट चुनें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| pat | स्ट्रिंग | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



