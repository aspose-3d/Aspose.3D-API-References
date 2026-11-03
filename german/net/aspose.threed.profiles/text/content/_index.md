---
title: "Text.Content"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Text-Eigenschaft. Inhalt des Textes"
type: docs
weight: 20
url: /de/net/aspose.threed.profiles/text/content/
---
## Text.Content property

Inhalt des Textes

```csharp
public string Content { get; set; }
```

## Beispiele

Der folgende Code zeigt, wie man ein 3D‑Mesh aus Text mit einer angegebenen Schriftdatei erstellt.

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

### Siehe auch

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


