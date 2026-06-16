---
title: "结构体"
second_title: "Aspose.3D for Java API 参考"
description: "由 lexchou 于 2017/11/13 创建。"
type: docs
weight: 262
url: /zh/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

由 lexchou 于 2017/11/13 创建。
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | 如果是结构体，则尝试复制输入值 |
| [clone()](#clone--) | 克隆当前实例 |
| [copyFrom(T t)](#copyFrom-T-) | 从参数 t 复制内部状态 |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


如果是结构体，则尝试复制输入值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | T | 要克隆的输入值 |

**Returns:**
T - 如果输入为 null 或已克隆实例，则为 null
### clone() {#clone--}
```
public abstract T clone()
```


克隆当前实例

**Returns:**
T - 已克隆的实例
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


从参数 t 复制内部状态

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| t | T | 要复制的源实例 |

