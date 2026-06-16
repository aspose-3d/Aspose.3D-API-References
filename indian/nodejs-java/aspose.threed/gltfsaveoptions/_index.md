---
title: "GltfSaveOptions"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

glTF फ़ॉर्मेट के लिए सेव विकल्प।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(contentType) | GltfSaveOptions का कंस्ट्रक्टर |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(format) | GltfSaveOptions का कंस्ट्रक्टर |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| forma | फ़ाइल फ़ॉर्मेट | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| नाम | विवरण |
| --- | --- |
| getPrettyPrint() | GLTF फ़ाइल की JSON सामग्री को मानव पढ़ने के लिए इंडेंट किया गया है, डिफ़ॉल्ट मान false है। |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| नाम | विवरण |
| --- | --- |
| setPrettyPrint(value) | GLTF फ़ाइल की JSON सामग्री को मानव पढ़ने के लिए इंडेंट किया गया है, डिफ़ॉल्ट मान false है। |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| नाम | विवरण |
| --- | --- |
| getFallbackNormal() | जब GLTF2 एक्सपोर्टर ने एक अमान्य नॉर्मल पाया, तो वैधता को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। डिफ़ॉल्ट मान (0, 1, 0) है। |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| नाम | विवरण |
| --- | --- |
| getEmbedAssets() | सभी बाहरी एसेट्स को base64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है। |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| नाम | विवरण |
| --- | --- |
| setEmbedAssets(value) | सभी बाहरी एसेट्स को base64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है। |

 **Result:**



---


### getImageFormat{#getImageFormat}

| नाम | विवरण |
| --- | --- |
| getImageFormat() | मानक glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प यह मार्गदर्शन करेगा कि Aspose.3D गैर-मानक छवियों को निर्यात के दौरान समर्थित फ़ॉर्मेट में कैसे परिवर्तित करे। डिफ़ॉल्ट मान है GltfEmbeddedImageFormat.PNG। प्रॉपर्टी का मान GltfEmbeddedImageFormat पूर्णांक स्थिरांक है। |

 **Result:**



---


### setImageFormat{#setImageFormat}

| नाम | विवरण |
| --- | --- |
| setImageFormat(value) | मानक glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प यह मार्गदर्शन करेगा कि Aspose.3D गैर-मानक छवियों को निर्यात के दौरान समर्थित फ़ॉर्मेट में कैसे परिवर्तित करे। डिफ़ॉल्ट मान है GltfEmbeddedImageFormat.PNG। प्रॉपर्टी का मान GltfEmbeddedImageFormat पूर्णांक स्थिरांक है। |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| नाम | विवरण |
| --- | --- |
| getMaterialConverter() | ज्यामिति की सामग्री को PBR सामग्री में परिवर्तित करने के लिए कस्टम कन्वर्टर। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 एक्सपोर्टर स्वचालित रूप से मानक सामग्री को PBR सामग्री में परिवर्तित करेगा। डिफ़ॉल्ट मान null है। इस प्रॉपर्टी का उपयोग glTF 2.0 फ़ाइल में सीन निर्यात करते समय किया जाता है। |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| नाम | विवरण |
| --- | --- |
| setMaterialConverter(value) | ज्यामिति की सामग्री को PBR सामग्री में परिवर्तित करने के लिए कस्टम कन्वर्टर। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 एक्सपोर्टर स्वचालित रूप से मानक सामग्री को PBR सामग्री में परिवर्तित करेगा। डिफ़ॉल्ट मान null है। इस प्रॉपर्टी का उपयोग glTF 2.0 फ़ाइल में सीन निर्यात करते समय किया जाता है। |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| नाम | विवरण |
| --- | --- |
| getUseCommonMaterials() | KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D को एक सेट वर्टेक्स/फ़्रैगमेंट शेडर निर्यात करने के लिए मजबूर किया जाएगा यदि #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| नाम | विवरण |
| --- | --- |
| setUseCommonMaterials(value) | KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D को एक सेट वर्टेक्स/फ़्रैगमेंट शेडर निर्यात करने के लिए मजबूर किया जाएगा यदि #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| नाम | विवरण |
| --- | --- |
| getExternalDracoEncoder() | ड्राको संपीड़न गति को तेज करने के लिए बाहरी ड्राको एन्कोडर का उपयोग करें। Aspose.3D एक नया उप-प्रक्रिया बनाएगा ताकि मेष को ड्राको फ़ॉर्मेट में एन्कोड किया जा सके, इसे अपने जोखिम पर उपयोग करें। |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| नाम | विवरण |
| --- | --- |
| setExternalDracoEncoder(value) | ड्राको संपीड़न गति को तेज करने के लिए बाहरी ड्राको एन्कोडर का उपयोग करें। Aspose.3D एक नया उप-प्रक्रिया बनाएगा ताकि मेष को ड्राको फ़ॉर्मेट में एन्कोड किया जा सके, इसे अपने जोखिम पर उपयोग करें। |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| नाम | विवरण |
| --- | --- |
| getFlipTexCoordV() | टेक्सचर कोऑर्डिनेट v(t) घटक को उलटें, डिफ़ॉल्ट मान true है। |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| नाम | विवरण |
| --- | --- |
| setFlipTexCoordV(value) | टेक्सचर कोऑर्डिनेट v(t) घटक को उलटें, डिफ़ॉल्ट मान true है। |

 **Result:**



---


### getBufferFile{#getBufferFile}

| नाम | विवरण |
| --- | --- |
| getBufferFile() | बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह तब अनदेखा किया जाता है जब बाइनरी मोड में glTF निर्यात किया जाता है। |

 **Result:**



---


### setBufferFile{#setBufferFile}

| नाम | विवरण |
| --- | --- |
| setBufferFile(value) | बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह तब अनदेखा किया जाता है जब बाइनरी मोड में glTF निर्यात किया जाता है। |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| नाम | विवरण |
| --- | --- |
| getSaveExtras() | दृश्य वस्तु की गतिशील प्रॉपर्टीज़ को उत्पन्न glTF फ़ाइल में 'extra' फ़ील्ड्स में सहेजें। यह एप्लिकेशन-विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान false है। |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| नाम | विवरण |
| --- | --- |
| setSaveExtras(value) | दृश्य वस्तु की गतिशील प्रॉपर्टीज़ को उत्पन्न glTF फ़ाइल में 'extra' फ़ील्ड्स में सहेजें। यह एप्लिकेशन-विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान false है। |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| नाम | विवरण |
| --- | --- |
| getApplyUnitScale() | मेश पर AssetInfo.UnitScaleFactor लागू करें। डिफ़ॉल्ट मान false है। |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| नाम | विवरण |
| --- | --- |
| setApplyUnitScale(value) | मेश पर AssetInfo.UnitScaleFactor लागू करें। डिफ़ॉल्ट मान false है। |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| नाम | विवरण |
| --- | --- |
| getDracoCompression() | ड्राको संपीड़न को सक्षम करने के लिए प्राप्त करता है या सेट करता है |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| नाम | विवरण |
| --- | --- |
| setDracoCompression(value) | ड्राको संपीड़न को सक्षम करने के लिए प्राप्त करता है या सेट करता है |

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



