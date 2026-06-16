---
title: "GltfSaveOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

glTF 格式的保存选项。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(contentType) | GltfSaveOptions 的构造函数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(format) | GltfSaveOptions 的构造函数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| forma | 文件格式 | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| 名称 | 描述 |
| --- | --- |
| getPrettyPrint() | GLTF 文件的 JSON 内容已缩进以便人类阅读，默认值为 false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| 名称 | 描述 |
| --- | --- |
| setPrettyPrint(value) | GLTF 文件的 JSON 内容已缩进以便人类阅读，默认值为 false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| 名称 | 描述 |
| --- | --- |
| getFallbackNormal() | 当 GLTF2 导出器检测到无效法线时，将使用此值替代原始值以绕过验证。默认值为 (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| 名称 | 描述 |
| --- | --- |
| getEmbedAssets() | 以 ASCII 模式将所有外部资源嵌入为 base64 到单个文件中，默认值为 false。 |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| 名称 | 描述 |
| --- | --- |
| setEmbedAssets(value) | 以 ASCII 模式将所有外部资源嵌入为 base64 到单个文件中，默认值为 false。 |

 **Result:**



---


### getImageFormat{#getImageFormat}

| 名称 | 描述 |
| --- | --- |
| getImageFormat() | 标准 glTF 仅支持 PNG/JPG 作为纹理格式，此选项将指导 Aspose.3D 在导出期间如何将非标准图像转换为支持的格式。默认值为 GltfEmbeddedImageFormat.PNG，该属性的值是 GltfEmbeddedImageFormat 整数常量。 |

 **Result:**



---


### setImageFormat{#setImageFormat}

| 名称 | 描述 |
| --- | --- |
| setImageFormat(value) | 标准 glTF 仅支持 PNG/JPG 作为纹理格式，此选项将指导 Aspose.3D 在导出期间如何将非标准图像转换为支持的格式。默认值为 GltfEmbeddedImageFormat.PNG，该属性的值是 GltfEmbeddedImageFormat 整数常量。 |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| 名称 | 描述 |
| --- | --- |
| getMaterialConverter() | 自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，glTF 2.0 导出器将自动将标准材质转换为 PBR 材质。默认值为 null。此属性在将场景导出为 glTF 2.0 文件时使用。 |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| 名称 | 描述 |
| --- | --- |
| setMaterialConverter(value) | 自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，glTF 2.0 导出器将自动将标准材质转换为 PBR 材质。默认值为 null。此属性在将场景导出为 glTF 2.0 文件时使用。 |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| 名称 | 描述 |
| --- | --- |
| getUseCommonMaterials() | 使用 KHR 通用材质扩展序列化材质，默认值为 false。将此设置为 false 将导致 Aspose.3D 导出一组顶点/片段着色器 #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| 名称 | 描述 |
| --- | --- |
| setUseCommonMaterials(value) | 使用 KHR 通用材质扩展序列化材质，默认值为 false。将此设置为 false 将导致 Aspose.3D 导出一组顶点/片段着色器 #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| 名称 | 描述 |
| --- | --- |
| getExternalDracoEncoder() | 使用外部 draco 编码器以加速 draco 压缩速度。Aspose.3D 将创建新子进程将网格编码为 draco 格式，使用时自行承担风险。 |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| 名称 | 描述 |
| --- | --- |
| setExternalDracoEncoder(value) | 使用外部 draco 编码器以加速 draco 压缩速度。Aspose.3D 将创建新子进程将网格编码为 draco 格式，使用时自行承担风险。 |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| 名称 | 描述 |
| --- | --- |
| getFlipTexCoordV() | 翻转纹理坐标 v(t) 分量，默认值为 true。 |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| 名称 | 描述 |
| --- | --- |
| setFlipTexCoordV(value) | 翻转纹理坐标 v(t) 分量，默认值为 true。 |

 **Result:**



---


### getBufferFile{#getBufferFile}

| 名称 | 描述 |
| --- | --- |
| getBufferFile() | 外部缓冲区文件的文件名，用于存储二进制数据。如果未指定此文件，Aspose.3D 将为您生成一个名称。导出二进制模式的 glTF 时此设置将被忽略。 |

 **Result:**



---


### setBufferFile{#setBufferFile}

| 名称 | 描述 |
| --- | --- |
| setBufferFile(value) | 外部缓冲区文件的文件名，用于存储二进制数据。如果未指定此文件，Aspose.3D 将为您生成一个名称。导出二进制模式的 glTF 时此设置将被忽略。 |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| 名称 | 描述 |
| --- | --- |
| getSaveExtras() | 将场景对象的动态属性保存到生成的 glTF 文件的 'extra' 字段中。这对于提供特定应用程序的数据很有用。默认值为 false。 |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| 名称 | 描述 |
| --- | --- |
| setSaveExtras(value) | 将场景对象的动态属性保存到生成的 glTF 文件的 'extra' 字段中。这对于提供特定应用程序的数据很有用。默认值为 false。 |

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


### getDracoCompression{#getDracoCompression}

| 名称 | 描述 |
| --- | --- |
| getDracoCompression() | 获取或设置是否启用 draco 压缩 |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| 名称 | 描述 |
| --- | --- |
| setDracoCompression(value) | 获取或设置是否启用 draco 压缩 |

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



