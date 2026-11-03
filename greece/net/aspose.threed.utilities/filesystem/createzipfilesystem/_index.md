---
title: "FileSystem.CreateZipFileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος FileSystem. Δημιουργήστε ένα σύστημα αρχείων για παροχή πρόσβασης μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα διαγραφεί μετά τη λειτουργία ανοίγματος/αποθήκευσης."
type: docs
weight: 40
url: /el/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Δημιουργήστε ένα σύστημα αρχείων για να παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα διαγραφεί μετά τη λειτουργία ανοίγματος/αποθήκευσης.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή για πρόσβαση στο αρχείο zip |
| baseDir | String | Ο βασικός φάκελος μέσα στο αρχείο zip. |

### Τιμή επιστροφής

Ένα σύστημα αρχείων zip

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοξεύεται όταν αποτύχει η ανάγνωση από τη ροή. |

## Παρατηρήσεις

Αυτό είναι ένα σύστημα αρχείων μόνο για ανάγνωση, επομένως δεν υποστηρίζονται λειτουργίες εγγραφής.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εισάγετε αρχείο και να παρέχετε εξαρτημένα αρχεία σε ένα αρχείο zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Δημιουργήστε μια παρουσία επιλογών φόρτωσης και καθορίστε ένα σύστημα αρχείων zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//Φορτώστε το αρχείο
var scene = Scene.FromFile(inputFile, opt);
```

### Δείτε επίσης

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Σύστημα αρχείων που παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα απορριφθεί μετά τη λειτουργία ανοίγματος/αποθήκευσης.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου για το αρχείο zip. |

### Τιμή επιστροφής

Ένα σύστημα αρχείων zip

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοξεύεται όταν αποτύχει η ανάγνωση από τη ροή. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εισάγετε αρχείο και να παρέχετε εξαρτημένα αρχεία σε ένα αρχείο zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Δημιουργήστε μια παρουσία επιλογών φόρτωσης και καθορίστε ένα σύστημα αρχείων zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//Φορτώστε το αρχείο
var scene = Scene.FromFile(inputFile, opt);
```

### Δείτε επίσης

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


