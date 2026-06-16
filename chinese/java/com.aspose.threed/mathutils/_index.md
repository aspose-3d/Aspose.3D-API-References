---
title: "MathUtils"
second_title: "Aspose.3D for Java API 参考"
description: "一组有用的数学实用工具。"
type: docs
weight: 99
url: /zh/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

一组有用的数学实用工具。
## 方法

| 方法 | 描述 |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | 将值限制在范围 [min, max] 内 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 检查点 p 是否位于三角形 (p0, p1, p2) 内 |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 检查射线 (origin, dir) 是否与线段 (start, end) 相交 |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | 将 [Vector3](../../com.aspose.threed/vector3) 从弧度转换为度。 |
| [toDegree(double radian)](#toDegree-double-) | 将数字从弧度转换为度 |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | 将数字从弧度转换为度 |
| [toDegree(float radian)](#toDegree-float-) | 将数字从弧度转换为度 |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | 将 [Vector3](../../com.aspose.threed/vector3) 从度转换为弧度 |
| [toRadian(double degree)](#toRadian-double-) | 将数字从度转换为弧度 |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | 将向量从度转换为弧度 |
| [toRadian(float degree)](#toRadian-float-) | 将数字从度转换为弧度 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


将值限制在范围 [min, max] 内

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| val | double | 要限制的值。 |
| min | double | 最小值。 |
| max | double | 最大值。 |

**Returns:**
double - 位于 [min, max] 之间的值 **示例:**

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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


检查点 p 是否位于三角形 (p0, p1, p2) 内

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | [Vector2](../../com.aspose.threed/vector2) |  |
| p0 | [Vector2](../../com.aspose.threed/vector2) |  |
| p1 | [Vector2](../../com.aspose.threed/vector2) |  |
| p2 | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
布尔
### rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b) {#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)
```


检查射线 (origin, dir) 是否与线段 (start, end) 相交

**Parameters:**
| 参数 | 类型 | 描述 |
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


将 [Vector3](../../com.aspose.threed/vector3) 从弧度转换为度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | 弧度值。 |

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


将数字从弧度转换为度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 弧度 | double | 弧度值。 |

**Returns:**
double - 角度值。 **示例:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


将数字从弧度转换为度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | 弧度值中的 x 分量。 |
| y | double | 弧度值中的 y 分量。 |
| z | double | 弧度值中的 z 分量。 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


将数字从弧度转换为度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 弧度 | float | 弧度值。 |

**Returns:**
float - 角度值。 **示例:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


将 [Vector3](../../com.aspose.threed/vector3) 从度转换为弧度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | 度值。 |

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


将数字从度转换为弧度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 度 | double | 度值。 |

**Returns:**
double - 弧度值。 **示例:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


将向量从度转换为弧度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | x 分量的度数值。 |
| y | double | y 分量的度数值。 |
| z | double | z 分量的度数值。 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


将数字从度转换为弧度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 度 | float | 度值。 |

**Returns:**
float - 弧度值。 **示例:**

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

