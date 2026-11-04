---
title: "FontFile.FromFile"
second_title: "Aspose.3D voor .NET API-referentie"
description: "FontFile methode. Laad FontFile vanaf bestandsnaam"
type: docs
weight: 10
url: /nl/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Laad FontFile van bestandsnaam

```csharp
public static FontFile FromFile(string fileName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Pad naar het lettertypebestand |

### Retourwaarde

FontFile instantie

### Exceptions

| exceptie | conditie |
| --- | --- |
| IOException | Wordt gegooid wanneer het lezen van het bestand mislukt. |

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

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


