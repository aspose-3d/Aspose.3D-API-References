---
title: MathUtils
second_title: Referensi API Aspose.3D untuk Java
description: Sekumpulan utilitas matematika yang berguna.
type: docs
weight: 99
url: /id/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

Sekumpulan utilitas matematika yang berguna.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | Batasi nilai ke rentang [min, max] |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Periksa apakah titik p berada di dalam segitiga (p0, p1, p2) |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Periksa apakah sinar (origin, dir) berpotongan dengan segmen garis (start, end) |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | Konversi sebuah [Vector3](../../com.aspose.threed/vector3) dari radian ke derajat. |
| [toDegree(double radian)](#toDegree-double-) | Konversi sebuah angka dari radian ke derajat |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | Konversi sebuah angka dari radian ke derajat |
| [toDegree(float radian)](#toDegree-float-) | Konversi sebuah angka dari radian ke derajat |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | Konversi sebuah [Vector3](../../com.aspose.threed/vector3) dari derajat ke radian |
| [toRadian(double degree)](#toRadian-double-) | Konversi sebuah angka dari derajat ke radian |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | Konversi sebuah vektor dari derajat ke radian |
| [toRadian(float degree)](#toRadian-float-) | Konversi sebuah angka dari derajat ke radian |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


Batasi nilai ke rentang [min, max]

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| val | double | Nilai untuk dipatok. |
| min | double | Nilai minimum. |
| max | double | Nilai maksimum. |

**Returns:**
double - Nilai antara [min, max] **Example:**

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Periksa apakah titik p berada di dalam segitiga (p0, p1, p2)

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Periksa apakah sinar (origin, dir) berpotongan dengan segmen garis (start, end)

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Konversi sebuah [Vector3](../../com.aspose.threed/vector3) dari radian ke derajat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | Nilai radian. |

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


Konversi sebuah angka dari radian ke derajat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radian | double | Nilai radian. |

**Returns:**
double - Nilai derajat. **Example:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


Konversi sebuah angka dari radian ke derajat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | Komponen x dalam nilai radian. |
| y | double | Komponen y dalam nilai radian. |
| z | double | Komponen z dalam nilai radian. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


Konversi sebuah angka dari radian ke derajat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radian | float | Nilai radian. |

**Returns:**
float - Nilai derajat. **Example:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


Konversi sebuah [Vector3](../../com.aspose.threed/vector3) dari derajat ke radian

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | Nilai derajat. |

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


Konversi sebuah angka dari derajat ke radian

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| derajat | double | Nilai derajat. |

**Returns:**
double - Nilai radian. **Example:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


Konversi sebuah vektor dari derajat ke radian

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | Komponen x dalam nilai derajat. |
| y | double | Komponen y dalam nilai derajat. |
| z | double | Komponen z dalam nilai derajat. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


Konversi sebuah angka dari derajat ke radian

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| derajat | float | Nilai derajat. |

**Returns:**
float - Nilai radian. **Example:**

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

