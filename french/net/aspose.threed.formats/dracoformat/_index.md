---
title: "Classe DracoFormat"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.DracoFormat. Format Google Draco"
type: docs
weight: 1150
url: /fr/net/aspose.threed.formats/dracoformat/
---
## DracoFormat class

Format Google Draco

```csharp
public class DracoFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode)(byte[]) | Décode le nuage de points ou le maillage à partir des données en mémoire |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode_1)(string) | Décode le nuage de points ou le maillage à partir du nom de fichier spécifié |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode)(Entity, DracoSaveOptions) | Encode l'entité en données brutes Draco |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_1)(Entity, Stream, DracoSaveOptions) | Encode l'entité vers le flux spécifié |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_2)(Entity, string, DracoSaveOptions) | Encode l'entité vers le fichier spécifié |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formate en chaîne |

## Exemples

Le code suivant montre comment encoder et décoder un Mesh vers/de tableau d'octets :

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//encoder le maillage au format Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//décoder le maillage depuis le format Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Voir aussi

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


