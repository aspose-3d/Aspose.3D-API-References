---
title: "MemoryFileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: 
type: docs
weight: 2680
url: /el/net/aspose.threed.utilities/memoryfilesystem/
---
## MemoryFileSystem class

Το [`MemoryFileSystem`](../memoryfilesystem) θα χαρτογραφήσει τις λειτουργίες ανάγνωσης/εγγραφής στη μνήμη.

```csharp
public class MemoryFileSystem : FileSystem
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MemoryFileSystem](memoryfilesystem)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [FileNames](../../aspose.threed.utilities/memoryfilesystem/filenames) { get; } | Ονόματα αρχείων σε αυτό το σύστημα αρχείων μνήμης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Αποδεσμεύστε το σύστημα αρχείων και απελευθερώστε τους πόρους του. |
| [GetFileContent](../../aspose.threed.utilities/memoryfilesystem/getfilecontent)(string) | Επιστρέφει το ακατέργαστο περιεχόμενο του συγκεκριμένου αρχείου. Ρίχνει FileNotFoundException εάν το συγκεκριμένο αρχείο δεν υπάρχει. |
| override [ReadFile](../../aspose.threed.utilities/memoryfilesystem/readfile)(string, IOConfig) | Δημιουργήστε μια ροή για την ανάγνωση εξαρτήσεων. |
| override [WriteFile](../../aspose.threed.utilities/memoryfilesystem/writefile)(string, IOConfig) | Δημιουργήστε μια ροή για τη γραφή εξαρτήσεων. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε το αρχείο στη μνήμη, περιλαμβάνοντας το εξαρτημένο αρχείο χρησιμοποιώντας MemoryFileSystem.

```csharp
//δημιουργήστε μια σκηνή με υλικό
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//δημιουργήστε μια επιλογή αποθήκευσης και καθορίστε το σύστημα αρχείων, ώστε το εξαρτημένο αρχείο να γραφτεί στη μνήμη
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var mfs = new MemoryFileSystem();
opt.FileSystem = mfs;
//Το όνομα αρχείου υλικού του obj συσχετίζεται με το όνομα αρχείου του obj, επομένως χρειαζόμαστε ένα σαφές όνομα.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
//Το test.obj γράφτηκε στη μεταβλητή ms, και μπορούμε επίσης να λάβουμε το περιεχόμενο του αρχείου test.mtl με
var materialFile = mfs.GetFileContent("test.mtl");
```

### Δείτε επίσης

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για Aspose.3D.dll -->
