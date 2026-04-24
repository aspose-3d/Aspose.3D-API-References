---
title: 構造体
second_title: Aspose.3D for Java API リファレンス
description: 2017年11月13日、lexchou によって作成されました。
type: docs
weight: 262
url: /ja/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

2017年11月13日、lexchou によって作成されました。
## Methods

| Method | 説明 |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | 入力値が構造体の場合、コピーしようとする |
| [clone()](#clone--) | 現在のインスタンスをクローンする |
| [copyFrom(T t)](#copyFrom-T-) | 引数 t から内部状態をコピーする |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


入力値が構造体の場合、コピーしようとする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | T | クローンする入力値 |

**Returns:**
T - 入力が null の場合またはクローンされたインスタンスの場合は null
### clone() {#clone--}
```
public abstract T clone()
```


現在のインスタンスをクローンする

**Returns:**
T - クローンされたインスタンス
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


引数 t から内部状態をコピーする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| t | T | コピー元インスタンス |

