---
title: "PlySaveOptions"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

सीन को PLY फ़ाइल के रूप में निर्यात करने के लिए सहेजने के विकल्प।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | PlySaveOptions का कंस्ट्रक्टर |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(contentType) | PlySaveOptions का कंस्ट्रक्टर |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| नाम | विवरण |
| --- | --- |
| getPointCloud() | सीन को पॉइंट क्लाउड के रूप में निर्यात करें, डिफ़ॉल्ट मान false है। |

 **Result:**



---


### setPointCloud{#setPointCloud}

| नाम | विवरण |
| --- | --- |
| setPointCloud(value) | सीन को पॉइंट क्लाउड के रूप में निर्यात करें, डिफ़ॉल्ट मान false है। |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| नाम | विवरण |
| --- | --- |
| getFlipCoordinate() | सीन को सहेजते समय निर्देशांक को उलटें, डिफ़ॉल्ट मान true है। |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| नाम | विवरण |
| --- | --- |
| setFlipCoordinate(value) | सीन को सहेजते समय निर्देशांक को उलटें, डिफ़ॉल्ट मान true है। |

 **Result:**



---


### getVertexElement{#getVertexElement}

| नाम | विवरण |
| --- | --- |
| getVertexElement() | वर्टेक्स डेटा के लिए एलिमेंट का नाम, डिफ़ॉल्ट मान "vertex" है। |

 **Result:**



---


### setVertexElement{#setVertexElement}

| नाम | विवरण |
| --- | --- |
| setVertexElement(value) | वर्टेक्स डेटा के लिए एलिमेंट का नाम, डिफ़ॉल्ट मान "vertex" है। |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| नाम | विवरण |
| --- | --- |
| getPositionComponents() | पोजीशन डेटा के घटक नाम, डिफ़ॉल्ट मान ("x", "y", "z") है। |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| नाम | विवरण |
| --- | --- |
| getNormalComponents() | नॉर्मल डेटा के घटक नाम, डिफ़ॉल्ट मान ("nx", "ny", "nz") है। |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| नाम | विवरण |
| --- | --- |
| getTextureCoordinateComponents() | टेक्सचर कोऑर्डिनेट डेटा के लिए घटक नाम, डिफ़ॉल्ट मान ("u", "v") है |

 **Result:**



---


### getColorComponents{#getColorComponents}

| नाम | विवरण |
| --- | --- |
| getColorComponents() | वर्टेक्स रंग के लिए घटक नाम, डिफ़ॉल्ट मान ("red", "green", "blue") है |

 **Result:**



---


### getFaceElement{#getFaceElement}

| नाम | विवरण |
| --- | --- |
| getFaceElement() | फेस डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "face" है |

 **Result:**



---


### setFaceElement{#setFaceElement}

| नाम | विवरण |
| --- | --- |
| setFaceElement(value) | फेस डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "face" है |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| नाम | विवरण |
| --- | --- |
| getFaceProperty() | फेस डेटा के लिए प्रॉपर्टी नाम, डिफ़ॉल्ट मान "vertex_index" है |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| नाम | विवरण |
| --- | --- |
| setFaceProperty(value) | फेस डेटा के लिए प्रॉपर्टी नाम, डिफ़ॉल्ट मान "vertex_index" है |

 **Result:**



---


### getExportTextures{#getExportTextures}

| नाम | विवरण |
| --- | --- |
| getExportTextures() | सीन में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |

 **Result:**



---


### setExportTextures{#setExportTextures}

| नाम | विवरण |
| --- | --- |
| setExportTextures(value) | सीन में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |

 **Result:**



---


### getFileFormat{#getFileFormat}

| नाम | विवरण |
| --- | --- |
| getFileFormat() | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट को प्राप्त करता है। |

 **Result:**



---


### getEncoding{#getEncoding}

| नाम | विवरण |
| --- | --- |
| getEncoding() | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर यह तय करेगा कि कौन सी एन्कोडिंग उपयोग की जाएगी। |

 **Result:**



---


### getFileSystem{#getFileSystem}

| नाम | विवरण |
| --- | --- |
| getFileSystem() | लोड/सेव के दौरान बाहरी निर्भरताओं को कैसे प्रबंधित किया जाए, इसे उपयोगकर्ता को संभालने की अनुमति देता है। |

 **Result:**



---


### setFileSystem{#setFileSystem}

| नाम | विवरण |
| --- | --- |
| setFileSystem(value) | लोड/सेव के दौरान बाहरी निर्भरताओं को कैसे प्रबंधित किया जाए, इसे उपयोगकर्ता को संभालने की अनुमति देता है। |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| नाम | विवरण |
| --- | --- |
| getLookupPaths() | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देते हैं। |

 **Result:**



---


### getFileName{#getFileName}

| नाम | विवरण |
| --- | --- |
| getFileName() | एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसी बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है। |

 **Result:**



---


### setFileName{#setFileName}

| नाम | विवरण |
| --- | --- |
| setFileName(value) | एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसी बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है। |

 **Result:**



---



