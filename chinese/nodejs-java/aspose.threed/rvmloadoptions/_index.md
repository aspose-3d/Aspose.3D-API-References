---
title: "RvmLoadOptions"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

AVEVA Plant Design Management System 的 RVM 文件的加载选项。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(contentType) | 构造一个 RvmLoadOptions 实例 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload() | 构造一个 RvmLoadOptions 实例 |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| 名称 | 描述 |
| --- | --- |
| getGenerateMaterials() | 如果 RVM 文件中未导出颜色表，则为场景中的每个对象生成随机颜色的材质。默认值为 true。 |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| 名称 | 描述 |
| --- | --- |
| setGenerateMaterials(value) | 如果 RVM 文件中未导出颜色表，则为场景中的每个对象生成随机颜色的材质。默认值为 true。 |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| 名称 | 描述 |
| --- | --- |
| getCylinderRadialSegments() | 获取或设置圆柱体的径向段数，默认值为 16。 |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| 名称 | 描述 |
| --- | --- |
| setCylinderRadialSegments(value) | 获取或设置圆柱体的径向段数，默认值为 16。 |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| 名称 | 描述 |
| --- | --- |
| getDishLongitudeSegments() | 获取或设置碟形体的经向段数，默认值为 12。 |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| 名称 | 描述 |
| --- | --- |
| setDishLongitudeSegments(value) | 获取或设置碟形体的经向段数，默认值为 12。 |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| 名称 | 描述 |
| --- | --- |
| getDishLatitudeSegments() | 获取或设置碟形体的纬向段数，默认值为 8。 |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| 名称 | 描述 |
| --- | --- |
| setDishLatitudeSegments(value) | 获取或设置碟形体的纬向段数，默认值为 8。 |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| 名称 | 描述 |
| --- | --- |
| getTorusTubularSegments() | 获取或设置环面的管状段数，默认值为 20。 |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| 名称 | 描述 |
| --- | --- |
| setTorusTubularSegments(value) | 获取或设置环面的管状段数，默认值为 20。 |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| 名称 | 描述 |
| --- | --- |
| getRectangularTorusSegments() | 获取或设置矩形环面的径向段数，默认值为 20。 |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| 名称 | 描述 |
| --- | --- |
| setRectangularTorusSegments(value) | 获取或设置矩形环面的径向段数，默认值为 20。 |

 **Result:**



---


### getCenterScene{#getCenterScene}

| 名称 | 描述 |
| --- | --- |
| getCenterScene() | 在加载后将场景居中。 |

 **Result:**



---


### setCenterScene{#setCenterScene}

| 名称 | 描述 |
| --- | --- |
| setCenterScene(value) | 在加载后将场景居中。 |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| 名称 | 描述 |
| --- | --- |
| getAttributePrefix() | 获取或设置在外部属性文件中定义的属性前缀，前缀用于避免名称冲突，默认值为 "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| 名称 | 描述 |
| --- | --- |
| setAttributePrefix(value) | 获取或设置在外部属性文件中定义的属性前缀，前缀用于避免名称冲突，默认值为 "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| 名称 | 描述 |
| --- | --- |
| getLookupAttributes() | 获取或设置是否从外部属性列表文件（.att/.attrib/.txt）加载属性，默认值为 true。 |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| 名称 | 描述 |
| --- | --- |
| setLookupAttributes(value) | 获取或设置是否从外部属性列表文件（.att/.attrib/.txt）加载属性，默认值为 true。 |

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



