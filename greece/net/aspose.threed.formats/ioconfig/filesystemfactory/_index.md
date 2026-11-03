---
title: "IOConfig.FileSystemFactory"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα IOConfig. Λαμβάνει ή ορίζει την κλάση εργοστασίου για το FileSystem. Η προεπιλεγμένη εργοστασιακή κλάση θα δημιουργήσει LocalFileSystem, η οποία δεν είναι κατάλληλη για περιβάλλον διακομιστή"
type: docs
weight: 60
url: /el/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

Λαμβάνει ή ορίζει την κλάση εργοστασίου για το FileSystem. Το προεπιλεγμένο εργοστάσιο θα δημιουργήσει το LocalFileSystem, το οποίο δεν είναι κατάλληλο για περιβάλλον διακομιστή.

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## Παραδείγματα

Το προεπιλεγμένο FileSystem στα SaveOptions/LoadOptions είναι σύστημα αρχείων βασισμένο σε κατάλογο· μπορείτε να παρακάμψετε την προεπιλεγμένη υλοποίηση καθορίζοντάς το μέσω IOConfig.FileSystemFactory:

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//Το opt.FileSystem θα είναι τώρα ψεύτικο σύστημα αρχείων
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//Το αρχείο υλικού output.mtl δεν θα γραφτεί πουθενά επειδή έχουμε ρυθμίσει ένα ψεύτικο σύστημα αρχείων ως προεπιλεγμένη υλοποίηση.
```

### Δείτε επίσης

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


