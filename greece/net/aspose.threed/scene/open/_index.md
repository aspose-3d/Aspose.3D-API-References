---
title: "Scene.Open"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Scene. Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου."
type: docs
weight: 140
url: /el/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
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

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ρεύμα.

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, FileFormat.GLTF2);
}
```

### Δείτε επίσης

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, LoadOptions, CancellationToken) {#open_2}

Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
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

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ρεύμα με επιπλέον επιλογές φόρτωσης.

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    var opt = new FbxLoadOptions();
    opt.LookupPaths.Add("textures");
    scene.Open(stream, opt);
}
```

### Δείτε επίσης

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream) {#open}

Ανοίγει τη σκηνή από το δοσμένο ρεύμα

```csharp
public void Open(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ρεύμα εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο του ρεύματος. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ρεύμα.

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream);
}
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, CancellationToken) {#open_3}

Ανοίγει τη σκηνή από το δοσμένο ρεύμα

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
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

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ρεύμα με διακριτικό ακύρωσης.

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, cts.Token);
}
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, FileFormat, CancellationToken) {#open_5}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| μορφή | FileFormat | Μορφότυπος αρχείου. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από όνομα αρχείου με διακριτικό ακύρωσης.

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
scene.Open("input.fbx", FileFormat.FBX7400ASCII, cts.Token);

```

### Δείτε επίσης

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions) {#open_6}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Open(string fileName, LoadOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| επιλογές | LoadOptions | Πιο λεπτομερής διαμόρφωση για το άνοιγμα του ρεύματος. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από όνομα αρχείου με επιπλέον επιλογές φόρτωσης.

```csharp
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts);
```

### Δείτε επίσης

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions, CancellationToken) {#open_7}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| επιλογές | LoadOptions | Πιο λεπτομερής διαμόρφωση για το άνοιγμα του ρεύματος. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από όνομα αρχείου με επιπλέον επιλογές φόρτωσης και διακριτικό ακύρωσης.

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts, cts.Token);
```

### Δείτε επίσης

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string) {#open_4}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι

```csharp
public void Open(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από όνομα αρχείου.

```csharp
Scene scene = new Scene();
scene.Open("input.fbx");
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, CancellationToken) {#open_8}

Ανοίγει τη σκηνή από το δοσμένο μονοπάτι

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία φόρτωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ImportException](../../importexception/) | Εκτοπίζεται όταν η είσοδος δεν είναι έγκυρος 3D μορφότυπος. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από όνομα αρχείου και μια πηγή διακριτικού ακύρωσης.

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


