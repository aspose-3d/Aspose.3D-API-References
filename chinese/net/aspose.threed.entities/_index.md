---
title: "Aspose.ThreeD.Entities"
second_title: "Aspose.3D for .NET API 参考"
description: "所有几何体和实体都定义在此命名空间中"
type: docs
weight: 40
url: /zh/net/aspose.threed.entities/
---
所有几何体和实体都定义在此命名空间中

## 类

| 类 | 描述 |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | 此类将变换后的网格封装为布尔运算的操作数。 |
| [BooleanOperator](./booleanoperator/) | 布尔运算符允许您对两个 [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/) 实例执行布尔运算。 |
| [Box](./box/) | 盒子。 |
| [Camera](./camera/) | 相机描述了观察者观看场景的视点。 |
| [Circle](./circle/) | 一个 [`Circle`](../aspose.threed.entities/circle/) 曲线由圆形边缘上的一组点组成。 |
| [CompositeCurve](./compositecurve/) | 一个 [`CompositeCurve`](../aspose.threed.entities/compositecurve/) 由多个曲线段组成。 |
| [Curve](./curve/) | 所有曲线实现的基类。 |
| [Cylinder](./cylinder/) | 参数化圆柱体。当 radiusTop/radiusBottom 中有一个为零时，它也可用于表示圆锥体。 |
| [Dish](./dish/) | 参数化抛物面。 |
| [Ellipse](./ellipse/) | 一个 [`Ellipse`](../aspose.threed.entities/ellipse/) 定义了一组形成椭圆形状的点。 |
| [Frustum](./frustum/) | [`Camera`](../aspose.threed.entities/camera/) 和 [`Light`](../aspose.threed.entities/light/) 的基类。 |
| [Geometry](./geometry/) | 所有可渲染几何对象的基类（如 [`Mesh`](../aspose.threed.entities/mesh/)、[`NurbsSurface`](../aspose.threed.entities/nurbssurface/)、[`Patch`](../aspose.threed.entities/patch/) 等）。 |
| [HalfSpace](./halfspace/) | [`HalfSpace`](../aspose.threed.entities/halfspace/) 表示被平面划分的无限空间，可与 [`BooleanOperator`](../aspose.threed.entities/booleanoperator/) 一起使用。 |
| [Light](./light/) | 光线照亮了场景。 |
| [Line](./line/) | 折线是一条由一组点（使用[`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/)）定义的路径，并通过[`Segments`](../aspose.threed.entities/line/segments/)连接，这意味着它也可以是一组相连的线段。该线通常是线性对象，这意味着它不能用于表示曲线，如需表示曲线，请使用[`NurbsCurve`](../aspose.threed.entities/nurbscurve/)。 |
| [LinearExtrusion](./linearextrusion/) | 线性拉伸以二维形状为输入，并在第三维度上扩展该形状。 |
| [Mesh](./mesh/) | 网格由许多 n 边多边形组成。 |
| [NurbsCurve](./nurbscurve/) | [NURBS 曲线](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) 是一种由 NURBS（非均匀有理基样条）表示的曲线，NURBS 曲线由其[`Order`](../aspose.threed.entities/nurbscurve/order/)、一组加权的[`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/)以及[`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/)定义。控制点中的 w 分量用作控制点的权重，无论它是二维还是三维。 |
| [NurbsDirection](./nurbsdirection/) | 一个 3D [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) 有两个方向，分别是 [`U`](../aspose.threed.entities/nurbssurface/u/) 和 [`V`](../aspose.threed.entities/nurbssurface/v/)，[`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) 为每个方向定义数据。方向实际上是一条 NURBS 曲线，这意味着它也由其[`Order`](../aspose.threed.entities/nurbsdirection/order/)、[`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/)以及一组加权控制点（在 [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) 中定义）决定。 |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) 是一种由 [NURBS（非均匀有理基样条）](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) 表示的曲面，[`NurbsSurface`](../aspose.threed.entities/nurbssurface/) 由两个 [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/)[`U`](../aspose.threed.entities/nurbssurface/u/) 和 [`V`](../aspose.threed.entities/nurbssurface/v/) 定义。控制点中的 w 分量用作控制点的权重，无论方向的类型是二维还是三维。 |
| [Patch](./patch/) | `[`Patch`](../aspose.threed.entities/patch/) 是一种参数化建模曲面，类似于 [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)，它也由两个 [`PatchDirection`](../aspose.threed.entities/patchdirection/)，即 [`U`](../aspose.threed.entities/patch/u/) 和 [`V`](../aspose.threed.entities/patch/v/) 定义。但 [`Patch`](../aspose.threed.entities/patch/) 与 [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) 的区别在于，[`PatchDirection`](../aspose.threed.entities/patchdirection/) 曲线可以是 Bezier、QuadraticBezier、BasisSpline、CardinalSpline 或 Linear 之一。 |
| [PatchDirection](./patchdirection/) | `Patch` 的 U 和 V 方向。 |
| [Plane](./plane/) | 参数化平面。 |
| [PointCloud](./pointcloud/) | 点云不包含拓扑信息，仅包含控制点和顶点元素。 |
| [PolygonBuilder](./polygonbuilder/) | 用于为 [`Mesh`](../aspose.threed.entities/mesh/) 构建多边形的辅助类。 |
| [PolygonModifier](./polygonmodifier/) | 用于修改多边形的实用工具 |
| [Primitive](./primitive/) | 所有基元的基类 |
| [Pyramid](./pyramid/) | 参数化金字塔。 |
| [RectangularTorus](./rectangulartorus/) | 参数化矩形环面。 |
| [RevolvedAreaSolid](./revolvedareasolid/) | 此类通过围绕轴旋转由轮廓提供的横截面来表示实体模型。 |
| [Shape](./shape/) | 该形状描述了一组控制点上的变形，类似于 Maya 中的 cluster deformer。例如，我们可以向已创建的几何体添加形状。形状和几何体具有相同的拓扑信息，但控制点的位置不同。通过不同程度的影响，几何体实现变形效果。 |
| [Skeleton](./skeleton/) | [`Skeleton`](../aspose.threed.entities/skeleton/) 主要被 CAD 软件用于帮助设计师操作骨架结构的变换，在 CAD 软件之外通常无用。为了使骨架层级在 CAD 软件中表现为单一对象，需要通过将 [`Type`](../aspose.threed.entities/skeleton/type/) 设置为 Skeleton，将顶层 [`Skeleton`](../aspose.threed.entities/skeleton/) 节点标记为根节点，并将所有子节点设置为 Bone。 |
| [Sphere](./sphere/) | 参数化球体。 |
| [SweptAreaSolid](./sweptareasolid/) | `[`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) 通过沿导线扫掠轮廓来构建几何体。 |
| [Torus](./torus/) | 参数化环面。 |
| [TransformedCurve](./transformedcurve/) | `[`TransformedCurve`](../aspose.threed.entities/transformedcurve/) 通过使用变换矩阵为曲线提供放置位置。这允许在 [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) 或 [`CompositeCurve`](../aspose.threed.entities/compositecurve/) 中执行变换。 |
| [TriMesh](./trimesh/) | TriMesh 包含可直接被 GPU 使用的原始数据。此类是一个实用工具，用于帮助构建仅包含每顶点数据的网格。 |
| [TriMesh&lt;T&gt;](./trimesh-1/) | 针对用户静态定义的顶点类型的通用版 [`TriMesh`](../aspose.threed.entities/trimesh/)。 |
| [TrimmedCurve](./trimmedcurve/) | 在两端修剪基曲线的有界曲线。 |
| [VertexElement](./vertexelement/) | 顶点元素的基类。顶点元素类型由 VertexElementType 标识。VertexElement 描述顶点元素如何映射到几何表面以及映射信息在内存中的布局。VertexElement 包含法线、UV 或其他类型的信息。 |
| [VertexElementBinormal](./vertexelementbinormal/) | 为指定组件定义副法线向量。 |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | 用于定义具体 [`VertexElement`](../aspose.threed.entities/vertexelement/) 实现的辅助类。 |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | 为指定组件定义边缘折痕 |
| [VertexElementHole](./vertexelementhole/) | 定义指定多边形是否为孔洞 |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | 用于定义具体 [`VertexElement`](../aspose.threed.entities/vertexelement/) 实现的辅助类。 |
| [VertexElementMaterial](./vertexelementmaterial/) | 为指定组件定义材质索引。一个节点可以拥有多种材质，[`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) 用于在不同材质下渲染几何体的不同部分。 |
| [VertexElementNormal](./vertexelementnormal/) | 为指定组件定义法线向量。 |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | 为指定组件定义多边形组，以将相关多边形归为一组。 |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | 平滑组是多边形网格中的一组多边形，旨在呈现平滑表面。早期的一些 3D 建模软件（如 DOS 版 3D Studio Max）使用平滑组来避免为每个网格顶点存储法线向量。 |
| [VertexElementSpecular](./vertexelementspecular/) | 为指定组件定义高光颜色。 |
| [VertexElementTangent](./vertexelementtangent/) | 为指定组件定义切线向量。 |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | 用于定义具体 [`VertexElement`](../aspose.threed.entities/vertexelement/) 实现的辅助类。 |
| [VertexElementUserData](./vertexelementuserdata/) | 为指定组件定义自定义用户数据。通常这是针对特定用途的应用程序专用数据。 |
| [VertexElementUV](./vertexelementuv/) | 为指定组件定义 UV 坐标。几何体可以拥有多个 [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) 元素，每个元素都有不同的 [`TextureMapping`](../aspose.threed.entities/texturemapping/)。 |
| [VertexElementVector4](./vertexelementvector4/) | 用于定义具体 [`VertexElement`](../aspose.threed.entities/vertexelement/) 实现的辅助类。 |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | 为指定组件定义顶点颜色 |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | 为指定组件定义顶点折痕 |
| [VertexElementVisibility](./vertexelementvisibility/) | 定义指定组件是否可见 |
| [VertexElementWeight](./vertexelementweight/) | 为指定组件定义混合权重。 |
## Structures

