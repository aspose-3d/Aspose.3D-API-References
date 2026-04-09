---
title: NurbsDirection
second_title: Aspose.3D for Java API Reference
description: एक 3D  में दो दिशा होती हैं,  और ,  प्रत्येक दिशा के डेटा को परिभाषित करता है।
type: docs
weight: 113
url: /hi/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

एक 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) में दो दिशा होती हैं, [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) और [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), और [NurbsDirection](../../com.aspose.threed/nurbsdirection) प्रत्येक दिशा के डेटा को परिभाषित करता है। एक दिशा वास्तव में एक NURBS कर्व है, जिसका मतलब है कि यह अपने [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors) और भारित कंट्रोल पॉइंट्स के सेट (जो [NurbsSurface](../../com.aspose.threed/nurbssurface) में परिभाषित हैं) द्वारा भी परिभाषित होती है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | एक नया [NurbsDirection](../../com.aspose.threed/nurbsdirection) का इंस्टेंस बनाएं |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | वर्तमान दिशा में नियंत्रण बिंदुओं की गिनती प्राप्त करता है। |
| [getDegree()](#getDegree--) | NURBS वक्र की डिग्री प्राप्त करता है, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है |
| [getDivisions()](#getDivisions--) | वर्तमान दिशा में आसन्न कंट्रोल पॉइंट्स के बीच विभाजनों की संख्या प्राप्त करता है। |
| [getKnotVectors()](#getKnotVectors--) | नॉट वेक्टर प्राप्त करता है, यह पैरामीटर मानों की एक श्रृंखला है जो निर्धारित करती है कि नियंत्रण बिंदु NURBS वक्र को कहाँ और कैसे प्रभावित करते हैं। |
| [getMultiplicity()](#getMultiplicity--) | बहुलता प्राप्त करता है। |
| [getOrder()](#getOrder--) | NURBS वक्र का क्रम प्राप्त करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र के किसी भी बिंदु को प्रभावित करते हैं। |
| [getType()](#getType--) | वर्तमान दिशा का प्रकार प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | वर्तमान दिशा में नियंत्रण बिंदुओं की गिनती सेट करता है। |
| [setDegree(int value)](#setDegree-int-) | NURBS वक्र की डिग्री सेट करता है, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है |
| [setDivisions(int value)](#setDivisions-int-) | वर्तमान दिशा में आसन्न कंट्रोल पॉइंट्स के बीच विभाजनों की संख्या सेट करता है। |
| [setOrder(int value)](#setOrder-int-) | NURBS वक्र का क्रम सेट करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र के किसी भी बिंदु को प्रभावित करते हैं। |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | वर्तमान दिशा का प्रकार सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


एक नया [NurbsDirection](../../com.aspose.threed/nurbsdirection) का इंस्टेंस बनाएं

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
### getCount() {#getCount--}
```
public int getCount()
```


वर्तमान दिशा में नियंत्रण बिंदुओं की गिनती प्राप्त करता है।

**Returns:**
int - वर्तमान दिशा में नियंत्रण बिंदुओं की गिनती।
### getDegree() {#getDegree--}
```
public int getDegree()
```


NURBS वक्र की डिग्री प्राप्त करता है, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है

**Returns:**
int - NURBS वक्र की डिग्री, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


वर्तमान दिशा में आसन्न कंट्रोल पॉइंट्स के बीच विभाजनों की संख्या प्राप्त करता है।

**Returns:**
इंट - वर्तमान दिशा में आसन्न कंट्रोल पॉइंट्स के बीच विभाजनों की संख्या।
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


नॉट वेक्टर प्राप्त करता है, यह पैरामीटर मानों की एक श्रृंखला है जो निर्धारित करती है कि नियंत्रण बिंदु NURBS वक्र को कहाँ और कैसे प्रभावित करते हैं।

**Returns:**
java.util.List<java.lang.Double> - नॉट वेक्टर, यह पैरामीटर मानों की एक श्रृंखला है जो निर्धारित करती है कि नियंत्रण बिंदु NURBS वक्र को कहाँ और कैसे प्रभावित करते हैं।
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


बहुलता प्राप्त करता है।

**Returns:**
java.util.List<java.lang.Integer> - बहुलता।
### getOrder() {#getOrder--}
```
public int getOrder()
```


NURBS वक्र का क्रम प्राप्त करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र के किसी भी बिंदु को प्रभावित करते हैं।

**Returns:**
int - NURBS वक्र का क्रम, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या निर्धारित करता है जो वक्र पर किसी भी बिंदु को प्रभावित करते हैं।
### getType() {#getType--}
```
public NurbsType getType()
```


वर्तमान दिशा का प्रकार प्राप्त करता है।

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
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




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


वर्तमान दिशा में नियंत्रण बिंदुओं की गिनती सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


NURBS वक्र की डिग्री सेट करता है, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


वर्तमान दिशा में आसन्न कंट्रोल पॉइंट्स के बीच विभाजनों की संख्या सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


NURBS वक्र का क्रम सेट करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र के किसी भी बिंदु को प्रभावित करते हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


वर्तमान दिशा का प्रकार सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | नया मान |

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

