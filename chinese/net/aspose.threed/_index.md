---
title: Aspose.ThreeD
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.3D 的基础命名空间
type: docs
weight: 10
url: /zh/net/aspose.threed/
---
Aspose.3D 的基础命名空间

## 类

| 类 | 描述 |
| --- | --- |
| [A3DObject](./a3dobject/) | 所有 Aspose.ThreeD 对象的基类，所有子类都将支持动态属性。 |
| [AssetInfo](./assetinfo/) | 资产信息。资产信息可以附加到一个[`Scene`](../aspose.threed/scene/)。子[`Scene`](../aspose.threed/scene/)可以拥有自己的[`AssetInfo`](../aspose.threed/assetinfo/)来覆盖父级的定义。 |
| [AxisSystem](./axissystem/) | 轴系是坐标系统、上向量和前向量的组合。 |
| [BonePose](./bonepose/) | [`BonePose`](../aspose.threed/bonepose/) 包含骨骼节点的变换矩阵。 |
| [CustomObject](./customobject/) | 此类管理 3D 文件中使用的元数据或自定义对象。所有自定义属性都保存为动态属性。 |
| [Entity](./entity/) | 所有实体的基类。Entity 表示一个具体对象，附加在类似[`Light`](../aspose.threed.entities/light/)/[`Geometry`](../aspose.threed.entities/geometry/)的节点下。 |
| [ExportException](./exportexception/) | Aspose.3D 导出场景到文件失败时的异常 |
| [FileFormat](./fileformat/) | 文件格式定义 |
| [FileFormatType](./fileformattype/) | 文件格式类型 |
| [GlobalTransform](./globaltransform/) | 全局变换类似于[`Transform`](../aspose.threed/transform/)，但它是不可变的，因为它表示最终评估后的变换。在评估全局变换时使用右手坐标系。 |
| [Group](./group/) | [`Group`](../aspose.threed/group/) 表示[`Node`](../aspose.threed/node/)的逻辑关系。 |
| [ImageRenderOptions](./imagerenderoptions/) | [`Render`](../aspose.threed/scene/render/) 和 [`Render`](../aspose.threed/scene/render/) 的选项 |
| [ImportException](./importexception/) | Aspose.3D 打开指定源失败时的异常。 |
| [License](./license/) | 提供对组件授权的方法。 |
| [Metered](./metered/) | 提供设置计量键的方法。 |
| [Node](./node/) | 表示场景图中的一个元素。场景图是由 Node 对象组成的树。树的管理服务封装在此类中。请注意，Aspose.3D SDK 不会验证构建的场景图的有效性。调用者有责任确保不会在节点层次结构中生成循环图。除了树管理之外，此类还定义了描述对象在场景中位置所需的所有属性。这些信息包括基本的平移、旋转和缩放属性，以及用于枢轴、限制和 IK 关节属性（如刚度和阻尼）的更高级选项。首次创建时，Node 对象是"empty"（即：它是一个没有任何图形表示，仅包含位置信息的对象）。在此状态下，它可用于表示节点树结构中的父节点，但功能有限。此类对象的常规用法是为其添加一个实体以专门化节点（参见"Entity"）。实体本身是一个对象，并与 Node 关联。这也意味着同一实体可以在多个节点之间共享。Camera、Light、Mesh 等都是实体，并且它们都派生自基类 Entity。 |
| [NodeVisitor](./nodevisitor/) | 回调函数，用于遍历整个节点层次结构。 |
| [Pose](./pose/) | 姿势用于在几何体进行蒙皮时存储变换矩阵。姿势是一组[`BonePose`](../aspose.threed/bonepose/)，每个[`BonePose`](../aspose.threed/bonepose/)保存骨骼节点的具体变换信息。 |
| [Property](./property/) | 用于保存用户自定义属性的类。 |
| [PropertyCollection](./propertycollection/) | 属性集合 |
| [Scene](./scene/) | 场景是一个顶层对象，包含节点、几何体、材质、纹理、动画、姿势、子场景等。场景可以拥有子场景，在 collada、blender、fbx 等文件中充当多文档支持。节点层次结构可通过[`RootNode`](../aspose.threed/scene/rootnode/)[`Library`](../aspose.threed/scene/library/)访问，Library 用于在序列化期间（如元数据或自定义对象）保存未附加对象的引用，以便将其用作库。 |
| [SceneObject](./sceneobject/) | 将在场景内部存储的对象的根类。 |
| [Transform](./transform/) | 变换包含允许以最低成本访问对象的平移/缩放/旋转或变换矩阵的信息，这用于局部变换。 |
| [TrialException](./trialexception/) | 当未应用许可证时，在 Scene.Open/Scene.Save 中会抛出此异常。您可以通过将 SuppressTrialException 设置为 true 来关闭此异常。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [INamedObject](./inamedobject/) | 具有名称的对象 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [Axis](./axis/) | 坐标轴。 |
| [CoordinateSystem](./coordinatesystem/) | 左手坐标系或右手坐标系。 |
| [FileContentType](./filecontenttype/) | 文件内容类型 |
| [PoseType](./posetype/) | 姿势类型。 |
| [PropertyFlags](./propertyflags/) | 属性的标志 |


