---
title: "PlyFormat"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

PLY 格式。  @hideconstructor


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


### encode{#encode}

| 名称 | 描述 |
| --- | --- |
| encode(entity, fileName) | 对实体进行编码并将结果保存到外部文件中。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| fileName | 字符串 | 要写入的文件 |

 **Result:**



---


### encode{#encode}

| 名称 | 描述 |
| --- | --- |
| encode(entity, fileName, opt) | 对实体进行编码并将结果保存到外部文件中。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要编码的实体 |
| fileName | 字符串 | 要写入的文件 |
| opt | PlySaveOptions | 保存选项 |

 **Result:**



---


### decode{#decode}

| 名称 | 描述 |
| --- | --- |
| decode(fileName) | 从指定的流中解码点云或网格。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 输入流 |

 **Result:**
几何


---


### decode{#decode}

| 名称 | 描述 |
| --- | --- |
| decode(fileName, opt) | 从指定的流中解码点云或网格。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 输入流 |
| opt | PlyLoadOptions | PLY 格式的加载选项 |

 **Result:**
几何


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



