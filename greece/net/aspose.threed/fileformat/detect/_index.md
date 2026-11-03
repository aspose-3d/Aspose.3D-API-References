---
title: "FileFormat.Detect"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "FileFormat μέθοδος. Ανιχνεύει τη μορφή του αρχείου από τη ροή δεδομένων· το όνομα αρχείου είναι προαιρετικό για την εικασία τύπων που δεν έχουν μαγική κεφαλίδα"
type: docs
weight: 460
url: /el/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

Ανίχνευση της μορφής αρχείου από τη ροή δεδομένων, το όνομα αρχείου είναι προαιρετικό για την εικασία τύπων που δεν έχουν μαγική κεφαλίδα.

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή που περιέχει δεδομένα για ανίχνευση |
| fileName | String | Αρχικό όνομα αρχείου των δεδομένων, χρησιμοποιείται ως υπόδειξη. |

### Τιμή επιστροφής

Η [`FileFormat`](../) παρουσία του εντοπισμένου τύπου ή null εάν αποτύχει.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εξαίρεση που ρίχνεται όταν αποτυγχάνει η ανάγνωση των δεδομένων. |

## Παραδείγματα

```csharp
byte[] bytes = new byte[100];//take the bytes from your source
var fmt = FileFormat.Detect(new MemoryStream(bytes), "input-file");
Console.WriteLine($"Input data format: {fmt}");
```

### Δείτε επίσης

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)

---

## Detect(string) {#detect_1}

Ανίχνευση της μορφής αρχείου από το όνομα αρχείου, το αρχείο πρέπει να είναι αναγνώσιμο ώστε το Aspose.3D να μπορεί να ανιχνεύσει τη μορφή αρχείου μέσω της κεφαλίδας του αρχείου.

```csharp
public static FileFormat Detect(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Διαδρομή προς το αρχείο για ανίχνευση μορφής αρχείου. |

### Τιμή επιστροφής

Η [`FileFormat`](../) παρουσία του εντοπισμένου τύπου ή null εάν αποτύχει.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εξαίρεση που ρίχνεται όταν αποτυγχάνει η ανάγνωση των δεδομένων. |

## Παραδείγματα

```csharp
var fmt = FileFormat.Detect("input.fbx");
Console.WriteLine($"Input file format: {fmt}");
```

### Δείτε επίσης

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


