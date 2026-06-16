---
title: "RenderingAPI"
second_title: "Aspose.3D for Java API 参考"
description: "常用的渲染 API"
type: docs
weight: 269
url: /zh/java/com.aspose.threed/renderingapi/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RenderingAPI extends Enum<RenderingAPI>
```

常用的渲染 API
## 字段

| 字段 | 描述 |
| --- | --- |
| [ARNOLD](#ARNOLD) | Arnold 渲染器 |
| [CUSTOM](#CUSTOM) | 自定义渲染 API |
| [DIRECTX](#DIRECTX) | DirectX |
| [MANTLE](#MANTLE) | AMD Mantle |
| [MENTAL_RAY](#MENTAL-RAY) | MentalRay |
| [METAL](#METAL) | 由 Apple 开发的 Metal |
| [NONE](#NONE) | 无渲染 API |
| [OPENGL](#OPENGL) | OpenGL |
| [OPENGLES](#OPENGLES) | OpenGL ES |
| [PREVIEW](#PREVIEW) | PreviewColorAPI，兼容 FBX |
| [RENDER_MAN](#RENDER-MAN) | RenderMan |
| [RENDER_WARE](#RENDER-WARE) | RenderWare |
| [SHADERFX](#SHADERFX) | ShaderFX 渲染器 |
| [STAGE3D](#STAGE3D) | Adobe Flash 中使用的 Stage3D |
| [VULKAN](#VULKAN) | Vulkan |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ARNOLD {#ARNOLD}
```
public static final RenderingAPI ARNOLD
```


Arnold 渲染器

### CUSTOM {#CUSTOM}
```
public static final RenderingAPI CUSTOM
```


自定义渲染 API

### DIRECTX {#DIRECTX}
```
public static final RenderingAPI DIRECTX
```


DirectX

### MANTLE {#MANTLE}
```
public static final RenderingAPI MANTLE
```


AMD Mantle

### MENTAL_RAY {#MENTAL-RAY}
```
public static final RenderingAPI MENTAL_RAY
```


MentalRay

### METAL {#METAL}
```
public static final RenderingAPI METAL
```


由 Apple 开发的 Metal

### NONE {#NONE}
```
public static final RenderingAPI NONE
```


无渲染 API

### OPENGL {#OPENGL}
```
public static final RenderingAPI OPENGL
```


OpenGL

### OPENGLES {#OPENGLES}
```
public static final RenderingAPI OPENGLES
```


OpenGL ES

### PREVIEW {#PREVIEW}
```
public static final RenderingAPI PREVIEW
```


PreviewColorAPI，兼容 FBX

### RENDER_MAN {#RENDER-MAN}
```
public static final RenderingAPI RENDER_MAN
```


RenderMan

### RENDER_WARE {#RENDER-WARE}
```
public static final RenderingAPI RENDER_WARE
```


RenderWare

### SHADERFX {#SHADERFX}
```
public static final RenderingAPI SHADERFX
```


ShaderFX 渲染器

### STAGE3D {#STAGE3D}
```
public static final RenderingAPI STAGE3D
```


Adobe Flash 中使用的 Stage3D

### VULKAN {#VULKAN}
```
public static final RenderingAPI VULKAN
```


Vulkan

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RenderingAPI valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[RenderingAPI](../../com.aspose.threed/renderingapi)
### values() {#values--}
```
public static RenderingAPI[] values()
```




**Returns:**
com.aspose.threed.RenderingAPI[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

