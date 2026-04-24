---
title: A3DObject 类
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.A3DObject 类。所有 Aspose.ThreeD 对象的基类，所有子类都将支持动态属性。
type: docs
weight: 10
url: /zh/net/aspose.threed/a3dobject/
---
## A3DObject class

所有 Aspose.ThreeD 对象的基类，所有子类都将支持动态属性。

```csharp
public class A3DObject : INamedObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [A3DObject](a3dobject/#constructor)() | 初始化 `A3DObject` 类的无名称新实例。 |
| [A3DObject](a3dobject/#constructor_1)(string) | 初始化 `A3DObject` 类的新实例。 |

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
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/#removeproperty)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/#removeproperty_1)(string) | 移除通过名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* interface [INamedObject](../inamedobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


