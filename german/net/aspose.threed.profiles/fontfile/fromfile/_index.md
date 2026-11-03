---
title: "FontFile.FromFile"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FontFile-Methode. Lädt FontFile aus Dateinamen"
type: docs
weight: 10
url: /de/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Lade FontFile aus Dateinamen

```csharp
public static FontFile FromFile(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Pfad zur Schriftdatei |

### Rückgabewert

FontFile-Instanz

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen aus der Datei fehlschlägt. |

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

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


