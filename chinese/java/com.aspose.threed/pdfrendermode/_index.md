---
title: "PdfRenderMode"
second_title: "Aspose.3D for Java API 参考"
description: "渲染模式指定 3D 艺术作品的渲染风格。"
type: docs
weight: 289
url: /zh/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

渲染模式指定 3D 艺术作品的渲染风格。
## 字段

| 字段 | 描述 |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | 显示每个节点的包围盒边缘，沿该节点本地坐标空间的轴对齐。 |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | 以单一颜色显示边缘，但会去除背向和被遮挡的边缘。 |
| [ILLUSTRATION](#ILLUSTRATION) | 显示带有表面的轮廓边缘，去除被遮挡的线条。 |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | 显示带有光照和纹理表面的轮廓边缘，并添加发光项以去除艺术作品中光照不足的区域。 |
| [SHADED_VERTICES](#SHADED-VERTICES) | 仅显示顶点，但使用其顶点颜色并应用光照。 |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | 仅显示边缘，但在两个顶点之间插值其颜色并应用光照。 |
| [SOLID](#SOLID) | 显示带纹理和光照的几何形状。 |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | 显示带有光照和纹理表面的轮廓边缘，去除被遮挡的线条。 |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | 显示带纹理和光照的几何形状（三角形），并在其上方以单一颜色绘制边缘。 |
| [TRANSPARENT](#TRANSPARENT) | 显示带纹理和光照的几何形状（三角形），并添加透明度。 |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | 显示每个节点的包围盒面，沿该节点本地坐标空间的轴对齐，并添加透明度。 |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | 显示每个节点的包围盒边缘和面，沿该节点本地坐标空间的轴对齐，并添加透明度。 |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | 显示带纹理和光照的几何形状（三角形），并添加透明度，同时在其上方以单一颜色的不透明边缘绘制。 |
| [VERTICES](#VERTICES) | 仅以单一颜色显示顶点。 |
| [WIREFRAME](#WIREFRAME) | 仅以单一颜色显示边缘。 |
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
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


显示每个节点的包围盒边缘，沿该节点本地坐标空间的轴对齐。

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


以单一颜色显示边缘，但会去除背向和被遮挡的边缘。

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


显示带有表面的轮廓边缘，去除被遮挡的线条。

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


显示带有光照和纹理表面的轮廓边缘，并添加发光项以去除艺术作品中光照不足的区域。

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


仅显示顶点，但使用其顶点颜色并应用光照。

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


仅显示边缘，但在两个顶点之间插值其颜色并应用光照。

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


显示带纹理和光照的几何形状。

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


显示带有光照和纹理表面的轮廓边缘，去除被遮挡的线条。

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


显示带纹理和光照的几何形状（三角形），并在其上方以单一颜色绘制边缘。

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


显示带纹理和光照的几何形状（三角形），并添加透明度。

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


显示每个节点的包围盒面，沿该节点本地坐标空间的轴对齐，并添加透明度。

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


显示每个节点的包围盒边缘和面，沿该节点本地坐标空间的轴对齐，并添加透明度。

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


显示带纹理和光照的几何形状（三角形），并添加透明度，同时在其上方以单一颜色的不透明边缘绘制。

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


仅以单一颜色显示顶点。

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


仅以单一颜色显示边缘。

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
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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

