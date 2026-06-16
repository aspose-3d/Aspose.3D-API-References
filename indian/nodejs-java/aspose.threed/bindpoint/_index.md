---
title: "BindPoint"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

एक BindPoint आमतौर पर ऑब्जेक्ट की प्रॉपर्टी पर बनाया जाता है, कुछ प्रॉपर्टी प्रकारों में कई कंपोनेंट फ़ील्ड होते हैं (जैसे Vector3 फ़ील्ड), BindPoint प्रत्येक कंपोनेंट फ़ील्ड के लिए चैनल उत्पन्न करेगा और चैनलों के माध्यम से फ़ील्ड को एक या अधिक कीफ़्रेम सीक्वेंस इंस्टेंस से जोड़ता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(scene, prop) | BindPoint क्लास का नया इंस्टेंस प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| scene | Scene | ऐसी scene जो एनीमेशन को सम्मिलित करती है। |
| prop | Property | प्रॉपर्टी। |

 **Result:**



---


### getProperty{#getProperty}

| नाम | विवरण |
| --- | --- |
| getProperty() | CurveMapping से जुड़ी प्रॉपर्टी को प्राप्त करता है |

 **Result:**



---


### setProperty{#setProperty}

| नाम | विवरण |
| --- | --- |
| setProperty(value) | CurveMapping से जुड़ी प्रॉपर्टी को प्राप्त करता है |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| नाम | विवरण |
| --- | --- |
| getChannelsCount() | इस एनीमेशन कर्व मैपिंग में परिभाषित प्रॉपर्टी चैनलों की कुल संख्या को प्राप्त करता है। |

 **Result:**
Number


---


### getName{#getName}

| नाम | विवरण |
| --- | --- |
| getName() | नाम को प्राप्त करता है या सेट करता है। नाम। |

 **Result:**
Number


---


### setName{#setName}

| नाम | विवरण |
| --- | --- |
| setName(value) | नाम को प्राप्त करता है या सेट करता है। नाम। |

 **Result:**
Number


---


### getProperties{#getProperties}

| नाम | विवरण |
| --- | --- |
| getProperties() | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

 **Result:**
Number


---


### get{#get}

| नाम | विवरण |
| --- | --- |
| get(channelName) |  |

 **Result:**
Number


---


### getKeyframeSequence{#getKeyframeSequence}

| नाम | विवरण |
| --- | --- |
| getKeyframeSequence(channelName) | निर्दिष्ट चैनल में पहली कीफ़्रेम अनुक्रम प्राप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| channelName | स्ट्रिंग | खोजने के लिए चैनल का नाम |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| नाम | विवरण |
| --- | --- |
| getKeyframeSequences(channelName) | निर्दिष्ट चैनल में सभी कीफ़्रेम अनुक्रम प्राप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| channelName | स्ट्रिंग | खोजने के लिए चैनल का नाम |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| नाम | विवरण |
| --- | --- |
| createKeyframeSequence(name) | एक नया कर्व बनाता है और इसे कर्व मैपिंग के पहले चैनल से जोड़ता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नए अनुक्रम का नाम। |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| नाम | विवरण |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | कीफ़्रेम अनुक्रम को निर्दिष्ट चैनल से बाइंड करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| channelName | स्ट्रिंग | कीफ़्रेम अनुक्रम किस चैनल से बंधा होगा |
| अनुक्रम | KeyframeSequence | बाइंड करने के लिए कीफ़्रेम अनुक्रम |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| नाम | विवरण |
| --- | --- |
| getChannel(channelName) | दिए गए नाम से चैनल प्राप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| channelName | स्ट्रिंग | खोजने के लिए चैनल का नाम |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| नाम | विवरण |
| --- | --- |
| addChannel(name, value) | निर्दिष्ट चैनल प्रॉपर्टी जोड़ता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |
| मान | ऑब्जेक्ट | मान। |

 **Result:**
boolean


---


### addChannel{#addChannel}

| नाम | विवरण |
| --- | --- |
| addChannel(name, type, value) | निर्दिष्ट चैनल प्रॉपर्टी जोड़ता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |
| type | क्लास | प्रकार। |
| मान | ऑब्जेक्ट | मान। |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| नाम | विवरण |
| --- | --- |
| resetChannels() | इस एनीमेशन कर्व मैपिंग के प्रॉपर्टी चैनलों को खाली करता है। |

 **Result:**
boolean


---


### toString{#toString}

| नाम | विवरण |
| --- | --- |
| toString() | ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है। |

 **Result:**
स्ट्रिंग


---


### removeProperty{#removeProperty}

| नाम | विवरण |
| --- | --- |
| removeProperty(property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| property | Property | कौन सी प्रॉपर्टी हटानी है |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| नाम | विवरण |
| --- | --- |
| removeProperty(property) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| propert | स्ट्रिंग | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| नाम | विवरण |
| --- | --- |
| getProperty(property) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| property | स्ट्रिंग | प्रॉपर्टी का नाम |

 **Result:**
ऑब्जेक्ट


---


### setProperty{#setProperty}

| नाम | विवरण |
| --- | --- |
| setProperty(property, value) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| property | स्ट्रिंग | प्रॉपर्टी का नाम |
| मान | ऑब्जेक्ट | प्रॉपर्टी का मान |

 **Result:**
ऑब्जेक्ट


---


### findProperty{#findProperty}

| नाम | विवरण |
| --- | --- |
| findProperty(propertyName) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेेटिव प्रॉपर्टी (इसके नाम द्वारा पहचानी गई)। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| propertyName | स्ट्रिंग | प्रॉपर्टी का नाम। |

 **Result:**
Property


---



