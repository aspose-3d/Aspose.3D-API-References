---
title: "MathUtils"
second_title: "Aspose.3D for Java API Referansı"
description: "Kullanışlı matematiksel yardımcı programların bir seti."
type: docs
weight: 99
url: /tr/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

Kullanışlı matematiksel yardımcı programların bir seti.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | Değeri [min, max] aralığına sınırlayın |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | p noktasının (p0, p1, p2) üçgeninin içinde olup olmadığını kontrol et |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Işının (origin, dir) çizgi segmenti (start, end) ile kesişip kesişmediğini kontrol et |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | [Vector3](../../com.aspose.threed/vector3) nesnesini radyandan dereceye dönüştür. |
| [toDegree(double radian)](#toDegree-double-) | Bir sayıyı radyandan dereceye dönüştür |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | Bir sayıyı radyandan dereceye dönüştür |
| [toDegree(float radian)](#toDegree-float-) | Bir sayıyı radyandan dereceye dönüştür |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | [Vector3](../../com.aspose.threed/vector3) nesnesini dereceden radyana dönüştür |
| [toRadian(double degree)](#toRadian-double-) | Bir sayıyı dereceden radyana dönüştür |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | Bir vektörü dereceden radyana dönüştür |
| [toRadian(float degree)](#toRadian-float-) | Bir sayıyı dereceden radyana dönüştür |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


Değeri [min, max] aralığına sınırlayın

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| val | double | Sınırlanacak değer. |
| min | double | Minimum değer. |
| max | double | Maximum değer. |

**Returns:**
double - [min, max] arasındaki değer **Example:**

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


p noktasının (p0, p1, p2) üçgeninin içinde olup olmadığını kontrol et

**Parameters:**
| Parametre | Tür | Açıklama |
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


Işının (origin, dir) çizgi segmenti (start, end) ile kesişip kesişmediğini kontrol et

**Parameters:**
| Parametre | Tür | Açıklama |
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


[Vector3](../../com.aspose.threed/vector3) nesnesini radyandan dereceye dönüştür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | Radyan değeri. |

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


Bir sayıyı radyandan dereceye dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radyan | double | Radyan değeri. |

**Returns:**
double - Derece değeri. **Example:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


Bir sayıyı radyandan dereceye dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | Radyan değerindeki x bileşeni. |
| y | double | Radyan değerindeki y bileşeni. |
| z | double | Radyan değerindeki z bileşeni. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


Bir sayıyı radyandan dereceye dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| radyan | float | Radyan değeri. |

**Returns:**
float - Derece değeri. **Example:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


[Vector3](../../com.aspose.threed/vector3) nesnesini dereceden radyana dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | Derece değeri. |

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


Bir sayıyı dereceden radyana dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| derece | double | Derece değeri. |

**Returns:**
double - Radyan değeri. **Example:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


Bir vektörü dereceden radyana dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | Derece değerindeki x bileşeni. |
| y | double | Derece değerindeki y bileşeni. |
| z | double | Derece değerindeki z bileşeni. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


Bir sayıyı dereceden radyana dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| derece | float | Derece değeri. |

**Returns:**
float - Radyan değeri. **Example:**

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

