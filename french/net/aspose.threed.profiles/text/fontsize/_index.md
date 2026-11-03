---
title: "Text.FontSize"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Text propriété. Échelle de taille de police"
type: docs
weight: 40
url: /fr/net/aspose.threed.profiles/text/fontsize/
---
## Text.FontSize property

Échelle de taille de police.

```csharp
public float FontSize { get; set; }
```

## Exemples

Le code suivant montre comment créer un maillage 3D à partir du texte en utilisant le fichier de police spécifié.

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

### Voir aussi

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


