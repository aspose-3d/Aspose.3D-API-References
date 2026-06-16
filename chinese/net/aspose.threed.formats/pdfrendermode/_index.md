---
title: "枚举 PdfRenderMode"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.PdfRenderMode 枚举。渲染模式指定 3D 艺术作品的渲染风格"
type: docs
weight: 1410
url: /zh/net/aspose.threed.formats/pdfrendermode/
---
## PdfRenderMode enumeration

渲染模式指定 3D 艺术作品的渲染风格。

```csharp
public enum PdfRenderMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Solid | `0` | 显示带纹理和光照的几何形状。 |
| SolidWireframe | `1` | 显示带纹理和光照的几何形状（三角形），并在其上方绘制单色边缘。 |
| Transparent | `2` | 显示带纹理和光照的几何形状（三角形），并添加透明度层级。 |
| TransparentWireframe | `3` | 显示带纹理和光照的几何形状（三角形），并添加透明度层级，同时在其上方绘制单色不透明边缘。 |
| BoundingBox | `4` | 显示每个节点的包围盒边缘，且与该节点局部坐标空间的轴对齐。 |
| TransparentBoundingBox | `5` | 显示每个节点的包围盒面，且与该节点局部坐标空间的轴对齐，并添加透明度层级。 |
| TransparentBoundingBoxOutline | `6` | 显示每个节点的包围盒边缘和面， 与该节点的局部坐标空间轴对齐，并添加了透明度层级。 |
| Wireframe | `7` | 仅以单一颜色显示边缘。 |
| ShadedWireframe | `8` | 仅显示边缘，但在两个顶点之间插值其颜色并应用光照。 |
| HiddenWireframe | `9` | 以单一颜色显示边缘，但去除背向和被遮挡的边缘。 |
| Vertices | `10` | 仅以单一颜色显示顶点。 |
| ShadedVertices | `11` | 仅显示顶点，但使用其顶点颜色并应用光照。 |
| Illustration | `12` | 显示带有表面的轮廓边缘，去除被遮挡的线条。 |
| SolidOutline | `13` | 显示带有光照和纹理表面的轮廓边缘，去除被遮挡的线条。 |
| ShadedIllustration | `14` | 显示带有光照和纹理表面的轮廓边缘，并添加额外的自发光项以去除作品中光照不足的区域。 |

### 另请参见

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


