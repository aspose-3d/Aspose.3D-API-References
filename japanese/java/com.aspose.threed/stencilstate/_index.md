---
title: StencilState
second_title: Aspose.3D for Java API リファレンス
description: 面ごとのステンシルステート。
type: docs
weight: 175
url: /ja/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

面ごとのステンシルステート。
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | ステンシルテストで使用される比較関数を取得します |
| [getDepthFailAction()](#getDepthFailAction--) | ステンシルテストは合格だが深度テストが失敗したときのステンシルアクションを取得します。 |
| [getFailAction()](#getFailAction--) | ステンシルテストが失敗したときのステンシルアクションを取得します。 |
| [getPassAction()](#getPassAction--) | ステンシルテストと深度テストの両方が合格したときのステンシルアクションを取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | ステンシルテストで使用される比較関数を設定します |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | ステンシルテストは合格だが深度テストが失敗したときのステンシルアクションを設定します。 |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | ステンシルテストが失敗したときのステンシルアクションを設定します。 |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | ステンシルテストと深度テストの両方が合格したときのステンシルアクションを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | 説明 |
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
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


ステンシルテストで使用される比較関数を取得します

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


ステンシルテストは合格だが深度テストが失敗したときのステンシルアクションを取得します。

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


ステンシルテストが失敗したときのステンシルアクションを取得します。

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


ステンシルテストと深度テストの両方が合格したときのステンシルアクションを取得します。

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


ステンシルテストで使用される比較関数を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | 新しい値 |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


ステンシルテストは合格だが深度テストが失敗したときのステンシルアクションを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 新しい値 |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


ステンシルテストが失敗したときのステンシルアクションを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 新しい値 |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


ステンシルテストと深度テストの両方が合格したときのステンシルアクションを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 新しい値 |

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

