---
title: "PdfFormat"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

Adobe 的可移植文档格式  @hideconstructor


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


### extract{#extract}

| 名称 | 描述 |
| --- | --- |
| extract(fileName, password) | 从 PDF 文件中提取原始 3D 内容。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |
| passwor | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| 名称 | 描述 |
| --- | --- |
| extractScene(fileName) | 从 PDF 文件中提取 3D 场景。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| 名称 | 描述 |
| --- | --- |
| extractScene(fileName, password) | 从 PDF 文件中提取 3D 场景。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |
| passwor | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


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



