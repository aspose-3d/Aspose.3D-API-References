---
title: "MathUtils"
second_title: "مرجع Aspose.3D لـ Java API"
description: "مجموعة من الأدوات الرياضية المفيدة."
type: docs
weight: 99
url: /ar/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

مجموعة من الأدوات الرياضية المفيدة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | قيد القيمة إلى النطاق [min, max] |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | تحقق مما إذا كانت النقطة p داخل المثلث (p0, p1, p2) |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | تحقق مما إذا كان الشعاع (origin, dir) يتقاطع مع قطعة الخط (start, end) |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | تحويل [Vector3](../../com.aspose.threed/vector3) من الراديان إلى الدرجة. |
| [toDegree(double radian)](#toDegree-double-) | تحويل رقم من الراديان إلى الدرجة |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | تحويل رقم من الراديان إلى الدرجة |
| [toDegree(float radian)](#toDegree-float-) | تحويل رقم من الراديان إلى الدرجة |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | تحويل [Vector3](../../com.aspose.threed/vector3) من الدرجة إلى الراديان |
| [toRadian(double degree)](#toRadian-double-) | تحويل عدد من الدرجة إلى الراديان |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | تحويل متجه من الدرجة إلى الراديان |
| [toRadian(float degree)](#toRadian-float-) | تحويل عدد من الدرجة إلى الراديان |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


قيد القيمة إلى النطاق [min, max]

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| val | double | القيمة لتثبيتها. |
| min | double | القيمة الدنيا. |
| max | double | القيمة القصوى. |

**Returns:**
double - القيمة بين [min, max] **مثال:**

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| معامل | نوع | الوصف |
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


تحقق مما إذا كانت النقطة p داخل المثلث (p0, p1, p2)

**Parameters:**
| معامل | نوع | الوصف |
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


تحقق مما إذا كان الشعاع (origin, dir) يتقاطع مع قطعة الخط (start, end)

**Parameters:**
| معامل | نوع | الوصف |
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


تحويل [Vector3](../../com.aspose.threed/vector3) من الراديان إلى الدرجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | قيمة الراديان. |

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


تحويل رقم من الراديان إلى الدرجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| راديان | double | قيمة الراديان. |

**Returns:**
double - قيمة الدرجة. **مثال:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


تحويل رقم من الراديان إلى الدرجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | المكوّن x في قيمة الراديان. |
| y | double | المكوّن y في قيمة الراديان. |
| z | double | المكوّن z في قيمة الراديان. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


تحويل رقم من الراديان إلى الدرجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| راديان | float | قيمة الراديان. |

**Returns:**
float - قيمة الدرجة. **مثال:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


تحويل [Vector3](../../com.aspose.threed/vector3) من الدرجة إلى الراديان

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | قيمة الدرجة. |

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


تحويل عدد من الدرجة إلى الراديان

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| درجة | double | قيمة الدرجة. |

**Returns:**
double - قيمة الراديان. **مثال:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


تحويل متجه من الدرجة إلى الراديان

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | المكوّن x في قيمة الدرجة. |
| y | double | المكوّن y في قيمة الدرجة. |
| z | double | المكوّن z في قيمة الدرجة. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


تحويل عدد من الدرجة إلى الراديان

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| درجة | float | قيمة الدرجة. |

**Returns:**
float - قيمة الراديان. **مثال:**

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

