---
title: "Scene"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/scene/
---
## Scene class

एक सीन शीर्ष-स्तरीय ऑब्जेक्ट है जिसमें नोड्स, ज्योमेट्रीज़, मैटेरियल्स, टेक्सचर, एनीमेशन, पोज़, सब-सीन्स आदि शामिल होते हैं। सीन में सब-सीन्स हो सकते हैं, और यह collada/blender/fbx जैसी फ़ाइलों में मल्टीपल-डॉक्यूमेंट समर्थन के रूप में कार्य करता है। नोड पदानुक्रम को RootNodeLibrary के माध्यम से एक्सेस किया जा सकता है, जिसका उपयोग सीरियलाइज़ेशन के दौरान अनअटैच्ड ऑब्जेक्ट्स (जैसे मेटा डेटा या कस्टम ऑब्जेक्ट्स) का संदर्भ रखने के लिए किया जाता है, ताकि इसे लाइब्रेरी के रूप में उपयोग किया जा सके।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | Scene क्लास की एक नई इंस्टेंस को प्रारंभ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(entity) | Scene क्लास की एक नई इंस्टेंस को प्रारंभ करता है जिसमें एक एंटिटी नई नोड से जुड़ी होती है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | सीन से जुड़ी प्रारंभिक एंटिटी |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| नाम | विवरण |
| --- | --- |
| constructor_overload2(parentScene, name) | Scene क्लास का एक नया इंस्टेंस उप-सीन के रूप में आरंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| parentScene | Scene | पैरेंट सीन। |
| name | स्ट्रिंग | सीन का नाम। |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| नाम | विवरण |
| --- | --- |
| constructor_overload3(fileName) | Scene क्लास का एक नया इंस्टेंस आरंभ करता है और फ़ाइल को तुरंत खोलता है। यह एक अप्रचलित कंस्ट्रक्टर है, कृपया उपयोग करें #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | खोलने के लिए फ़ाइल का नाम। |

 **Result:**



---


### getSubScenes{#getSubScenes}

| नाम | विवरण |
| --- | --- |
| getSubScenes() | सभी उप-सीन प्राप्त करता है |

 **Result:**



---


### getLibrary{#getLibrary}

| नाम | विवरण |
| --- | --- |
| getLibrary() | सीन पदानुक्रम में सीधे उपयोग न किए जाने वाले ऑब्जेक्ट्स को लाइब्रेरी में परिभाषित किया जा सकता है। यह तब उपयोगी होता है जब आप उप-सीन का उपयोग कर रहे हों और पुन: उपयोग योग्य घटकों को उप-सीन के तहत रखें। |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| नाम | विवरण |
| --- | --- |
| getAnimationClips() | सीन में परिभाषित सभी AnimationClip प्राप्त करता है। |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| नाम | विवरण |
| --- | --- |
| getCurrentAnimationClip() | सक्रिय AnimationClip को प्राप्त या सेट करता है |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| नाम | विवरण |
| --- | --- |
| setCurrentAnimationClip(value) | सक्रिय AnimationClip को प्राप्त या सेट करता है |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| नाम | विवरण |
| --- | --- |
| getAssetInfo() | शीर्ष-स्तर की एसेट जानकारी, दस्तावेज़ जानकारी को प्राप्त या सेट करता है। |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| नाम | विवरण |
| --- | --- |
| setAssetInfo(value) | शीर्ष-स्तर की एसेट जानकारी, दस्तावेज़ जानकारी को प्राप्त या सेट करता है। |

 **Result:**



---


### getPoses{#getPoses}

| नाम | विवरण |
| --- | --- |
| getPoses() | इस सीन में उपयोग किए गए सभी Pose प्राप्त करता है। Pose। |

 **Result:**



---


### getRootNode{#getRootNode}

| नाम | विवरण |
| --- | --- |
| getRootNode() | सीन का रूट नोड प्राप्त करता है। रूट नोड। |

 **Result:**



---


### getScene{#getScene}

| नाम | विवरण |
| --- | --- |
| getScene() | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है। |

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


### getAnimationClip{#getAnimationClip}

| नाम | विवरण |
| --- | --- |
| getAnimationClip(name) | नामित AnimationClip प्राप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | यह |

 **Result:**
AnimationClip


---


### clear{#clear}

