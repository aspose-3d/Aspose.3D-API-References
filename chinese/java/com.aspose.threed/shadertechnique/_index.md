---
title: "ShaderTechnique"
second_title: "Aspose.3D for Java API 参考"
description: "Shader 技术表示具体的渲染实现。"
type: docs
weight: 169
url: /zh/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Shader 技术表示具体的渲染实现。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | 初始化 [ShaderTechnique](../../com.aspose.threed/shadertechnique) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | 将动态属性绑定到着色器参数 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 获取此技术的描述 |
| [getRenderAPI()](#getRenderAPI--) | 获取此技术使用的渲染 API |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | 获取渲染 API 的版本。 |
| [getShaderContent()](#getShaderContent--) | 获取嵌入式着色器脚本的内容。 |
| [getShaderEntry()](#getShaderEntry--) | 获取着色器的入口点，某些着色器如 HLSL 可以有自定义的着色器入口。 |
| [getShaderFile()](#getShaderFile--) | 获取外部着色器文件的文件名。 |
| [getShaderLanguage()](#getShaderLanguage--) | 获取此技术使用的着色器语言。 |
| [getShaderParameters()](#getShaderParameters--) | 获取着色器参数定义。 |
| [getShaderVersion()](#getShaderVersion--) | 获取此技术使用的着色器版本。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | 设置此技术的描述 |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | 设置此技术使用的渲染 API |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | 设置渲染 API 的版本。 |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | 设置嵌入式着色器脚本的内容。 |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | 设置着色器的入口点，某些着色器如 HLSL 可以有自定义入口。 |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | 设置外部着色器文件的文件名。 |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | 设置此技术使用的着色器语言。 |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | 设置此技术使用的着色器版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


初始化 [ShaderTechnique](../../com.aspose.threed/shadertechnique) 类的新实例。

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


将动态属性绑定到着色器参数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 动态属性的名称。 |
| shaderParameter | java.lang.String | 着色器参数的名称。 |

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
### getDescription() {#getDescription--}
```
public String getDescription()
```


获取此技术的描述

**Returns:**
java.lang.String - 此技术的描述
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


获取此技术使用的渲染 API

**Returns:**
java.lang.String - 此技术使用的渲染 API
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


获取渲染 API 的版本。

**Returns:**
java.lang.String - 渲染 API 的版本。
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


获取嵌入式着色器脚本的内容。它可以是 HLSL/GLSL 着色器源文件。

**Returns:**
byte[] - 嵌入式着色器脚本的内容。它可以是 HLSL/GLSL 着色器源文件。
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


获取着色器的入口点，某些着色器如 HLSL 可以有自定义的着色器入口。

**Returns:**
java.lang.String - 着色器的入口点，某些着色器如 HLSL 可以有自定义入口。
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


获取外部着色器文件的文件名。

**Returns:**
java.lang.String - 外部着色器文件的文件名。
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


获取此技术使用的着色器语言。

**Returns:**
java.lang.String - 此技术使用的着色器语言。
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


获取着色器参数定义。键是动态属性的名称，值是属性关联的着色器参数名称。

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - 着色器参数定义。键是动态属性的名称，值是属性关联的着色器参数名称。
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


获取此技术使用的着色器版本。

**Returns:**
java.lang.String - 此技术使用的着色器版本。
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


设置此技术的描述

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


设置此技术使用的渲染 API

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


设置渲染 API 的版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


设置嵌入式着色器脚本的内容。它可以是 HLSL/GLSL 着色器源文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] | 新值 |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


设置着色器的入口点，某些着色器如 HLSL 可以有自定义入口。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


设置外部着色器文件的文件名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


设置此技术使用的着色器语言。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


设置此技术使用的着色器版本。

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

