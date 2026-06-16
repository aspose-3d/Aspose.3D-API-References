---
title: "DracoSaveOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/dracosaveoptions/
---
## DracoSaveOptions class

Google Draco 文件的保存选项


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 构造用于保存 Draco 文件的默认配置。 |

 **Result:**



---


### getPositionBits{#getPositionBits}

| 名称 | 描述 |
| --- | --- |
| getPositionBits() | 位置的量化位数，默认值为 14 |

 **Result:**



---


### setPositionBits{#setPositionBits}

| 名称 | 描述 |
| --- | --- |
| setPositionBits(value) | 位置的量化位数，默认值为 14 |

 **Result:**



---


### getTextureCoordinateBits{#getTextureCoordinateBits}

| 名称 | 描述 |
| --- | --- |
| getTextureCoordinateBits() | 纹理坐标的量化位数，默认值为 12 |

 **Result:**



---


### setTextureCoordinateBits{#setTextureCoordinateBits}

| 名称 | 描述 |
| --- | --- |
| setTextureCoordinateBits(value) | 纹理坐标的量化位数，默认值为 12 |

 **Result:**



---


### getColorBits{#getColorBits}

| 名称 | 描述 |
| --- | --- |
| getColorBits() | 顶点颜色的量化位数，默认值为 10 |

 **Result:**



---


### setColorBits{#setColorBits}

| 名称 | 描述 |
| --- | --- |
| setColorBits(value) | 顶点颜色的量化位数，默认值为 10 |

 **Result:**



---


### getNormalBits{#getNormalBits}

| 名称 | 描述 |
| --- | --- |
| getNormalBits() | 法向量的量化位数，默认值为 10 |

 **Result:**



---


### setNormalBits{#setNormalBits}

| 名称 | 描述 |
| --- | --- |
| setNormalBits(value) | 法向量的量化位数，默认值为 10 |

 **Result:**



---


### getCompressionLevel{#getCompressionLevel}

| 名称 | 描述 |
| --- | --- |
| getCompressionLevel() | 压缩级别，默认值为 DracoCompressionLevel.STANDARD。属性的值是 DracoCompressionLevel 整数常量。 |

 **Result:**



---


### setCompressionLevel{#setCompressionLevel}

| 名称 | 描述 |
| --- | --- |
| setCompressionLevel(value) | 压缩级别，默认值为 DracoCompressionLevel.STANDARD。属性的值是 DracoCompressionLevel 整数常量。 |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| 名称 | 描述 |
| --- | --- |
| getApplyUnitScale() | 将 AssetInfo.UnitScaleFactor 应用于网格。默认值为 false。 |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| 名称 | 描述 |
| --- | --- |
| setApplyUnitScale(value) | 将 AssetInfo.UnitScaleFactor 应用于网格。默认值为 false。 |

 **Result:**



---


### getPointCloud{#getPointCloud}

| 名称 | 描述 |
| --- | --- |
| getPointCloud() | 将场景导出为点云，默认值为 false。 |

 **Result:**



---


### setPointCloud{#setPointCloud}

| 名称 | 描述 |
| --- | --- |
| setPointCloud(value) | 将场景导出为点云，默认值为 false。 |

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



