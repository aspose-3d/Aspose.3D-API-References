---
title: RelativeRectangle
second_title: Aspose.3D for Java API Reference
description: Relative rectangle  सापेक्ष घटक को निरपेक्ष मान में बदलने का सूत्र है  Scale  Reference Width  offset  इसलिए यदि हम इसे निरपेक्ष मान के रूप में प्रस्तुत करना चाहते हैं तो सभी scale फ़ील्ड को शून्य रखें और offset फ़ील्ड का उपयोग करें।
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

रिलेटिव रेक्टैंगल। रिलेटिव घटक से एब्सोल्यूट वैल्यू के बीच का सूत्र है: Scale \* (Reference Width) + offset। इसलिए यदि हम इसे एब्सोल्यूट वैल्यू के रूप में दर्शाना चाहते हैं, तो सभी स्केल फ़ील्ड को शून्य रखें, और इसके बजाय ऑफ़सेट फ़ील्ड का उपयोग करें।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | एक [RelativeRectangle](../../com.aspose.threed/relativerectangle) बनाएं |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | सभी offset फ़ील्ड को शून्य और दिए गए पैरामीटर से scale फ़ील्ड के साथ एक [RelativeRectangle](../../com.aspose.threed/relativerectangle) बनाएं। |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | ऊँचाई के लिए offset प्राप्त करता है |
| [getOffsetWidth()](#getOffsetWidth--) | चौड़ाई के लिए offset प्राप्त करता है |
| [getOffsetX()](#getOffsetX--) | निर्देशांक X के लिए offset प्राप्त करता है |
| [getOffsetY()](#getOffsetY--) | निर्देशांक Y के लिए offset प्राप्त करता है |
| [getScaleHeight()](#getScaleHeight--) | सापेक्ष ऊँचाई |
| [getScaleWidth()](#getScaleWidth--) | सापेक्ष चौड़ाई |
| [getScaleX()](#getScaleX--) | सापेक्ष निर्देशांक X |
| [getScaleY()](#getScaleY--) | सापेक्ष निर्देशांक Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | ऊँचाई के लिए offset सेट करता है |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | चौड़ाई के लिए offset सेट करता है |
| [setOffsetX(int value)](#setOffsetX-int-) | निर्देशांक X के लिए offset सेट करता है |
| [setOffsetY(int value)](#setOffsetY-int-) | निर्देशांक Y के लिए offset सेट करता है |
| [setScaleHeight(float value)](#setScaleHeight-float-) | सापेक्ष ऊँचाई |
| [setScaleWidth(float value)](#setScaleWidth-float-) | सापेक्ष चौड़ाई |
| [setScaleX(float value)](#setScaleX-float-) | सापेक्ष निर्देशांक X |
| [setScaleY(float value)](#setScaleY-float-) | सापेक्ष निर्देशांक Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | सापेक्ष आयत को निरपेक्ष आयत में बदलें |
| [toString()](#toString--) | इस इंस्टेंस के मान को java.lang.String में बदलता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


एक [RelativeRectangle](../../com.aspose.threed/relativerectangle) बनाएं

**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


सभी offset फ़ील्ड को शून्य और दिए गए पैरामीटर से scale फ़ील्ड के साथ एक [RelativeRectangle](../../com.aspose.threed/relativerectangle) बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
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


ऊँचाई के लिए offset प्राप्त करता है

**Returns:**
int - ऊँचाई के लिए ऑफ़सेट
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


चौड़ाई के लिए offset प्राप्त करता है

**Returns:**
int - चौड़ाई के लिए ऑफ़सेट
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


निर्देशांक X के लिए offset प्राप्त करता है

**Returns:**
int - X निर्देशांक के लिए ऑफ़सेट
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


निर्देशांक Y के लिए offset प्राप्त करता है

**Returns:**
int - Y निर्देशांक के लिए ऑफ़सेट
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


सापेक्ष ऊँचाई

**Returns:**
float - सापेक्ष ऊँचाई
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


सापेक्ष चौड़ाई

**Returns:**
float - सापेक्ष चौड़ाई
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


सापेक्ष निर्देशांक X

**Returns:**
float - सापेक्ष X निर्देशांक
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


सापेक्ष निर्देशांक Y

**Returns:**
float - सापेक्ष Y निर्देशांक
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


ऊँचाई के लिए offset सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


चौड़ाई के लिए offset सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


निर्देशांक X के लिए offset सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


निर्देशांक Y के लिए offset सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


सापेक्ष ऊँचाई

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


सापेक्ष चौड़ाई

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


सापेक्ष निर्देशांक X

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


सापेक्ष निर्देशांक Y

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


सापेक्ष आयत को निरपेक्ष आयत में बदलें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| बायाँ | int | आयत का बायाँ |
| ऊपर | int | आयत का शीर्ष |
| चौड़ाई | int | आयत की चौड़ाई |
| ऊँचाई | int | आयत की ऊँचाई |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


इस इंस्टेंस के मान को java.lang.String में बदलता है।

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

