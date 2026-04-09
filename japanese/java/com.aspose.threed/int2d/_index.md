---
title: Int2D
second_title: Aspose.3D for Java API リファレンス
description: 2017年5月17日、lexchou によって作成されました。
type: docs
weight: 86
url: /ja/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

lexchou が 2017/5/17 に作成。2 次元 int 配列ラッパー
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | デフォルトのデータ割り当てで 2D int 配列を構築します。 |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | 指定されたデータで 2D int 配列を構築します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | 指定された位置の要素を取得します |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | この2次元配列の総長さを取得します |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | 指定された位置の要素を設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


デフォルトのデータ割り当てで 2D int 配列を構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 行 | int | 2次元配列の行数 |
| 列 | int | 2次元配列の列数 |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


指定されたデータで 2D int 配列を構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 行 | int | 2次元配列の行数 |
| 列 | int | 2次元配列の列数 |
| データ | int[] | ラップする配列、Float2Dは内部でこの配列を使用します。 |

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
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


指定された位置の要素を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| r | int | 行 |
| c | int | 列 |

**Returns:**
int - 指定された位置の値
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public int getColumns()
```




**Returns:**
int
### getLength(int rank) {#getLength-int-}
```
public int getLength(int rank)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ランク | int |  |

**Returns:**
int
### getRows() {#getRows--}
```
public int getRows()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### length() {#length--}
```
public int length()
```


この2次元配列の総長さを取得します

**Returns:**
int - この2次元配列の浮動小数点数の総数。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(int r, int c, int v) {#set-int-int-int-}
```
public void set(int r, int c, int v)
```


指定された位置の要素を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| r | int | 行 |
| c | int | 列 |
| v | int | 値 |

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

