---
title: "DracoFormat"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google Draco फ़ॉर्मेट  @hideconstructor


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


### decode{#decode}

| नाम | विवरण |
| --- | --- |
| decode(fileName) | निर्दिष्ट फ़ाइल नाम से पॉइंट क्लाउड या मेष को डिकोड करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | फ़ाइल नाम में drc फ़ाइल शामिल है |

 **Result:**
जियोमेट्री


---


### decode{#decode}

| नाम | विवरण |
| --- | --- |
| decode(data) | मेमोरी डेटा से पॉइंट क्लाउड या मेष को डिकोड करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | कच्चे drc बाइट्स |

 **Result:**
जियोमेट्री


---


### encode{#encode}

| नाम | विवरण |
| --- | --- |
| encode(entity, fileName, options) | इकाई को निर्दिष्ट फ़ाइल में एन्कोड करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड की जाने वाली इकाई |
| fileName | स्ट्रिंग | लिखी जाने वाली फ़ाइल का नाम |
| विकल्प | DracoSaveOptions | पॉइंट क्लाउड को एन्कोड करने के अतिरिक्त विकल्प |

 **Result:**
जियोमेट्री


---


### encode{#encode}

| नाम | विवरण |
| --- | --- |
| encode(entity, options) | इकाई को Draco कच्चे डेटा में एन्कोड करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड की जाने वाली इकाई |
| विकल्प | DracoSaveOptions | पॉइंट क्लाउड को एन्कोड करने के अतिरिक्त विकल्प |

 **Result:**
byte[]


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



