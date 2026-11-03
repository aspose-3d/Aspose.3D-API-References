---
title: "DummyFileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: 
type: docs
weight: 2570
url: /el/net/aspose.threed.utilities/dummyfilesystem/
---
## DummyFileSystem class

Οι λειτουργίες ανάγνωσης/εγγραφής είναι ψεύτικες λειτουργίες.

```csharp
public class DummyFileSystem : FileSystem
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DummyFileSystem](dummyfilesystem)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Αποδεσμεύστε το σύστημα αρχείων και απελευθερώστε τους πόρους του. |
| override [ReadFile](../../aspose.threed.utilities/dummyfilesystem/readfile)(string, IOConfig) | Δημιουργήστε μια ροή για την ανάγνωση εξαρτήσεων. |
| override [WriteFile](../../aspose.threed.utilities/dummyfilesystem/writefile)(string, IOConfig) | Δημιουργήστε μια ροή για τη γραφή εξαρτήσεων. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε το αρχείο στη μνήμη και να αγνοήσετε όλες τις εξαρτημένες δημιουργίες αρχείων.

```csharp
//δημιουργήστε μια σκηνή με υλικό
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//δημιουργήστε μια επιλογή αποθήκευσης και καθορίστε το σύστημα αρχείων, ώστε το εξαρτημένο αρχείο να γραφτεί στη μνήμη
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = new DummyFileSystem();
opt.FileSystem = dfs;
//Το όνομα αρχείου υλικού του obj συσχετίζεται με το όνομα αρχείου του obj, επομένως χρειαζόμαστε ένα σαφές όνομα.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Δείτε επίσης

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για Aspose.3D.dll -->
