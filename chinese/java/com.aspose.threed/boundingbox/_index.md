---
title: "BoundingBox"
second_title: "Aspose.3D for Java API 参考"
description: "轴对齐的边界框 示例 以下代码展示了如何从 Entity 实例获取边界框。"
type: docs
weight: 24
url: /zh/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

轴对齐包围盒 **示例：** 以下代码展示了如何从 Entity 实例获取包围盒。

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 使用给定的最小角和最大角初始化有限的包围盒 |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | 使用给定的最小角和最大角初始化有限的包围盒 |
| [BoundingBox()](#BoundingBox--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | 用于检查它是否在当前边界框内部的边界框。 |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | 检查点 p 是否在边界框内部 |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定两个对象是否相等 |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | 从给定几何体构建边界框 |
| [getCenter()](#getCenter--) | 边界框的中心。 |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | 获取包围盒的范围。 |
| [getInfinite()](#getInfinite--) | 无限包围盒 |
| [getMaximum()](#getMaximum--) | 包围盒的最大角 |
| [getMinimum()](#getMinimum--) | 包围盒的最小角 |
| [getNull()](#getNull--) | 空包围盒 |
| [getSize()](#getSize--) | 边界框的大小 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码 |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | 将新盒合并到当前包围盒中。 |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | 将当前边界框与给定点合并 |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | 将当前边界框与给定点合并 |
| [merge(double x, double y, double z)](#merge-double-double-double-) | 将当前边界框与给定点合并 |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | 乘法运算符重载，新的边界框的最小和最大角将被矩阵转换。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | 检查当前边界框是否与指定的边界框重叠。 |
| [scale()](#scale--) | 计算任何包含点的绝对最大坐标值。 |
| [toString()](#toString--) | 获取包围盒的字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


使用给定的最小角和最大角初始化有限的包围盒

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | 最小角 |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | 最大角 **Example:** 以下代码展示了如何从最小和最大角构建边界框。 |

```
var minimum = new Vector3(0, 0, 0);
  var maximum = new Vector3(10, 10, 10);
  var boundingBox = new BoundingBox(minimum, maximum);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ) {#BoundingBox-double-double-double-double-double-double-}
```
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```


使用给定的最小角和最大角初始化有限的包围盒

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| minX | double | 最小角的 X |
| minY | double | 最小角的 Y |
| minZ | double | 最小角的 Z |
| maxX | double | 最大角的 X |
| maxY | double | 最大角的 Y |
|  | maxZ | double | 最大角的 Z **示例:** 以下代码展示了如何从最小和最大角构建一个边界框。 |

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox() {#BoundingBox--}
```
public BoundingBox()
```


### clone() {#clone--}
```
public BoundingBox clone()
```


克隆当前实例

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


用于检查它是否在当前边界框内部的边界框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
布尔
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


检查点 p 是否在边界框内部

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | 要测试的点 |

**Returns:**
boolean - 如果点在边界框内部则为 True **示例:** 以下代码展示了如何检查点是否在边界框内部。

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var pt = new Vector3(4, 4, 4);
  System.out.println("Bounding box overlaps = " + boundingBox.contains(pt));
```
### copyFrom(BoundingBox src) {#copyFrom-com.aspose.threed.BoundingBox-}
```
public void copyFrom(BoundingBox src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定两个对象是否相等

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的对象 |

**Returns:**
boolean - 如果两个对象相等则为 true
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


从给定几何体构建边界框

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | 用于计算边界框的几何体 |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of given geometry **Example:** The following code shows how to construct a bounding box from a geometry instance.

```
var sphere = (new Sphere()).toMesh();
  var boundingBox = BoundingBox.fromGeometry(sphere);
  System.out.println("Bounding box = " + boundingBox);
```
### getCenter() {#getCenter--}
```
public Vector3 getCenter()
```


边界框的中心。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The center of the bounding box.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtent() {#getExtent--}
```
public BoundingBoxExtent getExtent()
```


获取包围盒的范围。

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


无限包围盒

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


包围盒的最大角

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


包围盒的最小角

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


空包围盒

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


边界框的大小

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码

**Returns:**
int - 边界框的哈希码
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


将新盒合并到当前包围盒中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | 要合并的包围盒 |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


将当前边界框与给定点合并

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | 要合并到边界框的点 **示例:** 以下代码展示了如何将点合并到边界框。 |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


将当前边界框与给定点合并

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | 要合并到边界框的点 **示例:** 以下代码展示了如何将点合并到边界框。 |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


将当前边界框与给定点合并

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | 要合并到边界框的点 |
| y | double | 要合并到边界框的点 |
|  | z | double | 要合并到边界框的点 **示例:** 以下代码展示了如何将点合并到边界框。 |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


乘法运算符重载，新的边界框的最小和最大角将被矩阵转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | 输入的边界框。 |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | 用于变换边界框角点的矩阵 |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The product of bounding box and transform matrix.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### overlapsWith(BoundingBox box) {#overlapsWith-com.aspose.threed.BoundingBox-}
```
public boolean overlapsWith(BoundingBox box)
```


检查当前边界框是否与指定的边界框重叠。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | 要测试的另一个边界框 |

**Returns:**
boolean - 如果当前边界框与给定的边界框重叠则为 True **示例:** 以下代码展示了如何检查两个边界框是否相互重叠。

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


计算任何包含点的绝对最大坐标值。

**Returns:**
double - 任意包含点的计算得到的绝对最大坐标值。
### toString() {#toString--}
```
public String toString()
```


获取包围盒的字符串表示形式。

**Returns:**
java.lang.String - 边界框的字符串表示形式。
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

