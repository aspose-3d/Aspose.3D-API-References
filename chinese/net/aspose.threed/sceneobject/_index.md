---
title: 类 SceneObject
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.SceneObject 类。将在场景中存储的对象的根类
type: docs
weight: 2510
url: /zh/net/aspose.threed/sceneobject/
---
## SceneObject class

将在场景内部存储的对象的根类。

```csharp
public abstract class SceneObject : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SceneObject](sceneobject/#constructor)() | 初始化 SceneObject。 |
| [SceneObject](sceneobject/#constructor_1)(string) | 使用默认名称初始化 SceneObject |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |

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


