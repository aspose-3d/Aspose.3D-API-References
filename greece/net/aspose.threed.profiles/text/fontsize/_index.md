---
title: "Text.FontSize"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Text. Κλίμακα μεγέθους γραμματοσειράς"
type: docs
weight: 40
url: /el/net/aspose.threed.profiles/text/fontsize/
---
## Text.FontSize property

Κλίμακα μεγέθους γραμματοσειράς.

```csharp
public float FontSize { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα 3D πλέγμα από κείμενο χρησιμοποιώντας το καθορισμένο αρχείο γραμματοσειράς.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Δείτε επίσης

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


