---
title: "फ़ाइल फ़ॉर्मेट"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

फ़ाइल फ़ॉर्मेट परिभाषा  @hideconstructor


## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| MAYA_BINARY | ऑटोडेस्क माया बाइनरी फ़ॉर्मेट में |
| STL_BINARY | बाइनरी STL फ़ाइल फ़ॉर्मेट |
| STLASCII | ASCII STL फ़ाइल फ़ॉर्मेट |
| COLLADA | कोलाडा फ़ाइल फ़ॉर्मेट |
| GLTF | क्रोनोस ग्रुप का glTF |
| GLTF_BINARY | क्रोनोस ग्रुप का glTF बाइनरी फ़ॉर्मेट में |
| PDF | एडोब का पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट |
| DXF | ऑटोकैड DXF |
| PLY | पॉलीगॉन फ़ाइल फ़ॉर्मेट या स्टैनफ़ोर्ड ट्रायंगल फ़ॉर्मेट |
| X_BINARY | डायरेक्टएक्स X फ़ाइल बाइनरी फ़ॉर्मेट में |
| X_TEXT | डायरेक्टएक्स X फ़ाइल बाइनरी फ़ॉर्मेट में |
| DRACO | गूगल ड्रैको मेष |
| RVM_TEXT | AVEVA Plant Design Management System Model पाठ स्वरूप में |
| RVM_BINARY | AVEVA Plant Design Management System Model बाइनरी स्वरूप में |
| ASE | 3D Studio Max का ASCII सीन निर्यातकर्ता स्वरूप। |
| IFC | ISO 16739-1 Industry Foundation Classes डेटा मॉडल। |
| AMF | एडिटिव निर्माण फ़ाइल स्वरूप |
| VRML | यह वर्चुअल रियलिटी मॉडलिंग भाषा |
| ZIP | Zip अभिलेख जो अन्य 3d फ़ाइल स्वरूप को शामिल करता है। |
| USD | यूनिवर्सल सीन विवरण |
| USDZ | संपीड़ित यूनिवर्सल सीन विवरण |
| XYZ | Xyz बिंदु बादल फ़ाइल |
| PCD | PCL पॉइंट क्लाउड डेटा फ़ाइल ASCII मोड में |
| PCD_BINARY | PCL पॉइंट क्लाउड डेटा फ़ाइल बाइनरी मोड में |

## विधियाँ

### getVersion{#getVersion}

| नाम | विवरण |
| --- | --- |
| getVersion() | फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है |

 **Result:**



---


### getExtension{#getExtension}

| नाम | विवरण |
| --- | --- |
| getExtension() | इस प्रकार का एक्सटेंशन नाम प्राप्त करता है। |

 **Result:**



---


### getExtensions{#getExtensions}

| नाम | विवरण |
| --- | --- |
| getExtensions() | इस प्रकार के एक्सटेंशन नाम प्राप्त करता है। |

 **Result:**



---


### getContentType{#getContentType}

| नाम | विवरण |
| --- | --- |
| getContentType() | फ़ाइल फ़ॉर्मेट कंटेंट टाइप प्राप्त करता है। इस प्रॉपर्टी का मान FileContentType पूर्णांक स्थिरांक है। |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| नाम | विवरण |
| --- | --- |
| getFileFormatType() | फ़ाइल फ़ॉर्मेट प्रकार प्राप्त करता है |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| नाम | विवरण |
| --- | --- |
| getFormatByExtension(extensionName) | फ़ाइल एक्सटेंशन नाम से वांछित फ़ाइल फ़ॉर्मेट प्राप्त करता है। एक्सटेंशन नाम को एक डॉट ('.') से शुरू होना चाहिए। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| extensionNam | स्ट्रिंग | null |

 **Result:**
फ़ाइल फ़ॉर्मेट


---


### detect{#detect}

| नाम | विवरण |
| --- | --- |
| detect(fileName) | फ़ाइल नाम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल पढ़ने योग्य होनी चाहिए ताकि Aspose.3D फ़ाइल हेडर के माध्यम से फ़ॉर्मेट का पता लगा सके। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileNam | स्ट्रिंग | null |

 **Result:**
फ़ाइल फ़ॉर्मेट


---


### createLoadOptions{#createLoadOptions}

| नाम | विवरण |
| --- | --- |
| createLoadOptions() | इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट लोड विकल्प बनाएं |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| नाम | विवरण |
| --- | --- |
| createSaveOptions() | इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट सहेजने के विकल्प बनाएं |

 **Result:**
SaveOptions


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | फ़ॉर्मेट्स को स्ट्रिंग में बदलें |

 **Result:**
स्ट्रिंग


---



