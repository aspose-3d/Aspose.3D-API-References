---
title: "Scene.AssetInfo"
second_title: "Aspose.3D for .NET API 参考"
description: "Scene 属性。获取或设置顶层资产信息"
type: docs
weight: 50
url: /zh/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

获取或设置顶层资产信息

```csharp
public AssetInfo AssetInfo { get; set; }
```

### Property Value

文档信息。

## 示例

以下代码展示了如何从 FBX 文件读取应用程序信息：

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The FBX file is created by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion}");
```

### 另请参见

* class [AssetInfo](../../assetinfo/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


