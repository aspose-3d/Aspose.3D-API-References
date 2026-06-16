---
title: "Bone"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/bone/
---
## Bone class

एक बोन जियोमेट्री के कंट्रोल पॉइंट के उपसमुच्चय को परिभाषित करता है, और प्रत्येक कंट्रोल पॉइंट के लिए ब्लेंड वेट निर्धारित करता है। Bone ऑब्जेक्ट को सीधे उपयोग नहीं किया जा सकता, जियोमेट्री को डिफॉर्म करने के लिए एक SkinDeformer इंस्टेंस का उपयोग किया जाता है, और SkinDeformer कई बोंस के सेट के साथ आता है, प्रत्येक बोन एक नोड से जुड़ा होता है। नोट: जियोमेट्री का एक कंट्रोल पॉइंट एक से अधिक बोंस से बंधा हो सकता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(name) | Bone क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload() | Bone क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |

 **Result:**



---


### getWeightCount{#getWeightCount}

| नाम | विवरण |
| --- | --- |
| getWeightCount() | वज़न की गिनती प्राप्त करता है, यह setWeight(int, double) द्वारा स्वचालित रूप से विस्तारित किया जाता है। |

 **Result:**



---


### getTransform{#getTransform}

| नाम | विवरण |
| --- | --- |
| getTransform() | हड्डी को समाहित करने वाले नोड का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setTransform{#setTransform}

| नाम | विवरण |
| --- | --- |
| setTransform(value) | हड्डी को समाहित करने वाले नोड का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| नाम | विवरण |
| --- | --- |
| getBoneTransform() | हड्डी का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| नाम | विवरण |
| --- | --- |
| setBoneTransform(value) | हड्डी का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getNode{#getNode}

| नाम | विवरण |
| --- | --- |
| getNode() | नोड को प्राप्त करता है या सेट करता है। बोन नोड वह हड्डी है जिससे स्किन जुड़ी होती है, SkinDeformer बोन नोड का उपयोग कंट्रोल पॉइंट्स के विस्थापन को प्रभावित करने के लिए करता है। बोन नोड आमतौर पर एक Skeleton से जुड़ा होता है, लेकिन यह आवश्यक नहीं है। जुड़ा हुआ Skeleton आमतौर पर DCC सॉफ़्टवेयर द्वारा उपयोगकर्ता को स्केलेटन दिखाने के लिए प्रयोग किया जाता है। |

 **Result:**



---


### setNode{#setNode}

| नाम | विवरण |
| --- | --- |
| setNode(value) | नोड को प्राप्त करता है या सेट करता है। बोन नोड वह हड्डी है जिससे स्किन जुड़ी होती है, SkinDeformer बोन नोड का उपयोग कंट्रोल पॉइंट्स के विस्थापन को प्रभावित करने के लिए करता है। बोन नोड आमतौर पर एक Skeleton से जुड़ा होता है, लेकिन यह आवश्यक नहीं है। जुड़ा हुआ Skeleton आमतौर पर DCC सॉफ़्टवेयर द्वारा उपयोगकर्ता को स्केलेटन दिखाने के लिए प्रयोग किया जाता है। |

 **Result:**



---


### getName{#getName}

| नाम | विवरण |
| --- | --- |
| getName() | नाम को प्राप्त करता है या सेट करता है। नाम। |

 **Result:**



---


### setName{#setName}

| नाम | विवरण |
| --- | --- |
| setName(value) | नाम को प्राप्त करता है या सेट करता है। नाम। |

 **Result:**



---


### getProperties{#getProperties}

| नाम | विवरण |
| --- | --- |
| getProperties() | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

 **Result:**



---


### get{#get}

| नाम | विवरण |
| --- | --- |
| get(index) |  |

 **Result:**



---


### set{#set}

| नाम | विवरण |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| नाम | विवरण |
| --- | --- |
| getWeight(index) | इंडेक्स द्वारा निर्दिष्ट कंट्रोल पॉइंट के लिए वज़न प्राप्त करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| index | Number | कंट्रोल पॉइंट का इंडेक्स |

 **Result:**
Number


---


### setWeight{#setWeight}

| नाम | विवरण |
| --- | --- |
| setWeight(index, weight) | इंडेक्स द्वारा निर्दिष्ट कंट्रोल पॉइंट के लिए वज़न सेट करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| index | Number | कंट्रोल पॉइंट का इंडेक्स |
| वजन | Number | नया वजन |

 **Result:**
Number


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



