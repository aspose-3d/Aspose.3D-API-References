---
title: "FbxSaveOptions"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Fbx फ़ाइल के लिए सहेजने के विकल्प।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(format) | FbxSaveOptions को प्रारंभ करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| forma | फ़ाइल फ़ॉर्मेट | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(contentType) | नवीनतम समर्थित संस्करण का उपयोग करके FbxSaveOptions को प्रारंभ करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| नाम | विवरण |
| --- | --- |
| getReusePrimitiveMesh() | एक ही पैरामीटर वाले प्रिमिटिव्स के लिए मेष को पुन: उपयोग करें, इससे उन दृश्यों के FBX आउटपुट का आकार काफी कम हो जाएगा जो बड़ी संख्या में प्रिमिटिव आकारों (जैसे CAD फ़ाइलों से आयातित) से निर्मित हैं। डिफ़ॉल्ट मान false है। |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| नाम | विवरण |
| --- | --- |
| setReusePrimitiveMesh(value) | एक ही पैरामीटर वाले प्रिमिटिव्स के लिए मेष को पुन: उपयोग करें, इससे उन दृश्यों के FBX आउटपुट का आकार काफी कम हो जाएगा जो बड़ी संख्या में प्रिमिटिव आकारों (जैसे CAD फ़ाइलों से आयातित) से निर्मित हैं। डिफ़ॉल्ट मान false है। |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| नाम | विवरण |
| --- | --- |
| getEnableCompression() | FBX फ़ाइल में बड़े बाइनरी डेटा (जैसे एनीमेशन डेटा, कंट्रोल पॉइंट्स, वर्टेक्स एलिमेंट डेटा, इंडेक्स) का संपीड़न, डिफ़ॉल्ट मान true है। |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| नाम | विवरण |
| --- | --- |
| setEnableCompression(value) | FBX फ़ाइल में बड़े बाइनरी डेटा (जैसे एनीमेशन डेटा, कंट्रोल पॉइंट्स, वर्टेक्स एलिमेंट डेटा, इंडेक्स) का संपीड़न, डिफ़ॉल्ट मान true है। |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| नाम | विवरण |
| --- | --- |
| getFoldRepeatedCurveData() | पिछले डेटा की रेफ़रेंस काउंट बढ़ाकर दोहराए गए कर्व डेटा को पुन: उपयोग करना है या नहीं, यदि दोहराए गए कर्व डेटा को मोड़ा जाता है तो true; अन्यथा false। |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| नाम | विवरण |
| --- | --- |
| getExportLegacyMaterialProperties() | लेगेसी मटेरियल प्रॉपर्टीज़ को निर्यात करना है या नहीं, जो बैक कॉम्पैटिबिलिटी के लिए उपयोग होते हैं। यह विकल्प डिफ़ॉल्ट रूप से चालू है। |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| नाम | विवरण |
| --- | --- |
| setExportLegacyMaterialProperties(value) | लेगेसी मटेरियल प्रॉपर्टीज़ को निर्यात करना है या नहीं, जो बैक कॉम्पैटिबिलिटी के लिए उपयोग होते हैं। यह विकल्प डिफ़ॉल्ट रूप से चालू है। |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| नाम | विवरण |
| --- | --- |
| getVideoForTexture() | FBX के रूप में निर्यात करते समय टेक्सचर के लिए वीडियो इंस्टेंस उत्पन्न करना है या नहीं। |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| नाम | विवरण |
| --- | --- |
| setVideoForTexture(value) | FBX के रूप में निर्यात करते समय टेक्सचर के लिए वीडियो इंस्टेंस उत्पन्न करना है या नहीं। |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| नाम | विवरण |
| --- | --- |
| getEmbedTextures() | टेक्सचर को अंतिम आउटपुट फ़ाइल में एम्बेड करना है या नहीं। FBX एक्सपोर्टर फ़ाइल सिस्टम से टेक्सचर का कच्चा डेटा खोजने की कोशिश करेगा, और फ़ाइल को अंतिम FBX फ़ाइल में एम्बेड करेगा। डिफ़ॉल्ट मान false है। |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| नाम | विवरण |
| --- | --- |
| setEmbedTextures(value) | टेक्सचर को अंतिम आउटपुट फ़ाइल में एम्बेड करना है या नहीं। FBX एक्सपोर्टर फ़ाइल सिस्टम से टेक्सचर का कच्चा डेटा खोजने की कोशिश करेगा, और फ़ाइल को अंतिम FBX फ़ाइल में एम्बेड करेगा। डिफ़ॉल्ट मान false है। |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| नाम | विवरण |
| --- | --- |
| getGenerateVertexElementMaterial() | यदि संलग्न नोड में मटेरियल्स हैं तो ज्योमेट्रीज़ के लिए हमेशा VertexElementMaterial उत्पन्न करना है या नहीं। यह डिफ़ॉल्ट रूप से बंद है। |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| नाम | विवरण |
| --- | --- |
| setGenerateVertexElementMaterial(value) | यदि संलग्न नोड में मटेरियल्स हैं तो ज्योमेट्रीज़ के लिए हमेशा VertexElementMaterial उत्पन्न करना है या नहीं। यह डिफ़ॉल्ट रूप से बंद है। |

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



