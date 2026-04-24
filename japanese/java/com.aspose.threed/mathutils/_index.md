---
title: MathUtils
second_title: Aspose.3D for Java API リファレンス
description: 便利な数学ユーティリティのセットです。
type: docs
weight: 99
url: /ja/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

便利な数学ユーティリティのセットです。
## Methods

| Method | 説明 |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | 値を範囲 [min, max] にクランプします |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 点 p が三角形 (p0, p1, p2) の内部にあるか確認します |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 光線 (origin, dir) が線分 (start, end) と交差するか確認します |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | ラジアンから度へ [Vector3](../../com.aspose.threed/vector3) を変換します。 |
| [toDegree(double radian)](#toDegree-double-) | ラジアンから度へ数値を変換します |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | ラジアンから度へ数値を変換します |
| [toDegree(float radian)](#toDegree-float-) | ラジアンから度へ数値を変換します |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | 度からラジアンへ [Vector3](../../com.aspose.threed/vector3) を変換します |
| [toRadian(double degree)](#toRadian-double-) | 度からラジアンへ数値を変換する |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | 度からラジアンへベクトルを変換する |
| [toRadian(float degree)](#toRadian-float-) | 度からラジアンへ数値を変換する |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


値を範囲 [min, max] にクランプします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| val | double | クランプする値。 |
| min | double | 最小値。 |
| max | double | 最大値。 |

**Returns:**
double - [min, max] の間の値 **Example:**

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| Parameter | Type | 説明 |
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


点 p が三角形 (p0, p1, p2) の内部にあるか確認します

**Parameters:**
| Parameter | Type | 説明 |
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


光線 (origin, dir) が線分 (start, end) と交差するか確認します

**Parameters:**
| Parameter | Type | 説明 |
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


ラジアンから度へ [Vector3](../../com.aspose.threed/vector3) を変換します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | ラジアンの値。 |

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


ラジアンから度へ数値を変換します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ラジアン | double | ラジアンの値。 |

**Returns:**
double - 度の値。 **Example:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


ラジアンから度へ数値を変換します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double | ラジアン値の x 成分。 |
| y | double | ラジアン値の y 成分。 |
| z | double | ラジアン値の z 成分。 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


ラジアンから度へ数値を変換します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ラジアン | float | ラジアンの値。 |

**Returns:**
float - 度の値。 **Example:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


度からラジアンへ [Vector3](../../com.aspose.threed/vector3) を変換します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | 度の値。 |

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


度からラジアンへ数値を変換する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 度 | double | 度の値。 |

**Returns:**
double - ラジアンの値。 **Example:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


度からラジアンへベクトルを変換する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double | 度値の x 成分。 |
| y | double | 度値の y 成分。 |
| z | double | 度値の z 成分。 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


度からラジアンへ数値を変換する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 度 | float | 度の値。 |

**Returns:**
float - ラジアンの値。 **Example:**

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

