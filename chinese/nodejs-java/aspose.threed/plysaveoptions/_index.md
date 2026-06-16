---
title: "PlySaveOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

将场景导出为 PLY 文件的保存选项。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | PlySaveOptions 的构造函数 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(contentType) | PlySaveOptions 的构造函数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

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


### getFlipCoordinate{#getFlipCoordinate}

| 名称 | 描述 |
| --- | --- |
| getFlipCoordinate() | 在保存场景时翻转坐标，默认值为 true |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| 名称 | 描述 |
| --- | --- |
| setFlipCoordinate(value) | 在保存场景时翻转坐标，默认值为 true |

 **Result:**



---


### getVertexElement{#getVertexElement}

| 名称 | 描述 |
| --- | --- |
| getVertexElement() | 顶点数据的元素名称，默认值为 "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| 名称 | 描述 |
| --- | --- |
| setVertexElement(value) | 顶点数据的元素名称，默认值为 "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| 名称 | 描述 |
| --- | --- |
| getPositionComponents() | 位置数据的组件名称，默认值为 ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| 名称 | 描述 |
| --- | --- |
| getNormalComponents() | 法线数据的组件名称，默认值为 ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| 名称 | 描述 |
| --- | --- |
| getTextureCoordinateComponents() | 纹理坐标数据的组件名称，默认值为 ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| 名称 | 描述 |
| --- | --- |
| getColorComponents() | 顶点颜色的组件名称，默认值为 ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| 名称 | 描述 |
| --- | --- |
| getFaceElement() | 面数据的元素名称，默认值为 "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| 名称 | 描述 |
| --- | --- |
| setFaceElement(value) | 面数据的元素名称，默认值为 "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| 名称 | 描述 |
| --- | --- |
| getFaceProperty() | 面数据的属性名称，默认值为 "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| 名称 | 描述 |
| --- | --- |
| setFaceProperty(value) | 面数据的属性名称，默认值为 "vertex_index" |

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



