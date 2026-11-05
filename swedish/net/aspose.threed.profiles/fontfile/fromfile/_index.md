---
title: "FontFile.FromFile"
second_title: "Aspose.3D för .NET API‑referens"
description: "FontFile-metod. Ladda FontFile från filnamn"
type: docs
weight: 10
url: /sv/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Läs in FontFile från filnamn

```csharp
public static FontFile FromFile(string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Sökväg till typsnittfilen |

### Returvärde

FontFile-instans

### Undantag

| undantag | villkor |
| --- | --- |
| IOException | Kastas när läsning från fil misslyckas. |

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

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


