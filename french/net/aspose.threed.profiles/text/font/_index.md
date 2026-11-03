---
title: "Text.Font"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Text propriété. La police du texte"
type: docs
weight: 30
url: /fr/net/aspose.threed.profiles/text/font/
---
## Text.Font property

La police du texte.

```csharp
public FontFile Font { get; set; }
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

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


