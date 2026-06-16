---
title: "FbxSaveOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Fbx 文件的保存选项。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(format) | 初始化 FbxSaveOptions |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| forma | 文件格式 | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(contentType) | 使用最新支持的版本初始化 FbxSaveOptions。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| 名称 | 描述 |
| --- | --- |
| getReusePrimitiveMesh() | 在具有相同参数的原语上复用网格，这将显著减小由大量原始形状（如从 CAD 文件导入）构建的场景的 FBX 输出大小。默认值为 false。 |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| 名称 | 描述 |
| --- | --- |
| setReusePrimitiveMesh(value) | 在具有相同参数的原语上复用网格，这将显著减小由大量原始形状（如从 CAD 文件导入）构建的场景的 FBX 输出大小。默认值为 false。 |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| 名称 | 描述 |
| --- | --- |
| getEnableCompression() | 压缩 FBX 文件中的大型二进制数据（例如动画数据、控制点、顶点元素数据、索引），默认值为 true。 |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| 名称 | 描述 |
| --- | --- |
| setEnableCompression(value) | 压缩 FBX 文件中的大型二进制数据（例如动画数据、控制点、顶点元素数据、索引），默认值为 true。 |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| 名称 | 描述 |
| --- | --- |
| getFoldRepeatedCurveData() | 获取或设置是否通过增加最后数据的引用计数来复用重复的曲线数据；如果折叠重复曲线数据则为 true，否则为 false。 |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| 名称 | 描述 |
| --- | --- |
| getExportLegacyMaterialProperties() | 获取或设置是否导出旧版材质属性，用于向后兼容。此选项默认开启。 |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| 名称 | 描述 |
| --- | --- |
| setExportLegacyMaterialProperties(value) | 获取或设置是否导出旧版材质属性，用于向后兼容。此选项默认开启。 |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| 名称 | 描述 |
| --- | --- |
| getVideoForTexture() | 获取或设置在导出为 FBX 时是否为纹理生成 Video 实例。 |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| 名称 | 描述 |
| --- | --- |
| setVideoForTexture(value) | 获取或设置在导出为 FBX 时是否为纹理生成 Video 实例。 |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| 名称 | 描述 |
| --- | --- |
| getEmbedTextures() | 获取或设置是否将纹理嵌入最终输出文件。FBX 导出器将尝试从文件系统中查找纹理的原始数据，并将文件嵌入最终的 FBX 文件。默认值为 false。 |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| 名称 | 描述 |
| --- | --- |
| setEmbedTextures(value) | 获取或设置是否将纹理嵌入最终输出文件。FBX 导出器将尝试从文件系统中查找纹理的原始数据，并将文件嵌入最终的 FBX 文件。默认值为 false。 |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| 名称 | 描述 |
| --- | --- |
| getGenerateVertexElementMaterial() | 获取或设置是否在附加节点包含材质时始终为几何体生成 VertexElementMaterial。此选项默认关闭。 |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| 名称 | 描述 |
| --- | --- |
| setGenerateVertexElementMaterial(value) | 获取或设置是否在附加节点包含材质时始终为几何体生成 VertexElementMaterial。此选项默认关闭。 |

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



