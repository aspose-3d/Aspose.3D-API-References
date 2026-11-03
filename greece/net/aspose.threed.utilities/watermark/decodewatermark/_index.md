---
title: "Watermark.DecodeWatermark"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Watermark μέθοδος. Αποκωδικοποιήστε το υδατογράφημα από ένα πλέγμα"
type: docs
weight: 10
url: /el/net/aspose.threed.utilities/watermark/decodewatermark/
---
## DecodeWatermark(Mesh) {#decodewatermark}

Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα

```csharp
public static string DecodeWatermark(Mesh input)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| είσοδος | Πλέγμα | Το πλέγμα για εξαγωγή υδατογραφήματος |

### Τιμή επιστροφής

Τυφλό υδατογράφημα ή null εάν δεν αποκωδικοποιηθεί υδατογράφημα.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| UnauthorizedAccessException | Το πλέγμα προστατεύεται με κωδικό, και ο παρεχόμενος κωδικός είναι λανθασμένος. |

## Παρατηρήσεις

Τόσο [`EncodeWatermark`](../encodewatermark/) όσο και `DecodeWatermark` θα εκτελέσουν έλεγχο άδειας. Η χρήση δοκιμής θα προκαλέσει εξαίρεση, μπορείτε να χρησιμοποιήσετε [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) για να καταστέλλετε την εξαίρεση, αλλά δεν θα αφαιρέσει τον περιορισμό εδώ. Απαιτείται έγκυρη άδεια για τη χρήση αυτών των λειτουργιών χωρίς περιορισμούς.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποκωδικοποιήσετε ένα τυφλό υδατογράφημα από ένα πλέγμα αποθηκευμένο σε αρχείο 3D

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh);
```

### Δείτε επίσης

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## DecodeWatermark(Mesh, string) {#decodewatermark_1}

Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα

```csharp
public static string DecodeWatermark(Mesh input, string password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| είσοδος | Πλέγμα | Το πλέγμα για εξαγωγή υδατογραφήματος |
| κωδικός | String | Ο κωδικός για την αποκρυπτογράφηση του υδατογραφήματος |

### Τιμή επιστροφής

Τυφλό υδατογράφημα ή null εάν δεν αποκωδικοποιηθεί υδατογράφημα.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| UnauthorizedAccessException | Το πλέγμα προστατεύεται με κωδικό, και ο παρεχόμενος κωδικός είναι λανθασμένος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποκωδικοποιήσετε ένα τυφλό υδατογράφημα από ένα πλέγμα αποθηκευμένο σε αρχείο 3D

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh, "password");
```

### Δείτε επίσης

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


