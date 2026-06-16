---
title: "TextureData"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

此类包含纹理的原始数据和格式定义。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | TextureData 的构造函数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | 数字 | null |
| 高度 | 数字 | null |
| strid | 数字 | null |
| bytesPerPixe | 数字 | null |
| pixelFormat | PixelFormat | PixelFormat |
| 数据 | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | 构造一个新的 TextureData 并分配像素数据。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | 数字 | null |
| 高度 | 数字 | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2() | TextureData 的构造函数 |

 **Result:**



---


### getData{#getData}

| 名称 | 描述 |
| --- | --- |
| getData() | 像素数据的原始字节 |

 **Result:**



---


### getWidth{#getWidth}

| 名称 | 描述 |
| --- | --- |
| getWidth() | 水平像素数量 |

 **Result:**



---


### getHeight{#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight() | 垂直像素数量 |

 **Result:**



---


### getStride{#getStride}

| 名称 | 描述 |
| --- | --- |
| getStride() | 扫描线的字节数。 |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| 名称 | 描述 |
| --- | --- |
| getBytesPerPixel() | 像素的字节数 |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| 名称 | 描述 |
| --- | --- |
| getPixelFormat() | 像素的格式。属性的值是 PixelFormat 整数常量。 |

 **Result:**



---


### fromFile{#fromFile}

| 名称 | 描述 |
| --- | --- |
| fromFile(fileName) | 从文件加载纹理 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |

 **Result:**
TextureData


---


### save{#save}

| 名称 | 描述 |
| --- | --- |
| save(fileName) | 将纹理数据保存到图像文件中 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 图像将被保存的文件名。 |

 **Result:**
TextureData


---


### save{#save}

| 名称 | 描述 |
| --- | --- |
| save(fileName, format) | 将纹理数据保存到图像文件中 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 图像将被保存的文件名。 |
| format | 字符串 | 输出文件的图像格式。 |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| 名称 | 描述 |
| --- | --- |
| mapPixels(mapMode) | 映射所有像素以进行读/写 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| 名称 | 描述 |
| --- | --- |
| mapPixels(mapMode, format) | 在给定像素格式下映射所有像素以进行读/写 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| 名称 | 描述 |
| --- | --- |
| mapPixels(rect, mapMode, format) | 在给定像素格式下映射由 rect 指定的像素以进行读取/写入 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rect | 要访问的像素区域 |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| 名称 | 描述 |
| --- | --- |
| transformPixelFormat(pixelFormat) | 将像素布局转换为新的像素格式。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



