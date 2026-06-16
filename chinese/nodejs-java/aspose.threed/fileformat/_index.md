---
title: "文件格式"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

文件格式定义  @hideconstructor


## 属性

| 名称 | 描述 |
| --- | --- |
| MAYA_BINARY | Autodesk Maya 的二进制格式 |
| STL_BINARY | 二进制 STL 文件格式 |
| STLASCII | ASCII STL 文件格式 |
| COLLADA | Collada 文件格式 |
| GLTF | Khronos Group 的 glTF |
| GLTF_BINARY | Khronos Group 的 glTF 二进制格式 |
| PDF | Adobe 的可移植文档格式 |
| DXF | AutoCAD DXF |
| PLY | Polygon 文件格式或 Stanford 三角形格式 |
| X_BINARY | 二进制格式的 DirectX X 文件 |
| X_TEXT | 二进制格式的 DirectX X 文件 |
| DRACO | Google Draco 网格 |
| RVM_TEXT | AVEVA Plant Design Management System Model 文本格式 |
| RVM_BINARY | AVEVA Plant Design Management System Model 二进制格式 |
| ASE | 3D Studio Max 的 ASCII 场景导出器格式。 |
| IFC | ISO 16739-1 行业基础类数据模型。 |
| AMF | 增材制造文件格式 |
| VRML | 该虚拟现实建模语言 |
| ZIP | 包含其他 3d 文件格式的 Zip 存档。 |
| USD | 通用场景描述 |
| USDZ | 压缩通用场景描述 |
| XYZ | Xyz 点云文件 |
| PCD | PCL 点云数据文件（ASCII 模式） |
| PCD_BINARY | PCL 点云数据文件（二进制模式） |

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


### getFormatByExtension{#getFormatByExtension}

| 名称 | 描述 |
| --- | --- |
| getFormatByExtension(extensionName) | 根据文件扩展名获取首选文件格式。扩展名应以点（'.'）开头。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| extensionNam | 字符串 | null |

 **Result:**
文件格式


---


### detect{#detect}

| 名称 | 描述 |
| --- | --- |
| detect(fileName) | 根据文件名检测文件格式，文件必须可读，以便 Aspose.3D 能通过文件头检测文件格式。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileNam | 字符串 | null |

 **Result:**
文件格式


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



