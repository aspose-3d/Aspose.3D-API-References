---
title: "RvmSaveOptions.AttributePrefix"
second_title: "Aspose.3D for .NET API 参考"
description: "RvmSaveOptions 属性。获取或设置将被导出的属性前缀，导出的属性将不包含前缀；具有不同前缀的自定义属性将不会被导出，默认值为 rvm。例如，如果属性为 rvmRefno345，则导出的属性为 Refno 345，前缀被去除"
type: docs
weight: 30
url: /zh/net/aspose.threed.formats/rvmsaveoptions/attributeprefix/
---
## RvmSaveOptions.AttributePrefix property

获取或设置将被导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。例如，如果属性为 rvm:Refno=345，导出的属性将为 Refno = 345，前缀被去除。

```csharp
public string AttributePrefix { get; set; }
```

## 示例

以下代码展示了如何在 RVM 中导出属性。

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//导出属性需要节点名称
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//带有 rvm: 前缀的属性将被导出。
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### 另请参见

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


