---
title: "StencilState"
second_title: "Aspose.3D for Java API 参考"
description: "每个面的模板状态。"
type: docs
weight: 175
url: /zh/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

每个面的模板状态。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的对象。 |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | 获取在模板测试中使用的比较函数 |
| [getDepthFailAction()](#getDepthFailAction--) | 获取当模板测试通过但深度测试失败时的模板操作。 |
| [getFailAction()](#getFailAction--) | 获取当模板测试失败时的模板操作。 |
| [getPassAction()](#getPassAction--) | 获取当模板测试和深度测试均通过时的模板操作。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | 设置在模板测试中使用的比较函数 |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | 设置当模板测试通过但深度测试失败时的模板操作。 |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | 设置当模板测试失败时的模板操作。 |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | 设置当模板测试和深度测试均通过时的模板操作。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
布尔
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


获取在模板测试中使用的比较函数

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


获取当模板测试通过但深度测试失败时的模板操作。

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


获取当模板测试失败时的模板操作。

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


获取当模板测试和深度测试均通过时的模板操作。

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

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


设置在模板测试中使用的比较函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | 新值 |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


设置当模板测试通过但深度测试失败时的模板操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 新值 |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


设置当模板测试失败时的模板操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 新值 |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


设置当模板测试和深度测试均通过时的模板操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | 新值 |

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

