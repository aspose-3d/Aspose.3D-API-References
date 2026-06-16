---
title: "RelativeRectangle"
second_title: "Aspose.3D for Java API 参考"
description: "相对矩形  公式在相对组件与绝对值之间是  Scale  Reference Width  offset  因此如果我们想让它表示绝对值，请将所有 scale 字段设为零并改用 offset 字段。"
type: docs
weight: 147
url: /zh/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

相对矩形 相对组件与绝对值之间的公式为：Scale \* (Reference Width) + offset 所以如果我们想让它表示绝对值，请将所有比例字段设为零，而使用偏移字段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | 构造一个 [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | 构造一个 [RelativeRectangle](../../com.aspose.threed/relativerectangle) 并将所有 offset 字段设为零，scale 字段使用给定参数。 |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | 获取高度的偏移量 |
| [getOffsetWidth()](#getOffsetWidth--) | 获取宽度的偏移量 |
| [getOffsetX()](#getOffsetX--) | 获取坐标 X 的偏移量 |
| [getOffsetY()](#getOffsetY--) | 获取坐标 Y 的偏移量 |
| [getScaleHeight()](#getScaleHeight--) | 相对高度 |
| [getScaleWidth()](#getScaleWidth--) | 相对宽度 |
| [getScaleX()](#getScaleX--) | 相对坐标 X |
| [getScaleY()](#getScaleY--) | 相对坐标 Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | 设置高度的偏移量 |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | 设置宽度的偏移量 |
| [setOffsetX(int value)](#setOffsetX-int-) | 设置坐标 X 的偏移量 |
| [setOffsetY(int value)](#setOffsetY-int-) | 设置坐标 Y 的偏移量 |
| [setScaleHeight(float value)](#setScaleHeight-float-) | 相对高度 |
| [setScaleWidth(float value)](#setScaleWidth-float-) | 相对宽度 |
| [setScaleX(float value)](#setScaleX-float-) | 相对坐标 X |
| [setScaleY(float value)](#setScaleY-float-) | 相对坐标 Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | 将相对矩形转换为绝对矩形 |
| [toString()](#toString--) | 将此实例的值转换为 java.lang.String。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


构造一个 [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | int |  |
| 顶部 | int |  |
| 宽度 | int |  |
| 高度 | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


克隆当前实例

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
布尔
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


构造一个 [RelativeRectangle](../../com.aspose.threed/relativerectangle) 并将所有 offset 字段设为零，scale 字段使用给定参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | float |  |
| scaleY | float |  |
| scaleWidth | float |  |
| scaleHeight | float |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


获取高度的偏移量

**Returns:**
int - 高度的偏移量
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


获取宽度的偏移量

**Returns:**
int - 宽度的偏移量
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


获取坐标 X 的偏移量

**Returns:**
int - X 坐标的偏移量
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


获取坐标 Y 的偏移量

**Returns:**
int - Y 坐标的偏移量
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


相对高度

**Returns:**
float - 相对高度
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


相对宽度

**Returns:**
float - 相对宽度
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


相对坐标 X

**Returns:**
float - 相对 X 坐标
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


相对坐标 Y

**Returns:**
float - 相对 Y 坐标
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


设置高度的偏移量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


设置宽度的偏移量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


设置坐标 X 的偏移量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


设置坐标 Y 的偏移量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


相对高度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


相对宽度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


相对坐标 X

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


相对坐标 Y

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


将相对矩形转换为绝对矩形

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | int | 矩形的左侧 |
| 顶部 | int | 矩形的顶部 |
| 宽度 | int | 矩形的宽度 |
| 高度 | int | 矩形的高度 |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


将此实例的值转换为 java.lang.String。

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

