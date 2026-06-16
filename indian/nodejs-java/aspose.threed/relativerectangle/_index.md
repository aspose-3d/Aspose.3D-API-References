---
title: "RelativeRectangle"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

सापेक्ष आयत  सापेक्ष घटक से निरपेक्ष मान के बीच का सूत्र है:  स्केल  (संदर्भ चौड़ाई) + ऑफसेट  इसलिए यदि हम इसे निरपेक्ष मान के रूप में प्रदर्शित करना चाहते हैं, तो सभी स्केल फ़ील्ड को शून्य रखें, और इसके बजाय ऑफसेट फ़ील्ड का उपयोग करें।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(left, top, width, height) | एक RelativeRectangle बनाएं |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| बायाँ | Number | null |
| to | Number | null |
| widt | Number | null |
| heigh | Number | null |

 **Result:**



---


### getScaleX{#getScaleX}

| नाम | विवरण |
| --- | --- |
| getScaleX() | सापेक्ष निर्देशांक X |

 **Result:**



---


### setScaleX{#setScaleX}

| नाम | विवरण |
| --- | --- |
| setScaleX(value) | सापेक्ष निर्देशांक X |

 **Result:**



---


### getScaleY{#getScaleY}

| नाम | विवरण |
| --- | --- |
| getScaleY() | सापेक्ष निर्देशांक Y |

 **Result:**



---


### setScaleY{#setScaleY}

| नाम | विवरण |
| --- | --- |
| setScaleY(value) | सापेक्ष निर्देशांक Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| नाम | विवरण |
| --- | --- |
| getScaleWidth() | सापेक्ष चौड़ाई |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| नाम | विवरण |
| --- | --- |
| setScaleWidth(value) | सापेक्ष चौड़ाई |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| नाम | विवरण |
| --- | --- |
| getScaleHeight() | सापेक्ष ऊँचाई |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| नाम | विवरण |
| --- | --- |
| setScaleHeight(value) | सापेक्ष ऊँचाई |

 **Result:**



---


### getOffsetX{#getOffsetX}

| नाम | विवरण |
| --- | --- |
| getOffsetX() | निर्देशांक X के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |

 **Result:**



---


### setOffsetX{#setOffsetX}

| नाम | विवरण |
| --- | --- |
| setOffsetX(value) | निर्देशांक X के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |

 **Result:**



---


### getOffsetY{#getOffsetY}

| नाम | विवरण |
| --- | --- |
| getOffsetY() | निर्देशांक Y के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |

 **Result:**



---


### setOffsetY{#setOffsetY}

| नाम | विवरण |
| --- | --- |
| setOffsetY(value) | निर्देशांक Y के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| नाम | विवरण |
| --- | --- |
| getOffsetWidth() | चौड़ाई के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| नाम | विवरण |
| --- | --- |
| setOffsetWidth(value) | चौड़ाई के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| नाम | विवरण |
| --- | --- |
| getOffsetHeight() | ऊँचाई के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| नाम | विवरण |
| --- | --- |
| setOffsetHeight(value) | ऊँचाई के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |

 **Result:**



---


### toAbsolute{#toAbsolute}

| नाम | विवरण |
| --- | --- |
| toAbsolute(left, top, width, height) | सापेक्ष आयत को निरपेक्ष आयत में बदलें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| बायाँ | Number | आयत का बायाँ भाग |
| ऊपर | Number | आयत का ऊपर भाग |
| चौड़ाई | Number | आयत की चौड़ाई |
| height | Number | आयत की ऊँचाई |

 **Result:**
Rect


---


### fromScale{#fromScale}

| नाम | विवरण |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | सभी ऑफ़सेट फ़ील्ड को शून्य और दिए गए पैरामीटरों से स्केल फ़ील्ड के साथ एक RelativeRectangle बनाएं। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| स्केल | Number | null |
| स्केल | Number | null |
| scaleWidt | Number | null |
| scaleHeigh | Number | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | इस इंस्टेंस के मान को java.lang.String में परिवर्तित करता है। |

 **Result:**
RelativeRectangle


---



