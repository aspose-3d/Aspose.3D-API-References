---
title: TextureData
second_title: Aspose.3D for Java API Reference
description: यह क्लास टेक्सचर के कच्चे डेटा और फ़ॉर्मेट परिभाषा को समाहित करती है।
type: docs
weight: 187
url: /hi/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

यह क्लास टेक्सचर के कच्चे डेटा और फ़ॉर्मेट परिभाषा को समाहित करती है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | [TextureData](../../com.aspose.threed/texturedata) का कंस्ट्रक्टर |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | एक नया [TextureData](../../com.aspose.threed/texturedata) बनाता है और पिक्सेल डेटा आवंटित करता है। |
| [TextureData()](#TextureData--) | [TextureData](../../com.aspose.threed/texturedata) का कंस्ट्रक्टर |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | फ़ाइल से टेक्सचर लोड करें |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | स्ट्रीम से टेक्सचर लोड करें |
| [getBytesPerPixel()](#getBytesPerPixel--) | पिक्सेल के बाइट्स की संख्या |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | पिक्सेल डेटा के कच्चे बाइट्स |
| [getHeight()](#getHeight--) | ऊर्ध्वाधर पिक्सेल की संख्या |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getPixelFormat()](#getPixelFormat--) | पिक्सेल का प्रारूप |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getStride()](#getStride--) | स्कैनलाइन के बाइट्स की संख्या। |
| [getWidth()](#getWidth--) | क्षैतिज पिक्सेल की संख्या |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | पढ़ने/लिखने के लिए सभी पिक्सेल को मैप करें |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | दिए गए पिक्सेल फ़ॉर्मेट में पढ़ने/लिखने के लिए सभी पिक्सेल को मैप करें |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | दिए गए पिक्सेल फ़ॉर्मेट में पढ़ने/लिखने के लिए rect द्वारा निर्दिष्ट पिक्सेल को मैप करें |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | टेक्सचर डेटा को निर्दिष्ट इमेज फ़ॉर्मेट में सहेजें |
| [save(String fileName)](#save-java.lang.String-) | टेक्सचर डेटा को इमेज फ़ाइल में सहेजें |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | टेक्सचर डेटा को इमेज फ़ाइल में सहेजें |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | पिक्सेल लेआउट को नए पिक्सेल फ़ॉर्मेट में बदलें। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


[TextureData](../../com.aspose.threed/texturedata) का कंस्ट्रक्टर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| चौड़ाई | int |  |
| ऊँचाई | int |  |
| स्ट्राइड | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| डेटा | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


एक नया [TextureData](../../com.aspose.threed/texturedata) बनाता है और पिक्सेल डेटा आवंटित करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| चौड़ाई | int |  |
| ऊँचाई | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


[TextureData](../../com.aspose.threed/texturedata) का कंस्ट्रक्टर

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेटिव प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


फ़ाइल से टेक्सचर लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


स्ट्रीम से टेक्सचर लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


पिक्सेल के बाइट्स की संख्या

**Returns:**
int - पिक्सेल के बाइट्स की संख्या
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


पिक्सेल डेटा के कच्चे बाइट्स

**Returns:**
byte[] - पिक्सेल डेटा के कच्चे बाइट्स
### getHeight() {#getHeight--}
```
public int getHeight()
```


ऊर्ध्वाधर पिक्सेल की संख्या

**Returns:**
int - लंबवत पिक्सेल की संख्या
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


पिक्सेल का प्रारूप

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है।

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getStride() {#getStride--}
```
public int getStride()
```


स्कैनलाइन के बाइट्स की संख्या।

**Returns:**
int - स्कैनलाइन के बाइट्स की संख्या।
### getWidth() {#getWidth--}
```
public int getWidth()
```


क्षैतिज पिक्सेल की संख्या

**Returns:**
int - क्षैतिज पिक्सेल की संख्या
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


पढ़ने/लिखने के लिए सभी पिक्सेल को मैप करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | मैप मोड |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


दिए गए पिक्सेल फ़ॉर्मेट में पढ़ने/लिखने के लिए सभी पिक्सेल को मैप करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | मैप मोड |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | पिक्सेल फ़ॉर्मेट |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


दिए गए पिक्सेल फ़ॉर्मेट में पढ़ने/लिखने के लिए rect द्वारा निर्दिष्ट पिक्सेल को मैप करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | पहुँचने वाले पिक्सेल का क्षेत्र |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | मैप मोड |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | पिक्सेल फ़ॉर्मेट |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


डायनामिक प्रॉपर्टी को हटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


टेक्सचर डेटा को निर्दिष्ट इमेज फ़ॉर्मेट में सहेजें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | सहेजी गई इमेज को रखने वाली स्ट्रीम |
| format | java.lang.String | इमेज फ़ॉर्मेट, आमतौर पर फ़ाइल एक्सटेंशन |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


टेक्सचर डेटा को इमेज फ़ाइल में सहेजें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | इमेज जहाँ सहेजी जाएगी उसका फ़ाइल नाम। |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


टेक्सचर डेटा को इमेज फ़ाइल में सहेजें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | इमेज जहाँ सहेजी जाएगी उसका फ़ाइल नाम। |
| format | java.lang.String | आउटपुट फ़ाइल का इमेज फ़ॉर्मेट। |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


पिक्सेल लेआउट को नए पिक्सेल फ़ॉर्मेट में बदलें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | गंतव्य पिक्सेल फ़ॉर्मेट |

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

