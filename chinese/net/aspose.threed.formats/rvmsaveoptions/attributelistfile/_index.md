---
title: "RvmSaveOptions.AttributeListFile"
second_title: "Aspose.3D for .NET API 参考"
description: "RvmSaveOptions 属性。获取或设置属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null"
type: docs
weight: 20
url: /zh/net/aspose.threed.formats/rvmsaveoptions/attributelistfile/
---
## RvmSaveOptions.AttributeListFile property

获取或设置属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。

```csharp
public string AttributeListFile { get; set; }
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


