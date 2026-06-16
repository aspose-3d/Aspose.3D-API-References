---
title: "TextureData"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

यह क्लास टेक्सचर का कच्चा डेटा और फ़ॉर्मेट परिभाषा रखती है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | TextureData का कंस्ट्रक्टर |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| widt | Number | null |
| heigh | Number | null |
| strid | Number | null |
| bytesPerPixe | Number | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | एक नया TextureData बनाता है और पिक्सेल डेटा आवंटित करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| widt | Number | null |
| heigh | Number | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| नाम | विवरण |
| --- | --- |
| constructor_overload2() | TextureData का कंस्ट्रक्टर |

 **Result:**



---


### getData{#getData}

| नाम | विवरण |
| --- | --- |
| getData() | पिक्सेल डेटा के कच्चे बाइट्स |

 **Result:**



---


### getWidth{#getWidth}

| नाम | विवरण |
| --- | --- |
| getWidth() | क्षैतिज पिक्सेल की संख्या |

 **Result:**



---


### getHeight{#getHeight}

| नाम | विवरण |
| --- | --- |
| getHeight() | ऊर्ध्वाधर पिक्सेल की संख्या |

 **Result:**



---


### getStride{#getStride}

| नाम | विवरण |
| --- | --- |
| getStride() | एक स्कैनलाइन के बाइट्स की संख्या। |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| नाम | विवरण |
| --- | --- |
| getBytesPerPixel() | एक पिक्सेल के बाइट्स की संख्या |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| नाम | विवरण |
| --- | --- |
| getPixelFormat() | पिक्सेल का फ़ॉर्मेट। इस प्रॉपर्टी का मान PixelFormat पूर्णांक स्थिरांक है। |

 **Result:**



---


### fromFile{#fromFile}

| नाम | विवरण |
| --- | --- |
| fromFile(fileName) | फ़ाइल से एक टेक्सचर लोड करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileNam | स्ट्रिंग | null |

 **Result:**
TextureData


---


### save{#save}

| नाम | विवरण |
| --- | --- |
| save(fileName) | टेक्सचर डेटा को इमेज फ़ाइल में सहेजें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | इमेज जहाँ सहेजी जाएगी, उसका फ़ाइल नाम। |

 **Result:**
TextureData


---


### save{#save}

| नाम | विवरण |
| --- | --- |
| save(fileName, format) | टेक्सचर डेटा को इमेज फ़ाइल में सहेजें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | इमेज जहाँ सहेजी जाएगी, उसका फ़ाइल नाम। |
| format | स्ट्रिंग | आउटपुट फ़ाइल का इमेज फ़ॉर्मेट। |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| नाम | विवरण |
| --- | --- |
| mapPixels(mapMode) | सभी पिक्सेल को पढ़ने/लिखने के लिए मैप करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| नाम | विवरण |
| --- | --- |
| mapPixels(mapMode, format) | दिए गए पिक्सेल फ़ॉर्मेट में पढ़ने/लिखने के लिए सभी पिक्सेल को मैप करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| नाम | विवरण |
| --- | --- |
| mapPixels(rect, mapMode, format) | दिए गए पिक्सेल फ़ॉर्मेट में पढ़ने/लिखने के लिए rect द्वारा निर्दिष्ट पिक्सेल को मैप करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| rect | Rect | पहुँचने योग्य पिक्सेल का क्षेत्र |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| नाम | विवरण |
| --- | --- |
| transformPixelFormat(pixelFormat) | पिक्सेल की लेआउट को नए पिक्सेल फ़ॉर्मेट में बदलें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



