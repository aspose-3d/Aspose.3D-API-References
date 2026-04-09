---
title: Text 类
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Profiles.Text 类。文本轮廓，该轮廓使用字体和文字描述轮廓
type: docs
weight: 1820
url: /zh/net/aspose.threed.profiles/text/
---
## Text class

文本轮廓，此轮廓使用字体和文本描述轮廓。

```csharp
public class Text : Profile
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Text](text/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | 文本内容 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | 文本的字体。 |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | 字体大小比例。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点；如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的边界框。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

## 示例

以下代码展示了如何使用指定的字体文件从文本创建 3D 网格。

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### 另请参见

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


