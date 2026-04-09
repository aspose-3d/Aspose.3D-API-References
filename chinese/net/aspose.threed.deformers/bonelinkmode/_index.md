---
title: 枚举 BoneLinkMode
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Deformers.BoneLinkMode 枚举。骨骼链接模式指的是骨骼在层次结构中与其父骨骼连接或链接的方式。
type: docs
weight: 200
url: /zh/net/aspose.threed.deformers/bonelinkmode/
---
## BoneLinkMode enumeration

骨骼的链接模式指骨骼在层次结构中与其父骨骼连接或链接的方式。

```csharp
public enum BoneLinkMode
```

### 值

| 名称 | 数值 | 描述 |
| --- | --- | --- |
| Normalize | `0` | 在此模式下，子骨骼的变换会相对于其父骨骼的变换进行归一化。 |
| Additive | `1` | 加法模式通过将子骨骼的局部变换加到父骨骼的变换上来计算子骨骼的变换。 |
| TotalOne | `2` | Total One 确保父子骨骼的组合变换产生的整体变换缩放至整体长度为一个单位。 |

### 另请参见

* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


