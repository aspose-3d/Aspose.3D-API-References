---
title: KeyFrame
second_title: Aspose.3D for Java API Reference
description: एक कीफ़्रेम मुख्यतः समय और मान द्वारा परिभाषित होता है; कुछ इंटरपोलेशन प्रकारों जैसे टैंजेंट/टेंशन/बायस/कंटिन्यूटी का उपयोग अंतिम सैंपल किए गए मान की गणना में भी किया जाता है।
type: docs
weight: 89
url: /hi/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

एक कीफ़्रेम मुख्यतः समय और मान द्वारा परिभाषित होता है, कुछ इंटरपोलेशन प्रकारों जैसे टैंजेंट/टेंशन/बायस/कंटिन्यूटी का उपयोग अंतिम सैंपल किए गए मान की गणना में भी किया जाता है। गैर-कीफ़्रेम समय स्थितियों में सैंपल किए गए मान पिछले और अगले कीफ़्रेम के बीच इंटरपोलेट किए जाते हैं। पहले/आखिरी कीफ़्रेम से पहले/बाद के मान को [Extrapolation](../../com.aspose.threed/extrapolation) क्लास द्वारा गणना किया जाता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | निर्दिष्ट वक्र पर एक नया कीफ़्रेम बनाएं। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | TCB स्प्लाइन में उपयोग किया गया बायस प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | TCB स्प्लाइन में उपयोग की गई कंटिन्यूटी प्राप्त करता है। |
| [getFlat()](#getFlat--) | यदि कीफ़्रेम फ्लैट है तो उसे प्राप्त या सेट करें। |
| [getIndependentTangent()](#getIndependentTangent--) | बाहरी और अगला इन टैंजेंट स्वतंत्र होते हैं, इसे प्राप्त करता है। |
| [getInterpolation()](#getInterpolation--) | कीफ़्रेम का इंटरपोलेशन प्रकार प्राप्त करता है, list.data[index] निर्धारित करता है कि सैंपल किया गया मान कैसे गणना किया जाता है। |
| [getNextInTangent()](#getNextInTangent--) | इस कीफ़्रेम पर अगला इन (बायाँ) टैंजेंट प्राप्त करता है। |
| [getNextInWeight()](#getNextInWeight--) | इस कीफ़्रेम पर अगला इन (बायाँ) वज़न प्राप्त करता है। |
| [getOutTangent()](#getOutTangent--) | इस कीफ़्रेम पर आउट (दायाँ) टैंजेंट प्राप्त करता है। |
| [getOutWeight()](#getOutWeight--) | इस कीफ़्रेम पर आउट (दायाँ) वज़न प्राप्त करता है। |
| [getStepMode()](#getStepMode--) | कीफ़्रेम का स्टेप मोड प्राप्त करता है। |
| [getTangentWeightMode()](#getTangentWeightMode--) | कीफ़्रेम का टैंजेंट वज़न मोड प्राप्त करता है। |
| [getTension()](#getTension--) | TCB स्प्लाइन में उपयोग किया गया टेंशन प्राप्त करता है। |
| [getTime()](#getTime--) | list.data[index] कीफ़्रेम की समय स्थिति प्राप्त करता है, जिसे सेकंड में मापा जाता है। |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | टैंजेंट समय-स्वतंत्र है, इसे प्राप्त करता है। |
| [getValue()](#getValue--) | कीफ़्रेम का मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | TCB स्प्लाइन में उपयोग किया गया बायस सेट करता है। |
| [setContinuity(float value)](#setContinuity-float-) | TCB स्प्लाइन में उपयोग की गई कंटिन्यूटी सेट करता है। |
| [setFlat(boolean value)](#setFlat-boolean-) | यदि कीफ़्रेम फ्लैट है तो उसे प्राप्त या सेट करें। |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | आउट और अगले इन टैन्जेंट को स्वतंत्र सेट करता है। |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | की की इंटरपोलेशन प्रकार सेट करता है, list.data[index] निर्धारित करता है कि सैंपल किया गया मान कैसे गणना किया जाता है। |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | इस की फ्रेम पर अगले इन (बाएँ) टैन्जेंट को सेट करता है। |
| [setNextInWeight(float value)](#setNextInWeight-float-) | इस की फ्रेम पर अगले इन (बाएँ) वजन को सेट करता है। |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | इस की फ्रेम पर आउट (दाएँ) टैन्जेंट को सेट करता है। |
| [setOutWeight(float value)](#setOutWeight-float-) | इस की फ्रेम पर आउट (दाएँ) वजन को सेट करता है। |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | की की स्टेप मोड सेट करता है। |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | की की टैन्जेंट वजन मोड सेट करता है। |
| [setTension(float value)](#setTension-float-) | TCB स्प्लाइन में उपयोग किए गए टेंशन को सेट करता है। |
| [setTime(double value)](#setTime-double-) | list.data[index] की फ्रेम की समय स्थिति सेट करता है, जिसे सेकंड में मापा जाता है। |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | टैन्जेंट को समय-स्वतंत्र सेट करता है। |
| [setValue(float value)](#setValue-float-) | की-फ़्रेम का मान सेट करता है। |
| [toString()](#toString--) | की फ्रेम का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


निर्दिष्ट वक्र पर एक नया कीफ़्रेम बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | वह कर्व जिस पर की फ्रेम बनाया जाएगा। |
| समय | double | की फ्रेम की समय स्थिति। |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


TCB स्प्लाइन में उपयोग किया गया बायस प्राप्त करता है।

**Returns:**
float - TCB स्प्लाइन में उपयोग किया गया बायस।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContinuity() {#getContinuity--}
```
public float getContinuity()
```


TCB स्प्लाइन में उपयोग की गई कंटिन्यूटी प्राप्त करता है।

**Returns:**
float - TCB स्प्लाइन में उपयोग की गई निरंतरता।
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


यदि की फ्रेम फ्लैट है तो प्राप्त करें या सेट करें। यदि अगले या पिछले की फ्रेम का मान समान है तो की फ्रेम फ्लैट होना चाहिए। फ्लैट की फ्रेम में फ्लैट टैन्जेंट और स्थिर इंटरपोलेशन होते हैं।

**Returns:**
boolean - यदि की फ्रेम फ्लैट है तो प्राप्त करें या सेट करें। यदि अगले या पिछले की फ्रेम का मान समान है तो की फ्रेम फ्लैट होना चाहिए। फ्लैट की फ्रेम में फ्लैट टैन्जेंट और स्थिर इंटरपोलेशन होते हैं।
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


बाहरी और अगला इन टैंजेंट स्वतंत्र होते हैं, इसे प्राप्त करता है।

**Returns:**
boolean - आउट और अगले इन टैन्जेंट स्वतंत्र हैं।
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


कीफ़्रेम का इंटरपोलेशन प्रकार प्राप्त करता है, list.data[index] निर्धारित करता है कि सैंपल किया गया मान कैसे गणना किया जाता है।

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


इस कीफ़्रेम पर अगला इन (बायाँ) टैंजेंट प्राप्त करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


इस कीफ़्रेम पर अगला इन (बायाँ) वज़न प्राप्त करता है।

**Returns:**
float - इस की फ्रेम पर अगले इन (बाएँ) वजन।
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


इस कीफ़्रेम पर आउट (दायाँ) टैंजेंट प्राप्त करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


इस कीफ़्रेम पर आउट (दायाँ) वज़न प्राप्त करता है।

**Returns:**
float - इस की फ्रेम पर आउट (दाएँ) वजन।
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


की की स्टेप मोड प्राप्त करता है। यदि इंटरपोलेशन प्रकार [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) है, तो list.data[index] तय करता है कि इंटरपोलेशन के दौरान कौन से की-फ़्रेम का मान उपयोग किया जाएगा। एक [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) का अर्थ है कि बाएँ की-फ़्रेम का मान उपयोग होगा। एक [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) का अर्थ है कि अगले दाएँ की-फ़्रेम का मान उपयोग होगा।

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


की की टैन्जेंट वजन मोड प्राप्त करता है। आउट टैन्जेंट या अगले इन टैन्जेंट को सही [WeightedMode](../../com.aspose.threed/weightedmode) चुनकर कस्टमाइज़ किया जा सकता है।

**Returns:**
int - की की टैन्जेंट वजन मोड। आउट टैन्जेंट या अगले इन टैन्जेंट को सही [WeightedMode](../../com.aspose.threed/weightedmode) चुनकर कस्टमाइज़ किया जा सकता है।
### getTension() {#getTension--}
```
public float getTension()
```


TCB स्प्लाइन में उपयोग किया गया टेंशन प्राप्त करता है।

**Returns:**
float - TCB स्प्लाइन में उपयोग किया गया तनाव
### getTime() {#getTime--}
```
public double getTime()
```


list.data[index] कीफ़्रेम की समय स्थिति प्राप्त करता है, जिसे सेकंड में मापा जाता है।

**Returns:**
double - list.data[index] कुंजी फ्रेम का समय स्थिति, सेकंड में मापा गया।
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


टैंजेंट समय-स्वतंत्र है, इसे प्राप्त करता है।

**Returns:**
boolean - टैन्जेंट समय-स्वतंत्र है
### getValue() {#getValue--}
```
public float getValue()
```


कीफ़्रेम का मान प्राप्त करता है।

**Returns:**
float - कुंजी-फ़्रेम का मान।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBias(float value) {#setBias-float-}
```
public void setBias(float value)
```


TCB स्प्लाइन में उपयोग किया गया बायस सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


TCB स्प्लाइन में उपयोग की गई कंटिन्यूटी सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


यदि की फ्रेम फ्लैट है तो प्राप्त करें या सेट करें। यदि अगले या पिछले की फ्रेम का मान समान है तो की फ्रेम फ्लैट होना चाहिए। फ्लैट की फ्रेम में फ्लैट टैन्जेंट और स्थिर इंटरपोलेशन होते हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


आउट और अगले इन टैन्जेंट को स्वतंत्र सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


की की इंटरपोलेशन प्रकार सेट करता है, list.data[index] निर्धारित करता है कि सैंपल किया गया मान कैसे गणना किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | नया मान |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


इस की फ्रेम पर अगले इन (बाएँ) टैन्जेंट को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


इस की फ्रेम पर अगले इन (बाएँ) वजन को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


इस की फ्रेम पर आउट (दाएँ) टैन्जेंट को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


इस की फ्रेम पर आउट (दाएँ) वजन को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


कुंजी की स्टेप मोड सेट करता है। यदि इंटरपोलेशन प्रकार [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) है, तो list.data[index] तय करता है कि इंटरपोलेशन के दौरान कौन से कुंजी-फ़्रेम का मान उपयोग होगा। एक [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) का अर्थ है कि बाएँ कुंजी-फ़्रेम का मान उपयोग होगा। एक [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) का अर्थ है कि अगले दाएँ कुंजी-फ़्रेम का मान उपयोग होगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | नया मान |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


कुंजी की टैन्जेंट वेट मोड सेट करता है। आउट टैन्जेंट या अगला इन टैन्जेंट सही [WeightedMode](../../com.aspose.threed/weightedmode) चुनकर अनुकूलित किया जा सकता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


TCB स्प्लाइन में उपयोग किए गए टेंशन को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


list.data[index] की फ्रेम की समय स्थिति सेट करता है, जिसे सेकंड में मापा जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


टैन्जेंट को समय-स्वतंत्र सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


की-फ़्रेम का मान सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### toString() {#toString--}
```
public String toString()
```


की फ्रेम का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है।

**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

