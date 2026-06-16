---
title: "RvmFormat"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/rvmformat/
---
## RvmFormat class

RVM 格式  @hideconstructor


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


### loadAttributes{#loadAttributes}

| 名称 | 描述 |
| --- | --- |
| loadAttributes(scene, fileName, prefix) | 从指定的文件名加载属性 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | Scene | 属性将被应用的场景 |
| fileName | 字符串 | 包含属性的文件名 |
| prefix | 字符串 | 属性前缀，用于避免名称冲突，默认值为 "rvm:" |

 **Result:**



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



