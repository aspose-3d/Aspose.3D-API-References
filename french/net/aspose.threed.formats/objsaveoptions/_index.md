---
title: "Classe ObjSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.ObjSaveOptions. Options d’enregistrement pour le fichier Wavefront OBJ."
type: docs
weight: 1370
url: /fr/net/aspose.threed.formats/objsaveoptions/
---
## ObjSaveOptions class

Options d'enregistrement pour le fichier wavefront obj

```csharp
public class ObjSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ObjSaveOptions](objsaveoptions/)() | Constructeur de `ObjSaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/objsaveoptions/applyunitscale/) { get; set; } | Appliquer [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) au maillage. La valeur par défaut est false. |
| [AxisSystem](../../aspose.threed.formats/objsaveoptions/axissystem/) { get; set; } | Obtient ou définit le système d’axes dans le fichier exporté. |
| [EnableMaterials](../../aspose.threed.formats/objsaveoptions/enablematerials/) { get; set; } | Obtient ou définit si les matériaux d’import/export sont appliqués à chaque objet. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipCoordinateSystem](../../aspose.threed.formats/objsaveoptions/flipcoordinatesystem/) { get; set; } | Obtient ou définit si le système de coordonnées des points de contrôle/normales doit être inversé lors de l'importation/exportation. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [PointCloud](../../aspose.threed.formats/objsaveoptions/pointcloud/) { get; set; } | Obtient ou définit le drapeau indiquant si l’exportateur doit exporter la scène sous forme de nuage de points (sans structure topologique), la valeur par défaut est false. |
| [SerializeW](../../aspose.threed.formats/objsaveoptions/serializew/) { get; set; } | Obtient ou définit si le composant W doit être sérialisé dans la position des sommets du modèle. |
| [Verbose](../../aspose.threed.formats/objsaveoptions/verbose/) { get; set; } | Obtient ou définit si des commentaires doivent être générés pour chaque section. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


