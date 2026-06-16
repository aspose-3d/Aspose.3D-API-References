---
title: "PolygonModifier"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

पॉलीगॉन को संशोधित करने के यूटिलिटीज़  @hideconstructor


## विधियाँ

### triangulate{#triangulate}

| नाम | विवरण |
| --- | --- |
| triangulate(scene) | सभी बहुभुज-आधारित मेष को पूर्ण त्रिकोणीय मेष में परिवर्तित करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| scene | Scene | प्रसंस्करण के लिए दृश्य |

 **Result:**



---


### triangulate{#triangulate}

| नाम | विवरण |
| --- | --- |
| triangulate(mesh) | एक बहुभुज-आधारित मेष को पूर्ण त्रिकोणीय मेष में परिवर्तित करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| mesh | Mesh | मूल गैर-त्रिकोणीय मेष |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| नाम | विवरण |
| --- | --- |
| mergeMesh(scene) | पूरे दृश्य को एकल परिवर्तित मेष में परिवर्तित करें। सामान्य/टेक्सचर निर्देशांक जैसे वर्टेक्स तत्व अभी समर्थित नहीं हैं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| scene | Scene | विलय के लिए दृश्य |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| नाम | विवरण |
| --- | --- |
| mergeMesh(node) | पूरे नोड को एकल परिवर्तित मेष में परिवर्तित करें। सामान्य/टेक्सचर निर्देशांक जैसे वर्टेक्स तत्व अभी समर्थित नहीं हैं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| नोड | नोड | विलय के लिए नोड |

 **Result:**
Mesh


---


### scale{#scale}

| नाम | विवरण |
| --- | --- |
| scale(scene, scale) | इस दृश्य में सभी ज्यामितियों को स्केल करें (नियंत्रण बिंदुओं को स्केल करें, परिवर्तन मैट्रिक्स को नहीं)। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| scene | Scene | स्केल करने के लिए दृश्य |
| स्केल | Vector3 | स्केल कारक |

 **Result:**
Mesh


---


### scale{#scale}

| नाम | विवरण |
| --- | --- |
| scale(node, scale) | इस नोड में सभी ज्यामितियों को स्केल करें (नियंत्रण बिंदुओं को स्केल करें, परिवर्तन मैट्रिक्स को नहीं)। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| नोड | नोड | स्केल करने के लिए नोड |
| स्केल | Vector3 | स्केल कारक |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| नाम | विवरण |
| --- | --- |
| generateNormal(mesh) | Mesh परिभाषा से सामान्य डेटा उत्पन्न करें |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| नाम | विवरण |
| --- | --- |
| generateUV(mesh, normals) | दिए गए इनपुट Mesh और निर्दिष्ट सामान्य डेटा से UV डेटा उत्पन्न करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| mesh | Mesh | इनपुट Mesh |
| सामान्य वेक्टर | VertexElementNormal | सामान्य डेटा |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| नाम | विवरण |
| --- | --- |
| generateUV(mesh) | दिए गए इनपुट Mesh से UV डेटा उत्पन्न करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| mesh | Mesh | इनपुट Mesh |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| नाम | विवरण |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | VertexElementMaterial द्वारा Mesh को उप‑Mesh में विभाजित करें। प्रत्येक उप‑Mesh केवल एक सामग्री का उपयोग करेगा। एक नोड पर Mesh विभाजन करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| नोड | नोड | null |
| नीति | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | प्रत्येक उप‑Mesh के लिए चाइल्ड नोड बनाएं। |
| removeOldMesh | boolean | विभाजन के बाद पुराना Mesh हटाएं, यदि यह पैरामीटर false है, तो पुराना और नया Mesh दोनों मौजूद रहेंगे। |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| नाम | विवरण |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | VertexElementMaterial द्वारा Mesh को उप‑Mesh में विभाजित करें। प्रत्येक उप‑Mesh केवल एक सामग्री का उपयोग करेगा। दृश्य के सभी नोड्स पर Mesh विभाजन करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| scen | Scene | null |
| नीति | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| नाम | विवरण |
| --- | --- |
| splitMesh(mesh, policy) | VertexElementMaterial द्वारा Mesh को उप‑Mesh में विभाजित करें। प्रत्येक उप‑Mesh केवल एक सामग्री का उपयोग करेगा। मूल Mesh में कोई परिवर्तन नहीं होगा। |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| नाम | विवरण |
| --- | --- |
| buildTangentBinormal(scene) | यह दृश्य के सभी Mesh पर टैंजेंट और बाइनॉर्मल बनाएगा। Normal आवश्यक है, यदि Mesh पर Normal मौजूद नहीं है, तो यह स्थिति से Normal डेटा भी बनाएगा। UV भी आवश्यक है, यदि कोई UV परिभाषित नहीं है तो Mesh को अनदेखा किया जाएगा। |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| नाम | विवरण |
| --- | --- |
| buildTangentBinormal(mesh) | यह मेष पर टैन्जेंट और बिनॉर्मल बनाएगा Normal आवश्यक है, यदि मेष पर normal मौजूद नहीं है, तो यह position से normal डेटा भी बनाएगा। UV भी आवश्यक है, यदि कोई UV नहीं मिला तो एक अपवाद उठाया जाएगा। |

 **Result:**
Mesh[]


---



