---
title: "RvmSaveOptions.AttributeListFile"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα RvmSaveOptions. Λαμβάνει ή ορίζει το όνομα αρχείου της λίστας χαρακτηριστικών· ο εξαγωγέας θα δημιουργήσει ένα όνομα βάσει του ονόματος αρχείου .rvm όταν αυτή η ιδιότητα είναι ακαθόριστη. Η προεπιλεγμένη τιμή είναι null"
type: docs
weight: 20
url: /el/net/aspose.threed.formats/rvmsaveoptions/attributelistfile/
---
## RvmSaveOptions.AttributeListFile property

Λαμβάνει ή ορίζει το όνομα αρχείου της λίστας χαρακτηριστικών, ο εξαγωγέας θα δημιουργήσει ένα όνομα βασισμένο στο όνομα του αρχείου .rvm όταν αυτή η ιδιότητα είναι ακαθόριστη, η προεπιλεγμένη τιμή είναι null.

```csharp
public string AttributeListFile { get; set; }
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


