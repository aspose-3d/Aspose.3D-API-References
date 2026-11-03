---
title: "Κλάση FileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Utilities.FileSystem. Ενσωμάτωση συστήματος αρχείων. Το Aspose.3D θα το χρησιμοποιήσει για ανάγνωση/εγγραφή εξαρτήσεων"
type: docs
weight: 2750
url: /el/net/aspose.threed.utilities/filesystem/
---
## FileSystem class

Ενσωμάτωση του συστήματος αρχείων. Το Aspose.3D θα το χρησιμοποιήσει για ανάγνωση/εγγραφή εξαρτήσεων.

```csharp
public abstract class FileSystem : IDisposable
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [CreateDummyFileSystem](../../aspose.threed.utilities/filesystem/createdummyfilesystem/)() | Δημιουργήστε ένα ψεύτικο σύστημα αρχείων, οι λειτουργίες ανάγνωσης/εγγραφής είναι ψεύτικες λειτουργίες. |
| static [CreateLocalFileSystem](../../aspose.threed.utilities/filesystem/createlocalfilesystem/)(string) | Αρχικοποιήστε ένα νέο `FileSystem` που έχει πρόσβαση μόνο στον τοπικό φάκελο. Όλες οι λειτουργίες ανάγνωσης/εγγραφής αρχείων σε αυτήν την παρουσία του FileSystem θα αντιστοιχίζονται στον καθορισμένο φάκελο. |
| static [CreateMemoryFileSystem](../../aspose.threed.utilities/filesystem/creatememoryfilesystem/)(Dictionary&lt;string, MemoryStream&gt;) |  |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem_1)(string) | Σύστημα αρχείων που παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα απορριφθεί μετά τη λειτουργία ανοίγματος/αποθήκευσης. |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem)(Stream, string) | Δημιουργήστε ένα σύστημα αρχείων για να παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα διαγραφεί μετά τη λειτουργία ανοίγματος/αποθήκευσης. |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose/)() | Αποδεσμεύστε το σύστημα αρχείων και απελευθερώστε τους πόρους του. |
| abstract [ReadFile](../../aspose.threed.utilities/filesystem/readfile/)(string, IOConfig) | Δημιουργήστε μια ροή για την ανάγνωση εξαρτήσεων. |
| abstract [WriteFile](../../aspose.threed.utilities/filesystem/writefile/)(string, IOConfig) | Δημιουργήστε μια ροή για τη γραφή εξαρτήσεων. |

## Παραδείγματα

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

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


