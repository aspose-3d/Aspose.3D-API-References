---
title: "PushConstant"
second_title: "Aspose.3D for Java API 参考"
description: "通过推送常量向着色器提供数据的实用工具。"
type: docs
weight: 141
url: /zh/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

通过推送常量向着色器提供数据的实用工具。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PushConstant()](#PushConstant--) | [PushConstant](../../com.aspose.threed/pushconstant) 的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | 将准备好的数据提交到图形管线。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | 将矩阵写入常量 |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | 将 3 分量向量写入常量 |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | 将 4 分量向量写入常量 |
| [write(float f)](#write-float-) | 将 float 值写入常量 |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | 将 4 分量向量写入常量 |
| [write(int n)](#write-int-) | 将 int 值写入常量 |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


[PushConstant](../../com.aspose.threed/pushconstant) 的构造函数

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


将准备好的数据提交到图形管线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 阶段 | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
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

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


将矩阵写入常量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | 要写入的矩阵 |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


将 3 分量向量写入常量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


将 4 分量向量写入常量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


将 float 值写入常量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


将 4 分量向量写入常量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| z | float |  |
| w | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(int n) {#write-int-}
```
public PushConstant write(int n)
```


将 int 值写入常量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
