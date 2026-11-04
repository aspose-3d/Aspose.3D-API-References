---
title: "Text.Content"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Text eigenschap. Inhoud van de tekst"
type: docs
weight: 20
url: /nl/net/aspose.threed.profiles/text/content/
---
## Text.Content property

Inhoud van de tekst

```csharp
public string Content { get; set; }
```

## Voorbeelden

De volgende code toont hoe je een 3D-mesh maakt van tekst met behulp van een opgegeven lettertypebestand.

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

### Zie ook

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


