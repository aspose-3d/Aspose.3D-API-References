---
title: "RvmSaveOptions.AttributePrefix"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα RvmSaveOptions. Λαμβάνει ή ορίζει το πρόθεμα των χαρακτηριστικών που θα εξαχθούν· η εξαχθείσα ιδιότητα δεν θα περιέχει πρόθεμα· προσαρμοσμένες ιδιότητες με διαφορετικό πρόθεμα δεν θα εξαχθούν· η προεπιλεγμένη τιμή είναι rvm. Για παράδειγμα, αν μια ιδιότητα είναι rvmRefno345, το εξαχθέν χαρακτηριστικό θα είναι Refno 345· το πρόθεμα αφαιρείται"
type: docs
weight: 30
url: /el/net/aspose.threed.formats/rvmsaveoptions/attributeprefix/
---
## RvmSaveOptions.AttributePrefix property

Λαμβάνει ή ορίζει το πρόθεμα των χαρακτηριστικών που θα εξαχθούν, η εξαγόμενη ιδιότητα δεν θα περιέχει πρόθεμα, προσαρμοσμένες ιδιότητες με διαφορετικό πρόθεμα δεν θα εξαχθούν, η προεπιλεγμένη τιμή είναι 'rvm:'. Για παράδειγμα, εάν μια ιδιότητα είναι rvm:Refno=345, το εξαγόμενο χαρακτηριστικό θα είναι Refno = 345, το πρόθεμα αφαιρείται.

```csharp
public string AttributePrefix { get; set; }
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


