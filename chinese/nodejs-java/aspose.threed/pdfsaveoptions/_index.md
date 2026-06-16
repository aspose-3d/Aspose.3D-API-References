---
title: "PdfSaveOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

PDF 导出时的保存选项。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | PdfSaveOptions 的构造函数 |

 **Result:**



---


### getRenderMode{#getRenderMode}

| 名称 | 描述 |
| --- | --- |
| getRenderMode() | 渲染模式指定 3D 艺术作品的渲染风格。属性的值是 PdfRenderMode 整数常量。 |

 **Result:**



---


### setRenderMode{#setRenderMode}

| 名称 | 描述 |
| --- | --- |
| setRenderMode(value) | 渲染模式指定 3D 艺术作品的渲染风格。属性的值是 PdfRenderMode 整数常量。 |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| 名称 | 描述 |
| --- | --- |
| getLightingScheme() | LightingScheme 指定要应用于 3D 艺术作品的照明。属性的值是 PdfLightingScheme 整数常量。 |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| 名称 | 描述 |
| --- | --- |
| setLightingScheme(value) | LightingScheme 指定要应用于 3D 艺术作品的照明。属性的值是 PdfLightingScheme 整数常量。 |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| 名称 | 描述 |
| --- | --- |
| getBackgroundColor() | PDF 文件中 3D 视图的背景颜色。 |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| 名称 | 描述 |
| --- | --- |
| setBackgroundColor(value) | PDF 文件中 3D 视图的背景颜色。 |

 **Result:**



---


### getFaceColor{#getFaceColor}

| 名称 | 描述 |
| --- | --- |
| getFaceColor() | 获取或设置在渲染 3D 内容时使用的面颜色。仅在 RenderMode 的值为 Illustration 时相关。 |

 **Result:**



---


### setFaceColor{#setFaceColor}

| 名称 | 描述 |
| --- | --- |
| setFaceColor(value) | 获取或设置在渲染 3D 内容时使用的面颜色。仅在 RenderMode 的值为 Illustration 时相关。 |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| 名称 | 描述 |
| --- | --- |
| getAuxiliaryColor() | 获取或设置在渲染 3D 内容时使用的辅助颜色。此颜色的解释取决于 RenderMode。 |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| 名称 | 描述 |
| --- | --- |
| setAuxiliaryColor(value) | 获取或设置在渲染 3D 内容时使用的辅助颜色。此颜色的解释取决于 RenderMode。 |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| 名称 | 描述 |
| --- | --- |
| getFlipCoordinateSystem() | 获取或设置在导出期间翻转场景的坐标系。 |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| 名称 | 描述 |
| --- | --- |
| setFlipCoordinateSystem(value) | 获取或设置在导出期间翻转场景的坐标系。 |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| 名称 | 描述 |
| --- | --- |
| getEmbedTextures() | 将外部纹理嵌入 PDF 文件，默认值为 false。 |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| 名称 | 描述 |
| --- | --- |
| setEmbedTextures(value) | 将外部纹理嵌入 PDF 文件，默认值为 false。 |

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



