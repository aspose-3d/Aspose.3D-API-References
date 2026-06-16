---
title: "RvmSaveOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Aveva PDMS RVM 文件的保存选项。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | RvmSaveOptions 的构造函数 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(contentType) | RvmSaveOptions 的构造函数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| 名称 | 描述 |
| --- | --- |
| getFileNote() | 文件头中的文件备注。 |

 **Result:**



---


### setFileNote{#setFileNote}

| 名称 | 描述 |
| --- | --- |
| setFileNote(value) | 文件头中的文件备注。 |

 **Result:**



---


### getAuthor{#getAuthor}

| 名称 | 描述 |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| 名称 | 描述 |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| 名称 | 描述 |
| --- | --- |
| getCreationTime() | 导出此文件的时间戳，默认值为当前时间 |

 **Result:**



---


### setCreationTime{#setCreationTime}

| 名称 | 描述 |
| --- | --- |
| setCreationTime(value) | 导出此文件的时间戳，默认值为当前时间 |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| 名称 | 描述 |
| --- | --- |
| getAttributePrefix() | 获取或设置将被导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。例如，如果属性为 rvm:Refno=345，导出的属性将为 Refno = 345，前缀被去除。 |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| 名称 | 描述 |
| --- | --- |
| setAttributePrefix(value) | 获取或设置将被导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。例如，如果属性为 rvm:Refno=345，导出的属性将为 Refno = 345，前缀被去除。 |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| 名称 | 描述 |
| --- | --- |
| getAttributeListFile() | 获取或设置属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。 |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| 名称 | 描述 |
| --- | --- |
| setAttributeListFile(value) | 获取或设置属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。 |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| 名称 | 描述 |
| --- | --- |
| getExportAttributes() | 获取或设置是否将属性列表导出到外部 .att 文件，默认值为 false。 |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| 名称 | 描述 |
| --- | --- |
| setExportAttributes(value) | 获取或设置是否将属性列表导出到外部 .att 文件，默认值为 false。 |

 **Result:**



---


### getExportTextures{#getExportTextures}

| 名称 | 描述 |
| --- | --- |
| getExportTextures() | 尝试将场景中使用的纹理复制到输出目录。 |

 **Result:**



---


### setExportTextures{#setExportTextures}

| 名称 | 描述 |
| --- | --- |
| setExportTextures(value) | 尝试将场景中使用的纹理复制到输出目录。 |

 **Result:**



---


### getFileFormat{#getFileFormat}

| 名称 | 描述 |
| --- | --- |
| getFileFormat() | 获取当前保存/加载选项中指定的文件格式。 |

 **Result:**



---


### getEncoding{#getEncoding}

| 名称 | 描述 |
| --- | --- |
| getEncoding() | 获取或设置基于文本文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。 |

 **Result:**



---


### getFileSystem{#getFileSystem}

| 名称 | 描述 |
| --- | --- |
| getFileSystem() | 允许用户处理在加载/保存期间如何管理外部依赖项。 |

 **Result:**



---


### setFileSystem{#setFileSystem}

| 名称 | 描述 |
| --- | --- |
| setFileSystem(value) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| 名称 | 描述 |
| --- | --- |
| getLookupPaths() | 某些文件（如 OBJ）依赖外部文件，查找路径允许 Aspose.3D 查找并加载外部文件。 |

 **Result:**



---


### getFileName{#getFileName}

| 名称 | 描述 |
| --- | --- |
| getFileName() | 导出/导入场景的文件名。此项可选，但在序列化外部资源（如 OBJ 的材质）时很有用。 |

 **Result:**



---


### setFileName{#setFileName}

| 名称 | 描述 |
| --- | --- |
| setFileName(value) | 导出/导入场景的文件名。此项可选，但在序列化外部资源（如 OBJ 的材质）时很有用。 |

 **Result:**



---



