---
title: MathUtils
second_title: Aspose.3D for Java API Reference
description: उपयोगी गणितीय उपयोगिताओं का एक सेट।
type: docs
weight: 99
url: /hi/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

उपयोगी गणितीय उपयोगिताओं का एक सेट।
## Methods

| Method | विवरण |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | मान को रेंज [min, max] में क्लैंप करें |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | जाँचें कि बिंदु p त्रिभुज (p0, p1, p2) के अंदर है या नहीं |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | जाँचें कि किरण (origin, dir) रेखा खंड (start, end) के साथ प्रतिच्छेद करती है या नहीं |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | [Vector3](../../com.aspose.threed/vector3) को रेडियन से डिग्री में बदलें। |
| [toDegree(double radian)](#toDegree-double-) | संख्या को रेडियन से डिग्री में बदलें |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | संख्या को रेडियन से डिग्री में बदलें |
| [toDegree(float radian)](#toDegree-float-) | संख्या को रेडियन से डिग्री में बदलें |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | [Vector3](../../com.aspose.threed/vector3) को डिग्री से रेडियन में बदलें |
| [toRadian(double degree)](#toRadian-double-) | डिग्री से रेडियन में संख्या परिवर्तित करें |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | डिग्री से रेडियन में वेक्टर परिवर्तित करें |
| [toRadian(float degree)](#toRadian-float-) | डिग्री से रेडियन में संख्या परिवर्तित करें |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


मान को रेंज [min, max] में क्लैंप करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| val | double | क्लैंप करने के लिए मान। |
| min | double | न्यूनतम मान। |
| max | double | अधिकतम मान। |

**Returns:**
double - मान [min, max] के बीच **Example:**

```
double val = 195;
     //Clamp value to [0, 100]
     double clampedValue = MathUtils.clamp(val, 0, 100);
     //This will output 100
     System.out.printf("Value = %d", val);
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
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| p0 | [Vector2](../../com.aspose.threed/vector2) |  |
| d0 | [Vector2](../../com.aspose.threed/vector2) |  |
| p1 | [Vector2](../../com.aspose.threed/vector2) |  |
| d1 | [Vector2](../../com.aspose.threed/vector2) |  |
| results | [Vector2\[\]](../../com.aspose.threed/vector2) |  |

**Returns:**
int
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




### pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2) {#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)
```


जाँचें कि बिंदु p त्रिभुज (p0, p1, p2) के अंदर है या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| p | [Vector2](../../com.aspose.threed/vector2) |  |
| p0 | [Vector2](../../com.aspose.threed/vector2) |  |
| p1 | [Vector2](../../com.aspose.threed/vector2) |  |
| p2 | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
boolean
### rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b) {#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)
```


जाँचें कि किरण (origin, dir) रेखा खंड (start, end) के साथ प्रतिच्छेद करती है या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| origin | [Vector2](../../com.aspose.threed/vector2) |  |
| dir | [Vector2](../../com.aspose.threed/vector2) |  |
| a | [Vector2](../../com.aspose.threed/vector2) |  |
| b | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### toDegree(Vector3 radian) {#toDegree-com.aspose.threed.Vector3-}
```
public static Vector3 toDegree(Vector3 radian)
```


[Vector3](../../com.aspose.threed/vector3) को रेडियन से डिग्री में बदलें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | रेडियन मान। |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value. **Example:**

```
Vector3 degrees = MathUtils.toDegree(new Vector3(0.34, 0.9, 0.2));
     System.out.printf("Degrees = %s", degrees);
```
### toDegree(double radian) {#toDegree-double-}
```
public static double toDegree(double radian)
```


संख्या को रेडियन से डिग्री में बदलें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| रेडियन | double | रेडियन मान। |

**Returns:**
double - डिग्री मान। **Example:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


संख्या को रेडियन से डिग्री में बदलें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double | रेडियन मान में x घटक। |
| y | double | रेडियन मान में y घटक। |
| z | double | रेडियन मान में z घटक। |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


संख्या को रेडियन से डिग्री में बदलें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| रेडियन | फ़्लोट | रेडियन मान। |

**Returns:**
float - डिग्री मान। **Example:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


[Vector3](../../com.aspose.threed/vector3) को डिग्री से रेडियन में बदलें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | डिग्री मान। |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value. **Example:**

```
Vector3 radians = MathUtils.toRadian(new Vector3(90, 134, 0));
     System.out.printf("Radians = %s", radians);
```
### toRadian(double degree) {#toRadian-double-}
```
public static double toRadian(double degree)
```


डिग्री से रेडियन में संख्या परिवर्तित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डिग्री | double | डिग्री मान। |

**Returns:**
double - रेडियन मान। **Example:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


डिग्री से रेडियन में वेक्टर परिवर्तित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double | डिग्री मान में x घटक। |
| y | double | डिग्री मान में y घटक। |
| z | double | डिग्री मान में z घटक। |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


डिग्री से रेडियन में संख्या परिवर्तित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डिग्री | फ़्लोट | डिग्री मान। |

**Returns:**
float - रेडियन मान। **Example:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
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

