---
title: 类 Node
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Node 类。表示场景图中的一个元素。场景图是由 Node 对象组成的树。树的管理服务全部封装在此类中。请注意，Aspose.3D SDK 不会检测构建的场景图的有效性。调用者有责任确保不会在节点层次结构中生成循环图。除了树管理外，此类还定义了描述对象在场景中位置所需的所有属性。这些信息包括基本的平移、旋转和缩放属性，以及用于枢轴、限制和 IK 关节的更高级选项，如刚度和阻尼。首次创建时，Node 对象为空，即它是一个没有任何图形表示、仅包含位置信息的对象。在此状态下，它可用于表示节点树结构中的父节点，但功能有限。此类对象的常规用法是为其添加一个实体，以专门化节点，参见 Entity。实体本身也是一个对象，并与 Node 关联。这也意味着同一实体可以在多个节点之间共享。Camera、Light、Mesh 等都是实体，并且都派生自基类 Entity。
type: docs
weight: 1630
url: /zh/net/aspose.threed/node/
---
## Node class

表示场景图中的一个元素。场景图是由 Node 对象组成的树。树的管理服务封装在此类中。请注意，Aspose.3D SDK 不会验证构建的场景图的有效性。调用者有责任确保不会在节点层次结构中生成循环图。除了树管理之外，此类还定义了描述对象在场景中位置所需的所有属性。这些信息包括基本的平移、旋转和缩放属性，以及用于枢轴、限制和 IK 关节属性（如刚度和阻尼）的更高级选项。首次创建时，Node 对象是"empty"（即：它是一个没有任何图形表示，仅包含位置信息的对象）。在此状态下，它可用于表示节点树结构中的父节点，但功能有限。此类对象的常规用法是为其添加一个实体以专门化节点（参见"Entity"）。实体本身是一个对象，并与 Node 关联。这也意味着同一实体可以在多个节点之间共享。Camera、Light、Mesh 等都是实体，并且它们都派生自基类 Entity。

```csharp
public class Node : SceneObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Node](node/#constructor)() | 初始化 `Node` 类的新实例。 |
| [Node](node/#constructor_1)(string) | 初始化 `Node` 类的新实例。 |
| [Node](node/#constructor_2)(string, Entity) | 初始化 `Node` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssetInfo](../../aspose.threed/node/assetinfo/) { get; set; } | 每个节点的资源信息 |
| [ChildNodes](../../aspose.threed/node/childnodes/) { get; } | 获取子节点集合。 |
| [Entities](../../aspose.threed/node/entities/) { get; } | 获取所有节点实体。 |
| [Entity](../../aspose.threed/node/entity/) { get; set; } | 获取或设置附加到此节点的第一个实体，若设置，将清除其他实体。 |
| [Excluded](../../aspose.threed/node/excluded/) { get; set; } | 获取或设置在导出时是否排除此节点及其所有子节点/实体。 |
| [GlobalTransform](../../aspose.threed/node/globaltransform/) { get; } | 获取全局变换。 |
| [Material](../../aspose.threed/node/material/) { get; set; } | 获取或设置与此节点关联的第一种材质，若设置，将清除其他材质。 |
| [Materials](../../aspose.threed/node/materials/) { get; } | 获取与此节点关联的材质。 |
| [MetaDatas](../../aspose.threed/node/metadatas/) { get; } | 获取此节点中定义的元数据。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/node/parentnode/) { get; set; } | 获取或设置父节点。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Transform](../../aspose.threed/node/transform/) { get; } | 获取局部变换。 |
| [Visible](../../aspose.threed/node/visible/) { get; set; } | 获取或设置以显示节点。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accept](../../aspose.threed/node/accept/)(NodeVisitor) | 遍历所有后代节点（包括当前节点），并将访问者调用到该节点。访问者可以通过返回 false 来中断遍历。 |
| [AddChildNode](../../aspose.threed/node/addchildnode/)(Node) | 向此节点添加子节点 |
| [AddEntity](../../aspose.threed/node/addentity/)(Entity) | 向节点添加实体。 |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode)() | 创建子节点 |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_1)(Entity) | 创建一个附加了给定实体的新子节点 |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_2)(string) | 使用给定节点名称创建一个新子节点 |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_3)(string, Entity) | 使用给定节点名称创建一个新子节点 |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_4)(string, Entity, Material) | 使用给定的节点名称创建一个新子节点，并附加指定的实体和材质 |
| [EvaluateGlobalTransform](../../aspose.threed/node/evaluateglobaltransform/)(bool) | 评估全局变换，是否包括几何变换。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetBoundingBox](../../aspose.threed/node/getboundingbox/)() | 计算节点的包围盒 |
| [GetChild](../../aspose.threed/node/getchild/#getchild)(int) | 获取指定索引处的子节点。 |
| [GetChild](../../aspose.threed/node/getchild/#getchild_1)(string) | 获取具有指定名称的子节点 |
| [GetEntity&lt;T&gt;](../../aspose.threed/node/getentity/)() |  |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [Merge](../../aspose.threed/node/merge/)(Node) | 分离节点下的所有内容并将其附加到当前节点。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [SelectObjects](../../aspose.threed/node/selectobjects/)(string) | 使用类似 XPath 的查询语法选择当前节点下的多个对象。 |
| [SelectSingleObject](../../aspose.threed/node/selectsingleobject/)(string) | 使用类似 XPath 的查询语法选择当前节点下的单个对象。 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| override [ToString](../../aspose.threed/node/tostring/)() | 获取此节点的字符串表示。 |

### 另请参见

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


