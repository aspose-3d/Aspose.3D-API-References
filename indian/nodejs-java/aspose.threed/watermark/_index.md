---
title: "Watermark"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/watermark/
---
## Watermark class

ब्लाइंड वॉटरमार्क को मेष में एन्कोड/डिकोड करने के लिए उपयोगिता।  @hideconstructor


## विधियाँ

### encodeWatermark{#encodeWatermark}

| नाम | विवरण |
| --- | --- |
| encodeWatermark(input, text) | एक पाठ को मेष के ब्लाइंड वॉटरमार्क में एन्कोड करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| input | Mesh | ब्लाइंड वॉटरमार्क एन्कोड करने के लिए मेष |
| text | स्ट्रिंग | मेष में एन्कोड करने के लिए पाठ |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| नाम | विवरण |
| --- | --- |
| encodeWatermark(input, text, password) | एक पाठ को मेष के ब्लाइंड वॉटरमार्क में एन्कोड करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| input | Mesh | ब्लाइंड वॉटरमार्क एन्कोड करने के लिए मेष |
| text | स्ट्रिंग | मेष में एन्कोड करने के लिए पाठ |
| password | स्ट्रिंग | वॉटरमार्क की सुरक्षा के लिए पासवर्ड, यह वैकल्पिक है। |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| नाम | विवरण |
| --- | --- |
| decodeWatermark(input) | मेष से वॉटरमार्क को डिकोड करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| input | Mesh | वॉटरमार्क निकालने के लिए मेष |

 **Result:**
स्ट्रिंग


---


### decodeWatermark{#decodeWatermark}

| नाम | विवरण |
| --- | --- |
| decodeWatermark(input, password) | मेष से वॉटरमार्क को डिकोड करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| input | Mesh | वॉटरमार्क निकालने के लिए मेष |
| password | स्ट्रिंग | वॉटरमार्क को डिक्रिप्ट करने के लिए पासवर्ड |

 **Result:**
स्ट्रिंग


---



