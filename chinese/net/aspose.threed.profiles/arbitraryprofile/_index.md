---
title: "ArbitraryProfile 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Profiles.ArbitraryProfile 类。 此类允许您直接从任意曲线构建二维轮廓"
type: docs
weight: 1670
url: /zh/net/aspose.threed.profiles/arbitraryprofile/
---
## ArbitraryProfile class

此类允许您直接从任意曲线构建 2D 配置文件。

```csharp
public class ArbitraryProfile : Profile
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ArbitraryProfile](arbitraryprofile/#constructor)() | `ArbitraryProfile` 的构造函数 |
| [ArbitraryProfile](arbitraryprofile/#constructor_1)(Curve) | `ArbitraryProfile` 的构造函数，带有初始曲线。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Curve](../../aspose.threed.profiles/arbitraryprofile/curve/) { get; set; } | 用于构建轮廓的曲线 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [Holes](../../aspose.threed.profiles/arbitraryprofile/holes/) { get; } | 轮廓的孔，也表示为曲线 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


