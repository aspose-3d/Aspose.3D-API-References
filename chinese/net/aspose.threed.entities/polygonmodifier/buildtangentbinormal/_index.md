---
title: "PolygonModifier.BuildTangentBinormal"
second_title: "Aspose.3D for .NET API 参考"
description: "PolygonModifier 方法。此操作将在场景的所有网格上创建切线和副法线。如果网格上不存在法线，则需要法线，并且它还会从位置创建法线数据。UV 也是必需的，如果未定义 UV，则该网格将被忽略。"
type: docs
weight: 20
url: /zh/net/aspose.threed.entities/polygonmodifier/buildtangentbinormal/
---
## BuildTangentBinormal(Scene) {#buildtangentbinormal_1}

这将在场景的所有 mesh 上创建切线和副法线。需要 Normal，如果某个 mesh 上不存在 Normal，它还会根据位置创建 Normal 数据。UV 也必须存在，如果未定义 UV，则该 mesh 将被忽略。

```csharp
public static void BuildTangentBinormal(Scene scene)
```

### 另请参见

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## BuildTangentBinormal(Mesh) {#buildtangentbinormal}

这将在 mesh 上创建切线和副法线。需要 Normal，如果 mesh 上不存在 Normal，它还会根据位置创建 Normal 数据。UV 也必须存在，如果未找到 UV，将抛出异常。

```csharp
public static void BuildTangentBinormal(Mesh mesh)
```

### 另请参见

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


