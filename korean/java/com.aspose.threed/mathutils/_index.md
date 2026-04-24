---
title: MathUtils
second_title: Aspose.3D for Java API 레퍼런스
description: 유용한 수학 유틸리티 집합.
type: docs
weight: 99
url: /ko/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

유용한 수학 유틸리티 집합.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | 값을 [min, max] 범위로 제한합니다 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 점 p가 삼각형 (p0, p1, p2) 내부에 있는지 확인합니다 |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 광선 (origin, dir)이 선분 (start, end)과 교차하는지 확인합니다 |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | [Vector3](../../com.aspose.threed/vector3)를 라디안에서 도(degree)로 변환합니다. |
| [toDegree(double radian)](#toDegree-double-) | 숫자를 라디안에서 도(degree)로 변환합니다 |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | 숫자를 라디안에서 도(degree)로 변환합니다 |
| [toDegree(float radian)](#toDegree-float-) | 숫자를 라디안에서 도(degree)로 변환합니다 |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | [Vector3](../../com.aspose.threed/vector3)를 도(degree)에서 라디안으로 변환합니다 |
| [toRadian(double degree)](#toRadian-double-) | Convert a number from degree to radian |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | Convert a vector from degree to radian |
| [toRadian(float degree)](#toRadian-float-) | Convert a number from degree to radian |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


값을 [min, max] 범위로 제한합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| val | double | Value to clamp. |
| min | double | Minimum value. |
| max | double | Maximum value. |

**Returns:**
double - The value between [min, max] **Example:**

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


점 p가 삼각형 (p0, p1, p2) 내부에 있는지 확인합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


광선 (origin, dir)이 선분 (start, end)과 교차하는지 확인합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


[Vector3](../../com.aspose.threed/vector3)를 라디안에서 도(degree)로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | The radian value. |

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


숫자를 라디안에서 도(degree)로 변환합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| radian | double | The radian value. |

**Returns:**
double - The degree value. **Example:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


숫자를 라디안에서 도(degree)로 변환합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | The x component in radian value. |
| y | double | The y component in radian value. |
| z | double | The z component in radian value. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


숫자를 라디안에서 도(degree)로 변환합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| radian | float | The radian value. |

**Returns:**
float - The degree value. **Example:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


[Vector3](../../com.aspose.threed/vector3)를 도(degree)에서 라디안으로 변환합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | The degree value. |

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


Convert a number from degree to radian

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| degree | double | The degree value. |

**Returns:**
double - The radian value. **Example:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


Convert a vector from degree to radian

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | The x component in degree value. |
| y | double | The y component in degree value. |
| z | double | The z component in degree value. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


Convert a number from degree to radian

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| degree | float | The degree value. |

**Returns:**
float - The radian value. **Example:**

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

