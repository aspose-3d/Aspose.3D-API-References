---
title: "TextureBase"
second_title: "Aspose.3D for Java API 参考"
description: "所有具体纹理的基类。"
type: docs
weight: 185
url: /zh/java/com.aspose.threed/texturebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureBase extends A3DObject
```

所有具体纹理的基类。纹理定义了几何表面的外观和质感。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextureBase(String name)](#TextureBase-java.lang.String-) | 初始化一个新的 [TextureBase](../../com.aspose.threed/texturebase) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getAlpha()](#getAlpha--) | 获取纹理的默认 alpha 值。当 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) 为 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) 时有效。默认值为 1.0，有效值范围在 0 到 1 之间。 |
| [getAlphaSource()](#getAlphaSource--) | 获取纹理是否定义了 alpha 通道。 |
| [getClass()](#getClass--) |  |
| [getMagFilter()](#getMagFilter--) | 获取放大过滤器。 |
| [getMinFilter()](#getMinFilter--) | 获取缩小过滤器。 |
| [getMipFilter()](#getMipFilter--) | 获取 mip 级别采样的过滤器。 |
| [getName()](#getName--) | 获取名称。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getUVRotation()](#getUVRotation--) | 获取纹理的旋转角度 |
| [getUVScale()](#getUVScale--) | 获取 UV 缩放。 |
| [getUVTranslation()](#getUVTranslation--) | 获取 UV 平移。 |
| [getWrapModeU()](#getWrapModeU--) | 获取 U 方向的纹理环绕模式。 |
| [getWrapModeV()](#getWrapModeV--) | 获取 V 方向的纹理环绕模式。 |
| [getWrapModeW()](#getWrapModeW--) | 获取 W 方向的纹理环绕模式。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setAlpha(double value)](#setAlpha-double-) | 设置纹理的默认 alpha 值。当 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) 为 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) 时有效。默认值为 1.0，有效值范围在 0 到 1 之间。 |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | 设置纹理是否定义 alpha 通道。 |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | 设置放大过滤器。 |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | 设置缩小过滤器。 |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | 设置 mip 级别采样的过滤器。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setRotation(double u, double v)](#setRotation-double-double-) | 设置 UV 旋转。 |
| [setScale(double u, double v)](#setScale-double-double-) | 设置 UV 缩放。 |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | 设置 UV 平移。 |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | 设置纹理的旋转 |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | 设置 UV 缩放。 |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | 设置 UV 平移。 |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | 设置 U 方向的纹理环绕模式。 |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | 设置 V 方向的纹理环绕模式。 |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | 设置 W 方向的纹理环绕模式。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBase(String name) {#TextureBase-java.lang.String-}
```
public TextureBase(String name)
```


初始化一个新的 [TextureBase](../../com.aspose.threed/texturebase) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String | 属性名称。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


获取纹理的默认 alpha 值。当 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) 为 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) 时有效。默认值为 1.0，有效值范围在 0 到 1 之间。

**Returns:**
double - 纹理的默认 alpha 值。当 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) 为 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) 时有效。默认值为 1.0，有效值范围为 0 到 1。
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


获取纹理是否定义 alpha 通道。默认值为 [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)。

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


获取放大过滤器。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


获取缩小过滤器。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


获取 mip 级别采样的过滤器。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


获取所有属性的集合。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


获取指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 找到的属性的值
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


获取纹理的旋转角度

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


获取 UV 缩放。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


获取 UV 平移。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


获取 U 方向的纹理环绕模式。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


获取 V 方向的纹理环绕模式。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


获取 W 方向的纹理环绕模式。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


移除动态属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


移除通过名称标识的指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


设置纹理的默认 alpha 值。当 [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) 为 [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) 时有效。默认值为 1.0，有效值范围在 0 到 1 之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


设置纹理是否定义 alpha 通道。默认值为 [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | 新值 |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


设置放大过滤器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新值 |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


设置缩小过滤器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新值 |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


设置 mip 级别采样的过滤器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


设置指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |
| 值 | java.lang.Object | 属性的值 |

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


设置 UV 旋转。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| u | double | U。 |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


设置 UV 缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| u | double | U。 |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


设置 UV 平移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| u | double | U。 |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


设置纹理的旋转

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


设置 UV 缩放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


设置 UV 平移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


设置 U 方向的纹理环绕模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新值 |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


设置 V 方向的纹理环绕模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新值 |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


设置 W 方向的纹理环绕模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新值 |

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

