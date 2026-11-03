---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος FileSystem. Αρχικοποιήστε ένα νέο FileSystem που έχει πρόσβαση μόνο στον τοπικό φάκελο. Όλες οι αναγνώσεις/εγγραφές αρχείων σε αυτήν την παρουσία του FileSystem θα αντιστοιχούν στον καθορισμένο φάκελο"
type: docs
weight: 20
url: /el/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Αρχικοποιήστε ένα νέο [`FileSystem`](../) που έχει πρόσβαση μόνο στον τοπικό φάκελο. Όλες οι αναγνώσεις/εγγραφές αρχείων σε αυτήν την παρουσία του FileSystem θα αντιστοιχούν στον καθορισμένο φάκελο.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κατάλογος | String | Ο κατάλογος στο φυσικό σας σύστημα αρχείων ως εικονικός ριζικός κατάλογος. |

### Τιμή επιστροφής

Μια νέα παρουσία του συστήματος αρχείων για παροχή τοπικής πρόσβασης σε αρχεία

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| FileNotFoundException | Εκτοξεύεται όταν δεν μπορεί να βρεθεί ο φάκελος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εισάγετε αρχείο και να παρέχετε εξαρτημένα αρχεία σε έναν δεδομένο κατάλογο

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//Δημιουργήστε μια παρουσία επιλογών φόρτωσης και καθορίστε ένα τοπικό σύστημα αρχείων
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//Φορτώστε το αρχείο
var scene = Scene.FromFile(inputFile, opt);
```

### Δείτε επίσης

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


