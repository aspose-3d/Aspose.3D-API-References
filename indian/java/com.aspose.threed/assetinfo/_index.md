---
title: AssetInfo
second_title: Aspose.3D for Java API Reference
description: एसेट की जानकारी।
type: docs
weight: 17
url: /hi/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

एसेट की जानकारी। एसेट जानकारी को एक [Scene](../../com.aspose.threed/scene) से संलग्न किया जा सकता है। चाइल्ड [Scene](../../com.aspose.threed/scene) अपनी स्वयं की [AssetInfo](../../com.aspose.threed/assetinfo) रख सकता है ताकि पैरेंट की परिभाषा को ओवरराइड किया जा सके। **Example:** निम्नलिखित कोड दिखाता है कि fbx फ़ाइल से एसेट जानकारी कैसे पढ़ी जाए:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | नए [AssetInfo](../../com.aspose.threed/assetinfo) क्लास का एक नया उदाहरण आरंभ करता है। |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | नए [AssetInfo](../../com.aspose.threed/assetinfo) क्लास का एक नया उदाहरण आरंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getAmbient()](#getAmbient--) | इस एसेट का डिफ़ॉल्ट एम्बिएंट रंग प्राप्त करता है या सेट करता है |
| [getApplicationName()](#getApplicationName--) | इस एसेट को बनाने वाले एप्लिकेशन को प्राप्त करता है |
| [getApplicationVendor()](#getApplicationVendor--) | एप्लिकेशन विक्रेता का नाम प्राप्त करता है |
| [getApplicationVersion()](#getApplicationVersion--) | इस एसेट को बनाने वाले एप्लिकेशन का संस्करण प्राप्त करता है। |
| [getAuthor()](#getAuthor--) | इस एसेट के लेखक को प्राप्त करता है |
| [getAxisSystem()](#getAxisSystem--) | एसेट जानकारी का कोऑर्डिनेट सिस्टम/अप वेक्टर/फ्रंट वेक्टर प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | इस एसेट की टिप्पणी प्राप्त करता है। |
| [getCoordinateSystem()](#getCoordinateSystem--) | इस एसेट में उपयोग किए गए कोऑर्डिनेट सिस्टम को प्राप्त करता है। |
| [getCopyright()](#getCopyright--) | दस्तावेज़ का कॉपीराइट प्राप्त करता है |
| [getCreationTime()](#getCreationTime--) | इस एसेट का निर्माण समय प्राप्त करता है या सेट करता है |
| [getFrontVector()](#getFrontVector--) | इस एसेट में उपयोग किए गए फ्रंट-वेक्टर को प्राप्त करता है। |
| [getKeywords()](#getKeywords--) | इस एसेट के कीवर्ड प्राप्त करता है |
| [getModificationTime()](#getModificationTime--) | इस एसेट का संशोधन समय प्राप्त करता है या सेट करता है |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRevision()](#getRevision--) | इस एसेट का रिवीजन नंबर प्राप्त करता है, जो आमतौर पर संस्करण नियंत्रण प्रणाली में उपयोग होता है। |
| [getSubject()](#getSubject--) | इस एसेट का विषय प्राप्त करता है |
| [getTitle()](#getTitle--) | इस एसेट का शीर्षक प्राप्त करता है |
| [getUnitName()](#getUnitName--) | इस एसेट में उपयोग की गई लंबाई की इकाई प्राप्त करता है। |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | वास्तविक दुनिया के मीटर के लिए स्केल फैक्टर प्राप्त करता है। |
| [getUpVector()](#getUpVector--) | इस एसेट में उपयोग किए गए अप-वेक्टर को प्राप्त करता है। |
| [getUrl()](#getUrl--) | इस एसेट का URL प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | इस एसेट का डिफ़ॉल्ट एम्बिएंट रंग प्राप्त करता है या सेट करता है |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | इस एसेट को बनाने वाले एप्लिकेशन को सेट करता है |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | एप्लिकेशन विक्रेता का नाम सेट करता है |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | इस एसेट को बनाने वाले एप्लिकेशन का संस्करण सेट करता है। |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | इस एसेट के लेखक को सेट करता है |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | एसेट जानकारी के कोऑर्डिनेट सिस्टम/अप वेक्टर/फ्रंट वेक्टर को सेट करता है। |
| [setComment(String value)](#setComment-java.lang.String-) | इस एसेट की टिप्पणी सेट करता है। |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | इस एसेट में उपयोग किए गए कोऑर्डिनेट सिस्टम को सेट करता है। |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | दस्तावेज़ का कॉपीराइट सेट करता है |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | इस एसेट का निर्माण समय प्राप्त करता है या सेट करता है |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | इस एसेट में उपयोग किए गए फ्रंट-वेक्टर को सेट करता है। |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | इस एसेट के कीवर्ड सेट करता है |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | इस एसेट का संशोधन समय प्राप्त करता है या सेट करता है |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRevision(String value)](#setRevision-java.lang.String-) | इस एसेट का रिवीजन नंबर सेट करता है, जो आमतौर पर संस्करण नियंत्रण प्रणाली में उपयोग होता है। |
| [setSubject(String value)](#setSubject-java.lang.String-) | इस एसेट का विषय सेट करता है |
| [setTitle(String value)](#setTitle-java.lang.String-) | इस एसेट का शीर्षक सेट करता है |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | इस एसेट में उपयोग की गई लंबाई की इकाई सेट करता है। |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | वास्तविक विश्व मीटर के लिए स्केल फैक्टर सेट करता है। |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | इस एसेट में उपयोग किए जाने वाले अप-वेक्टर को सेट करता है। |
| [setUrl(String value)](#setUrl-java.lang.String-) | इस एसेट का URL प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


नए [AssetInfo](../../com.aspose.threed/assetinfo) क्लास का एक नया उदाहरण आरंभ करता है।

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


नए [AssetInfo](../../com.aspose.threed/assetinfo) क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम |

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


इस एसेट का डिफ़ॉल्ट एम्बिएंट रंग प्राप्त करता है या सेट करता है

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


इस एसेट को बनाने वाले एप्लिकेशन को प्राप्त करता है

**Returns:**
java.lang.String - वह एप्लिकेशन जो इस एसेट को बनाया है
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


एप्लिकेशन विक्रेता का नाम प्राप्त करता है

**Returns:**
java.lang.String - एप्लिकेशन विक्रेता का नाम
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


इस एसेट को बनाने वाले एप्लिकेशन का संस्करण प्राप्त करता है।

**Returns:**
java.lang.String - वह एप्लिकेशन संस्करण जिसने इस एसेट को बनाया।
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


इस एसेट के लेखक को प्राप्त करता है

**Returns:**
java.lang.String - इस एसेट का लेखक
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


एसेट जानकारी का कोऑर्डिनेट सिस्टम/अप वेक्टर/फ्रंट वेक्टर प्राप्त करता है।

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


इस एसेट की टिप्पणी प्राप्त करता है।

**Returns:**
java.lang.String - इस एसेट की टिप्पणी।
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


इस एसेट में उपयोग किए गए कोऑर्डिनेट सिस्टम को प्राप्त करता है।

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


दस्तावेज़ का कॉपीराइट प्राप्त करता है

**Returns:**
java.lang.String - दस्तावेज़ का कॉपीराइट
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


इस एसेट का निर्माण समय प्राप्त करता है या सेट करता है

**Returns:**
java.util.Calendar - या इस एसेट का निर्माण समय सेट करता है
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


इस एसेट में उपयोग किए गए फ्रंट-वेक्टर को प्राप्त करता है।

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


इस एसेट के कीवर्ड प्राप्त करता है

**Returns:**
java.lang.String - इस एसेट के कीवर्ड
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


इस एसेट का संशोधन समय प्राप्त करता है या सेट करता है

**Returns:**
java.util.Calendar - या इस एसेट का संशोधन समय सेट करता है
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


इस एसेट का रिवीजन नंबर प्राप्त करता है, जो आमतौर पर संस्करण नियंत्रण प्रणाली में उपयोग होता है।

**Returns:**
java.lang.String - इस एसेट का रिवीजन नंबर, आमतौर पर संस्करण नियंत्रण प्रणाली में उपयोग किया जाता है।
### getSubject() {#getSubject--}
```
public String getSubject()
```


इस एसेट का विषय प्राप्त करता है

**Returns:**
java.lang.String - इस एसेट का विषय
### getTitle() {#getTitle--}
```
public String getTitle()
```


इस एसेट का शीर्षक प्राप्त करता है

**Returns:**
java.lang.String - इस एसेट का शीर्षक
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


इस एसेट में उपयोग की गई लंबाई इकाई प्राप्त करता है। उदाहरण: सेमी/मी/किमी/इंच/फ़ीट

**Returns:**
java.lang.String - इस एसेट में उपयोग की गई लंबाई इकाई। उदाहरण: सेमी/मी/किमी/इंच/फ़ीट
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


वास्तविक दुनिया के मीटर के लिए स्केल फैक्टर प्राप्त करता है।

**Returns:**
double - वास्तविक विश्व मीटर के लिए स्केल फैक्टर। **Remarks:** यदि इकाई नाम null है तो यह सीरियलाइज़ेशन के दौरान अनदेखा किया जाता है।
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


इस एसेट में उपयोग किए गए अप-वेक्टर को प्राप्त करता है।

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


इस एसेट का URL प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - या इस एसेट का URL सेट करता है।
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


इस एसेट का डिफ़ॉल्ट एम्बिएंट रंग प्राप्त करता है या सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | नया मान |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


इस एसेट को बनाने वाले एप्लिकेशन को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


एप्लिकेशन विक्रेता का नाम सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


इस एसेट को बनाने वाले एप्लिकेशन का संस्करण सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


इस एसेट के लेखक को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


एसेट जानकारी के कोऑर्डिनेट सिस्टम/अप वेक्टर/फ्रंट वेक्टर को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | नया मान |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


इस एसेट की टिप्पणी सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


इस एसेट में उपयोग किए गए कोऑर्डिनेट सिस्टम को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | नया मान |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


दस्तावेज़ का कॉपीराइट सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


इस एसेट का निर्माण समय प्राप्त करता है या सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.util.Calendar | नया मान |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


इस एसेट में उपयोग किए गए फ्रंट-वेक्टर को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | नया मान |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


इस एसेट के कीवर्ड सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


इस एसेट का संशोधन समय प्राप्त करता है या सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.util.Calendar | नया मान |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


इस एसेट का रिवीजन नंबर सेट करता है, जो आमतौर पर संस्करण नियंत्रण प्रणाली में उपयोग होता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


इस एसेट का विषय सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


इस एसेट का शीर्षक सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


इस एसेट में उपयोग की गई लंबाई इकाई सेट करता है। उदाहरण: सेमी/मी/किमी/इंच/फ़ीट

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


वास्तविक विश्व मीटर के लिए स्केल फैक्टर सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नई मान **Remarks:** यदि इकाई नाम null है तो यह सीरियलाइज़ेशन के दौरान अनदेखा किया जाता है। |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


इस एसेट में उपयोग किए जाने वाले अप-वेक्टर को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | नया मान |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


इस एसेट का URL प्राप्त करता है या सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### toString() {#toString--}
```
public String toString()
```




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

