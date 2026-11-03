---
title: "Classe PlyFormat"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.PlyFormat. Le format PLY"
type: docs
weight: 1430
url: /fr/net/aspose.threed.formats/plyformat/
---
## PlyFormat class

Le format PLY.

```csharp
public class PlyFormat : FileFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Obtient si Aspose.3D prend en charge l'exportation de la scène vers le format de fichier actuel. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Obtient si Aspose.3D prend en charge l'importation de la scène depuis le format de fichier actuel. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Obtient le type de contenu du format de fichier |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Obtient le nom d'extension de ce type. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Obtient les noms d'extension de ce type. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Obtient le type de format de fichier |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Obtient la version du format de fichier |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Crée des options de chargement par défaut pour ce format de fichier |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Crée des options d'enregistrement par défaut pour ce format de fichier |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode)(Stream) | Décodez un nuage de points ou un maillage depuis le flux spécifié. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_2)(string) | Décodez un nuage de points ou un maillage depuis le flux spécifié. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_1)(Stream, PlyLoadOptions) | Décodez un nuage de points ou un maillage depuis le flux spécifié. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_3)(string, PlyLoadOptions) | Décodez un nuage de points ou un maillage depuis le flux spécifié. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode)(Entity, Stream) | Encodez l'entité et enregistrez le résultat dans le flux. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_2)(Entity, string) | Encodez l'entité et enregistrez le résultat dans un fichier externe. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_1)(Entity, Stream, PlySaveOptions) | Encodez l'entité et enregistrez le résultat dans le flux. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_3)(Entity, string, PlySaveOptions) | Encodez l'entité et enregistrez le résultat dans un fichier externe. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formate en chaîne |

## Exemples

Le code suivant montre comment encoder un maillage dans un fichier PLY :

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//encoder le maillage au format PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

Le code suivant montre comment décoder un maillage depuis un fichier PLY :

```csharp
//Générer un fichier de test pour le décodage
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Décoder le fichier
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Voir aussi

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


