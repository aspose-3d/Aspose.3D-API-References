---
title: NurbsCurve
second_title: Aspose.3D for Java API Reference
description: NURBS curve एक वक्र है जो NURBSNon-uniform rational basis spline द्वारा दर्शाया जाता है। एक NURBS curve को उसके एक सेट ऑफ weighted बिंदुओं और एक ... द्वारा परिभाषित किया जाता है। नियंत्रण बिंदु में w घटक को नियंत्रण बिंदु के वजन के रूप में उपयोग किया जाता है, चाहे वह ... हो या ...
type: docs
weight: 112
url: /hi/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Constructors

| Constructor | विवरण |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | [NurbsCurve](../../com.aspose.threed/nurbscurve) क्लास का नया उदाहरण प्रारंभ करता है। |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | [NurbsCurve](../../com.aspose.threed/nurbscurve) क्लास का नया उदाहरण प्रारंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | NURBS वक्र का मूल्यांकन करें |
| [evaluate(int steps)](#evaluate-int-) | NURBS वक्र का मूल्यांकन करें |
| [evaluateAt(double u)](#evaluateAt-double-) | निर्दिष्ट स्थिति पर वक्र बिंदु का मूल्यांकन करें |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | रेखा का रंग प्राप्त करता है, डिफ़ॉल्ट मान सफ़ेद (1, 1, 1) है |
| [getControlPoints()](#getControlPoints--) | सभी नियंत्रण बिंदु प्राप्त करता है |
| [getCurveType()](#getCurveType--) | वक्र का प्रकार प्राप्त करता है। |
| [getDegree()](#getDegree--) | NURBS वक्र की डिग्री प्राप्त करता है, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है |
| [getDimension()](#getDimension--) | वक्र का आयाम प्राप्त करता है। |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getKnotVectors()](#getKnotVectors--) | नॉट वेक्टर प्राप्त करता है, यह पैरामीटर मानों की एक श्रृंखला है जो निर्धारित करती है कि नियंत्रण बिंदु NURBS वक्र को कहाँ और कैसे प्रभावित करते हैं। |
| [getMultiplicity()](#getMultiplicity--) | बहुलता प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getOrder()](#getOrder--) | NURBS वक्र का क्रम प्राप्त करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र के किसी भी बिंदु को प्रभावित करते हैं। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRational()](#getRational--) | यह निर्धारित करता है कि यह तर्कसंगत है या नहीं, यह मान दर्शाता है कि यह [NurbsCurve](../../com.aspose.threed/nurbscurve) तर्कसंगत स्प्लाइन है या गैर-तर्कसंगत स्प्लाइन। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | रेखा का रंग सेट करता है, डिफ़ॉल्ट मान सफ़ेद (1, 1, 1) है |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | वक्र का प्रकार सेट करता है। |
| [setDegree(int value)](#setDegree-int-) | NURBS वक्र की डिग्री सेट करता है, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | वक्र का आयाम सेट करता है। |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setOrder(int value)](#setOrder-int-) | NURBS वक्र का क्रम सेट करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र के किसी भी बिंदु को प्रभावित करते हैं। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRational(boolean value)](#setRational-boolean-) | यह निर्धारित करता है कि यह तर्कसंगत है या नहीं, यह मान दर्शाता है कि यह [NurbsCurve](../../com.aspose.threed/nurbscurve) तर्कसंगत स्प्लाइन है या गैर-तर्कसंगत स्प्लाइन। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


[NurbsCurve](../../com.aspose.threed/nurbscurve) क्लास का नया उदाहरण प्रारंभ करता है।

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


[NurbsCurve](../../com.aspose.threed/nurbscurve) क्लास का नया उदाहरण प्रारंभ करता है।

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


NURBS वक्र का मूल्यांकन करें

**Returns:**
com.aspose.threed.Vector4[] - वक्र में बिंदु
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


NURBS वक्र का मूल्यांकन करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| कदम | int | दो निकटवर्ती नॉट्स के बीच मूल्यांकन आवृत्ति, डिफ़ॉल्ट मान 20 है |

**Returns:**
com.aspose.threed.Vector4[] - वक्र में बिंदु
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


निर्दिष्ट स्थिति पर वक्र बिंदु का मूल्यांकन करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| u | double | वक्र में स्थिति, 0 और 1 के बीच |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है।

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


रेखा का रंग प्राप्त करता है, डिफ़ॉल्ट मान सफ़ेद (1, 1, 1) है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


सभी नियंत्रण बिंदु प्राप्त करता है

**Returns:**
java.util.List<com.aspose.threed.Vector4> - सभी नियंत्रण बिंदु
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


वक्र का प्रकार प्राप्त करता है।

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


NURBS वक्र की डिग्री प्राप्त करता है, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है

**Returns:**
int - NURBS वक्र की डिग्री, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


वक्र का आयाम प्राप्त करता है।

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है।

**Returns:**
बूलियन - निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में।
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
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getOrder() {#getOrder--}
```
public int getOrder()
```


NURBS वक्र का क्रम प्राप्त करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र के किसी भी बिंदु को प्रभावित करते हैं।

**Returns:**
int - NURBS वक्र का क्रम, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या निर्धारित करता है जो वक्र पर किसी भी बिंदु को प्रभावित करते हैं।
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - सभी पैरेंट नोड्स, एक इकाई को ज्यामिति इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है
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
### getRational() {#getRational--}
```
public boolean getRational()
```


जाँचता है कि यह तर्कसंगत है या नहीं, यह मान दर्शाता है कि यह [NurbsCurve](../../com.aspose.threed/nurbscurve) तर्कसंगत स्प्लाइन है या गैर‑तर्कसंगत स्प्लाइन। गैर‑तर्कसंगत B‑spline तर्कसंगत B‑splines का एक विशेष मामला है।

**Returns:**
boolean - यह तर्कसंगत है या नहीं, यह मान दर्शाता है कि यह [NurbsCurve](../../com.aspose.threed/nurbscurve) तर्कसंगत स्प्लाइन है या गैर‑तर्कसंगत स्प्लाइन। गैर‑तर्कसंगत B‑spline तर्कसंगत B‑splines का एक विशेष मामला है।
### getScene() {#getScene--}
```
public Scene getScene()
```


उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


रेखा का रंग सेट करता है, डिफ़ॉल्ट मान सफ़ेद (1, 1, 1) है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


वक्र का प्रकार सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | नया मान |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


NURBS वक्र की डिग्री सेट करता है, डिग्री को क्रम - 1 के रूप में परिभाषित किया जाता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


वक्र का आयाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | नया मान **Remarks:** एक [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) वक्र के लिए, नियंत्रण बिंदु में z घटक उपयोग नहीं किया जाता है। |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


NURBS वक्र का क्रम सेट करता है, यह निकटवर्ती नियंत्रण बिंदुओं की संख्या को परिभाषित करता है जो वक्र के किसी भी बिंदु को प्रभावित करते हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

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

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


सेट करता है कि यह तर्कसंगत है या नहीं, यह मान दर्शाता है कि यह [NurbsCurve](../../com.aspose.threed/nurbscurve) तर्कसंगत स्प्लाइन है या गैर‑तर्कसंगत स्प्लाइन। गैर‑तर्कसंगत B‑spline तर्कसंगत B‑splines का एक विशेष मामला है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

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

