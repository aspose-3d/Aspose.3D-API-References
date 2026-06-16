---
title: "GLSLSource"
second_title: "Aspose.3D for Java API 参考"
description: "GLSL 中着色器的源代码"
type: docs
weight: 70
url: /zh/java/com.aspose.threed/glslsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.ShaderSource](../../com.aspose.threed/shadersource)
```
public final class GLSLSource extends ShaderSource
```

GLSL 中着色器的源代码
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GLSLSource()](#GLSLSource--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [defineInclude(String fileName, String content)](#defineInclude-java.lang.String-java.lang.String-) | 为 GLSL 源代码中的 \#include 定义虚拟文件 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComputeShader()](#getComputeShader--) | 获取计算着色器的源代码。 |
| [getFragmentShader()](#getFragmentShader--) | 获取片段着色器的源代码。 |
| [getGeometryShader()](#getGeometryShader--) | 获取几何着色器的源代码。 |
| [getVertexShader()](#getVertexShader--) | 获取顶点着色器的源代码 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setComputeShader(String value)](#setComputeShader-java.lang.String-) | 设置计算着色器的源代码。 |
| [setFragmentShader(String value)](#setFragmentShader-java.lang.String-) | 设置片段着色器的源代码。 |
| [setGeometryShader(String value)](#setGeometryShader-java.lang.String-) | 设置几何着色器的源代码。 |
| [setVertexShader(String value)](#setVertexShader-java.lang.String-) | 设置顶点着色器的源代码 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GLSLSource() {#GLSLSource--}
```
public GLSLSource()
```


### defineInclude(String fileName, String content) {#defineInclude-java.lang.String-java.lang.String-}
```
public void defineInclude(String fileName, String content)
```


为 GLSL 源代码中的 \#include 定义虚拟文件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 虚拟文件的文件名 |
| 内容 | java.lang.String |  |

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
### getComputeShader() {#getComputeShader--}
```
public String getComputeShader()
```


获取计算着色器的源代码。

**Returns:**
java.lang.String - 计算着色器的源代码。
### getFragmentShader() {#getFragmentShader--}
```
public String getFragmentShader()
```


获取片段着色器的源代码。

**Returns:**
java.lang.String - 片段着色器的源代码。
### getGeometryShader() {#getGeometryShader--}
```
public String getGeometryShader()
```


获取几何着色器的源代码。

**Returns:**
java.lang.String - 几何着色器的源代码。
### getVertexShader() {#getVertexShader--}
```
public String getVertexShader()
```


获取顶点着色器的源代码

**Returns:**
java.lang.String - 顶点着色器的源代码
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




### setComputeShader(String value) {#setComputeShader-java.lang.String-}
```
public void setComputeShader(String value)
```


设置计算着色器的源代码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setFragmentShader(String value) {#setFragmentShader-java.lang.String-}
```
public void setFragmentShader(String value)
```


设置片段着色器的源代码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setGeometryShader(String value) {#setGeometryShader-java.lang.String-}
```
public void setGeometryShader(String value)
```


设置几何着色器的源代码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setVertexShader(String value) {#setVertexShader-java.lang.String-}
```
public void setVertexShader(String value)
```


设置顶点着色器的源代码

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

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