| नाम | विवरण |
| --- | --- |
| clear() | सीन की सामग्री को साफ़ करता है और डिफ़ॉल्ट सेटिंग्स को पुनर्स्थापित करता है। |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| नाम | विवरण |
| --- | --- |
| createAnimationClip(name) | AnimationClip बनाने और रजिस्टर करने के लिए एक शॉर्टहैंड फ़ंक्शन। पहला AnimationClip CurrentAnimationClip को असाइन किया जाएगा। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | एनीमेशन क्लिप का नाम |

 **Result:**
AnimationClip


---


### open{#open}

| नाम | विवरण |
| --- | --- |
| open(fileName, options) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके दिए गए पथ से सीन खोलता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | फ़ाइल नाम। |
| विकल्प | LoadOptions | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

 **Result:**
AnimationClip


---


### open{#open}

| नाम | विवरण |
| --- | --- |
| open(fileName) | दिए गए पथ से सीन खोलता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | फ़ाइल नाम। |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| नाम | विवरण |
| --- | --- |
| fromFile(fileName) | दिए गए पथ से सीन खोलता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | फ़ाइल नाम। |

 **Result:**
AnimationClip


---


### save{#save}

| नाम | विवरण |
| --- | --- |
| save(fileName) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन सहेजता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | फ़ाइल नाम। |

 **Result:**
AnimationClip


---


### save{#save}

| नाम | विवरण |
| --- | --- |
| save(fileName, format) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन सहेजता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | फ़ाइल नाम। |
| format | फ़ाइल फ़ॉर्मेट | फ़ॉर्मेट। |

 **Result:**
AnimationClip


---


### save{#save}

| नाम | विवरण |
| --- | --- |
| save(fileName, options) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन सहेजता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| fileName | स्ट्रिंग | फ़ाइल नाम। |
| विकल्प | SaveOptions | स्ट्रीम सहेजने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

 **Result:**
AnimationClip


---


### render{#render}

| नाम | विवरण |
| --- | --- |
| render(camera, fileName) | दिए गए कैमरे के परिप्रेक्ष्य से सीन को बाहरी फ़ाइल में रेंडर करता है। डिफ़ॉल्ट आउटपुट आकार 1024x768 है और आउटपुट फ़ॉर्मेट png है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के परिप्रेक्ष्य से सीन को रेंडर करना है। |
| fileName | स्ट्रिंग | आउटपुट फ़ाइल का फ़ाइल नाम |

 **Result:**
AnimationClip


---


### render{#render}

| नाम | विवरण |
| --- | --- |
| render(camera, fileName, size, format) | दिए गए कैमरे के परिप्रेक्ष्य से सीन को बाहरी फ़ाइल में रेंडर करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के परिप्रेक्ष्य से सीन को रेंडर करना है। |
| fileName | स्ट्रिंग | आउटपुट फ़ाइल का फ़ाइल नाम |
| आकार | Vector2 | अंतिम रेंडर की गई छवि का आकार |
| format | स्ट्रिंग | आउटपुट फ़ाइल का इमेज फ़ॉर्मेट |

 **Result:**
AnimationClip


---


### render{#render}

| नाम | विवरण |
| --- | --- |
| render(camera, fileName, size, format, options) | दिए गए कैमरे के परिप्रेक्ष्य से सीन को बाहरी फ़ाइल में रेंडर करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के परिप्रेक्ष्य से सीन को रेंडर करना है। |
| fileName | स्ट्रिंग | आउटपुट फ़ाइल का फ़ाइल नाम |
| आकार | Vector2 | अंतिम रेंडर की गई छवि का आकार |
| format | स्ट्रिंग | आउटपुट फ़ाइल का इमेज फ़ॉर्मेट |
| विकल्प | ImageRenderOptions | आंतरिक सेटिंग्स को अनुकूलित करने का विकल्प। |

 **Result:**
AnimationClip


---


### render{#render}

| नाम | विवरण |
| --- | --- |
| render(camera, bitmap) | दिए गए कैमरा के दृष्टिकोण से सीन को बिटमैप में रेंडर करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के परिप्रेक्ष्य से सीन को रेंडर करना है। |
| bitmap | TextureData | रेंडर किए गए परिणाम का लक्ष्य |

 **Result:**
AnimationClip


---


### render{#render}

| नाम | विवरण |
| --- | --- |
| render(camera, bitmap, options) | दिए गए कैमरा के दृष्टिकोण से सीन को बिटमैप में रेंडर करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के परिप्रेक्ष्य से सीन को रेंडर करना है। |
| bitmap | TextureData | रेंडर किए गए परिणाम का लक्ष्य |
| विकल्प | ImageRenderOptions | आंतरिक सेटिंग्स को अनुकूलित करने का विकल्प। |

 **Result:**
AnimationClip


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



