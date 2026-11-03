---
title: "Classe DracoSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.DracoSaveOptions. Options d'enregistrement pour les fichiers Google Draco."
type: docs
weight: 1160
url: /fr/net/aspose.threed.formats/dracosaveoptions/
---
## DracoSaveOptions class

Options d'enregistrement pour les fichiers Google draco

```csharp
public class DracoSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DracoSaveOptions](dracosaveoptions/)() | Construire une configuration par défaut pour l'enregistrement des fichiers Draco. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/dracosaveoptions/applyunitscale/) { get; set; } | Appliquer [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) au maillage. La valeur par défaut est false. |
| [ColorBits](../../aspose.threed.formats/dracosaveoptions/colorbits/) { get; set; } | Bits de quantification pour la couleur des sommets, la valeur par défaut est 10 |
| [CompressionLevel](../../aspose.threed.formats/dracosaveoptions/compressionlevel/) { get; set; } | Niveau de compression, la valeur par défaut est Standard |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [NormalBits](../../aspose.threed.formats/dracosaveoptions/normalbits/) { get; set; } | Bits de quantification pour les vecteurs normaux, la valeur par défaut est 10 |
| [PointCloud](../../aspose.threed.formats/dracosaveoptions/pointcloud/) { get; set; } | Exporter la scène en nuage de points, la valeur par défaut est false. |
| [PositionBits](../../aspose.threed.formats/dracosaveoptions/positionbits/) { get; set; } | Bits de quantification pour la position, la valeur par défaut est 14 |
| [TextureCoordinateBits](../../aspose.threed.formats/dracosaveoptions/texturecoordinatebits/) { get; set; } | Bits de quantification pour les coordonnées de texture, la valeur par défaut est 12 |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


