---
title: "UsdSaveOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

USD/USDZ 格式的保存选项。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 使用 FileFormat.USD 格式初始化新的 UsdSaveOptions。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(fileFormat) | 使用指定的 USD/USDZ 格式初始化新的 UsdSaveOptions。 |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| 名称 | 描述 |
| --- | --- |
| getPrimitiveToMesh() | 在导出过程中将原始实体转换为网格。或者直接将原始实体编码到输出文件（将使用 Aspose 的扩展定义来处理非官方原始实体，如 Dish、Torus），默认值为 true。 |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| 名称 | 描述 |
| --- | --- |
| setPrimitiveToMesh(value) | 在导出过程中将原始实体转换为网格。或者直接将原始实体编码到输出文件（将使用 Aspose 的扩展定义来处理非官方原始实体，如 Dish、Torus），默认值为 true。 |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| 名称 | 描述 |
| --- | --- |
| getExportMetaData() | 通过 USD 的 customData 字段导出节点的属性。 |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| 名称 | 描述 |
| --- | --- |
| setExportMetaData(value) | 通过 USD 的 customData 字段导出节点的属性。 |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| 名称 | 描述 |
| --- | --- |
| getMaterialConverter() | 自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，USD 导出器将自动将标准材质转换为 PBR 材质。默认值为 null。 |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| 名称 | 描述 |
| --- | --- |
| setMaterialConverter(value) | 自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，USD 导出器将自动将标准材质转换为 PBR 材质。默认值为 null。 |

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



