---
title: "Int2D"
second_title: "Aspose.3D for Java API 参考"
description: "由 lexchou 于 2017/5/17 创建。"
type: docs
weight: 86
url: /zh/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

由 lexchou 于 2017/5/17 创建。二维 int 数组包装器
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | 使用默认数据分配构造二维 int 数组。 |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | 使用给定数据构造二维 int 数组 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | 获取指定位置的元素 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | 获取此二维数组的总长度 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | 设置指定位置的元素 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


使用默认数据分配构造二维 int 数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 行 | int | 二维数组的行数 |
| 列 | int | 二维数组的列数 |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


使用给定数据构造二维 int 数组

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 行 | int | 二维数组的行数 |
| 列 | int | 二维数组的列数 |
| 数据 | int[] | 要包装的数组，Float2D 将在内部使用此数组。 |

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
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


获取指定位置的元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r | int | 行 |
| c | int | 列 |

**Returns:**
int - 指定位置的值
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rank | int |  |

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


获取此二维数组的总长度

**Returns:**
int - 此二维数组中浮点数的总数。
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


设置指定位置的元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r | int | 行 |
| c | int | 列 |
| v | int | 数值 |

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

