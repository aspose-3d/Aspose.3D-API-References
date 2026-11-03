---
title: "Κλάση ZipArchiveFileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Utilities.ZipArchiveFileSystem. Σύστημα αρχείων που παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα απορριφθεί μετά τη λειτουργία ανοίγματος/αποθήκευσης."
type: docs
weight: 2830
url: /el/net/aspose.threed.utilities/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

Σύστημα αρχείων που παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα απορριφθεί μετά τη λειτουργία ανοίγματος/αποθήκευσης.

```csharp
public class ZipArchiveFileSystem : FileSystem
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Dispose](../../aspose.threed.utilities/ziparchivefilesystem/dispose/)() | Αποδεσμεύστε το ZipArchiveFileSystem και ελευθερώστε τους εσωτερικούς του πόρους. |
| override [ReadFile](../../aspose.threed.utilities/ziparchivefilesystem/readfile/)(string, IOConfig) | Άνοιγμα αρχείου για ανάγνωση |
| override [WriteFile](../../aspose.threed.utilities/ziparchivefilesystem/writefile/)(string, IOConfig) | Άνοιγμα αρχείου για εγγραφή, δεν έχει υλοποιηθεί σε αυτήν την κλάση. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εισάγετε αρχείο και να παρέχετε εξαρτημένα αρχεία σε ένα αρχείο zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Δημιουργήστε μια παρουσία επιλογών φόρτωσης και καθορίστε ένα σύστημα αρχείων zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new ZipArchiveFileSystem("textures.zip");
//Φορτώστε το αρχείο
var scene = Scene.FromFile(inputFile, opt);
```

### Δείτε επίσης

* class [FileSystem](../filesystem/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


