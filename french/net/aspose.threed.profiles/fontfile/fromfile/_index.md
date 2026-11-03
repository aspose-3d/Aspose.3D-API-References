---
title: "FontFile.FromFile"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode FontFile. Chargez FontFile à partir du nom de fichier"
type: docs
weight: 10
url: /fr/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Charger FontFile à partir du nom de fichier

```csharp
public static FontFile FromFile(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Chemin vers le fichier de police |

### Valeur de retour

instance FontFile

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancée lorsque la lecture du fichier a échoué. |

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

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


