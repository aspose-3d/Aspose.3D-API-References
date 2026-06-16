---
title: "NurbsCurve"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

NURBS कर्व एक कर्व है जो NURBS (Non-uniform rational basis spline) द्वारा दर्शाया जाता है, एक NURBS कर्व अपने Order, वजनयुक्त Geometry.ControlPoints के सेट और KnotVectors द्वारा परिभाषित होता है। नियंत्रण बिंदु में w घटक को नियंत्रण बिंदु के वजन के रूप में उपयोग किया जाता है, चाहे वह CurveDimension.TWO_DIMENSIONAL हो या CurveDimension.THREE_DIMENSIONAL।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | NurbsCurve वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(name) | NurbsCurve वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| name | स्ट्रिंग | नाम |

 **Result:**



---


### getControlPoints{#getControlPoints}

| नाम | विवरण |
| --- | --- |
| getControlPoints() | सभी नियंत्रण बिंदु प्राप्त करता है |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| नाम | विवरण |
| --- | --- |
| getMultiplicity() | बहुलता प्राप्त करता है। बहुलता। |

 **Result:**



---


### getOrder{#getOrder}

| नाम | विवरण |
| --- | --- |
| getOrder() | NURBS वक्र का क्रम प्राप्त करता है या सेट करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र पर किसी भी बिंदु को प्रभावित करते हैं। क्रम। |

 **Result:**



---


### setOrder{#setOrder}

| नाम | विवरण |
| --- | --- |
| setOrder(value) | NURBS वक्र का क्रम प्राप्त करता है या सेट करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र पर किसी भी बिंदु को प्रभावित करते हैं। क्रम। |

 **Result:**



---


### getDimension{#getDimension}

| नाम | विवरण |
| --- | --- |
| getDimension() | वक्र का आयाम प्राप्त करता है या सेट करता है। इस गुण का मान CurveDimension पूर्णांक स्थिरांक है। CurveDimension.TWO_DIMENSIONAL वक्र के लिए, नियंत्रण बिंदु में z घटक उपयोग नहीं किया जाता है। |

 **Result:**



---


### setDimension{#setDimension}

| नाम | विवरण |
| --- | --- |
| setDimension(value) | वक्र का आयाम प्राप्त करता है या सेट करता है। इस गुण का मान CurveDimension पूर्णांक स्थिरांक है। CurveDimension.TWO_DIMENSIONAL वक्र के लिए, नियंत्रण बिंदु में z घटक उपयोग नहीं किया जाता है। |

 **Result:**



---


### getCurveType{#getCurveType}

| नाम | विवरण |
| --- | --- |
| getCurveType() | वक्र के प्रकार को प्राप्त करता है या सेट करता है। प्रॉपर्टी का मान NurbsType पूर्णांक स्थिरांक है। वक्र का प्रकार। |

 **Result:**



---


### setCurveType{#setCurveType}

| नाम | विवरण |
| --- | --- |
| setCurveType(value) | वक्र के प्रकार को प्राप्त करता है या सेट करता है। प्रॉपर्टी का मान NurbsType पूर्णांक स्थिरांक है। वक्र का प्रकार। |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| नाम | विवरण |
| --- | --- |
| getKnotVectors() | नॉट वेक्टर प्राप्त करता है, यह पैरामीटर मानों का एक अनुक्रम है जो निर्धारित करता है कि नियंत्रण बिंदु NURBS वक्र को कैसे और कहाँ प्रभावित करते हैं। |

 **Result:**



---


### getRational{#getRational}

| नाम | विवरण |
| --- | --- |
| getRational() | रैशनल है या नहीं प्राप्त करता है या सेट करता है, यह मान दर्शाता है कि यह NurbsCurve रैशनल स्प्लाइन है या नॉन-रैशनल स्प्लाइन। नॉन-रैशनल B-spline रैशनल B-splines का एक विशेष मामला है। यदि यह रैशनल स्प्लाइन है तो true; अन्यथा, false नॉन-रैशनल स्प्लाइन है। |

 **Result:**



---


### setRational{#setRational}

| नाम | विवरण |
| --- | --- |
| setRational(value) | रैशनल है या नहीं प्राप्त करता है या सेट करता है, यह मान दर्शाता है कि यह NurbsCurve रैशनल स्प्लाइन है या नॉन-रैशनल स्प्लाइन। नॉन-रैशनल B-spline रैशनल B-splines का एक विशेष मामला है। यदि यह रैशनल स्प्लाइन है तो true; अन्यथा, false नॉन-रैशनल स्प्लाइन है। |

 **Result:**



---


### getColor{#getColor}

| नाम | विवरण |
| --- | --- |
| getColor() | रेखा का रंग प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान सफेद (1, 1, 1) है। |

 **Result:**



---


### setColor{#setColor}

| नाम | विवरण |
| --- | --- |
| setColor(value) | रेखा का रंग प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान सफेद (1, 1, 1) है। |

 **Result:**



---


### getParentNodes{#getParentNodes}

| नाम | विवरण |
| --- | --- |
| getParentNodes() | सभी पैरेंट नोड्स प्राप्त करता है, एक इकाई को ज्यामिति इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है। नोड्स। |

 **Result:**



---


### getExcluded{#getExcluded}

| नाम | विवरण |
| --- | --- |
| getExcluded() | निर्यात के दौरान इस इकाई को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |

 **Result:**



---


### setExcluded{#setExcluded}

| नाम | विवरण |
| --- | --- |
| setExcluded(value) | निर्यात के दौरान इस इकाई को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |

 **Result:**



---


### getParentNode{#getParentNode}

| नाम | विवरण |
| --- | --- |
| getParentNode() | पहले पैरेंट नोड को प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। पैरेंट नोड। |

 **Result:**



---


### setParentNode{#setParentNode}

| नाम | विवरण |
| --- | --- |
| setParentNode(value) | पहले पैरेंट नोड को प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। पैरेंट नोड। |

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


### evaluate{#evaluate}

| नाम | विवरण |
| --- | --- |
| evaluate(steps) | NURBS वक्र का मूल्यांकन करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| steps | Number | दो पड़ोसी नॉट्स के बीच मूल्यांकन आवृत्ति, डिफ़ॉल्ट मान 20 है। |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| नाम | विवरण |
| --- | --- |
| evaluateAt(u) | निर्दिष्ट स्थिति पर वक्र बिंदु का मूल्यांकन करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| u | Number | वक्र में स्थिति, 0 और 1 के बीच। |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| नाम | विवरण |
| --- | --- |
| getEntityRendererKey() | रेंडरर में पंजीकृत इकाई रेंडरर की कुंजी प्राप्त करता है। |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| नाम | विवरण |
| --- | --- |
| getBoundingBox() | वर्तमान इकाई का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |

 **Result:**
EntityRendererKey


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



