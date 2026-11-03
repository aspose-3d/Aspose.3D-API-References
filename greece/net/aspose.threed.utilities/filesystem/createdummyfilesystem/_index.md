---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος FileSystem. Δημιουργήστε ένα ψεύτικο σύστημα αρχείων· οι λειτουργίες ανάγνωσης/εγγραφής είναι ψεύτικες."
type: docs
weight: 10
url: /el/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Δημιουργήστε ένα ψεύτικο σύστημα αρχείων, οι λειτουργίες ανάγνωσης/εγγραφής είναι ψεύτικες λειτουργίες.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Τιμή επιστροφής

Ένα ψεύτικο σύστημα αρχείων

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε το αρχείο στη μνήμη και να αγνοήσετε όλες τις εξαρτημένες δημιουργίες αρχείων.

```csharp
//δημιουργήστε μια σκηνή με υλικό
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//δημιουργήστε μια επιλογή αποθήκευσης και καθορίστε το σύστημα αρχείων, ώστε το εξαρτημένο αρχείο να γραφτεί στη μνήμη
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//Το όνομα αρχείου υλικού του obj συσχετίζεται με το όνομα αρχείου του obj, επομένως χρειαζόμαστε ένα σαφές όνομα.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Δείτε επίσης

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