| 结构 | 描述 |
| --- | --- |
| [EndPoint](./endpoint/) | 用于修剪曲线的端点，可以是参数值或笛卡尔点。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | 带有索引数据的 VertexElement。 |
| [IMeshConvertible](./imeshconvertible/) | 实现此接口的实体可以转换为 [`Mesh`](../aspose.threed.entities/mesh/) |
| [IOrientable](./iorientable/) | 可定向实体应实现此接口。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ApertureMode](./aperturemode/) | 相机光圈模式。光圈模式决定哪些数值驱动相机光圈。如果光圈模式为 HorizAndVert、Horizontal 或 Vertical，则使用视场角。如果光圈模式为 FocalLength，则使用焦距。 |
| [BooleanOperation](./booleanoperation/) | 网格的布尔运算 |
| [CurveDimension](./curvedimension/) | 曲线的维度。 |
| [LightType](./lighttype/) | 光类型。 |
| [MappingMode](./mappingmode/) | 确定元素如何映射到表面。[`MappingMode`](../aspose.threed.entities/mappingmode/) 定义了[`VertexElement`](../aspose.threed.entities/vertexelement/) 如何映射到几何体的表面。 |
| [NurbsType](./nurbstype/) | NURBS 类型。 |
| [PatchDirectionType](./patchdirectiontype/) | 补丁方向的类型。 |
| [ProjectionType](./projectiontype/) | 相机的投影类型。 |
| [ReferenceMode](./referencemode/) | [`ReferenceMode`](../aspose.threed.entities/referencemode/) 定义了映射信息的存储和引用方式。 |
| [RotationMode](./rotationmode/) | 视锥体的旋转模式 |
| [SkeletonType](./skeletontype/) | [`Skeleton`](../aspose.threed.entities/skeleton/) 的类型。 |
| [SplitMeshPolicy](./splitmeshpolicy/) | 在子网格之间共享顶点/控制点数据，或每个子网格拥有自己的压缩数据。 |
| [TextureMapping](./texturemapping/) | 用于[`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) 的纹理映射类型，描述使用了哪种纹理映射。 |
| [VertexElementType](./vertexelementtype/) | 顶点元素的类型，定义了它在建模中的使用方式。 |


