---
title: "ShaderSet"
second_title: "Aspose.3D for Java API 参考"
description: "针对每种材质的着色器程序"
type: docs
weight: 166
url: /zh/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

针对每种材质的着色器程序
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | 构造 [ShaderSet](../../com.aspose.threed/shaderset) 的实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 释放此实例并释放所有着色器程序。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | 获取在所需着色器不可用时的回退着色器 |
| [getLambert()](#getLambert--) | 获取用于渲染 lambert 材质的着色器 |
| [getPbr()](#getPbr--) | 获取用于渲染 PBR 材质的着色器 |
| [getPhong()](#getPhong--) | 获取用于渲染 phong 材质的着色器 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | 设置在所需着色器不可用时的回退着色器 |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | 设置用于渲染 lambert 材质的着色器 |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | 设置用于渲染 PBR 材质的着色器 |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | 设置用于渲染 phong 材质的着色器 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


构造 [ShaderSet](../../com.aspose.threed/shaderset) 的实例

### close() {#close--}
```
public void close()
```


释放此实例并释放所有着色器程序。

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
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


获取在所需着色器不可用时的回退着色器

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


获取用于渲染 lambert 材质的着色器

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


获取用于渲染 PBR 材质的着色器

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


获取用于渲染 phong 材质的着色器

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the phong material
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




### setFallback(ShaderProgram value) {#setFallback-com.aspose.threed.ShaderProgram-}
```
public void setFallback(ShaderProgram value)
```


设置在所需着色器不可用时的回退着色器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新值 |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


设置用于渲染 lambert 材质的着色器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新值 |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


设置用于渲染 PBR 材质的着色器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新值 |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


设置用于渲染 phong 材质的着色器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新值 |

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

