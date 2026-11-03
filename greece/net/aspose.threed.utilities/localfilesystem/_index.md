---
title: "LocalFileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: 
type: docs
weight: 2650
url: /el/net/aspose.threed.utilities/localfilesystem/
---
## LocalFileSystem class

Το [`LocalFileSystem`](../localfilesystem) θα χαρτογραφήσει τις λειτουργίες ανάγνωσης/εγγραφής σε τοπικό κατάλογο.

```csharp
public class LocalFileSystem : FileSystem
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LocalFileSystem](localfilesystem)(string) | Αρχικοποιήστε ένα νέο [`LocalFileSystem`](../localfilesystem) με καθορισμένο βασικό κατάλογο. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Αποδεσμεύστε το σύστημα αρχείων και απελευθερώστε τους πόρους του. |
| override [ReadFile](../../aspose.threed.utilities/localfilesystem/readfile)(string, IOConfig) | Δημιουργήστε μια ροή για την ανάγνωση εξαρτήσεων. |
| override [WriteFile](../../aspose.threed.utilities/localfilesystem/writefile)(string, IOConfig) | Δημιουργήστε μια ροή για τη γραφή εξαρτήσεων. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εισάγετε αρχείο και να παρέχετε εξαρτημένα αρχεία σε έναν δεδομένο κατάλογο

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Δημιουργήστε μια παρουσία επιλογών φόρτωσης και καθορίστε ένα σύστημα αρχείων zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new LocalFileSystem("textures/");
//Φορτώστε το αρχείο
var scene = Scene.FromFile(inputFile, opt);
```

### Δείτε επίσης

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για Aspose.3D.dll -->
