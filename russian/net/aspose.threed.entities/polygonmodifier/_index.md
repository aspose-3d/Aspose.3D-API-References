---
title: "Класс PolygonModifier"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.PolygonModifier. Утилиты для изменения полигонов"
type: docs
weight: 620
url: /ru/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

Утилиты для изменения полигонов.

```csharp
public class PolygonModifier
```

## Методы

| Имя | Описание |
| --- | --- |
| static [ApplyTransform](../../aspose.threed.entities/polygonmodifier/applytransform/)(Node, Matrix4) | Применить матрицу преобразования к контрольным точкам всех геометрий |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | Это создаст касательные и бинормали на сетке. Нормаль требуется; если нормаль отсутствует на сетке, она также будет создана из позиции. UV также требуется, будет выброшено исключение, если UV не найдено. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | Это создаст касательные и бинормали на всех сетках сцены. Нормаль требуется; если нормаль отсутствует на сетке, она также будет создана из позиции. UV также требуется, сетка будет игнорироваться, если UV не определён. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | Сгенерировать данные нормалей из определения Mesh |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | Сгенерировать UV‑данные из заданной входной Mesh |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | Сгенерировать UV‑данные из заданной входной Mesh и указанных данных нормалей. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | Преобразовать весь узел в одну трансформированную Mesh. Элементы вершины, такие как нормали/текстурные координаты, пока не поддерживаются. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | Преобразовать всю сцену в одну трансформированную Mesh. Элементы вершины, такие как нормали/текстурные координаты, пока не поддерживаются. |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | Масштабировать все геометрии (масштабировать контрольные точки, а не матрицу преобразования) в этом узле |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | Масштабировать все геометрии (масштабировать контрольные точки, а не матрицу преобразования) в этой сцене |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | Разделите сетку на под‑сетки с помощью [`VertexElementMaterial`](../vertexelementmaterial/). Каждая под‑сетка будет использовать только один материал. Исходная сетка не будет изменена |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | Разделите сетку на под‑сетки с помощью [`VertexElementMaterial`](../vertexelementmaterial/). Каждая под‑сетка будет использовать только один материал. Выполните разбиение сетки на всех узлах сцены. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | Разделите сетку на под‑сетки с помощью [`VertexElementMaterial`](../vertexelementmaterial/). Каждая под‑сетка будет использовать только один материал. Выполните разбиение сетки на узле |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | Преобразуйте полигональную сетку в полную треугольную сетку |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | Преобразуйте все полигональные сетки в полные треугольные сетки |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### См. также

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


