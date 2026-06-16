---
title: "WeightedMode"
second_title: "Aspose.3D for Java API 参考"
description: "加权模式。"
type: docs
weight: 231
url: /zh/java/com.aspose.threed/weightedmode/
---

**Inheritance:**
java.lang.Object
```
public final class WeightedMode
```

加权模式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WeightedMode()](#WeightedMode--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [BOTH](#BOTH) | 出向切线和下一个入向切线均已加权。 |
| [NEXT_IN_WEIGHT](#NEXT-IN-WEIGHT) | 下一个入向（左）切线已加权。 |
| [NONE](#NONE) | 出向和下一个入向的权重均未使用。 |
| [OUT_WEIGHT](#OUT-WEIGHT) | 出向（右）切线已加权。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WeightedMode() {#WeightedMode--}
```
public WeightedMode()
```


### BOTH {#BOTH}
```
public static final int BOTH
```


出向切线和下一个入向切线均已加权。

### NEXT_IN_WEIGHT {#NEXT-IN-WEIGHT}
```
public static final int NEXT_IN_WEIGHT
```


下一个入向（左）切线已加权。

### NONE {#NONE}
```
public static final int NONE
```


出向和下一个入向的权重均未使用。当计算需要切线信息时，将使用默认值（0.3333）。

### OUT_WEIGHT {#OUT-WEIGHT}
```
public static final int OUT_WEIGHT
```


出向（右）切线已加权。

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

