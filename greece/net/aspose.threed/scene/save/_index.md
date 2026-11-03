---
title: "Scene.Save"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Scene. Αποθηκεύει τη σκηνή σε ροή χρησιμοποιώντας την καθορισμένη μορφή αρχείου"
type: docs
weight: 160
url: /el/net/aspose.threed/scene/save/
---
## Save(Stream, FileFormat) {#save}

Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(Stream stream, FileFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ρεύμα εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο του ρεύματος. |
| μορφή | FileFormat | Μορφή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
Scene scene = Scene.FromFile("input.fbx");
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ);
}
```

### Δείτε επίσης

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, FileFormat, CancellationToken) {#save_1}

Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(Stream stream, FileFormat format, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ρεύμα εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο του ρεύματος. |
| μορφή | FileFormat | Μορφή. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία αποθήκευσης |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ, cts.Token);
}
```

### Δείτε επίσης

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions) {#save_2}

Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(Stream stream, SaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ρεύμα εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο του ρεύματος. |
| επιλογές | SaveOptions | Πιο λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
Scene scene = Scene.FromFile("input.fbx");
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Δείτε επίσης

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions, CancellationToken) {#save_3}

Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(Stream stream, SaveOptions options, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ρεύμα εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο του ρεύματος. |
| επιλογές | SaveOptions | Πιο λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία αποθήκευσης |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt, cts.Token);
}
```

### Δείτε επίσης

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string) {#save_4}

Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz");
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat) {#save_5}

Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(string fileName, FileFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| μορφή | FileFormat | Μορφή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ);
```

### Δείτε επίσης

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat, CancellationToken) {#save_6}

Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(string fileName, FileFormat format, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| μορφή | FileFormat | Μορφή. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία αποθήκευσης |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ, cts.Token);
```

### Δείτε επίσης

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions) {#save_7}

Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(string fileName, SaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| επιλογές | SaveOptions | Πιο λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts);
```

### Δείτε επίσης

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions, CancellationToken) {#save_8}

Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

```csharp
public void Save(string fileName, SaveOptions options, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου. |
| επιλογές | SaveOptions | Πιο λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για την εργασία αποθήκευσης |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση της εισόδου. |
| [ExportException](../../exportexception/) | Εκτοπίζεται όταν αποτύχει η εξαγωγή της σκηνής στην καθορισμένη μορφή 3D |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή

```csharp
var cts = new CancellationTokenSource();
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts, cts.Token);
```

### Δείτε επίσης

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


