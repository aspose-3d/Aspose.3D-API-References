---
title: "Classe PlySaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.PlySaveOptions. Options d'enregistrement pour l'exportation de la scène au format PLY."
type: docs
weight: 1450
url: /fr/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

Options d'enregistrement pour exporter la scène au format PLY.

```csharp
public class PlySaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | Constructeur de `PlySaveOptions` |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | Constructeur de `PlySaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/plysaveoptions/axissystem/) { get; set; } | Obtient ou définit le système d'axes dans le fichier STL exporté. |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | Les noms des composants pour la couleur des sommets, la valeur par défaut est (\"red\", \"green\", \"blue\") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | Le nom de l'élément pour les données de face, la valeur par défaut est \"face\" |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | Le nom de la propriété pour les données de face, la valeur par défaut est \"vertex_index\" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | Inverser la coordonnée lors de l'enregistrement de la scène, la valeur par défaut est true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | Les noms des composants pour les données normales, la valeur par défaut est (\"nx\", \"ny\", \"nz\") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | Exporter la scène en tant que nuage de points, la valeur par défaut est false. |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | Les noms des composants pour les données de position, la valeur par défaut est (\"x\", \"y\", \"z\") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | Les noms des composants pour les données de coordonnées de texture, la valeur par défaut est (\"u\", \"v\") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | Le nom de l'élément pour les données de sommet, la valeur par défaut est \"vertex\" |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


