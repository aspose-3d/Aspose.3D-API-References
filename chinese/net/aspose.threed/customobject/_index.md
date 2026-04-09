---
title: CustomObject 类
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.CustomObject 类。用于管理 3D 文件中使用的元数据或自定义对象。所有自定义属性均保存为动态属性。
type: docs
weight: 180
url: /zh/net/aspose.threed/customobject/
---
## CustomObject class

此类管理 3D 文件中使用的元数据或自定义对象。所有自定义属性都保存为动态属性。

```csharp
public class CustomObject : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CustomObject](customobject/#constructor)() | 初始化 `CustomObject` 类的新实例。 |
| [CustomObject](customobject/#constructor_1)(string) | 初始化 `CustomObject` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


