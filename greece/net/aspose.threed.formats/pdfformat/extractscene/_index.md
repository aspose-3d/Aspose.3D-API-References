---
title: "PdfFormat.ExtractScene"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος PdfFormat. Εξάγει 3D σκηνές από αρχείο PDF"
type: docs
weight: 20
url: /el/net/aspose.threed.formats/pdfformat/extractscene/
---
## ExtractScene(string) {#extractscene_1}

Εξαγωγή 3D σκηνών από αρχείο PDF.

```csharp
public List<Scene> ExtractScene(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου του εισερχόμενου αρχείου PDF |

### Τιμή επιστροφής

Λίστα των αποκωδικοποιημένων 3D σκηνών που υποστηρίζονται από το Aspose.3D

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε όλες τις υποστηριζόμενες 3D σκηνές από ένα 3D αρχείο PDF και να τις γράψετε σε μορφή obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Δείτε επίσης

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(string, byte[]) {#extractscene_2}

Εξαγωγή 3D σκηνών από αρχείο PDF.

```csharp
public List<Scene> ExtractScene(string fileName, byte[] password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου του εισερχόμενου αρχείου PDF |
| κωδικός | Byte[] | Κωδικός πρόσβασης του αρχείου PDF |

### Τιμή επιστροφής

Λίστα των αποκωδικοποιημένων 3D σκηνών που υποστηρίζονται από το Aspose.3D

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε όλες τις υποστηριζόμενες 3D σκηνές από ένα 3D αρχείο PDF και να τις γράψετε σε μορφή obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Δείτε επίσης

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(Stream, byte[]) {#extractscene}

Εξαγωγή ακατέργαστου 3D περιεχομένου από τη ροή PDF.

```csharp
public List<Scene> ExtractScene(Stream stream, byte[] password = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή του εισερχόμενου αρχείου PDF |
| κωδικός | Byte[] | Κωδικός πρόσβασης του αρχείου PDF |

### Τιμή επιστροφής

Λίστα των αποκωδικοποιημένων 3D σκηνών που υποστηρίζονται από το Aspose.3D

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε όλες τις υποστηριζόμενες 3D σκηνές από ένα 3D αρχείο PDF και να τις γράψετε σε μορφή obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Δείτε επίσης

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


