---
title: "Text.FontSize"
second_title: "Aspose.3D för .NET API‑referens"
description: "Text egenskap. Skala för teckenstorlek"
type: docs
weight: 40
url: /sv/net/aspose.threed.profiles/text/fontsize/
---
## Text.FontSize property

Typsnittsstorleksskala.

```csharp
public float FontSize { get; set; }
```

## Exempel

Följande kod visar hur man skapar ett 3D-nät från text med angiven typsnittsfil.

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

### Se även

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


