---
title: "Aspose.ThreeD.Utilities"
second_title: "Aspose.3D for .NET API 参考"
description: "所有实用类都定义在此命名空间中。"
type: docs
weight: 100
url: /zh/net/aspose.threed.utilities/
---
所有实用工具类都定义在此命名空间中。

## 类

| 类 | 描述 |
| --- | --- |
| [FileSystem](./filesystem/) | 文件系统封装。Aspose.3D 将使用它来读取/写入依赖项。 |
| [IOExtension](./ioextension/) | 用于将矩阵/向量写入二进制写入器的实用程序 |
| [MathUtils](./mathutils/) | 一组有用的数学实用程序。 |
| [ParseException](./parseexception/) | 当 Aspose.3D 未能解析输入时抛出的异常。 |
| [SemanticAttribute](./semanticattribute/) | 允许用户使用自己的结构来静态声明 [`VertexDeclaration`](../aspose.threed.utilities/vertexdeclaration/) |
| [TransformBuilder](./transformbuilder/) | [`TransformBuilder`](../aspose.threed.utilities/transformbuilder/) 用于通过一系列变换构建变换矩阵。 |
| [Vertex](./vertex/) | 顶点引用，用于访问 [`TriMesh`](../aspose.threed.entities/trimesh/) 中的原始顶点。 |
| [VertexDeclaration](./vertexdeclaration/) | 自定义顶点结构的声明 |
| [VertexField](./vertexfield/) | 顶点字段内存布局描述。 |
| [Watermark](./watermark/) | 用于对网格进行盲水印编码/解码的实用程序。 |
## Structures

| 结构 | 描述 |
| --- | --- |
| [BoundingBox](./boundingbox/) | 轴对齐包围盒 |
| [BoundingBox2D](./boundingbox2d/) | [`Vector2`](../aspose.threed.utilities/vector2/) 的轴对齐包围盒 |
| [FMatrix4](./fmatrix4/) | 所有分量为 float 类型的 4x4 矩阵 |
| [FVector2](./fvector2/) | 具有两个分量的 float 向量。 |
| [FVector3](./fvector3/) | 具有三个分量的 float 向量。 |
| [FVector4](./fvector4/) | 具有四个分量的 float 向量。 |
| [Matrix4](./matrix4/) | 4x4 矩阵实现。 |
| [Quaternion](./quaternion/) | 四元数通常用于在计算机图形学中执行旋转。 |
| [Rect](./rect/) | 用于表示矩形的类 |
| [RelativeRectangle](./relativerectangle/) | 相对矩形。相对组件到绝对值的公式为：Scale * (Reference Width) + offset。因此，如果我们想让它表示绝对值，请将所有 scale 字段设为零，并改用 offset 字段。 |
| [Vector2](./vector2/) | 一个具有两个分量的向量。 |
| [Vector3](./vector3/) | 一个具有三个分量的向量。 |
| [Vector4](./vector4/) | 一个具有四个分量的向量。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IArrayList&lt;T&gt;](./iarraylist-1/) | Aspose.3D 拥有自己高度优化的 List 实现，以获得更好的加载/保存性能。仅向用户公开此接口，且该接口兼容 IList 以及类似的接口。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [BoundingBoxExtent](./boundingboxextent/) | 包围盒的范围 |
| [ComposeOrder](./composeorder/) | 组合变换矩阵的顺序 |
| [RotationOrder](./rotationorder/) | 顺序决定在变换矩阵中先后应用哪些 rx、ry、rz。 |
| [VertexFieldDataType](./vertexfielddatatype/) | 顶点字段的数据类型 |
| [VertexFieldSemantic](./vertexfieldsemantic/) | 顶点字段的语义 |


