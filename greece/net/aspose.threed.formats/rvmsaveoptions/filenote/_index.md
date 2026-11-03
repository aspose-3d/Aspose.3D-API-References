---
title: "RvmSaveOptions.FileNote"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα RvmSaveOptions. Σημείωση αρχείου στην κεφαλίδα του αρχείου"
type: docs
weight: 70
url: /el/net/aspose.threed.formats/rvmsaveoptions/filenote/
---
## RvmSaveOptions.FileNote property

Σημείωση αρχείου στην κεφαλίδα του αρχείου.

```csharp
public string FileNote { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//Το όνομα του κόμβου απαιτείται για την εξαγωγή χαρακτηριστικών
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Ιδιότητες με πρόθεμα rvm: θα εξαχθούν.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### Δείτε επίσης

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


