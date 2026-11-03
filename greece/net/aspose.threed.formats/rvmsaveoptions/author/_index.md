---
title: "RvmSaveOptions.Author"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα RvmSaveOptions. Πληροφορίες συγγραφέα, η προεπιλεγμένη τιμή είναι 3daspose"
type: docs
weight: 40
url: /el/net/aspose.threed.formats/rvmsaveoptions/author/
---
## RvmSaveOptions.Author property

Πληροφορίες συγγραφέα, η προεπιλεγμένη τιμή είναι '3d@aspose'

```csharp
public string Author { get; set; }
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


