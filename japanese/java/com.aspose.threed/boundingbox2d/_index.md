---
title: "BoundingBox2D"
second_title: "Aspose.3D for Java API リファレンス"
description: "軸に平行なバウンディングボックス"
type: docs
weight: 25
url: /ja/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

軸に平行なバウンディングボックス（[Vector2](../../com.aspose.threed/vector2) 用）
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | 指定された最小コーナーと最大コーナーで有限バウンディングボックスを初期化する |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [INFINITE](#INFINITE) | 無限バウンディングボックス |
| [NULL](#NULL) | ヌルバウンディングボックス |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | バウンディングボックスの範囲を取得します。 |
| [getMaximum()](#getMaximum--) | バウンディングボックスの最大コーナー |
| [getMinimum()](#getMinimum--) | バウンディングボックスの最小コーナー |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | 新しいボックスを現在のバウンディングボックスにマージします。 |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | 新しいボックスを現在のバウンディングボックスにマージします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | バウンディングボックスの文字列表現を取得します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


指定された最小コーナーと最大コーナーで有限バウンディングボックスを初期化する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | 最小コーナー |
| maximum | [Vector2](../../com.aspose.threed/vector2) | 最大コーナー |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


無限バウンディングボックス

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


ヌルバウンディングボックス

### clone() {#clone--}
```
public BoundingBox2D clone()
```


現在のインスタンスをクローンする

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
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


バウンディングボックスの範囲を取得します。

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


バウンディングボックスの最大コーナー

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


バウンディングボックスの最小コーナー

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The minimum corner of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### merge(BoundingBox2D bb) {#merge-com.aspose.threed.BoundingBox2D-}
```
public void merge(BoundingBox2D bb)
```


新しいボックスを現在のバウンディングボックスにマージします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | マージするバウンディングボックス |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


新しいボックスを現在のバウンディングボックスにマージします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | マージするポイント |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


バウンディングボックスの文字列表現を取得します。

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

