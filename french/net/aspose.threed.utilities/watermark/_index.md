---
title: "Classe Watermark"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Utilities.Watermark class. Utilitaire pour encoder/décoder un filigrane aveugle depuis/vers un maillage"
type: docs
weight: 2950
url: /fr/net/aspose.threed.utilities/watermark/
---
## Watermark class

Utilitaire pour encoder/décoder un filigrane invisible vers/de un maillage.

```csharp
public class Watermark
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark)(Mesh) | Décodez le filigrane depuis un maillage |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark_1)(Mesh, string) | Décodez le filigrane depuis un maillage |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark)(Mesh, string) | Encodez un texte dans le filigrane aveugle du maillage. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_1)(Mesh, string, string) | Encodez un texte dans le filigrane aveugle du maillage. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_2)(Mesh, string, string, bool) | Encodez un texte dans le filigrane aveugle du maillage. |

## Remarques

Les deux [`EncodeWatermark`](./encodewatermark/) et [`DecodeWatermark`](./decodewatermark/) effectueront une vérification de licence. L'utilisation en version d'essai déclenchera une exception, vous pouvez utiliser [`SuppressTrialException`](../../aspose.threed/trialexception/suppresstrialexception/) pour supprimer l'exception, mais cela ne lèvera pas la restriction ici. Une licence valide est requise pour utiliser ces fonctionnalités sans aucune restriction.

## Exemples

Le code suivant montre comment encoder un filigrane aveugle dans un maillage et le décoder.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", null);
var watermark = Watermark.DecodeWatermark(encodedMesh, null);
```

### Voir aussi

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


