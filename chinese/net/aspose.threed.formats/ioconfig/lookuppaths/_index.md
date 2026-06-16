---
title: "IOConfig.LookupPaths"
second_title: "Aspose.3D for .NET API 参考"
description: "IOConfig 属性。某些文件如 OBJ 依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件"
type: docs
weight: 50
url: /zh/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。

```csharp
public List<string> LookupPaths { get; set; }
```

## 示例

以下代码展示了如何手动指定查找纹理，以便导入器能够找到它们

```csharp
var opt = new ObjLoadOptions();
//指定查找路径，以便定位纹理。
opt.LookupPaths.Add("textures");
var scene = Scene.FromFile("input.obj", opt);
scene.Save("output.glb");
```

### 另请参见

* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


