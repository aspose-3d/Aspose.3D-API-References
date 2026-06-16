---
title: "DracoFormat"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google Draco 格式  @hideconstructor


## 方法

### getVersion{#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion() | 获取文件格式版本 |

 **Result:**



---


### getExtension{#getExtension}

| 名称 | 描述 |
| --- | --- |
| getExtension() | 获取此类型的扩展名。 |

 **Result:**



---


### getExtensions{#getExtensions}

| 名称 | 描述 |
| --- | --- |
| getExtensions() | 获取此类型的扩展名列表。 |

 **Result:**



---


### getContentType{#getContentType}

| 名称 | 描述 |
| --- | --- |
| getContentType() | 获取文件格式的内容类型。属性值为 FileContentType 整数常量。 |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| 名称 | 描述 |
| --- | --- |
| getFileFormatType() | 获取文件格式类型 |

 **Result:**



---


### decode{#decode}

| 名称 | 描述 |
| --- | --- |
| decode(fileName) | 从指定的文件名解码点云或网格 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名包含 drc 文件 |

 **Result:**
几何


---


### decode{#decode}

| 名称 | 描述 |
| --- | --- |
| decode(data) | 从内存数据解码点云或网格 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 原始 drc 字节 |

 **Result:**
几何


---


### encode{#encode}

| 名称 | 描述 |
| --- | --- |
| encode(entity, fileName, options) | 将实体编码到指定文件 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 待编码的实体 |
| fileName | 字符串 | 待写入的文件名 |
| options | DracoSaveOptions | 用于编码点云的额外选项 |

 **Result:**
几何


---


### encode{#encode}

| 名称 | 描述 |
| --- | --- |
| encode(entity, options) | 将实体编码为 Draco 原始数据 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 待编码的实体 |
| options | DracoSaveOptions | 用于编码点云的额外选项 |

 **Result:**
byte[]


---


### createLoadOptions{#createLoadOptions}

| 名称 | 描述 |
| --- | --- |
| createLoadOptions() | 为此文件格式创建默认加载选项 |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| 名称 | 描述 |
| --- | --- |
| createSaveOptions() | 为此文件格式创建默认保存选项 |

 **Result:**
SaveOptions


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 将格式转换为字符串 |

 **Result:**
字符串


---



