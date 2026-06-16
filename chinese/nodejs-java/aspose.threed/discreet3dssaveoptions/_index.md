---
title: "Discreet3dsSaveOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

3DS 文件的保存选项。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | Discreet3dsSaveOptions 的构造函数 |

 **Result:**



---


### getExportLight{#getExportLight}

| 名称 | 描述 |
| --- | --- |
| getExportLight() | 获取或设置是否导出场景中的所有灯光。 |

 **Result:**



---


### setExportLight{#setExportLight}

| 名称 | 描述 |
| --- | --- |
| setExportLight(value) | 获取或设置是否导出场景中的所有灯光。 |

 **Result:**



---


### getExportCamera{#getExportCamera}

| 名称 | 描述 |
| --- | --- |
| getExportCamera() | 获取或设置是否导出场景中的所有相机。 |

 **Result:**



---


### setExportCamera{#setExportCamera}

| 名称 | 描述 |
| --- | --- |
| setExportCamera(value) | 获取或设置是否导出场景中的所有相机。 |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| 名称 | 描述 |
| --- | --- |
| getDuplicatedNameSeparator() | 对象名称与重复计数器之间的分隔符，默认值为 "_"。当场景中包含使用相同名称的对象时，Aspose.3D 3DS 导出器将为该对象生成不同的名称。例如，有两个名为 "Box" 的节点，第一个节点的名称为 "Box"，第二个节点将在默认配置下获得新名称 "Box_2"。 |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| 名称 | 描述 |
| --- | --- |
| setDuplicatedNameSeparator(value) | 对象名称与重复计数器之间的分隔符，默认值为 "_"。当场景中包含使用相同名称的对象时，Aspose.3D 3DS 导出器将为该对象生成不同的名称。例如，有两个名为 "Box" 的节点，第一个节点的名称为 "Box"，第二个节点将在默认配置下获得新名称 "Box_2"。 |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| 名称 | 描述 |
| --- | --- |
| getDuplicatedNameCounterBase() | 用于为重复名称生成新名称的计数器，默认值为 2。 |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| 名称 | 描述 |
| --- | --- |
| setDuplicatedNameCounterBase(value) | 用于为重复名称生成新名称的计数器，默认值为 2。 |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| 名称 | 描述 |
| --- | --- |
| getDuplicatedNameCounterFormat() | 重复计数器的格式，默认值为空字符串。 |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| 名称 | 描述 |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | 重复计数器的格式，默认值为空字符串。 |

 **Result:**



---


### getMasterScale{#getMasterScale}

| 名称 | 描述 |
| --- | --- |
| getMasterScale() | 获取或设置导出时使用的主比例。 |

 **Result:**



---


### setMasterScale{#setMasterScale}

| 名称 | 描述 |
| --- | --- |
| setMasterScale(value) | 获取或设置导出时使用的主比例。 |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| 名称 | 描述 |
| --- | --- |
| getGammaCorrectedColor() | 3ds 文件可能为同一属性包含原始颜色和伽马校正颜色，将此设置为 true 将在可能的情况下使用伽马校正颜色，否则 Aspose.3D 将尝试使用原始颜色。 |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| 名称 | 描述 |
| --- | --- |
| setGammaCorrectedColor(value) | 3ds 文件可能为同一属性包含原始颜色和伽马校正颜色，将此设置为 true 将在可能的情况下使用伽马校正颜色，否则 Aspose.3D 将尝试使用原始颜色。 |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| 名称 | 描述 |
| --- | --- |
| getFlipCoordinateSystem() | 获取或设置在导入/导出期间控制点/法线的翻转坐标系。 |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| 名称 | 描述 |
| --- | --- |
| setFlipCoordinateSystem(value) | 获取或设置在导入/导出期间控制点/法线的翻转坐标系。 |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| 名称 | 描述 |
| --- | --- |
| getHighPreciseColor() | 如果此值为 true，生成的 3ds 文件将使用高精度颜色，即红/绿/蓝每个通道采用 32 位浮点数。否则生成的文件将使用 24 位颜色，每个通道使用 8 位字节。默认值为 false，因为并非所有应用程序都支持高精度颜色。 |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| 名称 | 描述 |
| --- | --- |
| setHighPreciseColor(value) | 如果此值为 true，生成的 3ds 文件将使用高精度颜色，即红/绿/蓝每个通道采用 32 位浮点数。否则生成的文件将使用 24 位颜色，每个通道使用 8 位字节。默认值为 false，因为并非所有应用程序都支持高精度颜色。 |

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



