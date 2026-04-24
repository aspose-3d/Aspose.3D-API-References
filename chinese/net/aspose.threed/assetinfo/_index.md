---
title: 类 AssetInfo
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.AssetInfo 类。资产信息。资产信息可以附加到 Scene。子 Scene 可以拥有自己的 AssetInfo 来覆盖父级的定义。
type: docs
weight: 130
url: /zh/net/aspose.threed/assetinfo/
---
## AssetInfo class

资产信息。资产信息可以附加到一个 [`Scene`](../scene/)。子 [`Scene`](../scene/) 可以拥有自己的 `AssetInfo` 来覆盖父级的定义。

```csharp
public class AssetInfo : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AssetInfo](assetinfo/#constructor)() | 初始化 `AssetInfo` 类的新实例。 |
| [AssetInfo](assetinfo/#constructor_1)(string) | 初始化 `AssetInfo` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Ambient](../../aspose.threed/assetinfo/ambient/) { get; set; } | 获取或设置此资产的默认环境颜色 |
| [ApplicationName](../../aspose.threed/assetinfo/applicationname/) { get; set; } | 获取或设置创建此资产的应用程序 |
| [ApplicationVendor](../../aspose.threed/assetinfo/applicationvendor/) { get; set; } | 获取或设置应用程序供应商的名称 |
| [ApplicationVersion](../../aspose.threed/assetinfo/applicationversion/) { get; set; } | 获取或设置创建此资产的应用程序的版本。 |
| [Author](../../aspose.threed/assetinfo/author/) { get; set; } | 获取或设置此资产的作者 |
| [AxisSystem](../../aspose.threed/assetinfo/axissystem/) { get; set; } | 获取或设置资产信息的坐标系/上向量/前向量。 |
| [Comment](../../aspose.threed/assetinfo/comment/) { get; set; } | 获取或设置此资产的注释。 |
| [CoordinateSystem](../../aspose.threed/assetinfo/coordinatesystem/) { get; set; } | 获取或设置此资产使用的坐标系。 |
| [Copyright](../../aspose.threed/assetinfo/copyright/) { get; set; } | 获取或设置文档的版权信息 |
| [CreationTime](../../aspose.threed/assetinfo/creationtime/) { get; set; } | 获取或设置此资产的创建时间 |
| [FrontVector](../../aspose.threed/assetinfo/frontvector/) { get; set; } | 获取或设置此资产使用的前向量。 |
| [Keywords](../../aspose.threed/assetinfo/keywords/) { get; set; } | 获取或设置此资产的关键字 |
| [ModificationTime](../../aspose.threed/assetinfo/modificationtime/) { get; set; } | 获取或设置此资产的修改时间 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Revision](../../aspose.threed/assetinfo/revision/) { get; set; } | 获取或设置此资产的修订号，通常用于版本控制系统。 |
| [Subject](../../aspose.threed/assetinfo/subject/) { get; set; } | 获取或设置此资产的主题 |
| [Title](../../aspose.threed/assetinfo/title/) { get; set; } | 获取或设置此资产的标题 |
| [UnitName](../../aspose.threed/assetinfo/unitname/) { get; set; } | 获取或设置此资产使用的长度单位，例如 cm/m/km/英寸/英尺 |
| [UnitScaleFactor](../../aspose.threed/assetinfo/unitscalefactor/) { get; set; } | 获取或设置到实际米的比例因子。 |
| [UpVector](../../aspose.threed/assetinfo/upvector/) { get; set; } | 获取或设置此资产使用的上向量。 |
| [Url](../../aspose.threed/assetinfo/url/) { get; set; } | 获取或设置此资产的 URL。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

## 示例

以下代码演示如何从 fbx 文件读取资产信息：

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The file is created at {scene.AssetInfo.CreationTime} by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion} ");
```

### 另请参见

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


