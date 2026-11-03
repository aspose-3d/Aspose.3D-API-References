---
title: "Scene.FromStream"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Scene. Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου."
type: docs
weight: 30
url: /el/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ρεύμα εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο του ρεύματος. |
| μορφή | FileFormat | Μορφότυπος αρχείου. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή

```csharp
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream);
}
```

### Δείτε επίσης

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, LoadOptions, CancellationToken) {#fromstream_1}

Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ρεύμα εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο του ρεύματος. |
| επιλογές | LoadOptions | Πιο λεπτομερής διαμόρφωση για το άνοιγμα του ρεύματος. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή με επιλογές φόρτωσης

```csharp
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, opts);
}
```

### Δείτε επίσης

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, CancellationToken) {#fromstream_2}

Ανοίγει τη σκηνή από το δοσμένο ρεύμα

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ρεύμα εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο του ρεύματος. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή με πηγή διακριτικού ακύρωσης

```csharp
var cts = new CancellationTokenSource();
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, cts.Token);
}
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


