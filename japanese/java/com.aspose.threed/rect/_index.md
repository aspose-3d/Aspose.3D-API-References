---
title: Rect
second_title: Aspose.3D for Java API リファレンス
description: 矩形を表すクラスです
type: docs
weight: 144
url: /ja/java/com.aspose.threed/rect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Rect implements Struct<Rect>, Serializable
```

矩形を表すクラスです
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Rect(int x, int y, int width, int height)](#Rect-int-int-int-int-) | クラス [Rect](../../com.aspose.threed/rect) のコンストラクタです。 |
| [Rect()](#Rect--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(int x, int y)](#contains-int-int-) | 与えられた点が矩形の内部にある場合は true を返します。 |
| [copyFrom(Rect src)](#copyFrom-com.aspose.threed.Rect-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | 矩形の下端を取得します |
| [getClass()](#getClass--) |  |
| [getHeight()](#getHeight--) | サイズの高さを取得します |
| [getLeft()](#getLeft--) | 矩形の左端を取得します |
| [getRight()](#getRight--) | 矩形の右端を取得します |
| [getTop()](#getTop--) | 矩形の上端を取得します |
| [getWidth()](#getWidth--) | サイズの幅を取得します |
| [getX()](#getX--) | サイズの x を取得します |
| [getY()](#getY--) | サイズの y を取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHeight(int value)](#setHeight-int-) | サイズの高さを設定します |
| [setWidth(int value)](#setWidth-int-) | サイズの幅を設定します |
| [setX(int value)](#setX-int-) | サイズの x を設定します |
| [setY(int value)](#setY-int-) | サイズの y を設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rect(int x, int y, int width, int height) {#Rect-int-int-int-int-}
```
public Rect(int x, int y, int width, int height)
```


クラス [Rect](../../com.aspose.threed/rect) のコンストラクタです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | int |  |
| y | int |  |
| 幅 | int |  |
| 高さ | int |  |

### Rect() {#Rect--}
```
public Rect()
```


### clone() {#clone--}
```
public Rect clone()
```


現在のインスタンスをクローンする

**Returns:**
[Rect](../../com.aspose.threed/rect)
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


与えられた点が矩形の内部にある場合は true を返します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | int |  |
| y | int |  |

**Returns:**
boolean
### copyFrom(Rect src) {#copyFrom-com.aspose.threed.Rect-}
```
public void copyFrom(Rect src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [Rect](../../com.aspose.threed/rect) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBottom() {#getBottom--}
```
public int getBottom()
```


矩形の下端を取得します

**Returns:**
int - 矩形の下端
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeight() {#getHeight--}
```
public int getHeight()
```


サイズの高さを取得します

**Returns:**
int - サイズの高さ
### getLeft() {#getLeft--}
```
public int getLeft()
```


矩形の左端を取得します

**Returns:**
int - 矩形の左端
### getRight() {#getRight--}
```
public int getRight()
```


矩形の右端を取得します

**Returns:**
int - 矩形の右端
### getTop() {#getTop--}
```
public int getTop()
```


矩形の上端を取得します

**Returns:**
int - 矩形の上端
### getWidth() {#getWidth--}
```
public int getWidth()
```


サイズの幅を取得します

**Returns:**
int - サイズの幅
### getX() {#getX--}
```
public int getX()
```


サイズの x を取得します

**Returns:**
int - サイズの x
### getY() {#getY--}
```
public int getY()
```


サイズの y を取得します

**Returns:**
int - サイズの y
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


サイズの高さを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


サイズの幅を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


サイズの x を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


サイズの y を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

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

