---
title: "TriMesh"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

एक TriMesh कच्चा डेटा रखता है जिसे GPU द्वारा सीधे उपयोग किया जा सकता है। यह क्लास एक उपयोगिता है जो केवल प्रति-वर्टेक्स डेटा वाले मेष को बनाने में मदद करती है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(name, declaration) | TriMesh का एक उदाहरण प्रारंभ करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | इस TriMesh का नाम |
| घोषणा | VertexDeclaration | वर्टेक्स की घोषणा |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| नाम | विवरण |
| --- | --- |
| getVertexDeclaration() | TriMesh का वर्टेक्स लेआउट। |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| नाम | विवरण |
| --- | --- |
| getVerticesCount() | इस TriMesh में वर्टेक्स की संख्या |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| नाम | विवरण |
| --- | --- |
| getIndicesCount() | इस TriMesh में सूचकांकों की संख्या |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| नाम | विवरण |
| --- | --- |
| getUnmergedVerticesCount() | beginVertex() और endVertex() द्वारा पास किए गए अनमर्ज्ड वर्टिसेज़ की संख्या। |

 **Result:**



---


### getCapacity{#getCapacity}

| नाम | विवरण |
| --- | --- |
| getCapacity() | पूर्व-आवंटित वर्टिसेज़ की क्षमता। |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| नाम | विवरण |
| --- | --- |
| getVerticesSizeInBytes() | सभी वर्टिसेज़ का कुल आकार बाइट्स में |

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


### fromMesh{#fromMesh}

| नाम | विवरण |
| --- | --- |
| fromMesh(declaration, mesh) | दिए गए मेष ऑब्जेक्ट और दिए गए वर्टेक्स लेआउट से एक TriMesh बनाएं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| नाम | विवरण |
| --- | --- |
| copyFrom(input, vd) | इनपुट से नए वर्टेक्स लेआउट के साथ TriMesh कॉपी करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| input | TriMesh | कॉपी करने के लिए इनपुट TriMesh |
| vd | VertexDeclaration | आउटपुट TriMesh की नई वर्टेक्स घोषणा |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| नाम | विवरण |
| --- | --- |
| fromMesh(mesh, useFloat) | दिए गए मेष ऑब्जेक्ट से एक TriMesh बनाएं, वर्टेक्स घोषणा इनपुट मेष की संरचना पर आधारित है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | प्रत्येक वर्टेक्स तत्व घटक के लिए डबल प्रकार के बजाय फ़्लोट प्रकार का उपयोग करें। |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| नाम | विवरण |
| --- | --- |
| beginVertex() | वर्टेक्स जोड़ना शुरू करें |

 **Result:**
वर्टेक्स


---


### endVertex{#endVertex}

| नाम | विवरण |
| --- | --- |
| endVertex() | वर्टेक्स जोड़ना समाप्त करें |

 **Result:**
वर्टेक्स


---


### verticesToArray{#verticesToArray}

| नाम | विवरण |
| --- | --- |
| verticesToArray() | वर्टेक्स डेटा को बाइट एरे में परिवर्तित करें |

 **Result:**
byte[]


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() |  |

 **Result:**
स्ट्रिंग


---


### fromRawData{#fromRawData}

| नाम | विवरण |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | कच्चे डेटा से TriMesh बनाएं। लौटाया गया TriMesh प्रदर्शन के लिए इनपुट बाइट एरे की कॉपी नहीं करेगा, एरे में बाहरी परिवर्तन इस इंस्टेंस में प्रतिबिंबित होंगे। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| vd | VertexDeclaration | वर्टेक्स घोषणा, कम से कम एक फ़ील्ड होना आवश्यक है। |
| vertices | byte[] | इनपुट वर्टेक्स डेटा, वर्टेक्स की न्यूनतम लंबाई वर्टेक्स घोषणा के आकार के बराबर या उससे अधिक होनी चाहिए |
| indices | Number[] | त्रिभुज इंडेक्स |
| generateVertexMapping | boolean | जेनरेट करें |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| नाम | विवरण |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | बाइट्स से वर्टेक्स लोड करें, बाइट्स की लंबाई वर्टेक्स आकार का पूर्णांक गुणज होनी चाहिए। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| नाम | विवरण |
| --- | --- |
| readVector4(idx, field) | vector4 फ़ील्ड पढ़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| idx | Number | पढ़ने के लिए वर्टेक्स का इंडेक्स |
| field | VertexField | Vector4/FVector4 डेटा प्रकार वाला फ़ील्ड |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| नाम | विवरण |
| --- | --- |
| readFVector4(idx, field) | vector4 फ़ील्ड पढ़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| idx | Number | पढ़ने के लिए वर्टेक्स का इंडेक्स |
| field | VertexField | Vector4/FVector4 डेटा प्रकार वाला फ़ील्ड |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| नाम | विवरण |
| --- | --- |
| readVector3(idx, field) | vector3 फ़ील्ड पढ़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| idx | Number | पढ़ने के लिए वर्टेक्स का इंडेक्स |
| field | VertexField | Vector3/FVector3 डेटा प्रकार वाला फ़ील्ड |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| नाम | विवरण |
| --- | --- |
| readFVector3(idx, field) | vector3 फ़ील्ड पढ़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| idx | Number | पढ़ने के लिए वर्टेक्स का इंडेक्स |
| field | VertexField | Vector3/FVector3 डेटा प्रकार वाला फ़ील्ड |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| नाम | विवरण |
| --- | --- |
| readVector2(idx, field) | vector2 फ़ील्ड पढ़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| idx | Number | पढ़ने के लिए वर्टेक्स का इंडेक्स |
| field | VertexField | Vector2/FVector2 डेटा प्रकार वाला फ़ील्ड |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| नाम | विवरण |
| --- | --- |
| readFVector2(idx, field) | vector2 फ़ील्ड पढ़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| idx | Number | पढ़ने के लिए वर्टेक्स का इंडेक्स |
| field | VertexField | Vector2/FVector2 डेटा प्रकार वाला फ़ील्ड |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| नाम | विवरण |
| --- | --- |
| readDouble(idx, field) | double फ़ील्ड पढ़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| idx | Number | पढ़ने के लिए वर्टेक्स का इंडेक्स |
| field | VertexField | float/double संगत डेटा प्रकार वाला फ़ील्ड |

 **Result:**
Number


---


### readFloat{#readFloat}

| नाम | विवरण |
| --- | --- |
| readFloat(idx, field) | float फ़ील्ड पढ़ें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| idx | Number | पढ़ने के लिए वर्टेक्स का इंडेक्स |
| field | VertexField | float/double संगत डेटा प्रकार वाला फ़ील्ड |

 **Result:**
Number


---


### getBoundingBox{#getBoundingBox}

| नाम | विवरण |
| --- | --- |
| getBoundingBox() | वर्तमान इकाई का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |

 **Result:**
Number


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


### iterator{#iterator}

| नाम | विवरण |
| --- | --- |
| iterator() | आंतरिक उपयोग के लिए आरक्षित। |

 **Result:**
Property


---



