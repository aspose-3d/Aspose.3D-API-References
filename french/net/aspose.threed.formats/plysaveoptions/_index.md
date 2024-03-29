---
title: PlySaveOptions
second_title: Référence de l'API Aspose.3D pour .NET
description: Enregistrer les options dexportation de la scène en tant que fichier PLY.
type: docs
weight: 1300
url: /fr/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

Enregistrer les options d'exportation de la scène en tant que fichier PLY.

```csharp
public class PlySaveOptions : SaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PlySaveOptions](plysaveoptions#constructor)() | Constructeur de[`PlySaveOptions`](../plysaveoptions) |
| [PlySaveOptions](plysaveoptions#constructor_1)(FileContentType) | Constructeur de[`PlySaveOptions`](../plysaveoptions) |

## Propriétés

| Nom | La description |
| --- | --- |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents) { get; set; } | Les noms des composants pour la couleur des sommets, la valeur par défaut est ("rouge", "vert", "bleu") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est nulle, ce qui signifie que l'importateur/exportateur décidera quel encodage utiliser. |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement) { get; set; } | Le nom de l'élément pour les données de visage, la valeur par défaut est "face" |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty) { get; set; } | Le nom de la propriété pour les données de visage, la valeur par défaut est "vertex_index" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrer/Charger actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Le nom de fichier de la scène d'exportation/importation. Ceci est facultatif, mais utile lors de la sérialisation de ressources externes comme le matériel d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Autoriser l'utilisateur à gérer la gestion des dépendances externes lors du chargement/sauvegarde. |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate) { get; set; } | Retournez les coordonnées lors de l'enregistrement de la scène, la valeur par défaut est true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher un fichier externe à charger. |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents) { get; set; } | Les noms des composants pour les données normales, la valeur par défaut est ("nx", "ny", "nz") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud) { get; set; } | Exporter la scène sous forme de nuage de points, la valeur par défaut est false. |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents) { get; set; } | Les noms des composants pour les données de position, la valeur par défaut est ("x", "y", "z") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents) { get; set; } | Les noms des composants pour les données de coordonnées de texture, la valeur par défaut est ("u", "v") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement) { get; set; } | Le nom de l'élément pour les données de vertex, la valeur par défaut est "vertex" |

### Voir également

* class [SaveOptions](../saveoptions)
* espace de noms [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
