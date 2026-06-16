---
title: "StlLoadOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/stlloadoptions/
---
## StlLoadOptions class

STL的加载选项


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化一个新的 StlLoadOptions 实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(contentType) | 初始化一个新的 StlLoadOptions 实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| 名称 | 描述 |
| --- | --- |
| getFlipCoordinateSystem() | 获取或设置在导入期间是否翻转控制点/法线的坐标系。 |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| 名称 | 描述 |
| --- | --- |
| setFlipCoordinateSystem(value) | 获取或设置在导入期间是否翻转控制点/法线的坐标系。 |

 **Result:**



---


### getRecalculateNormal{#getRecalculateNormal}

| 名称 | 描述 |
| --- | --- |
| getRecalculateNormal() | 忽略 STL 文件中存储的法线数据，并根据顶点位置重新计算法线数据。默认值为 false。 |

 **Result:**



---


### setRecalculateNormal{#setRecalculateNormal}

| 名称 | 描述 |
| --- | --- |
| setRecalculateNormal(value) | 忽略 STL 文件中存储的法线数据，并根据顶点位置重新计算法线数据。默认值为 false。 |

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



