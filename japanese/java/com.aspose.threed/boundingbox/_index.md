---
title: BoundingBox
second_title: Aspose.3D for Java API リファレンス
description: 軸に平行なバウンディングボックス Example  以下のコードは、Entity インスタンスからバウンディングボックスを取得する方法を示しています。
type: docs
weight: 24
url: /ja/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

軸に平行なバウンディングボックス **Example:** 次のコードは Entity インスタンスからバウンディングボックスを取得する方法を示しています。

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Initialize a finite bounding box with given minimum and maximum corner |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Initialize a finite bounding box with given minimum and maximum corner |
| [BoundingBox()](#BoundingBox--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | 現在のバウンディングボックス内にあるかどうかをチェックするバウンディングボックス。 |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | 点 p がバウンディングボックス内にあるか確認する |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 2 つのオブジェクトが等しいかどうかを判断する |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | 与えられたジオメトリからバウンディングボックスを構築する |
| [getCenter()](#getCenter--) | バウンディングボックスの中心。 |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Gets the extent of the bounding box. |
| [getInfinite()](#getInfinite--) | The infinite bounding box |
| [getMaximum()](#getMaximum--) | The maximum corner of the bounding box |
| [getMinimum()](#getMinimum--) | The minimum corner of the bounding box |
| [getNull()](#getNull--) | The null bounding box |
| [getSize()](#getSize--) | バウンディングボックスのサイズ |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返す |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Merges the new box into the current bounding box. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | 現在のバウンディングボックスを指定された点とマージする |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | 現在のバウンディングボックスを指定された点とマージする |
| [merge(double x, double y, double z)](#merge-double-double-double-) | 現在のバウンディングボックスを指定された点とマージする |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | 乗算の演算子オーバーロード。新しいバウンディングボックスの最小角と最大角は行列によって変換されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | 現在のバウンディングボックスが指定されたバウンディングボックスと重なるか確認する。 |
| [scale()](#scale--) | 含まれる任意の点の絶対的な最大座標値を計算する。 |
| [toString()](#toString--) | Gets the string representation of the bounding box. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Initialize a finite bounding box with given minimum and maximum corner

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | The minimum corner |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | 最大コーナー **Example:** 以下のコードは、最小コーナーと最大コーナーからバウンディングボックスを構築する方法を示しています。 |

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


Initialize a finite bounding box with given minimum and maximum corner

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| minX | double | 最小コーナーの X |
| minY | double | 最小コーナーの Y |
| minZ | double | 最小コーナーの Z |
| maxX | double | 最大コーナーの X |
| maxY | double | 最大コーナーの Y |
|  | maxZ | double | 最大コーナーの Z **Example:** 以下のコードは、最小コーナーと最大コーナーからバウンディングボックスを構築する方法を示しています。 |

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


現在のインスタンスをクローンする

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


現在のバウンディングボックス内にあるかどうかをチェックするバウンディングボックス。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


点 p がバウンディングボックス内にあるか確認する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | テストするポイント |

**Returns:**
boolean - ポイントがバウンディングボックス内にある場合は True **Example:** 以下のコードは、ポイントがバウンディングボックス内にあるかどうかを確認する方法を示しています。

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


2 つのオブジェクトが等しいかどうかを判断する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較するオブジェクト |

**Returns:**
boolean - 2つのオブジェクトが等しい場合は true
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


与えられたジオメトリからバウンディングボックスを構築する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | バウンディングボックスを計算するジオメトリ |

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


バウンディングボックスの中心。

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


Gets the extent of the bounding box.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


The infinite bounding box

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


The maximum corner of the bounding box

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


The minimum corner of the bounding box

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


The null bounding box

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


バウンディングボックスのサイズ

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返す

**Returns:**
int - バウンディングボックスのハッシュコード
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Merges the new box into the current bounding box.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | The bounding box to merge |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


現在のバウンディングボックスを指定された点とマージする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | バウンディングボックスにマージされるポイント **Example:** 以下のコードは、ポイントをバウンディングボックスにマージする方法を示しています。 |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


現在のバウンディングボックスを指定された点とマージする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | バウンディングボックスにマージされるポイント **Example:** 以下のコードは、ポイントをバウンディングボックスにマージする方法を示しています。 |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


現在のバウンディングボックスを指定された点とマージする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double | バウンディングボックスにマージされるポイント |
| y | double | バウンディングボックスにマージされるポイント |
|  | z | double | バウンディングボックスにマージされるポイント **Example:** 以下のコードは、ポイントをバウンディングボックスにマージする方法を示しています。 |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


乗算の演算子オーバーロード。新しいバウンディングボックスの最小角と最大角は行列によって変換されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | 入力バウンディングボックス。 |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | バウンディングボックスのコーナーを変換するために使用される行列 |

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


現在のバウンディングボックスが指定されたバウンディングボックスと重なるか確認する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | テストする他のバウンディングボックス |

**Returns:**
boolean - 現在のバウンディングボックスが指定されたものと重なる場合は True **Example:** 以下のコードは、2つのバウンディングボックスが互いに重なるかどうかを確認する方法を示しています。

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


含まれる任意の点の絶対的な最大座標値を計算する。

**Returns:**
double - 含まれる任意のポイントの計算された絶対最大座標値。
### toString() {#toString--}
```
public String toString()
```


Gets the string representation of the bounding box.

**Returns:**
java.lang.String - バウンディングボックスの文字列表現。
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

