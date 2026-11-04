---
title: "Text.Font"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Text eigenschap. Het lettertype van de tekst"
type: docs
weight: 30
url: /nl/net/aspose.threed.profiles/text/font/
---
## Text.Font property

Het lettertype van de tekst.

```csharp
public FontFile Font { get; set; }
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

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


