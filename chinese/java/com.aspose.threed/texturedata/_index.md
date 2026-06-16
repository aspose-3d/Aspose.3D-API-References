---
title: "TextureData"
second_title: "Aspose.3D for Java API 参考"
description: "此类包含纹理的原始数据和格式定义。"
type: docs
weight: 187
url: /zh/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

此类包含纹理的原始数据和格式定义。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | [TextureData](../../com.aspose.threed/texturedata) 的构造函数 |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | 构造一个新的 [TextureData](../../com.aspose.threed/texturedata) 并分配像素数据。 |
| [TextureData()](#TextureData--) | [TextureData](../../com.aspose.threed/texturedata) 的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | 从文件加载纹理 |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | 从流加载纹理 |
| [getBytesPerPixel()](#getBytesPerPixel--) | 像素的字节数 |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | 像素数据的原始字节 |
| [getHeight()](#getHeight--) | 垂直像素数量 |
| [getName()](#getName--) | 获取名称。 |
| [getPixelFormat()](#getPixelFormat--) | 像素的格式 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getStride()](#getStride--) | 扫描行的字节数。 |
| [getWidth()](#getWidth--) | 水平像素数量 |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | 映射所有像素以进行读/写 |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | 以给定像素格式映射所有像素以进行读/写 |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | 映射由矩形指定的像素，以给定像素格式进行读取/写入 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | 将纹理数据保存为指定的图像格式 |
| [save(String fileName)](#save-java.lang.String-) | 将纹理数据保存到图像文件 |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | 将纹理数据保存到图像文件 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | 将像素布局转换为新的像素格式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


[TextureData](../../com.aspose.threed/texturedata) 的构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int |  |
| 高度 | int |  |
| 步幅 | int |  |
| 每像素字节数 | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| 数据 | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


构造一个新的 [TextureData](../../com.aspose.threed/texturedata) 并分配像素数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int |  |
| 高度 | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


[TextureData](../../com.aspose.threed/texturedata) 的构造函数

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


从文件加载纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


从流加载纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


像素的字节数

**Returns:**
int - 像素的字节数
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


像素数据的原始字节

**Returns:**
byte[] - 像素数据的原始字节
### getHeight() {#getHeight--}
```
public int getHeight()
```


垂直像素数量

**Returns:**
int - 垂直像素数量
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


像素的格式

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


扫描行的字节数。

**Returns:**
int - 扫描行的字节数。
### getWidth() {#getWidth--}
```
public int getWidth()
```


水平像素数量

**Returns:**
int - 水平像素数量
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


映射所有像素以进行读/写

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | 映射模式 |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


以给定像素格式映射所有像素以进行读/写

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | 映射模式 |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | 像素格式 |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


映射由矩形指定的像素，以给定像素格式进行读取/写入

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | 要访问的像素区域 |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | 映射模式 |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | 像素格式 |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


将纹理数据保存为指定的图像格式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 保存图像的流 |
| 格式 | java.lang.String | 图像格式，通常为文件扩展名 |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


将纹理数据保存到图像文件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 图像将被保存的文件名。 |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


将纹理数据保存到图像文件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 图像将被保存的文件名。 |
| 格式 | java.lang.String | 输出文件的图像格式。 |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


将像素布局转换为新的像素格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | 目标像素格式 |

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

