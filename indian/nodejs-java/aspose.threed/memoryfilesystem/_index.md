---
title: "MemoryFileSystem"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

MemoryFileSystem पढ़ने/लिखने के संचालन को मेमोरी में मैप करेगा।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| नाम | विवरण |
| --- | --- |
| getFileNames() | फ़ाइल नाम जो इस मेमोरी फ़ाइल सिस्टम में हैं। |

 **Result:**



---


### getFileContent{#getFileContent}

| नाम | विवरण |
| --- | --- |
| getFileContent(fileName) | निर्दिष्ट फ़ाइल की कच्ची सामग्री लौटाता है। यदि निर्दिष्ट फ़ाइल मौजूद नहीं है तो System.IO.FileNotFoundException फेंके। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileNam | स्ट्रिंग | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| नाम | विवरण |
| --- | --- |
| readFile(fileName, options) | निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileNam | स्ट्रिंग | null |
| विकल्प | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| नाम | विवरण |
| --- | --- |
| writeFile(fileName, options) | निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileNam | स्ट्रिंग | null |
| विकल्प | IOConfig | null |

 **Result:**
Stream


---



