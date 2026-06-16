---
title: "PlyFormat"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

PLY फ़ॉर्मेट।  @hideconstructor


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


### encode{#encode}

| नाम | विवरण |
| --- | --- |
| encode(entity, fileName) | इकाई को एन्कोड करें और परिणाम को एक बाहरी फ़ाइल में सहेजें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड करने के लिए इकाई |
| fileName | स्ट्रिंग | जिस फ़ाइल में लिखना है |

 **Result:**



---


### encode{#encode}

| नाम | विवरण |
| --- | --- |
| encode(entity, fileName, opt) | इकाई को एन्कोड करें और परिणाम को एक बाहरी फ़ाइल में सहेजें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड करने के लिए इकाई |
| fileName | स्ट्रिंग | जिस फ़ाइल में लिखना है |
| opt | PlySaveOptions | सेव विकल्प |

 **Result:**



---


### decode{#decode}

| नाम | विवरण |
| --- | --- |
| decode(fileName) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | इनपुट स्ट्रीम |

 **Result:**
जियोमेट्री


---


### decode{#decode}

| नाम | विवरण |
| --- | --- |
| decode(fileName, opt) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | इनपुट स्ट्रीम |
| opt | PlyLoadOptions | PLY फ़ॉर्मेट का लोड विकल्प |

 **Result:**
जियोमेट्री


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



