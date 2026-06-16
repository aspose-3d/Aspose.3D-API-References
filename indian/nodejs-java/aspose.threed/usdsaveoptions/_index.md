---
title: "UsdSaveOptions"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

USD/USDZ फ़ॉर्मेट्स के लिए सहेजने के विकल्प।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | FileFormat.USD फ़ॉर्मेट के साथ एक नया UsdSaveOptions इनिशियलाइज़ करें। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(fileFormat) | निर्दिष्ट USD/USDZ फ़ॉर्मेट के साथ एक नया UsdSaveOptions इनिशियलाइज़ करें। |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| नाम | विवरण |
| --- | --- |
| getPrimitiveToMesh() | निर्यात के दौरान प्रिमिटिव एंटिटीज़ को मेष में परिवर्तित करें। या प्रिमिटिव्स को सीधे आउटपुट फ़ाइल में एन्कोड करें (अधिकारिक नहीं प्रिमिटिव्स जैसे Dish, Torus के लिए Aspose की एक्सटेंशन परिभाषा का उपयोग किया जाएगा) डिफ़ॉल्ट मान true है। |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| नाम | विवरण |
| --- | --- |
| setPrimitiveToMesh(value) | निर्यात के दौरान प्रिमिटिव एंटिटीज़ को मेष में परिवर्तित करें। या प्रिमिटिव्स को सीधे आउटपुट फ़ाइल में एन्कोड करें (अधिकारिक नहीं प्रिमिटिव्स जैसे Dish, Torus के लिए Aspose की एक्सटेंशन परिभाषा का उपयोग किया जाएगा) डिफ़ॉल्ट मान true है। |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| नाम | विवरण |
| --- | --- |
| getExportMetaData() | USD के customData फ़ील्ड के माध्यम से नोड की प्रॉपर्टीज़ निर्यात करें। |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| नाम | विवरण |
| --- | --- |
| setExportMetaData(value) | USD के customData फ़ील्ड के माध्यम से नोड की प्रॉपर्टीज़ निर्यात करें। |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| नाम | विवरण |
| --- | --- |
| getMaterialConverter() | जियोमेट्री की सामग्री को PBR सामग्री में बदलने के लिए कस्टम कन्वर्टर। यदि यह असाइन नहीं किया गया है, तो USD निर्यातकर्ता स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। डिफ़ॉल्ट मान null है। |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| नाम | विवरण |
| --- | --- |
| setMaterialConverter(value) | जियोमेट्री की सामग्री को PBR सामग्री में बदलने के लिए कस्टम कन्वर्टर। यदि यह असाइन नहीं किया गया है, तो USD निर्यातकर्ता स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। डिफ़ॉल्ट मान null है। |

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



