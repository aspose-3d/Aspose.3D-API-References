---
title: "Text.Font"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Text. Η γραμματοσειρά του κειμένου"
type: docs
weight: 30
url: /el/net/aspose.threed.profiles/text/font/
---
## Text.Font property

Η γραμματοσειρά του κειμένου.

```csharp
public FontFile Font { get; set; }
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

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


