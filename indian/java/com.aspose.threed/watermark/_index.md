---
title: Watermark
second_title: Aspose.3D for Java API Reference
description: मेश से/तक अंधा वॉटरमार्क एन्कोड/डिकोड करने के लिए उपयोगिता।
type: docs
weight: 230
url: /hi/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

मेश से/तक अंधा वॉटरमार्क एन्कोड/डिकोड करने के लिए उपयोगिता। **Remarks:** दोनों [Watermark](../../com.aspose.threed/watermark) और [Watermark](../../com.aspose.threed/watermark) लाइसेंस जांच करेंगे। ट्रायल उपयोग में अपवाद फेंका जाएगा, आप [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) का उपयोग करके अपवाद को दबा सकते हैं, लेकिन यह यहाँ प्रतिबंध को हटाएगा नहीं। इन सुविधाओं को बिना किसी प्रतिबंध के उपयोग करने के लिए एक वैध लाइसेंस आवश्यक है। **Example:** निम्नलिखित कोड दिखाता है कि कैसे अंधा वॉटरमार्क को मेश में एन्कोड और डिकोड किया जाए।

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Methods

| Method | विवरण |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | मेश से वॉटरमार्क डिकोड करें |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | मेश से वॉटरमार्क डिकोड करें |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | पाठ को मेश के अंधे वॉटरमार्क में एन्कोड करें। |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | पाठ को मेश के अंधे वॉटरमार्क में एन्कोड करें। |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | पाठ को मेश के अंधे वॉटरमार्क में एन्कोड करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeWatermark(Mesh input) {#decodeWatermark-com.aspose.threed.Mesh-}
```
public static String decodeWatermark(Mesh input)
```


मेश से वॉटरमार्क डिकोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | वॉटरमार्क निकालने के लिए मेश |

**Returns:**
java.lang.String - अंधा वॉटरमार्क या null यदि कोई वॉटरमार्क डिकोड नहीं हुआ।
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


मेश से वॉटरमार्क डिकोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | वॉटरमार्क निकालने के लिए मेश |
| पासवर्ड | java.lang.String | वॉटरमार्क को डिक्रिप्ट करने का पासवर्ड |

**Returns:**
java.lang.String - अंधा वॉटरमार्क या null यदि कोई वॉटरमार्क डिकोड नहीं हुआ।
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


पाठ को मेश के अंधे वॉटरमार्क में एन्कोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | अंधा वॉटरमार्क एन्कोड करने के लिए मेश |
| पाठ | java.lang.String | मेश में एन्कोड करने के लिए पाठ |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password)
```


पाठ को मेश के अंधे वॉटरमार्क में एन्कोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | अंधा वॉटरमार्क एन्कोड करने के लिए मेश |
| पाठ | java.lang.String | मेश में एन्कोड करने के लिए पाठ |
| पासवर्ड | java.lang.String | वॉटरमार्क को सुरक्षित करने का पासवर्ड, यह वैकल्पिक है |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password, boolean permanent) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password, boolean permanent)
```


पाठ को मेश के अंधे वॉटरमार्क में एन्कोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | अंधा वॉटरमार्क एन्कोड करने के लिए मेश |
| पाठ | java.lang.String | मेश में एन्कोड करने के लिए पाठ |
| पासवर्ड | java.lang.String | वॉटरमार्क को सुरक्षित करने का पासवर्ड, यह वैकल्पिक है |
| स्थायी | boolean | स्थायी वॉटरमार्क को ओवरराइट या हटाया नहीं जाएगा। |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

