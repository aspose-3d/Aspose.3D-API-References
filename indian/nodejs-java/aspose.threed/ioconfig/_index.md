---
title: "IOConfig"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/ioconfig/
---
## IOConfig class

सीरियलाइज़ेशन/डिसीरियलाइज़ेशन के लिए IO कॉन्फ़िग। उपयोगकर्ता यहाँ निर्भरताओं के लुक‑अप पाथ जैसी विस्तृत कॉन्फ़िगरेशन या फ़ॉर्मेट-संबंधित कॉन्फ़िग निर्दिष्ट कर सकता है  @hideconstructor


## विधियाँ

### getFileSystemFactory{#getFileSystemFactory}

| नाम | विवरण |
| --- | --- |
| getFileSystemFactory() | FileSystem के लिए फ़ैक्टरी क्लास को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट फ़ैक्टरी LocalFileSystem बनाएगी जो सर्वर पर्यावरण के लिए उपयुक्त नहीं है। |

 **Result:**



---


### setFileSystemFactory{#setFileSystemFactory}

| नाम | विवरण |
| --- | --- |
| setFileSystemFactory(value) | FileSystem के लिए फ़ैक्टरी क्लास को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट फ़ैक्टरी LocalFileSystem बनाएगी जो सर्वर पर्यावरण के लिए उपयुक्त नहीं है। |

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



