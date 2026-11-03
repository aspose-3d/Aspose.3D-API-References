---
title: "Watermark.EncodeWatermark"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Watermark μέθοδος. Κωδικοποιήστε ένα κείμενο σε τυφλό υδατογράφημα πλέγματος"
type: docs
weight: 20
url: /el/net/aspose.threed.utilities/watermark/encodewatermark/
---
## EncodeWatermark(Mesh, string) {#encodewatermark}

Κωδικοποίηση κειμένου σε τυφλό υδατογράφημα πλέγματος.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| είσοδος | Πλέγμα | Πλέγμα για κωδικοποίηση τυφλού υδατογραφήματος |
| κείμενο | String | Κείμενο για κωδικοποίηση στο πλέγμα |

### Τιμή επιστροφής

Μια νέα παρουσία πλέγματος με τυφλό υδατογράφημα κωδικοποιημένο

## Παρατηρήσεις

Τόσο `EncodeWatermark` όσο και [`DecodeWatermark`](../decodewatermark/) θα εκτελέσουν έλεγχο άδειας. Η χρήση δοκιμής θα προκαλέσει εξαίρεση, μπορείτε να χρησιμοποιήσετε το [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) για να καταστείλετε την εξαίρεση, αλλά δεν θα αφαιρέσει τον περιορισμό εδώ. Απαιτείται έγκυρη άδεια για τη χρήση αυτών των λειτουργιών χωρίς περιορισμούς.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα τυφλό υδατογράφημα σε ένα πλέγμα και να το αποθηκεύσετε σε αρχείο ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello");
new Scene(encodedMesh).Save("test.ply");
```

### Δείτε επίσης

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string) {#encodewatermark_1}

Κωδικοποίηση κειμένου σε τυφλό υδατογράφημα πλέγματος.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| είσοδος | Πλέγμα | Πλέγμα για κωδικοποίηση τυφλού υδατογραφήματος |
| κείμενο | String | Κείμενο για κωδικοποίηση στο πλέγμα |
| κωδικός | String | Κωδικός πρόσβασης για την προστασία του υδατογραφήματος, είναι προαιρετικός. |

### Τιμή επιστροφής

Μια νέα παρουσία πλέγματος με τυφλό υδατογράφημα κωδικοποιημένο

## Παρατηρήσεις

Τόσο `EncodeWatermark` όσο και [`DecodeWatermark`](../decodewatermark/) θα εκτελέσουν έλεγχο άδειας. Η χρήση δοκιμής θα προκαλέσει εξαίρεση, μπορείτε να χρησιμοποιήσετε το [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) για να καταστείλετε την εξαίρεση, αλλά δεν θα αφαιρέσει τον περιορισμό εδώ. Απαιτείται έγκυρη άδεια για τη χρήση αυτών των λειτουργιών χωρίς περιορισμούς.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα τυφλό υδατογράφημα σε ένα πλέγμα και να το αποθηκεύσετε σε αρχείο ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### Δείτε επίσης

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string, bool) {#encodewatermark_2}

Κωδικοποίηση κειμένου σε τυφλό υδατογράφημα πλέγματος.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password, bool permanent)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| είσοδος | Πλέγμα | Πλέγμα για κωδικοποίηση τυφλού υδατογραφήματος |
| κείμενο | String | Κείμενο για κωδικοποίηση στο πλέγμα |
| κωδικός | String | Κωδικός πρόσβασης για την προστασία του υδατογραφήματος, είναι προαιρετικός. |
| μόνιμο | Boolean | Το μόνιμο υδατογράφημα δεν θα αντικατασταθεί ή αφαιρεθεί. |

### Τιμή επιστροφής

Μια νέα παρουσία πλέγματος με τυφλό υδατογράφημα κωδικοποιημένο

## Παρατηρήσεις

Τόσο `EncodeWatermark` όσο και [`DecodeWatermark`](../decodewatermark/) θα εκτελέσουν έλεγχο άδειας. Η χρήση δοκιμής θα προκαλέσει εξαίρεση, μπορείτε να χρησιμοποιήσετε το [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) για να καταστείλετε την εξαίρεση, αλλά δεν θα αφαιρέσει τον περιορισμό εδώ. Απαιτείται έγκυρη άδεια για τη χρήση αυτών των λειτουργιών χωρίς περιορισμούς.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα τυφλό υδατογράφημα σε ένα πλέγμα και να το αποθηκεύσετε σε αρχείο ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### Δείτε επίσης

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


