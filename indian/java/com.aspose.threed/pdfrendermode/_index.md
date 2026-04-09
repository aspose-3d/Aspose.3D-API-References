---
title: PdfRenderMode
second_title: Aspose.3D for Java API Reference
description: रेंडर मोड उस शैली को निर्दिष्ट करता है जिसमें 3D कला रेंडर की जाती है।
type: docs
weight: 289
url: /hi/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

रेंडर मोड उस शैली को निर्दिष्ट करता है जिसमें 3D कला रेंडर की जाती है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | प्रत्येक नोड के बाउंडिंग बॉक्स किनारों को प्रदर्शित करता है, जो उस नोड के स्थानीय निर्देशांक स्थान के अक्षों के साथ संरेखित होते हैं। |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | किनारों को एकल रंग में प्रदर्शित करता है, हालांकि पीछे की ओर मुख वाले और अस्पष्ट किनारों को हटा देता है। |
| [ILLUSTRATION](#ILLUSTRATION) | सतहों के साथ सिल्हूट किनारों को प्रदर्शित करता है, अस्पष्ट रेखाओं को हटाता है। |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | प्रकाशित और टेक्सचरयुक्त सतहों के साथ सिल्हूट किनारों को प्रदर्शित करता है और कलाकृति के कम प्रकाशित क्षेत्रों को हटाने के लिए अतिरिक्त उत्सर्जक पद जोड़ता है। |
| [SHADED_VERTICES](#SHADED-VERTICES) | केवल शीर्ष बिंदुओं को प्रदर्शित करता है, हालांकि उनके शीर्ष रंग का उपयोग करता है और प्रकाश लागू करता है। |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | केवल किनारों को प्रदर्शित करता है, हालांकि उनके दो शीर्ष बिंदुओं के बीच रंग का अंतरण करता है और प्रकाश लागू करता है। |
| [SOLID](#SOLID) | टेक्सचरयुक्त और प्रकाशित ज्यामितीय आकारों को प्रदर्शित करता है। |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | प्रकाशित और टेक्सचरयुक्त सतहों के साथ सिल्हूट किनारों को प्रदर्शित करता है, अस्पष्ट रेखाओं को हटाता है। |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | टेक्सचरयुक्त और प्रकाशित ज्यामितीय आकारों (त्रिभुज) को उनके ऊपर एकल रंग के किनारों के साथ प्रदर्शित करता है। |
| [TRANSPARENT](#TRANSPARENT) | टेक्सचरयुक्त और प्रकाशित ज्यामितीय आकारों (त्रिभुज) को अतिरिक्त पारदर्शिता स्तर के साथ प्रदर्शित करता है। |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | प्रत्येक नोड के बाउंडिंग बॉक्स के चेहरों को प्रदर्शित करता है, जो उस नोड के स्थानीय निर्देशांक स्थान के अक्षों के साथ संरेखित होते हैं, अतिरिक्त पारदर्शिता स्तर के साथ। |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | प्रत्येक नोड के बाउंडिंग बॉक्स के किनारों और चेहरों को प्रदर्शित करता है, जो उस नोड के स्थानीय निर्देशांक स्थान के अक्षों के साथ संरेखित होते हैं, अतिरिक्त पारदर्शिता स्तर के साथ। |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | टेक्सचरयुक्त और प्रकाशित ज्यामितीय आकारों (त्रिभुज) को अतिरिक्त पारदर्शिता स्तर के साथ, उनके ऊपर एकल रंग के अपारदर्शी किनारों के साथ प्रदर्शित करता है। |
| [VERTICES](#VERTICES) | केवल शीर्ष बिंदुओं को एकल रंग में प्रदर्शित करता है। |
| [WIREFRAME](#WIREFRAME) | केवल किनारों को एकल रंग में प्रदर्शित करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


प्रत्येक नोड के बाउंडिंग बॉक्स किनारों को प्रदर्शित करता है, जो उस नोड के स्थानीय निर्देशांक स्थान के अक्षों के साथ संरेखित होते हैं।

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


किनारों को एकल रंग में प्रदर्शित करता है, हालांकि पीछे की ओर मुख वाले और अस्पष्ट किनारों को हटा देता है।

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


सतहों के साथ सिल्हूट किनारों को प्रदर्शित करता है, अस्पष्ट रेखाओं को हटाता है।

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


प्रकाशित और टेक्सचरयुक्त सतहों के साथ सिल्हूट किनारों को प्रदर्शित करता है और कलाकृति के कम प्रकाशित क्षेत्रों को हटाने के लिए अतिरिक्त उत्सर्जक पद जोड़ता है।

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


केवल शीर्ष बिंदुओं को प्रदर्शित करता है, हालांकि उनके शीर्ष रंग का उपयोग करता है और प्रकाश लागू करता है।

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


केवल किनारों को प्रदर्शित करता है, हालांकि उनके दो शीर्ष बिंदुओं के बीच रंग का अंतरण करता है और प्रकाश लागू करता है।

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


टेक्सचरयुक्त और प्रकाशित ज्यामितीय आकारों को प्रदर्शित करता है।

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


प्रकाशित और टेक्सचरयुक्त सतहों के साथ सिल्हूट किनारों को प्रदर्शित करता है, अस्पष्ट रेखाओं को हटाता है।

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


टेक्सचरयुक्त और प्रकाशित ज्यामितीय आकारों (त्रिभुज) को उनके ऊपर एकल रंग के किनारों के साथ प्रदर्शित करता है।

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


टेक्सचरयुक्त और प्रकाशित ज्यामितीय आकारों (त्रिभुज) को अतिरिक्त पारदर्शिता स्तर के साथ प्रदर्शित करता है।

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


प्रत्येक नोड के बाउंडिंग बॉक्स के चेहरों को प्रदर्शित करता है, जो उस नोड के स्थानीय निर्देशांक स्थान के अक्षों के साथ संरेखित होते हैं, अतिरिक्त पारदर्शिता स्तर के साथ।

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


प्रत्येक नोड के बाउंडिंग बॉक्स के किनारों और चेहरों को प्रदर्शित करता है, जो उस नोड के स्थानीय निर्देशांक स्थान के अक्षों के साथ संरेखित होते हैं, अतिरिक्त पारदर्शिता स्तर के साथ।

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


टेक्सचरयुक्त और प्रकाशित ज्यामितीय आकारों (त्रिभुज) को अतिरिक्त पारदर्शिता स्तर के साथ, उनके ऊपर एकल रंग के अपारदर्शी किनारों के साथ प्रदर्शित करता है।

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


केवल शीर्ष बिंदुओं को एकल रंग में प्रदर्शित करता है।

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


केवल किनारों को एकल रंग में प्रदर्शित करता है।

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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

