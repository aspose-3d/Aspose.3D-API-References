---
title: "RelativeRectangle"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "रिलेटिव आयत  रिलेटिव घटक से एब्सोल्यूट मान के बीच का सूत्र है  Scale  Reference Width  offset  इसलिए यदि हम इसे एब्सोल्यूट मान के रूप में दर्शाना चाहते हैं तो सभी स्केल फ़ील्ड को शून्य रखें और इसके बजाय ऑफ़सेट फ़ील्ड का उपयोग करें।"
type: docs
weight: 147
url: /hi/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

रिलेटिव आयत फ़ॉर्मूला रिलेटिव कंपोनेंट से एब्सोल्यूट वैल्यू के बीच है: Scale \* (Reference Width) + offset। इसलिए यदि हम इसे एब्सोल्यूट वैल्यू के रूप में दर्शाना चाहते हैं, तो सभी स्केल फ़ील्ड को शून्य रखें, और इसके बजाय ऑफ़सेट फ़ील्ड का उपयोग करें।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | एक [RelativeRectangle](../../com.aspose.threed/relativerectangle) बनाएं |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | सभी ऑफ़सेट फ़ील्ड को शून्य और दिए गए पैरामीटरों से स्केल फ़ील्ड के साथ एक [RelativeRectangle](../../com.aspose.threed/relativerectangle) बनाएं। |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | ऊँचाई के लिए ऑफ़सेट प्राप्त करता है |
| [getOffsetWidth()](#getOffsetWidth--) | चौड़ाई के लिए ऑफ़सेट प्राप्त करता है |
| [getOffsetX()](#getOffsetX--) | निर्देशांक X के लिए ऑफ़सेट प्राप्त करता है |
| [getOffsetY()](#getOffsetY--) | निर्देशांक Y के लिए ऑफ़सेट प्राप्त करता है |
| [getScaleHeight()](#getScaleHeight--) | रिलेटिव ऊँचाई |
| [getScaleWidth()](#getScaleWidth--) | रिलेटिव चौड़ाई |
| [getScaleX()](#getScaleX--) | रिलेटिव निर्देशांक X |
| [getScaleY()](#getScaleY--) | रिलेटिव निर्देशांक Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | ऊँचाई के लिए ऑफ़सेट सेट करता है |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | चौड़ाई के लिए ऑफ़सेट सेट करता है |
| [setOffsetX(int value)](#setOffsetX-int-) | निर्देशांक X के लिए ऑफ़सेट सेट करता है |
| [setOffsetY(int value)](#setOffsetY-int-) | निर्देशांक Y के लिए ऑफ़सेट सेट करता है |
| [setScaleHeight(float value)](#setScaleHeight-float-) | रिलेटिव ऊँचाई |
| [setScaleWidth(float value)](#setScaleWidth-float-) | रिलेटिव चौड़ाई |
| [setScaleX(float value)](#setScaleX-float-) | रिलेटिव निर्देशांक X |
| [setScaleY(float value)](#setScaleY-float-) | रिलेटिव निर्देशांक Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | रिलेटिव आयत को एब्सोल्यूट आयत में परिवर्तित करें |
| [toString()](#toString--) | इस इंस्टेंस के मान को java.lang.String में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


एक [RelativeRectangle](../../com.aspose.threed/relativerectangle) बनाएं

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बायाँ | int |  |
| ऊपर | int |  |
| चौड़ाई | int |  |
| ऊँचाई | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


सभी ऑफ़सेट फ़ील्ड को शून्य और दिए गए पैरामीटरों से स्केल फ़ील्ड के साथ एक [RelativeRectangle](../../com.aspose.threed/relativerectangle) बनाएं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | फ़्लोट |  |
| scaleY | फ़्लोट |  |
| scaleWidth | फ़्लोट |  |
| scaleHeight | फ़्लोट |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


ऊँचाई के लिए ऑफ़सेट प्राप्त करता है

**Returns:**
int - ऊँचाई के लिए ऑफ़सेट
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


चौड़ाई के लिए ऑफ़सेट प्राप्त करता है

**Returns:**
int - चौड़ाई के लिए ऑफ़सेट
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


निर्देशांक X के लिए ऑफ़सेट प्राप्त करता है

**Returns:**
int - निर्देशांक X के लिए ऑफ़सेट
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


निर्देशांक Y के लिए ऑफ़सेट प्राप्त करता है

**Returns:**
int - निर्देशांक Y के लिए ऑफ़सेट
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


रिलेटिव ऊँचाई

**Returns:**
float - सापेक्ष ऊँचाई
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


रिलेटिव चौड़ाई

**Returns:**
float - सापेक्ष चौड़ाई
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


रिलेटिव निर्देशांक X

**Returns:**
float - सापेक्ष निर्देशांक X
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


रिलेटिव निर्देशांक Y

**Returns:**
float - सापेक्ष निर्देशांक Y
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


ऊँचाई के लिए ऑफ़सेट सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


चौड़ाई के लिए ऑफ़सेट सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


निर्देशांक X के लिए ऑफ़सेट सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


निर्देशांक Y के लिए ऑफ़सेट सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


रिलेटिव ऊँचाई

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


रिलेटिव चौड़ाई

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


रिलेटिव निर्देशांक X

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


रिलेटिव निर्देशांक Y

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


रिलेटिव आयत को एब्सोल्यूट आयत में परिवर्तित करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बायाँ | int | आयत का बायाँ भाग |
| ऊपर | int | आयत का ऊपर वाला भाग |
| चौड़ाई | int | आयत की चौड़ाई |
| ऊँचाई | int | आयत की ऊँचाई |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


इस इंस्टेंस के मान को java.lang.String में परिवर्तित करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

