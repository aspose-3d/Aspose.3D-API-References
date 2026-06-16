---
title: "类 PostProcessing"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.PostProcessing 类。后处理效果"
type: docs
weight: 2250
url: /zh/net/aspose.threed.render/postprocessing/
---
## PostProcessing class

后处理效果

```csharp
public abstract class PostProcessing : A3DObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [Input](../../aspose.threed.render/postprocessing/input/) { get; set; } | 此后处理的输入 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


